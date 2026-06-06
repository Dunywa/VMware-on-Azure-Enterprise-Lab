# Phase 3 - Active Directory Deployment

Installed AD DS, DNS, and deployed the corp.local domain.

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
corp.local
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
corp.local
```

---

## DNS Configuration

DNS was configured to provide internal name resolution.

### Zones Created

### Forward Lookup Zone

```
corp.local
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
| helpdesk | Support Operations |

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

Insert screenshot:

```
screenshots/03-AD/DC01-Overview.png
```

### Active Directory Users and Computers

Insert screenshot:

```
screenshots/03-AD/ADUC.png
```

### DNS Manager

Insert screenshot:

```
screenshots/03-AD/DNS-Zone.png
```

---

## Outcome

Successfully deployed centralized authentication and name resolution services that support VMware infrastructure and workload virtual machines.
