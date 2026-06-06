# Phase 4 - Shared Storage Deployment
Configured iSCSI storage and shared datastores.

## Overview

Shared storage was deployed to support VMware cluster functionality including High Availability (HA), Distributed Resource Scheduler (DRS), and vMotion.

---

## Objectives

- Deploy centralized storage
- Configure iSCSI services
- Create shared virtual disks
- Present storage to VMware hosts

---

## Storage Server Deployment

### Server

```
Storage01
```

### Operating System

```
Windows Server 2022
```

---

## iSCSI Target Server Installation

The iSCSI Target Server role was installed.

### Installed Feature

```
iSCSI Target Server
```

---

## Virtual Disk Creation

### Virtual Disk 1

```
DS-PROD01
500 GB
```

### Virtual Disk 2

```
DS-PROD02
500 GB
```

---

## Datastore Presentation

Both virtual disks were presented to:

```
ESXI01
ESXI02
```

Hosts were configured to discover storage using iSCSI initiators.

---

## Validation

The following checks were completed:

- iSCSI connectivity verified
- Shared storage visible from ESXi hosts
- Datastore creation successful
- Storage accessible from all cluster nodes

---

## Screenshots

### Storage Server

```
screenshots/04-Storage/Storage01.png
```

### iSCSI Target Configuration

```
screenshots/04-Storage/iSCSI-Target.png
```

### Datastore View

```
screenshots/04-Storage/Datastores.png
```

---

## Outcome

Successfully deployed shared storage supporting VMware HA, DRS, and vMotion operations.
