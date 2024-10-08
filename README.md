# oracledb-minikube-setup

WIP

```
minikube config set memory 11000
minikube config set cpus 4 
minikube start --disk-size 70g
```

```
kubectl apply -f cert-manager.yaml
sleep 10
```

```
kubectl apply -f cluster-role-binding.yaml
kubectl apply -f oracle-database-operator.yaml
kubectl get pods -n oracle-database-operator-system
```

```
kubectl apply -f singleinstancedatabase_secrets.yaml
kubectl apply -f singleinstancedatabase_free.yaml
```

```
kubectl describe singleinstancedatabases freedb-sample
```

```
~/sqlcl/bin/sql sys/Welcome1@192.168.205.8:30484/FREEPDB1 as sysdba
```

