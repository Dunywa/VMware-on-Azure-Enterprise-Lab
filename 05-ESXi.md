# Phase 5 - ESXi

Deployed ESXi hosts and configured management networking.

## Overview

This phase focused on deploying the VMware hypervisor layer that provides virtualization services for workload virtual machines.

---

## Objectives

- Deploy ESXi hosts
- Configure management networking
- Configure DNS
- Configure NTP
- Prepare hosts for cluster integration

---

## Host Deployment

### ESXI01

| Setting | Value |
| --- | --- |
| Hostname | ESXI01 |
| IP Address | 10.0.3.10 |

### ESXI02

| Setting | Value |
| --- | --- |
| Hostname | ESXI02 |
| IP Address | 10.0.3.11 |

---

## Management Networking

Management interfaces were configured to allow:

- Host administration
- vCenter connectivity
- Storage communication

---

## DNS Configuration

Primary DNS:

```
DC01
```

DNS resolution was tested against:

```
corp.local
```

---

## NTP Configuration

Time synchronization was configured to ensure:

- Consistent logging
- Authentication reliability
- VMware service stability

---

## Validation

Completed tests:

- Host connectivity
- DNS resolution
- NTP synchronization
- Web management access

---

## Screenshots

### ESXI01 Summary

```
screenshots/05-ESXi/ESXI01.png
```

### ESXI02 Summary

```
screenshots/05-ESXi/ESXI02.png
```

---

## Outcome

Successfully established the VMware hypervisor platform that would support cluster services and virtual machine workloads.
