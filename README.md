# Cluster Agent - test
```bash
helm repo add Alon-katz https://alon-katz.github.io/cluster-agent-test/
helm install <RELEASE-NAME> Alon-katz/app1 --set cluster-agent.epsagonToken=<TOKEN> --set cluster-agent.clusterName=<CLUSTER_NAME>
```
