# [IN PROGRESS] AWS Certified DevOps Engineer - Professional

## Informacje ogólne i linki

[Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-devops-pro/AWS%20Certified%20DevOps%20Engineer%20Professional_Exam%20Guide_v1.5_FINAL%20(2).pdf)

[Przykładowe pytania](https://d1.awsstatic.com/training-and-certification/docs-devops-pro/AWS%20Certified%20DevOps%20Engineer%20-%20Professional_Sample%20Questions.pdf)

[AWS DevOps Blog](https://aws.amazon.com/blogs/devops/)

## Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

### AWS Training

[Exam Readiness Training (free)](https://www.aws.training/Details/eLearning?id=34146)

### Linux Academy

**AWS Certified DevOps Engineer - Professional Level** - *Craig Arcuri* (32h 24m)

**AWS Developer Tools Deep Dive** - *Craig Arcuri* (15h 54m)

**Cloudformation Deep Dive** - *Craig Arcuri* (15h 47m)

### Udemy

[AWS Certified DevOps Engineer Professional 2020 - Hands On!](https://www.udemy.com/course/aws-certified-devops-engineer-professional-hands-on/) - *Stephane Maarek* (20h)

## AWS Whitepapers

[Running Containerized Microservices on AWS](https://d1.awsstatic.com/training-and-certification/docs-devops-pro/running-containerized-microservices-on-aws.pdf)

[Microservices on AWS](https://d1.awsstatic.com/training-and-certification/docs-devops-pro/microservices-on-aws.pdf)

[Infrastructure as Code](https://d1.awsstatic.com/training-and-certification/docs-devops-pro/infrastructure-as-code.pdf)

[Blue/Green deployments](https://d1.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf)

[Practicing Continuous Integration and Continuous Delivery on AWS](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf)

[Risk and Compliance](https://d0.awsstatic.com/whitepapers/compliance/AWS_Risk_and_Compliance_Whitepaper.pdf)

## Usługi AWS, które trzeba znać

#### Amazon EC2 AutoScaling

[Changing the Lauch Configuration of an Autoscaling Group](https://docs.aws.amazon.com/autoscaling/ec2/userguide/change-launch-config.html)

[Autoscaling based on metrics]()

[Manual Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-manual-scaling.html)

[Dynamic Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scale-based-on-demand.html)

[Target Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scaling-target-tracking.html)

Choosing metrics:

*Not all metrics work for target tracking. This can be important when you are specifying a customized metric. The metric must be a valid utilization metric and describe how busy an instance is. The metric value must increase or decrease proportionally to the number of instances in the Auto Scaling group. That's so the metric data can be used to proportionally scale out or in the number of instances.*

[Scheduled Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/schedule_time.html)

[FAQ](https://aws.amazon.com/ec2/autoscaling/faqs/)

#### Elastic Load Balancing

[FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)

[Listeners for Your Classic Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/elb-listener-config.html)

#### AWS CloudTrail FAQ

[FAQ](https://aws.amazon.com/cloudtrail/faqs/)

#### AWS CodeCommit

[Use CloudWatch Events to Start a Pipeline (CodeCommit Source)](https://docs.aws.amazon.com/codepipeline/latest/userguide/triggering.html)

#### AWS CodeBuild

#### AWS CodeDeploy

#### AWS CodePipeline

[Detect and React to Changes in Pipeline State with Amazon CloudWatch Events](https://docs.aws.amazon.com/codepipeline/latest/userguide/detect-state-changes-cloudwatch-events.html)

#### AWS CloudFormation

[DeletionPolicy Attribute](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-deletionpolicy.html)

[CreationPolicy Attribute](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-creationpolicy.html)

[ChangeSet](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-changesets.html)

[Best practices](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/best-practices.html)

[Intrinsic Functions](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)

#### AWS CloudWatch

[Scheduled EBS volume snapshots using Amazon CloudWatch](https://aws.amazon.com/premiumsupport/knowledge-center/cloudwatch-setup-ebs-snapshots/)

[Taking Scheduled Snapshot](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/TakeScheduledSnapshot.html)

[CloudWatch Events Event Examples From Supported Services](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/EventTypes.html#api_event_type)

[Creating a Billing Alarm to Monitor Your Estimated AWS Charges](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)

#### AWS Elastic Beanstalk

[Elastic Beanstalk concepts](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/concepts.html)

[FAQ](https://aws.amazon.com/elasticbeanstalk/faqs/)

[Deployments](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.deploy-existing-version.html)

[Deployment Options](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.rolling-version-deploy.html)

[Blue / Green Deployments with Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.CNAMESwap.html)

[Elastic Beanstalk CLI](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html)

[Elastic Beanstalk with Docker](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker.html)

#### AWS OpsWorks

[Deploying Apps](https://docs.aws.amazon.com/opsworks/latest/userguide/workingapps-deploying.html)

[Installing Custom Cookbooks](https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-installingcustom-enable.html)

[Running Docker on AWS OpsWorks](https://aws.amazon.com/blogs/devops/running-docker-on-aws-opsworks/)

#### AWS Config

[What is AWS Config?](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)

[AWS Config Rules](https://github.com/awslabs/aws-config-rules)

[Creating Amazon CloudWatch Events Rule for AWS Config](https://docs.aws.amazon.com/config/latest/developerguide/monitor-config-with-cloudwatchevents.html)

[Multi-Account Multi-Region Data Aggregation](https://docs.aws.amazon.com/config/latest/developerguide/aggregate-data.html)

#### AWS Trusted Advisor

#### Amazon ECS i ECR

[Updating a Service](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/update-service.html)

[Task Definition Parameters](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)

#### AWS Lambda

[Using AWS Lambda with Amazon S2 Events](https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html)

[AWS Lambda Function Aliases](https://docs.aws.amazon.com/lambda/latest/dg/configuration-aliases.html)

#### AWS API Gateway

[Set up an API Gateway Canary Release Deployment](https://docs.aws.amazon.com/apigateway/latest/developerguide/canary-release.html)

#### Amazon RDS

[Cross-Region Automatic Disaster Recovery on Amazon RDS for Oracle Database Using DB Snapshots and AWS Lambda](https://aws.amazon.com/blogs/database/cross-region-automatic-disaster-recovery-on-amazon-rds-for-oracle-database-using-db-snapshots-and-aws-lambda/)

[Upgrading a MySQL Database with Reduced Downtime](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_UpgradeDBInstance.MySQL.html#USER_UpgradeDBInstance.MySQL.ReducedDowntime)

[Amazon RDS for Oracle Now Supports Managed Disaster Recovery and Data Proximity with Cross-region Read Replicas](https://aws.amazon.com/about-aws/whats-new/2019/11/amazon-rds-for-oracle-now-supports-managed-disaster-recovery-and-data-proximity-with-cross-region-read-replicas/)

[Using Amazon RDS Event Notification](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Events.html)

#### AWS Systems Manager

[Systems Manager Inventory](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-inventory.html)

#### IAM

[IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)

[Providing Access to AWS Accounts Owned by Third Parties](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_common-scenarios_third-party.html)

[About Web Identity Federation](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_providers_oidc.html)

[Getting Credential Reports for an AWS Account](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_getting-report.html)

[AWS::IAM::InstanceProfile](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-iam-instanceprofile.html)

[Choosing Between Managed Policies and Inline Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html#choosing-managed-or-inline)

[Delegate Access Across AWS Accounts Using IAM Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html)

#### AWS Discovery Service

[What is AWS Application Discovery Service](https://docs.aws.amazon.com/application-discovery/latest/userguide/what-is-appdiscovery.html)

## Pozostałe materiały

[Chcesz Wiedzieć, co Łączy AWS Lambdę, Aliasy i Kanarki?](https://chmurowisko.pl/co-laczy-aws-lambde-aliasy-i-kanarki/)

[Adding custom logic to AwS CodePipeline with AWS Lambda & Amazon CloudWatch Events](https://aws.amazon.com/blogs/devops/adding-custom-logic-to-aws-codepipeline-with-aws-lambda-and-amazon-cloudwatch-events/)

[Unit testing IAM policies across multiple accounts](https://aws.amazon.com/blogs/devops/unit-testing-iam-policies-across-multiple-accounts/)

[Serverless CI/CD for the Enterprise on the AWS Cloud](https://aws-quickstart.s3.amazonaws.com/quickstart-trek10-serverless-enterprise-cicd/doc/serverless-cicd-for-the-enterprise-on-the-aws-cloud.pdf)

[Earn Your DevOps Black Belt: Deployment Scenarios with AWS CloudFormation](https://www.slideshare.net/AmazonWebServices/earn-your-devops-black-belt-deployment-scenarios-with-aws-cloudformation-dev308r1-aws-reinvent-2018)

## How-to

[How to Automatically Revert and Receive Notifications About Changes to Your Amazon VPC Security Groups](https://aws.amazon.com/blogs/security/how-to-automatically-revert-and-receive-notifications-about-changes-to-your-amazon-vpc-security-groups/)

[How to Monitor AWS Account Configuration Changes and API Calls to Amazon EC2 Security Groups](https://aws.amazon.com/blogs/security/how-to-monitor-aws-account-configuration-changes-and-api-calls-to-amazon-ec2-security-groups/)

## Starsze materiały

Szczegóły techniczne i aktualny stan usług mogą nie być aktualne, ale opisane sposoby rozwiązania problemów nadal są aktualne:

[Creating a Serverless AMI Certification Pipeline](https://www.slideshare.net/davidski1/creating-a-serverless-ami-certification-pipeline)
