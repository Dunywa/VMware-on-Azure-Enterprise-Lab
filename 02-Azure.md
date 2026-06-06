# Phase 2 - Azure Infrastructure

Created Resource Groups, Virtual Networks, and Azure virtual machines.

## Overview

The Azure environment provides the foundational infrastructure required to host the VMware lab.

## Objectives

- Create a dedicated Resource Group
- Create a Virtual Network
- Configure subnet segmentation
- Deploy management servers

## Components Deployed

### Resource Group

RG-VMWARE-LAB

<img width="955" height="567" alt="RG-VMWARE-LAB" src="https://github.com/user-attachments/assets/00bb157e-ac0d-4df8-a9db-0a312b2af580" />

### Virtual Network

VNET-VMWARE-LAB

<img width="951" height="601" alt="VNET-VMWARE-LAB" src="https://github.com/user-attachments/assets/78e94649-3ab0-4014-a771-674a4c73578e" />


#### Address Space

```
10.0.0.0/16
```

---

#### Subnets

<img width="954" height="496" alt="Subnets" src="https://github.com/user-attachments/assets/979edbb1-1608-48d8-ab43-320e58f39cec" />

***Management Subnet***

```
10.0.1.0/24
```

Purpose:

- DC01
- vCenter01
- Jump01

---

***Server Subnet***

```
10.0.2.0/24
```

Purpose:

- Storage01
- Workload Servers

---

***VMware Subnet***

```
10.0.3.0/24
```

Purpose:

- ESXI01
- ESXI02


## Outcome

Successfully deployed the Azure infrastructure required to support the VMware environment and future workload expansion.
