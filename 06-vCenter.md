# Phase 6 - vCenter

Deployed vCenter and added ESXi hosts.

## Overview

This phase focused on deploying VMware vCenter Server to provide centralized management of the VMware infrastructure.

vCenter serves as the administrative platform for managing ESXi hosts, clusters, virtual machines, storage, networking, and advanced VMware features.

---

## Objectives

- Deploy VMware vCenter Server
- Configure centralized management
- Create inventory structure
- Add ESXi hosts
- Prepare the environment for clustering

---

## vCenter Deployment

### Server Name

```
vCenter01
```

### Deployment Type

```
VMware vCenter Server Appliance (VCSA)
```

### Purpose

- Centralized VMware Administration
- Host Management
- Cluster Management
- Performance Monitoring
- Resource Allocation
- Virtual Machine Management

---

## Inventory Creation

The VMware inventory structure was created to logically organize infrastructure resources.

### Inventory Structure

```
vCenter01
│
└── LAB-DC
```

---

## ESXi Host Onboarding

The following hosts were added to vCenter:

| Host | Purpose |
| --- | --- |
| ESXI01 | Compute Host |
| ESXI02 | Compute Host |

### Validation

Successfully verified:

- Host connectivity
- Inventory synchronization
- Resource visibility
- Management access

---

## Administrative Access

Administrative access was configured using:

### Local Administrator

```
administrator@vsphere.local
```

### Domain Integration (Optional)

```
corp.local
```

---

## Screenshots

### vCenter Dashboard

Insert Screenshot:

```
screenshots/06-vCenter/vCenter-Dashboard.png
```

### Hosts and Clusters

Insert Screenshot:

```
screenshots/06-vCenter/Hosts-And-Clusters.png
```

### ESXi Hosts Connected

Insert Screenshot:

```
screenshots/06-vCenter/ESXi-Hosts.png
```

---

## Outcome

Successfully deployed VMware vCenter Server and established centralized administration of the VMware environment.
