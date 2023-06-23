# cluster-auto-scaller
1 create custome policy using the given json format.
2 attach this policy to the cluster node group
3 deploye the auto scaller pod in your cluster

Your cluster can now auto scale up and auto scale down when ever any pod is in
pending state becuase of lack of memory and cpu, new node will be created and
this pending pods will be sheduled on that node. 
