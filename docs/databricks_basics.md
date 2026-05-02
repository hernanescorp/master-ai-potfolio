# Databricks & Cluster Basics
# Databricks Architecture on Azure

## Overview

Azure Databricks is built on top of Azure infrastructure.

- Azure provides the compute resources (VMs)
- Databricks manages and orchestrates Spark clusters

## Architecture

User → Databricks UI → Azure → Virtual Machines → Spark Execution

## Key Components

- Control Plane: managed by Databricks
- Data Plane: hosted in Azure
- Cluster: group of virtual machines
- Spark: distributed processing engine

## Execution Flow

1. User runs notebook
2. Databricks sends job to cluster
3. Azure VMs execute the workload
4. Results are returned to the user

## Cost Model

Costs are generated when clusters are running, as Azure is provisioning compute resources.
## What is a cluster?

A cluster is a group of machines working together as a single system to process data.

In this project, a single-node cluster is used for simplicity and cost efficiency.

## Apache Spark

Databricks is built on top of Apache Spark, which allows distributed data processing.

## Cluster Configuration

- Cluster name: master-ai-cluster
- Runtime: Spark 17.3 LTS
- Node type: Standard_D4ds_v4
- Mode: Single node
- Auto-termination: 10 minutes
- ML runtime: disabled

## Key Concepts

- Driver: controls execution
- Workers: process data (not used in single node)
- Nodes: machines in the cluster

## Purpose

The cluster is used to execute notebooks in a scalable cloud environment, simulating a real data engineering workflow.