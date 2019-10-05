# Deploy a high-availability web app using CloudFormation

![Project AWS architecture](images/udacity-aws-architecture-diagram.png)

# Usuage:

Use below command to deploy the stack.

```
 ./create-stack.sh UdagramProject udagram-project.yml udagram-project-parameters.json
```

# Other installation [optional]

If you would like to deploy infra/network structure and servers separately, you can follow below commands.

Create network stack:

```
 ./create-stack.sh UdagramProjectNetwork udagram-network.yml udagram-network-parameters.json
```

Deploy server stack:

```
 ./create-stack.sh UdagramProjectServers udagram-servers.yml udagram-servers-parameters.json
```

# Results of Cloudformation script deployment

1. Creating stack

![create-stack](images/create-stack.png)

2. Stack in-progress status on the cloudformation dashboard

![create-stack-in-progress](images/create-stack-in-progress.png)

3. Stack Events

![stack-events](images/stack-events.png)

4. Stack Resources

![stack-resources](images/stack-resources.png)

5. Stack Outputs

![stack-output](images/stack-output.png)

6. Stack Parameters

![stack-parameter](images/stack-parameter.png)

7. Stack complete status

![stack-complete-status](images/stack-complete-status.png)

8. VPC

![VPC](images/VPC.png)

9. Subnets

![subnets](images/subnets.png)

10. Routing tables

![route-tables](images/route-tables.png)

11. Internet Gateways

![internet-gateway](images/internet-gateway.png)

12. NAT Gateways

![nat-gateway](images/nat-gateway.png)

13. Secutiry Groups

![security-groups](images/security-groups.png)

14. EC2 instances

![running-instances](images/running-instances.png)

15. Load Balancer

![load-balancer](images/load-balancer.png)

16. Target Groups

![target-group](images/target-group.png)

17. Launch Configuration

![launch-configuration](images/launch-configuration.png)

18. Auto Scaling Groups

![auto-scaling-group](images/auto-scaling-group.png)

19. S3 (index.html)

![s3](images/s3.png)

20. Working test (Clouformation stack Output)

![working-test](images/working-test.png)

21. Udagram website result

![udagram-website-url](images/udagram-website-url.png)




