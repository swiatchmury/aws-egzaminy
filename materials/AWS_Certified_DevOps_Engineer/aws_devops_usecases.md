# AWS DevOps Use Cases

## Logs

### Cost effective way to ensure that logs are saved even during unplanned instance failure & saved forever

1. Use Amazon S3 lifecycle policy to move logs to Glacier
2. Configure an application to write logs to a separate EBS volume and set `delete on termination` to false; write a script that will transfer logs to S3 periodically
3. Clean unused volumes: first attach them to an instance, transfer logs to S3 and then remove volume.

## Deployments

### Blue / Green deployment with Autoscaling Group, Classic Load Balancer & highly available RDS

1. Create a Classic Load Balancer & Auto Scaling group for each environment
2. Use Amazon Route53 & create weighted alias records for each environment
3. Use RDS db instance with multi-AZ configuration. Connect both environments to the instance

### Upgrade RDS to the latest major version of DB with minimum downtime using CloudFormation

1. Update the EngineVersion property of the `AWS::RDS::DBInstance` resource type to the latest desired version
2. Launch a second stack.
3. Make the new RDS instance a read replica
4. When the status of the read replica is `AVAILABLE`, promote the replica to be a master

[Upgrading a MySQL Database with Reduced Downtime](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_UpgradeDBInstance.MySQL.html#USER_UpgradeDBInstance.MySQL.ReducedDowntime)

## Collecting info about instances - on-premises & EC2

1. Use AWS System Manager agent - Inventory

[Documentation](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-inventory.html)