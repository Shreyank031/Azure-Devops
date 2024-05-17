## How are you managing your Azure Resources?

#### We are using Resource groups per project where we create one Resource group for payment, one for Transactions, etc,. Using this Resource group, we manage access, we manage monitoring, security aspects, billing, locking for perticular resources. 

- You can also group resources based on environment (dev, test, prod), by application, or by team/department.

If your organization only has one Azure account, then we create Resouce Group for project - env

> Payments-dev

> Payments-Qa 

> Payments-prod


>>Note : If a VM(Resource) is part of one Resource Group, then it cannot be part of any other RG.

**Resource Group and Resource are one to many map**. ***1:many***

>>A Resource Group can contain multiple resources, but a single resource can only belong to one Resource Group. It's a one-to-many relationship (one Resource Group can have many resources, but one resource can have only one Resource Group)

