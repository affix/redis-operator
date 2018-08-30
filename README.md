# Redis Operator

A simple redis operator written using the operator-sdk

## Deploying

To deploy the operator simply runtime

```
$ kubectl apply -f deploy
```

This will deploy the operator, CRD, and rbac with an example redis setup with 1
replica.

This does not currently deploy a functioning cluster

## TODO

Deploy a full redis cluster
