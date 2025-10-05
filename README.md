# Pelorus Lab Configuration

Pelorus configuration for lab PoC testing GitOps deployment pattern via ArgoCD.

## Structure

```
values/
  pelorus-lab-values.yaml  - Custom Pelorus values for lab environment
```

## Usage

Referenced by ArgoCD ApplicationSet to overlay custom values on top of Pelorus Helm charts from GitHub master branch.
