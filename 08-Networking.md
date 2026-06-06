# Phase 8 - Networking

Configured vSwitches, VLANs, and port groups.

## Overview

This phase focused on configuring VMware networking to provide communication between management systems, infrastructure services, and workload virtual machines.

Network segmentation was implemented to improve organization, security, and manageability.

---

## Objectives

- Configure VMware virtual switches
- Create Port Groups
- Implement VLAN segmentation
- Configure management networking
- Support workload communication

---

## Standard vSwitch Configuration

### Virtual Switch

```
vSwitch0
```

Purpose:

- Host Management Traffic
- Virtual Machine Connectivity
- Infrastructure Services

---

## Port Groups

The following Port Groups were created:

### Management Network

```
Management Network
```

Purpose:

- ESXi Management
- vCenter Communication
- Administrative Access

---

### VLAN100

```
VLAN ID: 100
```

Purpose:

- Application Workloads
- Web Services

Example VMs:

```
APP01
WEB01
```

---

### VLAN200

```
VLAN ID: 200
```

Purpose:

- Database Services
- File Services

Example VMs:

```
SQL01
FILE01
TEST01
```

---

## Network Validation

The following tests were completed:

- Host connectivity
- VM connectivity
- VLAN communication
- DNS resolution
- Domain access

---

## Screenshots

### vSwitch Configuration

Insert Screenshot:

```
screenshots/08-Networking/vSwitch0.png
```

### Port Groups

Insert Screenshot:

```
screenshots/08-Networking/Port-Groups.png
```

### VLAN Configuration

Insert Screenshot:

```
screenshots/08-Networking/VLAN-Configuration.png
```

---

## Outcome

Successfully implemented a segmented and secure VMware networking architecture supporting management, infrastructure, and workload traffic.
