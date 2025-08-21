if we by mistake more pods with the same tag then it would be in a terminating state


few common commands

kubectl edit replicaset myreplicaset.  ---> this is on the fly config file change be careful

scale the number of replica

kubectl sclae replicaset myreplicaset --replicas=<no-of-replica set>