# AWS Certified Database Specialty

## Informacje ogólne

Jeśli nie pracowałeś(aś) z AWS wcześniej, ten egzamin nie jest dla Ciebie.

### Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

**Nie ma na ten moment dedykowanego kursu przygotowującego do tego certyfikatu**.

- Kursy na [A Cloud Guru](https://acloud.guru/):
  - [Introduction to Amazon RDS](https://acloud.guru/learn/aws-rds)
  - [AWS DynamoDB - From Beginner to Pro](https://acloud.guru/learn/aws-dynamodb)
- Kursy na [Linux Academy](https://linuxacademy.com):
  - [Amazon Aurora – Cloud SQL DB Essentials](https://linuxacademy.com/course/amazon-aurora-cloud-sql-db-essentials/)
- [QwikLabs](https://www.qwiklabs.com).
  - [@afronski](https://github.com/afronski): Polecam w szczególności ćwiczenia dotyczące *AWS DMS*.

### Praktyczne wskazówki odnośnie samego egzaminu

- [Wojtek Gawroński](https://github.com/afronski) zebrał swoje przemyślenia i informacje tutaj:
  - [The unofficial guide to AWS Certified Database Specialty Exam](https://awsgentleman.com/2020/03/16/the-unofficial-guide-to-aws-certified-database-specialty-exam/).

[@afronski](https://github.com/afronski):

> Bedąc kompletnie szczerym jeśli chodzi o sposób nauki: poświęć jak najwięcej czasu na wideo, szczególnie te *Deep Dive* oraz poziom 300 i wyżej z (lat 2018 i późniejszych). Oglądaj je na prędkości 1.5x i pomijaj fragmenty marketingowe oraz rób notatki. A potem **masa ćwiczeń**. *IMHO* *AWS Whitepapers* są w większości stare i nieaktualne.

## AWS Whitepapers

Lista interesujących dokumentów rekomendowanych do przeczytania przed przystąpieniem do egzaminu:

### Design and Architecture

- [SaaS Storage Strategies: Building a Multi-Tenant Storage Model on AWS](https://d1.awsstatic.com/whitepapers/Multi_Tenant_SaaS_Storage_Strategies.pdf).
  - [@afronski](https://github.com/afronski): Super pożyteczny dokument.

### Amazon RDS and Aurora

- [Determining the IOPS Needs for Oracle Database on AWS](https://d1.awsstatic.com/whitepapers/determining-iops-needs-for-oracle-database-on-aws.pdf).
- [Best Practices for Running Oracle Database on AWS](https://d1.awsstatic.com/whitepapers/best-practices-for-running-oracle-database-on-aws.pdf).
- [Amazon Aurora MySQL Database Administrator's Handbook](https://d1.awsstatic.com/whitepapers/RDS/amazon-aurora-connection-management-handbook.pdf).
  - [@afronski](https://github.com/afronski): Super pożyteczny materiał, szczególnie jeśli nie pracujesz z *Aurorą*.

### AWS Database Migration Service

- [AWS Database Migration Service Best Practices](https://d1.awsstatic.com/whitepapers/RDS/AWS_Database_Migration_Service_Best_Practices.pdf).
  - [@afronski](https://github.com/afronski): Obowiązkowy materiał!
- [Amazon Aurora Migration Handbook](https://d1.awsstatic.com/whitepapers/Migration/amazon-aurora-migration-handbook.pdf).
- [Migrating Your Databases to Amazon Aurora](https://d1.awsstatic.com/whitepapers/RDS/Migrating%20your%20databases%20to%20Amazon%20Aurora.pdf).

### Amazon DynamoDB

- [Comparing the Use of Amazon DynamoDB and Apache HBase for NoSQL](https://d1.awsstatic.com/whitepapers/AWS_Comparing_the_Use_of_DynamoDB_and_HBase_for_NoSQL.pdf).
  - [@afronski](https://github.com/afronski): Ten może wyglądać jak stary i nieaktualny, ale to w sumie dobre podsumowanie wielu kwestii dotyczących *DynamoDB*, część dot. *HBase* możesz śmiało pominąć.
- [Best Practices for Migrating from RDBMS to Amazon DynamoDB: Leverage the Power of NoSQL for Suitable Workloads](https://d1.awsstatic.com/whitepapers/migration-best-practices-rdbms-to-dynamodb.pdf).

### Other Services

- [Migrating to Apache HBase on Amazon S3 on Amazon EMR](https://d1.awsstatic.com/whitepapers/Migrating_to_Apache_Hbase_on_Amazon_S3_on_Amazon_EMR.pdf).
  - [@afronski](https://github.com/afronski): Ten był ciekawy dla mnie osobiście, ale ponieważ to *HBase*, więc możesz to śmiało pominąć.
- [Getting Started with Amazon DocumentDB (with MongoDB Compatibility)](https://d1.awsstatic.com/whitepapers/getting-started-with-amazon-documentdb.pdf?did=wp_card&trk=wp_card).
- [Use Amazon Elasticsearch Service to Log and Monitor (Almost) Everything](https://d1.awsstatic.com/whitepapers/whitepaper-use-amazon-elasticsearch-to-log-and-monitor-almost-everything.pdf).
- [Performance at Scale with Amazon Elasticache](https://d0.awsstatic.com/whitepapers/performance-at-scale-with-amazon-elasticache.pdf).
- [Database Caching Strategies Using Redis](https://d1.awsstatic.com/whitepapers/Database/database-caching-strategies-using-redis.pdf).

#### Amazon Redshift

[@afronski](https://github.com/afronski):

> *Redshift* jest na tym egzaminie dość pobieżnie potraktowany, więc poniższe materiały potraktuj jako nadobowiązkowe. Ale są super ciekawe, szczególnie ostatnia seria artykułów na temat projektowania tabel.

- [Sizing Cloud Data Warehouses](https://d1.awsstatic.com/whitepapers/Size-Cloud-Data-Warehouse-on-AWS.pdf).
- [Data Warehousing on AWS](https://d1.awsstatic.com/whitepapers/enterprise-data-warehousing-on-aws.pdf).
- [Amazon Redshift Engineering's Advanced Table Design Playbook](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-preamble-prerequisites-and-prioritization/).

## Usługi AWS, które trzeba znać na wylot

- *Amazon RDS* jako całość i praktycznie.
  - [@afronski](https://github.com/afronski): Co ciekawe szczegółowa wiedza na temat *SQL* albo jakiegokolwiek silnika bazodanowego nie da Ci znaczącej przewagi, liczy się doświadczenie operacyjne, szczególnie z usługami *AWS*.
- *Amazon Aurora* jakość i praktycznie.
- *AWS Database Migration Service* jako całość i praktycznie.
- *Amazon DynamoDB* jako całość i praktycznie.
- Reszta usług z portfolio *AWS* dotyczących baz danych - wystarczy ogólna wiedza.
- Fajnie mieć wiedzę na temat *AWS IAM*, *AWS CloudFormation*, *AWS KMS* i *AWS Secrets Manager*.

## Ćwiczenia i zagadnienia

- *Amazon RDS*:
  - *Parameter Groups*, *Option Groups*, oraz *logi* (także na *S3*).
  - *Maintenance Windows*, *Read Replicas*, *Multi-AZ*.
  - *RDS* z aplikacjami *Serverless*.
  - *Backups*, *Snapshots*, oraz przywracanie ich.
  - Szyfrowanie (*at rest* i *in transit*).
  - Połączenie *IAM* z *RDS*.
  - Ograniczenia konkretnych silników na *RDS*.
- *AWS Database Migration Service*:
  - Migracja bazy z *EC2* na *Aurorę*.
  - *AWS Schema Conversion Tool* - wliczając w to konwersję procedur składowanych.
- *AWS Key Management Service* oraz *Amazon Secrets Manager*:
  - Szyfrowanie danych w bazie z użyciem *AWS KMS* i klienta *AWS SDK*.
  - Automatyczna rotacja haseł oraz konfiguracja tego z użyciem *CloudFormation*.
- *Amazon Aurora*:
  - *Read Replicas*, *Multi-AZ*, wersja *Global*.
  - *Backups*, *Snapshots*, oraz przywracanie ich.
  - Różnice pomiędzy *Aurora PostgreSQL*,  *Aurora MySQL* i *Aurora Serverless*.
  - Skalowanie.
  - Szyfrowanie (*at rest* i *in transit*).
- *Amazon Neptune*:
  - Ładowanie danych, rodzaje zapytań, skalowanie.
- *Amazon Elasticache*:
  - Skalowanie oraz klastrowanie.
  - *Redis*, *Redis* i jeszcze raz *Redis*.
  - Repliacja i szyfrowanie w obu opcjach usługi.
- *Amazon Elasticsearch Service*:
  - Skalowanie oraz klastrowanie.
  - Przekazywanie logów z *CloudWatch Logs* do *ES*.
  - Publiczny i privatny dostęp (z *VPC*).
- *Amazon DynamoDB*:
  - Projektowanie tabel, dobór klucza głównego i sortującego.
  - Zastosowanie oraz ograniczenia *LSI* i *GSI*.
  - Transakcje.
  - *Global Tables*.
  - *Provisioned Throughput*, *Reserved* vs. *On Demand*.
  - *Backup*, *PITR* i przywracanie danych.
  - *Hot Partitions* - Zapis.
  - *Hot Partitions* - Odczyt (i *Amazon DynamoDB DAX*).
  - *DynamoDB Streams*.
- Amazon DocumentDB:
  - Ogólna wiedza.
Amazon Redshift:
  - Ogólna wiedza.

## Materiały video, które warto obejrzeć

Playlista od [Wojtka Gawrońskiego](https://github.com/afronski):

- [AWS Certified Databases - Specialty 2019](https://www.youtube.com/playlist?list=PLCRlJJDoP5o_4gmRGYRPUHcX4wimoMlJU).