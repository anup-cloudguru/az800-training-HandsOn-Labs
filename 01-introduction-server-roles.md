# Chapter 1: Introduction to Windows Server and Roles

## What is Windows Server?
Windows Server is an operating system designed to provide network services, manage enterprise environments, and support applications. Unlike a regular client computer that is used by an individual for tasks like gaming or document editing, a server is built to provide shared resources to multiple users across a network.

### Key Functions of a Windows Server
- **Resource Sharing:** A server can share files, printers, and other hardware resources.
- **Network Services:** Servers provide essential services like assigning IP addresses (DHCP), managing user accounts (Active Directory), and handling emails.
- **Security & Access Control:** They enforce security policies, ensuring only authorized users can access specific resources.
- **Database & Application Hosting:** Servers can run applications and host databases like SQL Server.

## Client vs. Server
A **client** is a user device such as a PC, laptop, or tablet that requests services from a server. On the other hand, a **server** processes these requests and provides the necessary services. 

### Operating System Overview
The **operating system (OS)** is the foundation that manages hardware and software resources. In the context of Windows Server, the OS allows administrators to install applications, configure security policies, and manage networking components.

Popular Windows Server versions include:
- Windows Server 2019
- Windows Server 2016
- Windows Server 2012 R2

## What are Roles in Windows Server?
A **role** in Windows Server defines a specific function or set of services the server provides within a network. Roles are made up of components called **role services**, which add functionality to the role.

### Common Server Roles
- **Active Directory Domain Services (AD DS):** Manages user authentication and permissions.
- **Domain Name System (DNS):** Resolves domain names to IP addresses.
- **Dynamic Host Configuration Protocol (DHCP):** Assigns IP addresses dynamically.
- **Hyper-V:** Provides virtualization services.
- **File and Storage Services:** Manages shared storage and file access.

## How to Add Server Roles
Roles are installed using the **Server Manager** tool in Windows Server.

### Steps to Add a Role:
1. Open **Server Manager**.
2. Click **Manage > Add Roles and Features**.
3. Choose the installation type (**Role-based or Feature-based installation**).
4. Select the server where the role will be installed.
5. Choose the role(s) you want to install.
6. Follow the prompts to add required **features** and complete the installation.

Some roles require additional configuration after installation, such as Active Directory setup or DHCP scope configuration.

## Summary
- A **Windows Server** provides resources and services in a networked environment.
- A **client** is an endpoint device that requests services from a server.
- **Roles** define what services a server provides, such as authentication, networking, or storage.
- Roles can be installed using the **Server Manager** in Windows Server.

This concludes Chapter 1. In the next chapter, we will explore **Active Directory Domain Services (AD DS)** and its role in managing users and computers in a Windows network.

---
