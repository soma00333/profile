# etcd-io/etcd-operator

Detail: - Added a workflow to guarantee that the import items are properly grouped and ordered, which improved code consistency and maintainability
- Enhanced the reconciliation logic to ensure that the number of replicas in the StatefulSet matches the number of etcd members in the cluster, which improved cluster consistency
Role: Contributor