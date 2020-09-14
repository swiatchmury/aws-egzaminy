# AWS Certified Solutions Architect - Professional

W tej sekcji znajdziesz materiały dotyczące egzaminu *AWS Certified Solutions Architect - Professional*.

## Informacje ogólne

Ten egzamin jest dla Ciebie jeśli pracowałeś(aś) z już z AWS. Im więcej doświadczenia, tym lepiej :-)

### Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

- [A Cloud Guru - AWS Certified Solutions Architect - Professional](https://acloud.guru/learn/aws-certified-solutions-architect-professional).
  - [@afronski](https://github.com/afronski): IMHO kurs jest słaby i pobieżny. W zasadzie do przerobienia w kilka dni i do zapomnienia.
- [Linux Academy - AWS Certified Solutions Architect - Professional](https://linuxacademy.com/course/aws-certified-solutions-architect-professional-2018/).
- [A Cloud Guru - Exam Simulator](https://acloud.guru/exam-simulator).
- [WhizLabs Quizzes](https://www.whizlabs.com/aws-solutions-architect-professional/).
- [QwikLabs](https://www.qwiklabs.com/).

### Praktyczne wskazówki odnośnie samego egzaminu

[@afronski](https://github.com/afronski):

> Ponad 4 miesiące przygotowań *dzień w dzień* i wyszedłem z egzaminu spocony, 5 minut przed końcem czasu. Poziom trudności jest niebotycznie wysoki, ten egzamin odstaje od wszystkiego co zdawałem wcześniej. Po 140 minutach ze 180 miałem 27 pytań oflagowanych do dalszego review a i tak pędziłem jak szalony żeby zdążyć je przeglądnąć wszystkie. Rozrzut jak *w ruskim czołgu*. Pytania od AppStream do szczegółów z Direct Connect, przez masę szczegółów dot. typowych usług. Strasznie dużo podchwytliwych z 2 odpowiedziami, które mają sens i są prawidłowe, ale w zależności od jednego słowa w pytaniu na 7 długich zdań wybrać trzeba jedną. Źle przeczytasz i jesteś w *dupie*. :wink: Ogólnie było mało pytań wielokrotnego wyboru. Większość pytań dot. sieci, *HA*, sporo o *Serverless*, *Elastic Beanstalk*, o dziwo kilka o *Elasticsearch*, mało o *RDS* i bazach danych. Może po 3-4 o *Kinesis* albo *DynamoDB*. **Prawie w ogóle filozofii z whitepapers takich jak WAF albo CAF.** Polecam **BARDZO DOKŁADNIE** czytać pytania, i wyrobić sobie umiejętność szybkiej eliminacji bzdurnych fragmentów pytania - czasu jest naprawdę mało.

[@afronski](https://github.com/afronski):

> Bedąc kompletnie szczerym jeśli chodzi o sposób nauki: poświęć jak najwięcej czasu na wideo, szczególnie te *Deep Dive* oraz poziom 300 i wyżej z (lat 2018 i późniejszych). Oglądaj je na prędkości 1.5x i pomijaj fragmenty marketingowe oraz rób notatki. A potem **masa ćwiczeń**. *IMHO* *AWS Whitepapers* są w większości stare i nieaktualne, co więcej na egzaminie teorii dot. WAF albo CAF prawie w ogóle nie ma - a jeśli jest to będziesz w stanie oprzeć się o własne doświadczenie.

## Zadania

Poniżej to nie jest wyczerpująca lista, ale bardzo przydatna wiedza, żeby złapać "*łatwe punkty*":

- Zapoznaj się z *AWS Systems Manager*.
- Trzeba znać ograniczenia i typy *Direct Connect Virtual Interfaces*.
- Poznaj *AWS Budgets*.
- Polecam mocno pobawić się *AWS Elastic Beanstalk*, w szczególności `.ebextensions`.
- Szyfrowane i nieszyfrowane *wolumeny*, *snapshoty* z *Amazon EBS*.
  - Musisz znać **na wylot** cały proces i jego ograniczenia, także dla *AWS KMS CMK*.
- *AWS Organizations* oraz *SCP*.
  - Trzeba bardzo dobrze znać ten element!
- *AWS Trusted Advisor*, *AWS Config* oraz *Amazon CloudWatch Events*.
  - W szczególności integracje i ograniczenia.
    - *Custom Rules* z *AWS Config*.
- Przeczytaj *FAQ* dla *AWS WAF*.
- Przeczytaj *FAQ* dla *Amazon EFS* (i wiedz jakie są różnice pomiędzy nim a *AWS Storage Gateway* i *FSx*).
  - Zapoznaj się z *AWS DataSync*.
- Przeczytaj *FAQ* dla *AWS Server Migration Services*.
  - Jakie rodzaje i platformy wirtualizacji wspiera?
- Przeczytaj *FAQ* dla *Amazon Simple Workflow Service*.
  - Jaka jest różnica pomiędzy tym a *AWS StepFunctions*?

## AWS Whitepapers

Lista interesujących dokumentów rekomendowanych do przeczytania przed przystąpieniem do egzaminu.

### **Must-Read**

- [AWS Well-Architected Framework](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf).
- [An Overview of the AWS Cloud Adoption Framework](https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf).
- [AWS Cloud Transformation Maturity Model](https://d1.awsstatic.com/whitepapers/AWS-Cloud-Transformation-Maturity-Model.pdf).
- [AWS Migration Whitepaper](https://d1.awsstatic.com/whitepapers/Migration/aws-migration-whitepaper.pdf).
- [Infrastructure as Code](https://d1.awsstatic.com/whitepapers/DevOps/infrastructure-as-code.pdf).

#### *Well-Architected Framework Pillars*

- [AWS WAF - Cost Optimization Pillar](https://d1.awsstatic.com/whitepapers/architecture/AWS-Cost-Optimization-Pillar.pdf).
- [AWS WAF - Reliability Pillar](https://d1.awsstatic.com/whitepapers/architecture/AWS-Reliability-Pillar.pdf).

### Storage

- [AWS Storage Services Overview](https://d1.awsstatic.com/whitepapers/AWS%20Storage%20Services%20Whitepaper-v9.pdf).
- [Building Big Data Storage Solutions (Data Lakes) for Maximum Flexibility](https://d1.awsstatic.com/whitepapers/Storage/data-lake-on-aws.pdf).

### Security

- [AWS Multiple Accounts Security Strategy](https://d0.awsstatic.com/aws-answers/AWS_Multi_Account_Security_Strategy.pdf).
- [AWS Security Best Practices](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf).
- [AWS Best Practices for DDoS Resiliency](https://d1.awsstatic.com/whitepapers/Security/DDoS_White_Paper.pdf).
- [Overview of AWS Security - Network Security](https://d1.awsstatic.com/whitepapers/Security/Networking_Security_Whitepaper.pdf).

### Networking

- [Amazon Virtual Private Cloud Connectivity Options](https://d1.awsstatic.com/whitepapers/aws-amazon-vpc-connectivity-options.pdf).
- [Building a Scalable and Secure Multi-VPC AWS Network Infrastructure](https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf).
- [Integrating AWS with Multiprotocol Label Switching](https://d1.awsstatic.com/whitepapers/Networking/integrating-aws-with-multiprotocol-label-switching.pdf).

### Use Cases and Architecture

- [Introduction to Scalable Gaming Patterns on AWS](https://d1.awsstatic.com/whitepapers/aws-scalable-gaming-patterns.pdf).
- [Web Application Hosting in the AWS Cloud](https://d1.awsstatic.com/whitepapers/aws-web-hosting-best-practices.pdf).
- [Backup and Recovery Approaches Using AWS](https://d1.awsstatic.com/whitepapers/Storage/Backup_and_Recovery_Approaches_Using_AWS.pdf).
- [Automating Elasticity](https://d1.awsstatic.com/whitepapers/cost-optimization-automating-elasticity.pdf).
- [Implementing Microservices on AWS](https://d1.awsstatic.com/whitepapers/microservices-on-aws.pdf).
- [Overview of Deployment Options on AWS](https://d1.awsstatic.com/whitepapers/overview-of-deployment-options-on-aws.pdf).
- [Practicing Continuous Integration and Continuous Delivery on AWS](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf).

### Databases

- [Getting Started with Amazon Aurora](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-ug.pdf#CHAP_GettingStartedAurora).
- [Migrating Applications Running Relational Databases to AWS](https://d1.awsstatic.com/whitepapers/Migration/migrating-applications-to-aws.pdf).
- [Performance at Scale with Amazon ElastiCache](https://d1.awsstatic.com/whitepapers/performance-at-scale-with-amazon-elasticache.pdf).
- [Multi-Tenant SaaS Storage Strategies](https://d1.awsstatic.com/whitepapers/Multi_Tenant_SaaS_Storage_Strategies.pdf).

### Cost-Efficiency

- [Introduction to AWS Economics](https://d1.awsstatic.com/whitepapers/introduction-to-aws-cloud-economics-final.pdf).
- [Amazon EC2 Reserved Instances and Other AWS Service Reservation Models](https://d1.awsstatic.com/whitepapers/cost-optimization-reservation-models.pdf).
  - [@afronski](https://github.com/afronski): Jeśli miałbym wymienić jakiś dokument, który był najważniejszy dla mnie to będzie ten - jeśli znasz to na wylot to całkiem sporo łatwych punktów przez to wpada.
- [Leveraging Amazon EC2 Spot Instances at Scale](https://d1.awsstatic.com/whitepapers/cost-optimization-leveraging-ec2-spot-instances.pdf).
- [Maximizing Value with AWS: Achieve Total Cost of Operation Benefits Using Cloud Computing](https://d1.awsstatic.com/whitepapers/total-cost-of-operation-benefits-using-aws.pdf).

## Usługi AWS, które warto znać

- Szczerze? Wszystkie, patrz wyżej. :wink:

## Lista nagrań re:Invent

Playlista od [Wojtka Gawrońskiego](https://github.com/afronski):

- [AWS Certified Solutions Architect - Professional 2019](https://www.youtube.com/playlist?list=PLCRlJJDoP5o8PxxCOPe3cZIw-4-uUAeV_).

Lista filmów od [Andrzeja Kaczyńskiego](https://github.com/andrewkaczynski):

- [AWS re:Invent 2017: Deep Dive on Amazon S3 & Amazon Glacier Storage Management with (STG311)](https://www.youtube.com/watch?v=SUWqDOnXeDw).
- [AWS re:Invent 2017: Deep Dive on Amazon Relational Database Service (RDS) (DAT302)](https://www.youtube.com/watch?v=TJxC-B9Q9tQ).
- [AWS re:Invent 2017: ElastiCache Deep Dive: Best Practices and Usage Patterns (DAT305)](https://www.youtube.com/watch?v=_YYBdsuUq2M).
- [AWS re:Invent 2017: Deep Dive: Using Hybrid Storage with AWS Storage Gateway to Solv (STG309)](https://www.youtube.com/watch?v=9wgaV70FeaM).
- [AWS re:Invent 2017: Networking Many VPCs: Transit and Shared Architectures (NET404)](https://www.youtube.com/watch?v=KGKrVO9xlqI).
- [AWS re:Invent 2017: Another Day, Another Billion Flows (NET405)](https://www.youtube.com/watch?v=8gc2DgBqo9U).
- [AWS re:Invent 2017: Deep Dive into the New Network Load Balancer (NET304)](https://www.youtube.com/watch?v=z0FBGIT1Ub4).
- [AWS re:Invent 2017: Best Practices for Managing Security Operations on AWS (SID206)](https://www.youtube.com/watch?v=gjrcoK8T3To).
- [AWS re:Invent 2017: Security Anti-Patterns: Mistakes to Avoid (FSV301)](https://www.youtube.com/watch?v=tzJmE_Jlas0).
- [AWS re:Invent 2017: Architecting Security and Governance Across a Multi-Account Stra (SID331)](https://www.youtube.com/watch?v=71fD8Oenwxc).
- [AWS re:Invent 2017: How to Assess Your Organization's Readiness to Migrate at Scale (ENT211)](https://www.youtube.com/watch?v=id-PY0GBHXA).
- [AWS re:Invent 2017: Migrating Databases and Data Warehouses to the Cloud: Getting St (DAT317)](https://www.youtube.com/watch?v=Y33TviLMBFY).
- [AWS re:Invent 2017: Scaling Up to Your First 10 Million Users (ARC201)](https://www.youtube.com/watch?v=w95murBkYmU).
- [AWS re:Invent 2017: Learn to Build a Cloud-Scale WordPress Site That Can Keep Up wit (STG324)](https://www.youtube.com/watch?v=dPdac4LL884).
- [AWS re:Invent 2017: Elastic Load Balancing Deep Dive and Best Practices (NET402)](https://www.youtube.com/watch?v=9TwkMMogojY).
- [AWS re:Invent 2017: Models of Availability (ARC321)](https://www.youtube.com/watch?v=xc_PZ5OPXcc).
- [AWS re:Invent 2017: How to Design a Multi-Region Active-Active Architecture (ARC319)](https://www.youtube.com/watch?v=RMrfzR4zyM4).
- [AWS re:Invent 2017: Disaster Recovery with AWS: Tiered Approaches to Balance Cost wi (ENT322)](https://www.youtube.com/watch?v=a7EMou07hRc).
- [AWS re:Invent 2017: Deep Dive on AWS CloudFormation (DEV317)](https://www.youtube.com/watch?v=01hy48R9Kr8).
- [AWS re:Invent 2017: Moving to Containers: Building with Docker and Amazon ECS (CON310)](https://www.youtube.com/watch?v=Qik9LBktjgs).
- [AWS re:Invent 2017: Continuous Integration Best Practices for Software Development T (DEV322)](https://www.youtube.com/watch?v=GEPJ7Lo346A).
- [AWS re:Invent 2017: Building a Solid Business Case for Cloud Migration (ENT203)](https://www.youtube.com/watch?v=CcspJkc7zqg).
- [AWS re:Invent 2017: Running Lean Architectures: How to Optimize for Cost Efficiency (ARC303)](https://www.youtube.com/watch?v=XQFweGjK_-o).
- [AWS re:Invent 2017: How Hess Has Continued to Optimize the AWS Cloud After Migrating (ENT218)](https://www.youtube.com/watch?v=1Z4BfRj2FiU).
- [AWS re:Invent 2018: Become an IAM Policy Master in 60 Minutes or Less (SEC316-R1)](https://www.youtube.com/watch?v=YQsK4MtsELU).
- [AWS re:Invent 2018: AWS DataSync - Automate & accelerate online data transfer (STG324)](https://www.youtube.com/watch?v=PA3PuU3beFI).
- [AWS re:Inforce 2019: Managing Multi-Account AWS Environments Using AWS Organizations (FND314)](https://www.youtube.com/watch?v=fxo67UeeN1A).
