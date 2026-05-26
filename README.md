# Sovereign Compute Ukraine - Infrastructure Configuration

This repository contains open-source infrastructure configurations, Kubernetes manifests, and deployment scripts for the **Sovereign Compute Ukraine** DePIN project.

## Project Overview
We operate high-performance, energy-resilient bare-metal GPU/CPU nodes within the decentralized cloud ecosystem (Akash Network). 

* **Provider Address:** `akash1rja3y2ctj3tzmesvh0zfhzzx95rfjw405hwt8d`
* **Target Workloads:** AI/ML Inference, Deep Learning, Decentralized RPC nodes.

## Tech Stack
* **Orchestration:** Kubernetes (K8s), Docker
* **OS:** Ubuntu Server 24.04 LTS
* **Network Protocol:** Akash Network (Cosmos SDK)

## Repository Structure
* `/kubernetes` - Cluster deployment manifests and cert-manager configs.
* `/akash-provider` - Sample Service Definition Language (SDL) files for AI workloads.
* `/nginx` - Reverse-proxy configurations for internal monitoring dashboard.

## Resilience & Sustainability
Our infrastructure is migrating to a hybrid solar-powered system (6-8 kW) with LiFePO4 battery storage to ensure 100% continuous uptime during grid power outages in Ukraine.
