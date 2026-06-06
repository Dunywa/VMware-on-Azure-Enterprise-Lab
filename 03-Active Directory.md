# Phase 3 - Active Directory Deployment

Installed AD DS, DNS, and deployed the inmspspace.com domain.

## Overview

The purpose of this phase was to deploy centralized identity and name resolution services for the VMware environment.

Enterprise environments rely on Active Directory and DNS to provide authentication, authorization, service discovery, and centralized administration.

---

## Objectives

- Deploy Active Directory Domain Services (AD DS)
- Deploy DNS services
- Create a domain structure
- Configure administrative accounts
- Prepare the environment for VMware integration

---

## Domain Configuration

### Domain Name

```
inmspspace.com
```

### Domain Controller

```
DC01
```

### Operating System

```
Windows Server 2022
```

---

## Active Directory Installation

The Active Directory Domain Services role was installed on DC01 and promoted to a domain controller.

### Installed Roles

- Active Directory Domain Services
- DNS Server

### Forest Configuration

```
inmspspace.com
```

---

## DNS Configuration

DNS was configured to provide internal name resolution.

### Zones Created

### Forward Lookup Zone

```
inmspspace.com
```

### DNS Responsibilities

- Name Resolution
- Service Location
- Active Directory Integration

---

## Service Accounts

The following administrative accounts were created:

| Account | Purpose |
| --- | --- |
| administrator | Domain Administration |
| vmwareadmin | VMware Administration |


---

## Validation

The following validation tests were completed:

- Domain Controller operational
- DNS resolving internal hosts
- User authentication successful
- Domain join functionality verified

---

## Screenshots

### Domain Controller

Screenshot:

<img width="1366" height="496" alt="DC01" src="https://github.com/user-attachments/assets/cb9c8720-0fa7-4e50-94f3-6f649766a739" />

### Active Directory Users and Computers

Screenshot:

<img width="1095" height="636" alt="Active Directory Users and Computers" src="https://github.com/user-attachments/assets/b4d268f3-6a84-4715-b6b8-814a02c59aa9" />

### DNS Manager

Screenshot:

<img width="1179" height="655" alt="DNS Manager" src="https://github.com/user-attachments/assets/48514b49-74a0-4748-b257-6cf97ea477a3" />


---

## Outcome

Successfully deployed centralized authentication and name resolution services that support VMware infrastructure and workload virtual machines.
