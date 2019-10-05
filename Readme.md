# Deploy a high-availability web app using CloudFormation

![Project AWS architecture](images/udagram-project-aws-architecture-diagram.pdf)

# Usuage:

Use below command to deploy the stack.

```
 ./create-stack.sh UdagramProject udagram-project.yml udagram-project-parameters.json
```

# Other installation [optional]

If you would like to deploy infra/network structure and servers differently, you can follow below commands.

Create network stack:

```
 ./create-stack.sh UdagramProjectNetwork udagram-network.yml udagram-network-parameters.json
```

Deploy server stack:

```
 ./create-stack.sh UdagramProjectServers udagram-servers.yml udagram-servers-parameters.json
```

# Results of Cloudformation script

1. Creating stack

![create-stack](images/create-stack.png)


