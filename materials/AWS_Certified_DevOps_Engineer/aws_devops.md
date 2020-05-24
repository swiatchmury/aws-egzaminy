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
=> solidnie omawia wiele zagadnień

**AWS Developer Tools Deep Dive** - *Craig Arcuri* (15h 54m)

**Cloudformation Deep Dive** - *Craig Arcuri* (15h 47m)

### Udemy

[AWS Certified DevOps Engineer Professional 2020 - Hands On!](https://www.udemy.com/course/aws-certified-devops-engineer-professional-hands-on/) - *Stephane Maarek* (20h)
=> najbardziej aktualny pod kątem egzaminu; ponadto bardzo dobrze pokazuje integrację różnych usług (co jest istotne na tym egzaminie)

### Testy

ACloudGuru - AWS Certified DevOps Engineer - Exam Simulator

[Udemy - AWS Certified DevOps Engineer Professional Practice Exams](https://www.udemy.com/course/aws-certified-devops-engineer-professional-practice-exams-amazon)

[Whizlabs - AWS Certified DevOps Engineer Professional](https://www.whizlabs.com/aws-devops-certification-training/practice-tests/)

[Braincert - AWS Certified DevOps Engineer – Professional DOP-C01 Practice Exams](https://www.braincert.com/course/10809-AWS-Certified-DevOps-Engineer-%E2%80%93-Professional-Practice-Exams)

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

[Manual Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-manual-scaling.html)

[Dynamic Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scale-based-on-demand.html)

[Target Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scaling-target-tracking.html)

[Scheduled Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/schedule_time.html)

[AutoScaling LifeCycle Hooks](https://docs.aws.amazon.com/autoscaling/ec2/userguide/lifecycle-hooks.html)

[AutoScaling Cooldown](https://docs.aws.amazon.com/autoscaling/ec2/userguide/Cooldown.html)

[FAQ](https://aws.amazon.com/ec2/autoscaling/faqs/)

Choosing metrics for AutoScaling:

*Not all metrics work for target tracking. This can be important when you are specifying a customized metric. The metric must be a valid utilization metric and describe how busy an instance is. The metric value must increase or decrease proportionally to the number of instances in the Auto Scaling group. That's so the metric data can be used to proportionally scale out or in the number of instances.*

#### Elastic Load Balancing

[FAQ](https://aws.amazon.com/elasticloadbalancing/faqs/)

[Listeners for Your Classic Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/elb-listener-config.html)

#### AWS CloudTrail FAQ

[FAQ](https://aws.amazon.com/cloudtrail/faqs/)

[Monitor Changes and Auto-Enable Logging in AWS CloudTrail](https://aws.amazon.com/blogs/mt/monitor-changes-and-auto-enable-logging-in-aws-cloudtrail/)

#### AWS CodeCommit

[Using Identity-Based Policies (IAM Policies) for CodeCommit](https://docs.aws.amazon.com/codecommit/latest/userguide/auth-and-access-control-iam-identity-based-access-control.html)

[CodeCommit Permissions Reference](https://docs.aws.amazon.com/codecommit/latest/userguide/auth-and-access-control-permissions-reference.html)

[Refining Access to Branches in AWS CodeCommit](https://aws.amazon.com/blogs/devops/refining-access-to-branches-in-aws-codecommit/)

[Manage Triggers for an AWS CodeCommit Repository](https://docs.aws.amazon.com/codecommit/latest/userguide/how-to-notify.html)

[Use CloudWatch Events to Start a Pipeline (CodeCommit Source)](https://docs.aws.amazon.com/codepipeline/latest/userguide/triggering.html)

#### AWS CodeBuild

[Build specification reference for CodeBuild](https://docs.aws.amazon.com/codebuild/latest/userguide/build-spec-ref.html)

[CodeBuild Samples](https://docs.aws.amazon.com/codebuild/latest/userguide/use-case-based-samples.html)

[Validating AWS CodeCommit Pull Requests with AWS CodeBuild and AWS Lambda](https://aws.amazon.com/blogs/devops/validating-aws-codecommit-pull-requests-with-aws-codebuild-and-aws-lambda/)

#### AWS CodeDeploy

[What is CodeDeploy?](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html)

[Working with Deployments in CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployments.html)

[AppSpec file structure hooks](https://docs.aws.amazon.com/codedeploy/latest/userguide/reference-appspec-file-structure-hooks.html)

[Monitoring Deployments with Amazon CloudWatch Events](https://docs.aws.amazon.com/codedeploy/latest/userguide/monitoring-cloudwatch-events.html)

[Monitoring Deployments with Amazon SNS Event Notifications](https://docs.aws.amazon.com/codedeploy/latest/userguide/monitoring-sns-event-notifications.html)

[Configure Advanced Options for a Deployment Group](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-groups-configure-advanced-options.html)

[Use the register-on-premises-instance Command (IAM User ARN) to Register an On-Premises Instance](https://docs.aws.amazon.com/codedeploy/latest/userguide/register-on-premises-instance-iam-user-arn.html)

[Use the register-on-premises-instance Command (IAM Session ARN) to Register an On-Premises Instance](https://docs.aws.amazon.com/codedeploy/latest/userguide/register-on-premises-instance-iam-session-arn.html)

[Working with Deployment Configurations in CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-configurations.html)

[Redeploy and Roll Back a Deployment with CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployments-rollback-and-redeploy.html)

#### AWS CodePipeline

[Best practices & Use cases](https://docs.aws.amazon.com/codepipeline/latest/userguide/best-practices.html)

[Detect and React to Changes in Pipeline State with Amazon CloudWatch Events](https://docs.aws.amazon.com/codepipeline/latest/userguide/detect-state-changes-cloudwatch-events.html)

[CodePipeline Actions Requirements](https://docs.aws.amazon.com/codepipeline/latest/userguide/reference-pipeline-structure.html#action-requirements)

[Invoke an AWS Lambda Function in a Pipeline in CodePipeline](https://docs.aws.amazon.com/codepipeline/latest/userguide/actions-invoke-lambda-function.html)

[Create and Add a Custom Action in CodePipeline](https://docs.aws.amazon.com/codepipeline/latest/userguide/actions-create-custom-action.html)

[Detect and React to Changes in Pipeline State with Amazon CloudWatch Events](https://docs.aws.amazon.com/codepipeline/latest/userguide/detect-state-changes-cloudwatch-events.html)

#### AWS CloudFormation

[DeletionPolicy Attribute](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-deletionpolicy.html)

[CreationPolicy Attribute](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-creationpolicy.html)

[Change Sets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-changesets.html)

[Best practices](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/best-practices.html)

[Intrinsic Functions](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)

[Best Practices for Deploying Applications on AWS CloudFormation Stacks](https://aws.amazon.com/blogs/devops/best-practices-for-deploying-applications-on-aws-cloudformation-stacks/)

#### AWS CloudWatch

[Scheduled EBS volume snapshots using Amazon CloudWatch](https://aws.amazon.com/premiumsupport/knowledge-center/cloudwatch-setup-ebs-snapshots/)

[Taking Scheduled Snapshot](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/TakeScheduledSnapshot.html)

[CloudWatch Events Event Examples From Supported Services](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/EventTypes.html#api_event_type)

[Creating a Billing Alarm to Monitor Your Estimated AWS Charges](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)

[New CloudWatch Events – Track and Respond to Changes to Your AWS Resources](https://aws.amazon.com/blogs/aws/new-cloudwatch-events-track-and-respond-to-changes-to-your-aws-resources/)

#### AWS Elastic Beanstalk

[Elastic Beanstalk concepts](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/concepts.html)

[Saved Configurations](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/environment-configuration-savedconfig.html)

[FAQ](https://aws.amazon.com/elasticbeanstalk/faqs/)

[Deployments](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.deploy-existing-version.html)

[Deployment Options](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.rolling-version-deploy.html)

[Blue / Green Deployments with Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.CNAMESwap.html)

[Elastic Beanstalk CLI](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html)

[Elastic Beanstalk with Docker](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker.html)

#### AWS OpsWorks

[Deploying Apps](https://docs.aws.amazon.com/opsworks/latest/userguide/workingapps-deploying.html)

[Installing Custom Cookbooks](https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-installingcustom-enable.html)

[Running Recipes](https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-assigningcustom.html)

[Running Docker on AWS OpsWorks](https://aws.amazon.com/blogs/devops/running-docker-on-aws-opsworks/)

[How to set up AWS OpsWorks Stacks auto healing notifications in Amazon CloudWatch Events](https://aws.amazon.com/blogs/mt/how-to-set-up-aws-opsworks-stacks-auto-healing-notifications-in-amazon-cloudwatch-events/)

[Using Berkshelf](https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-chef11-10.html#workingcookbook-chef11-10-berkshelf)

[Security Updates](https://docs.aws.amazon.com/opsworks/latest/userguide/workingsecurity-updates.html)

#### AWS Config

[What is AWS Config?](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)

[AWS Config Rules](https://github.com/awslabs/aws-config-rules)

[Creating Amazon CloudWatch Events Rule for AWS Config](https://docs.aws.amazon.com/config/latest/developerguide/monitor-config-with-cloudwatchevents.html)

[Multi-Account Multi-Region Data Aggregation](https://docs.aws.amazon.com/config/latest/developerguide/aggregate-data.html)

[How to Audit Your AWS Resources for Security Compliance by Using Custom AWS Config Rules](https://aws.amazon.com/blogs/security/how-to-audit-your-aws-resources-for-security-compliance-by-using-custom-aws-config-rules/)

#### AWS Trusted Advisor

[AWS Trusted Advisor Checklist](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/best-practice-checklist/)

[Monitoring Trusted Advisor check results with Amazon CloudWatch Events](https://docs.aws.amazon.com/awssupport/latest/user/cloudwatch-events-ta.html)

#### Amazon ECS i ECR

[Updating a Service](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/update-service.html)

[Task Definition Parameters](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)

#### AWS Lambda

[Best practices](https://docs.aws.amazon.com/lambda/latest/dg/best-practices.html)

[Using AWS Lambda with Amazon S3 Events](https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html)

[AWS Lambda Function Aliases](https://docs.aws.amazon.com/lambda/latest/dg/configuration-aliases.html)

#### AWS API Gateway

[Set up an API Gateway Canary Release Deployment](https://docs.aws.amazon.com/apigateway/latest/developerguide/canary-release.html)

#### Amazon RDS

[Cross-Region Automatic Disaster Recovery on Amazon RDS for Oracle Database Using DB Snapshots and AWS Lambda](https://aws.amazon.com/blogs/database/cross-region-automatic-disaster-recovery-on-amazon-rds-for-oracle-database-using-db-snapshots-and-aws-lambda/)

[Upgrading a MySQL Database with Reduced Downtime](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_UpgradeDBInstance.MySQL.html#USER_UpgradeDBInstance.MySQL.ReducedDowntime)

[Amazon RDS for Oracle Now Supports Managed Disaster Recovery and Data Proximity with Cross-region Read Replicas](https://aws.amazon.com/about-aws/whats-new/2019/11/amazon-rds-for-oracle-now-supports-managed-disaster-recovery-and-data-proximity-with-cross-region-read-replicas/)

[Using Amazon RDS Event Notification](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_Events.html)

[Near Zero Downtime Migration from MySQL to DynamoDB](https://aws.amazon.com/blogs/big-data/near-zero-downtime-migration-from-mysql-to-dynamodb/)

#### AWS Systems Manager

[AWS Systems Manager Inventory](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-inventory.html)

[AWS Systems Manager Patch Manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-patch.html)

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

#### S3 & Glacier

[Range retrieval for Amazon Glacier](https://aws.amazon.com/blogs/aws/new-range-retrieval-for-amazon-glacier/)

### Amazon ElasticSearch & Kibana

[Controlling Access to Kibana](https://docs.aws.amazon.com/elasticsearch-service/latest/developerguide/es-kibana.html#es-kibana-access)

### Amazon EC2

[Troubleshooting instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/TroubleshootingInstances.html)

### SAM

[Deploying Serverless Applications Gradually](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/automating-updates-to-serverless-apps.html)

### Amazon Kinesis

[Implement Serverless Log Analytics Using Amazon Kinesis Analytics](https://aws.amazon.com/blogs/big-data/implement-serverless-log-analytics-using-amazon-kinesis-analytics/)

## Pozostałe materiały

[Chcesz Wiedzieć, co Łączy AWS Lambdę, Aliasy i Kanarki?](https://chmurowisko.pl/co-laczy-aws-lambde-aliasy-i-kanarki/)

[Adding custom logic to AwS CodePipeline with AWS Lambda & Amazon CloudWatch Events](https://aws.amazon.com/blogs/devops/adding-custom-logic-to-aws-codepipeline-with-aws-lambda-and-amazon-cloudwatch-events/)

[Unit testing IAM policies across multiple accounts](https://aws.amazon.com/blogs/devops/unit-testing-iam-policies-across-multiple-accounts/)

[Serverless CI/CD for the Enterprise on the AWS Cloud](https://aws-quickstart.s3.amazonaws.com/quickstart-trek10-serverless-enterprise-cicd/doc/serverless-cicd-for-the-enterprise-on-the-aws-cloud.pdf)

[Earn Your DevOps Black Belt: Deployment Scenarios with AWS CloudFormation](https://www.slideshare.net/AmazonWebServices/earn-your-devops-black-belt-deployment-scenarios-with-aws-cloudformation-dev308r1-aws-reinvent-2018)

[Implementing GitFlow Usage AWS Code* services](https://aws.amazon.com/blogs/devops/implementing-gitflow-using-aws-codepipeline-aws-codecommit-aws-codebuild-and-aws-codedeploy/)

[Jenkins on AWS](https://d1.awsstatic.com/whitepapers/DevOps/Jenkins_on_AWS.pdf)

[Tagging resources](https://d1.awsstatic.com/whitepapers/aws-tagging-best-practices.pdf)

[Automate Your IT Operations Using AWS Step Functions and Amazon CloudWatch Events](https://aws.amazon.com/blogs/compute/automate-your-it-operations-using-aws-step-functions-and-amazon-cloudwatch-events/)

## How-to

[How to Automatically Revert and Receive Notifications About Changes to Your Amazon VPC Security Groups](https://aws.amazon.com/blogs/security/how-to-automatically-revert-and-receive-notifications-about-changes-to-your-amazon-vpc-security-groups/)

[How to Monitor AWS Account Configuration Changes and API Calls to Amazon EC2 Security Groups](https://aws.amazon.com/blogs/security/how-to-monitor-aws-account-configuration-changes-and-api-calls-to-amazon-ec2-security-groups/)

## Starsze materiały

Szczegóły techniczne i aktualny stan usług mogą nie być aktualne, ale opisane sposoby rozwiązania problemów nadal są aktualne:

[Creating a Serverless AMI Certification Pipeline](https://www.slideshare.net/davidski1/creating-a-serverless-ami-certification-pipeline)

## Praktyczne wskazówki odnośnie samego egzaminu

*Na podstawie doświadczeń szczęśliwych posiadaczy tego certyfikaty*

Nie ma się czego bać :-)
Pytania są scenariuszowe, dosyć długie, zwykle jednokrotnego wyboru
Każde słowo w scenariuszu ma znaczenie
Practice exam - trudniejszy niż rzeczywisty
Warto wziąć dodatkowe 30 min dla nieanglojęzycznych

### Szczegółowe wskazówki i zagadnienia do powtórzenia

- Powtórzyć informacje o usługach: Route53, EC2, Elastic Beanstalk, CloudFormation, CodePipeline, CodeBuild, CodeDeploy, CodeCommit, ECS, ECR, Auto Scaling, ALB, RDS, AWS Inspector, Lambda, CloudWatch (logs/event/metric), Step Function, SQS, SNS, Kinesis stream i Firehose, S3, Guardduty, OpsWorks, Systems Manager (patchowanie), Trusted Advisor, Config – oczywiście ten egzamin to składanie klocków w workflow wiec często jest po prostu usługa wymieniona jako jedna z flow, ale warto wiedzieć że tego można użyć
- RTO (Recovery Time Objective) & RPO (Recovery Point Objective) - warto wiedzieć, co to jest
[Disaster Recovery](https://en.wikipedia.org/wiki/Disaster_recovery) i na podstawie podanych czasów dobrać odpowiednie rozwiązania
- Rodzaje deploymentu: All at once, Rolling, Immutable, Blue/Green, Canary => w kontekście różnych usług, w tym Elastic Beanstalk. Dobór rodzaju deploymentu w zależności od wymagań takich jak: dopuszczalna przerwa w dostępności albo brak, koszty itd.
- Środowiska hybrydowe: monitorowanie za pomocą CloudWatch agent, możliwość deploymentu za pomocą CodeDeploy również na te środowiska
- Zrobienie AMI przyspiesza deployment aplikacji (a takze skraca czas uruchomienia instancji w ASG)
- ASG LifeCycle hooks
- RDS w wielu regionach, update RDS z minimalną niedostępnością
- Przesyłanie logów na jedno konto w środowisku multi-account: [Link](https://aws.amazon.com/pt/blogs/architecture/central-logging-in-multi-account-environments/)
- Jak zablokować klucz dostępowy AWS gdy wycieknie (np. znajdzie się na GitHubie) [Link](https://github.com/aws/Trusted-Advisor-Tools/tree/master/ExposedAccessKeys) i [Link](https://github.com/aws/Trusted-Advisor-Tools/tree/master/ExposedAccessKeys/stepbystep)
- OpsWorks: pojawia się - jako "zamydlacz" ale tez w prawidłowych odpowiedziach
- Flow CI/CD z wariantami: jedno czy wiele repozytoriów kodu; jeden czy wiele pipelinów
