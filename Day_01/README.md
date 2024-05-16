# Basics of Cloud Computing 

## What is Cloud?

The **cloud** refers to the vast network of servers and data centers that make up the infrastructure for cloud computing services. When you access data or use an application in the cloud, you're connecting to computing resources hosted elsewhere in the world, rather than on your local device or corporate data center.


## What is Cloud Computing?

Cloud computing is the delivery of computing services (software, storage, servers, databases, networking, analytics, intelligence etc.) over the internet ("the cloud"). Instead of owning and maintaining your own computing infrastructure, you can access these services from a cloud provider on an as-needed, pay-as-you-go basis.


> Earlier before the concept of cloud computing, the big tech companies like google, yahoo, microsoft and even small to medium sized organization had there own servers which was private to them and maintained by bunch of System Administrators. It's was basically a **Private Cloud**

## Challanges faced previously: 

- 24/7 uninterrupted Electricity. It's very challanging for a small to medium scale organization to achieve this.

- High upfront cost

- Limited scalability: It was difficult to quickly scale computing resources up or down based on changing demands, leading to either underutilization or capacity limitations.

- Maintenance and updates: Organizations had to handle the maintenance, upgrades, and security patches for their own hardware and software infrastructure, which was time-consuming and expensive.

### Entry of AWS

**By addressing this problems, what AWS said is, "We'll buidl data centers across the world. Companies can come to us and request for the service. Don't worry about Electricity, Security, Maintanance. Just tell us what service you want, and pay as you use it."**
> AWS played a pioneering role

## What is Private Cloud?

Private cloud refers to cloud computing resources that are dedicated to and accessible by a single organization/company. The hardware and software infrastructure is owned and managed by the organization itself, either on-premises or hosted by a third-party service provider.

Example: A banking service where it has hosted it's database in there private cloud.

## What is Public Cloud?

Public cloud, on the other hand, refers to cloud computing resources that are owned and operated by third-party cloud service providers (such as Amazon Web Services, Microsoft Azure, or Google Cloud Platform) in pay-per-use model.

## What is Hybrid Cloud?

Image a company wants to store sensitive data and don't trust third party cloud providers. The company or organization might be a bank who want's to store the database in there own private cloud. But also want's to utilize virtual machines from Azure or AWS for other tasks. The sensitive data resides in the private cloud, while other workloads leverage the public cloud.
Typically a combination of both Private and Public Cloud.

## Vocabulary

- Virtualization and Virtual Machines (VMs): **Virtualization** is the creation of virtual versions of resources like servers, storage, and networks. 

A **virtual machine** is a software-based emulation of a physical computer system./A multiple logical servers created by Virtualization is called Virtual Machines.

**Hypervisor** is a software that implements the Virtualization concept.

- API : An API is a set of rules and protocols that allow different software applications to communicate and interact with each other./"Programatically accessing a service".

Example : Image if you want to spin up 100 VMs from Azure/AWS, you can use an API provided by Azure and create it. It can be done using shell/python scripting and API exposed by Azure.

- Region and Availability: AWS/Azure has multiple geographic Regions, each with multiple isolated Availability Zones. This design provides high availability, fault tolerance, and low latency.

- Scalability and Elasticity: Scalability is the ability to increase or decrease resources as required. Elasticity refers to the dynamic scaling of resources in response to changing workload demands.

- Load Balancing: Load balancing distributes incoming traffic across multiple resources (e.g., servers) to optimize performance, fault tolerance, and efficient resource utilization.

- High Availability: High availability refers to the ability of a system or service to remain operational and accessible even in the event of individual component failures.
    - Example: Apps like Facebook, Instagram, X, Whatsapp rarely goes down.

- Disaster Management: Cloud providers provide disaster management capabilities through services like CloudEndure Disaster Recovery, enabling customers to protect and recover their applications and data in case of regional outages or disasters.

- Fault Tolerance: Fault tolerance refers to the ability of a system to continue operating properly in the event of individual component failures with minimum downtime.
