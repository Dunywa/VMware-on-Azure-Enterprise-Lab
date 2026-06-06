# Phase 2 - Azure Infrastructure

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

### Virtual Network

VNET-VMWARE-LAB

### Subnets

Management Subnet

Used for:

- Domain Controller
- vCenter
- Management Services

Server Subnet

Used for:

- Storage Server
- Workload Servers

VMware Subnet

Used for:

- ESXi Hosts

## Outcome

Successfully deployed the Azure infrastructure required to support the VMware environment and future workload expansion.
