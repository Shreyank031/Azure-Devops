# Resource, Resource Groups and Azure Resource Manager.

## Resource:

- A Resource is an **instance** of a service.
- Resource is a outcome of the service(eg: VM, sql_db, storage).

Example: Creating a VM or Sql db.

## Azure Resource Manager: 

- Azure Resource Manager is the deployment and management service in Azure. It allows you to create, update, and delete resources in a secure and consistent way.
- Whatever request you make for resources, it goes to Resource Manager. The request might be through UI, CLI or API.
- RM is an Interface b/w you and Actual creation of resource.

## Resource Group:

- Combination or Grouping of Resources
- A Resource Group is a logical container that holds related resources in Azure. 
- It allows you to manage and organize multiple resources as a single unit for ease of deployment, access control(RBAC), monitoring, and billing. 
- If you group resources, you can **track** and **manage** them easily.

> Note: You cannot create a resources without using Resource Group. It is mandatory in Azure.

