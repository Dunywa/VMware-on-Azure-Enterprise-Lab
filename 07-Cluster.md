# Phase 7 - Cluster

Configured HA, DRS, and cluster services.

## Overview

This phase focused on creating a VMware cluster to provide resiliency, workload balancing, and centralized resource management.

The cluster was designed to support High Availability (HA), Distributed Resource Scheduler (DRS), and shared storage integration.

---

## Objectives

- Create a VMware Datacenter
- Create a VMware Cluster
- Configure High Availability (HA)
- Configure Distributed Resource Scheduler (DRS)
- Integrate shared storage

---

## Datacenter Creation

### Datacenter Name

```
LAB-DC
```

Purpose:

- Organize VMware infrastructure
- Provide logical resource grouping

---

## Cluster Creation

### Cluster Name

```
LAB-CLUSTER
```

### Hosts Added

```
ESXI01
ESXI02
```

---

## High Availability (HA)

### Purpose

VMware HA automatically restarts virtual machines on surviving hosts in the event of host failure.

### Configuration

```
HA = Enabled
```

### Benefits

- Reduced downtime
- Automated recovery
- Improved service availability

---

## Distributed Resource Scheduler (DRS)

### Purpose

DRS automatically balances workloads across cluster hosts.

### Configuration

```
DRS = Enabled
```

### Benefits

- Resource optimization
- Load balancing
- Improved VM performance

---

## Datastore Integration

### Shared Datastores

```
DS-PROD01
DS-PROD02
```

### Connected Hosts

```
ESXI01
ESXI02
```

---

## Validation

The following checks were completed:

- Cluster healthy
- HA operational
- DRS operational
- Shared storage accessible
- Hosts communicating successfully

---

## Screenshots

### Cluster Overview

Insert Screenshot:

```
screenshots/07-Cluster/Cluster-Overview.png
```

### HA Configuration

Insert Screenshot:

```
screenshots/07-Cluster/HA-Enabled.png
```

### DRS Configuration

Insert Screenshot:

```
screenshots/07-Cluster/DRS-Enabled.png
```

### Datastores

Insert Screenshot:

```
screenshots/07-Cluster/Datastores.png
```

---

## Outcome

Successfully implemented a resilient VMware cluster capable of workload failover, automated resource balancing, and shared storage access.
