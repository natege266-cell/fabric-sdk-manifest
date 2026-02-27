# fabric-sdk-manifest

Fabric - A Modular SDK Assembly & Overlay Framework

***Scale Your SDKs, Not Your Overhead.***

## Introduction

### Current Situation

With a growing product portfolio and more vendor SDKs/customizations to manage, we need to ensure our iteration speed remains fast.

### Key Observation

The biggest cost is not adding features, but maintaining and evolving SDK-based projects over time.

### Goal

Fabric exists to solve the scalability problem, but not just a compilation problem.

## Download HT7210 Project Codebase

Use the following steps to download the HT7210 project codebase:

```bash
repo init -u git@github.com:Heights-Telecom-ASDC/fabric-sdk-manifest.git -b heights-ht7210-basic
repo sync
repo forall -c 'git lfs install && git lfs pull'
```

## Directory Structure

- **fabric-sdk-mgmt-base/** - Build orchestration, scripts, and common docs
- **fabric-sdk-mgmt-config/config/** - YAML project configuration files
- **sdk/** - SDK content, Docker files, and overlays
