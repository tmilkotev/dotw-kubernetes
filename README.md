# kubernetes

Cluster bootstrap and workload deployment.

## Purpose

This repository bootstraps clusters and deploys workloads.

It defines deployment manifests, target environments, and operational scripts.

---

## Structure

```
kubernetes/
├─ deployments/
│  ├─ apps/
│  └─ clusters/
│
├─ targets/
│
└─ scripts/
```

---

## Usage

Deploy to a target:

./targets/<target>/up.sh

Verify cluster and workloads:

./targets/<target>/verify.sh

Destroy cluster:

./targets/<target>/down.sh

---

## Targets

Targets define deployment environments.

Examples:

- targets/wsl-single/
- targets/vagrant-multinode/

---

## Deployments

Deployments contain workload definitions.

Examples:

- deployments/apps/
- deployments/clusters/

---

## Scripts

Scripts provide shared operational logic.

---

This repository serves as the cluster bootstrap and workload deployment layer.
