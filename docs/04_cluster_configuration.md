# Cluster Configuration

The project uses a simple single-node cluster for learning and cost control.

## Baseline Configuration

- Cluster name: `master-ai-cluster`
- Runtime: Spark 17.3 LTS
- Node type: `Standard_D4ds_v4`
- Mode: Single node
- Auto-termination: 10 minutes
- ML runtime: disabled

## Notes

Single-node mode is enough for development while still allowing Spark APIs and Databricks workflows to be tested.
