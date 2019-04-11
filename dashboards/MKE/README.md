To enable Kubernetes cluster metrics collection use the following option when creating a cluster:

```
  "advanced": {
    "enable_dcos_kubernetes_cluster_metrics_exporter": true
  }
```

The following dashboards are to be used in SOAK cluster and contain some example alerts:
- Kubernetes-SOAK-kc01.json
- Kubernetes-SOAK-kc02.json