# AWS Certified Solutions Architect - Associate

W tej sekcji znajdziesz materiały dotyczące egzaminu *AWS Certified Solutions Architect - Associate*.

### Informacje ogólne i linki

Według oficjalnej dokumentacji, egzamin ten jest skierowany do osób, które od co najmniej roku zajmują się projektowaniem rozwiązań bazujących na platformie Amazon AWS. Posiadanie praktycznego doświadczenia jest przydatne, ale w żaden sposób nie jest sprawdzane przed rejestracją na egzamin.

Na tą chwilę (kwiecień 2020) dostępne są dwie wersje egzaminu:

* Starsza (kod SAA-C01) - ma być wycofana 1 lipca 2020.
* Nowsza (kod SAA-C02) - dostępna od 23 marca 2020.

Zarejestrować się i zdawać można dowolną z tych dwóch wersji. Otrzymany certyfikat ważny jest przez 3 lata a po upływie tego czasu będzie trzeba recertyfikować się zdając nową wersję tego egzaminu lub egzamin AWS Certified Solutions Architect Professional.

Strona egzaminu oraz exam guide:

Poniższe dokumenty zawierają podstawowe informacje o egzaminie oraz zakres materiału, który należy przyswoić. Charakterystyczne dla egzaminów Amazonu jest to, że nie są podawane nazwy konkretnych serwisów, które należy znać a tylko domeny (zakresy tematyczne).

* [AWS Certified Solutions Architect – Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
* [Exam Guide - stara wersja](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS_Certified_Solutions_Architect_Associate-Exam_Guide_1.8.pdf)
* [Exam Guide - nowa wersja](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf)

### Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

Warto przejść przez jeden z poniższych kursów. Oba dobrze przygotowują do egzaminu. Pozwalają też na odfiltrowanie zakresu wiedzy, która jest wymagana do zdania. Hint: w ramach ACG można założyć sobie darmowy dostęp na tydzień, w ramach którego mamy pełny dostęp do materiału. Ważne, aby wypisać się z dostępu członkowskiego przed upływem 7 dni, inaczej karta zostanie obciążona miesięcznym kosztem. 

* [ACG AWS Certified Solutions Architect Associate 2020](https://acloud.guru/learn/aws-certified-solutions-architect-associate) - kurs nagrany przez Ryana Kroonenburga. Aktualizowany na bieżąco o nowe tematy, również te zgłaszane przez zdających.
* [LinuxAcademy AWS Certified Solutions Architect - Associate Level](https://linuxacademy.com/cp/modules/view/id/341) - kurs konkurencyjny do tego z ACG. Całkiem dobry poziom merytoryczny, ale rzadziej aktualizowany.
* [Ultimate AWS Certified Solutions Architect Associate 2020](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c02/) - kurs przygotowany przez Stephane Maarek. Również dobry merytorycznie i aktualizowany, więc kupno w czasie jednej z licznych promocji portalu Udemy jest dobrym pomysłem. 

Dodatkowo:
* Whizlabs - przykładowe pytania. Nie spodziewaj się dokładnie takich samych na egzaminie, ale można wykorzystać jako dodatkowe źródło do sprawdzenia swojej wiedzy.

### Usługi AWS, które trzeba znać w podstawowym zakresie

Lista usług i tematów, które powinno się znać:

* IAM:
  * Zabezpieczanie konta root.
  * Tworzenie użytkowników, grup, ról i polityk z uprawnieniami.
  * Generowanie dostępów - klucze API.
* S3:
  * Tworzenie bucketów.
  * Podstawowe parametry: Pricing Tiers, bezpieczeństwo i szyfrowanie, wersjonowanie, Cross Region Replication, Lifecycle Management, Glacier, itp.
  * Static Website.
* EC2:
  * Tworzenie instancji EC2.
  * Security Groups.
  * EBS - tworzenie dysków dla instancji, typy dysków, szyfrowanie i operowanie na nich, m.in. snapshoty, tworzenie obrazów (Images), co zrobić jeśli musimy przenieść dysk do innego AZ/regionu.
  * AMI Images i marketplace.
  * Userdata - do czego używamy.
  * IAM Instance Profile.
  * EC2 Instance Meta Data.
  * Elastic Load Balancing - typy load balancerów, do czego służy, zwłaszcza w kontekście zapewnienia wysokiej dostępności.
  * Autoscaling.
  * Metody obniżenia kosztów: instancje Spot i Reserved.
* RDS:
  * Przede wszystkim jakie rodzaje baz danych wchodzą w skład RDS (bazy relacyjne).
  * Tworzenie przykładowej bazy (free tier oferuje opcję tworzenia małej bazy do testów).
  * Backupy.
  * HA, znajomość konceptów Multi-AZ i Read Replica.
  * Aurora.
* DynamoDB:
  * Podstawowe koncepcje bazy NoSQL.
  * Podstawowe parametry i właściwości DynamoDB.
* Route53:
  * Route53 Policies: Simple, Weighted, Latency, Failover itp.
  * Hosted Zones: private & public.
  * Rejestracja domeny.
* VPC:
  * Budowanie przykładowego VPC z publicznymi i prywatnymi podsieciami.
  * Orientować się do czego służą elementy składowe VPC: np. Routing Tables, Egress-Only Gateway, Internet Gateway itp.
  * Co to jest NAT.
  * Network ACLs i ogólnie czym się różni od Security Groups.
  * Bastion host.
  * VPC Flow Logs.
* CloudWatch:
  * Podstawowe info o usłudze.
  * Wiedzieć co jest zbierane, m.in. logi, metryki. Alarmy.
* CloudTrail:
  * Rejestrowanie i audytowanie czynności wykonywanych na koncie AWS: KTO coś zrobił.
* CloudFront:
  * Do czego służy.
  * Podstawowe info o architekturze (rozszerza to co mamy w ramach Regionów i AZ).
* AWS Organizations:
  * Ogólne koncepcje, do czego służy, jak buduje się organizację złożoną z wielu kont AWS, co to jest SCP.
* Podstawowe informacje o serwisach, do czego służą oraz jak je można wykorzystać w danym scenariuszu: 
  * Elastic Beanstalk
  * Lambda
  * SNS
  * SQS (m.in. kolejki Standard & FIFO, Long Polling)
  * SWF
  * API Gateway
  * Kinesis
  * Cognito
  * CloudFormation
  * ECS
  * VPN
  * Direct Connect (bardzo ogólnie o usłudze - do czego służy i kiedy wybrać zamiast VPN)
  * Storage Gateway
  * Database Migration Service
  * Snowball
  * FSX (for Windows & Lustre)
  * EFS
  * Redshift
  * Elasticache
  * Athena
  * Macie
  * WAF

Dodatkowo zapoznaj się z podstawowymi informacjami o: 

* Architekturze AWS: regiony, Availability Zones, jak zapewniamy wysoką dostępność w ich ramach - m.in. Load Balancing, Autoscaling.
* Różne sposoby dostępu do AWS: portal, CLI, SDK (bardziej wiedzieć, że SDK jest).
* Co to jest Shared Responsibility Model.

Jak widać po powyższej liście usług (nazw) jest dużo. Przygotuj się, że z mniej popularnymi usługami spotkasz się w 1-2 pytaniach i będziesz musiał(a) zdecydować, która usługa może być przydatna w danym scenariuszu. 

Niektóre usługi łatwo przetestować za darmo w ramach konta AWS, ale niektóre zaczną generować koszty od samego początku lub przeklikanie ich nie jest możliwe. Można sobie założyć darmowe konto (free tier), ale kluczowe jest tutaj aby uważać na generowane koszty.

### FAQ dla serwisów AWS

Poniżej linki do FAQ poszczególnych serwisów. Znajomość informacji zawartych w FAQ jest przydatna a często kluczowa do zdania:

* [Amazon VPC FAQs](https://aws.amazon.com/vpc/faqs/)
* [AWS IAM FAQs](https://aws.amazon.com/iam/faqs/)
* [Amazon CloudWatch FAQs](https://aws.amazon.com/cloudwatch/faqs/)
* [Amazon EC2 FAQs](https://aws.amazon.com/ec2/faqs/)
* [Amazon S3 FAQs](https://aws.amazon.com/s3/faqs/)
* [Amazon RDS FAQs](https://aws.amazon.com/rds/faqs/)
* [Amazon DynamoDB FAQs](https://aws.amazon.com/dynamodb/faqs/)

Dodatkowo zalecane jest zapoznanie się z dokumentacją wymienionych wcześniej serwisów pod kątem podstawowych informacji wymaganych dla roli architekta. Nie spodziewajcie się jednak, że będziecie odpytywani ze szczegółów. Poziom Associate to przede wszystkim sprawdzenie znajomości FAQ dla serwisów oraz ogólnych koncepcji związanych z chmurą AWS, jej architekturą oraz ważniejszymi zagadnieniami technicznymi dla popularnych serwisów. Link do dokumentacji: [AWS Documentation](https://docs.aws.amazon.com/)

### Przykładowe pytania testowe

Na pewno nie spotkacie identycznych pytań, ale mogą być podobne.

* [Starszy egzamin SAA-C01](https://d1.awsstatic.com/training-and-certification/docs/AWS_Certified_Solutions_Architect_Associate_Sample_Questions.pdf)
* [Nowa wersja SAA-C02](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Sample-Questions.pdf)

### Praktyczne wskazówki odnośnie samego egzaminu

* Jest to pierwszy egzamin techniczny na ścieżce architekta. Poziom jest wyższy niż dla AWS Certified Cloud Practitioner, ale można spokojnie zdać posiadając stosunkowo niewielkie doświadczenie praktyczne lub nie posiadając go wcale - wtedy bardzo ważne jest przeklikanie serwisów w konsoli AWSa korzystając z okresu próbnego (free tier).
* Spodziewaj się pytań testowych jedno- oraz wielokrotnego wyboru. Każde z pytań może zawierać więcej niż jedną odpowiedź, która na pierwszy rzut oka wydaje się prawidłowa. Należy wybrać najlepszą.
* Nie ma karnych punktów za podanie błędnej odpowiedzi, więc jeśli nie znasz jej to zgaduj.
* Możesz natknąć się na pytania dodatkowe - dodane są w celach statystycznych i nie będą wliczane do końcowego wyniku.
* Jest możliwość wykupienia egzaminu praktycznego (kody SAA-P01 oraz SAA-P02). Egzamin taki pozwala na zaznajomienie się z przykładowymi pytaniami i mechaniką egzaminu, ale nie jest tani. Przystąpienie do egzaminu praktycznego nie jest też wymagane do rejestracji na właściwy egzamin.
* Dla osób, których wiodącym językiem nie jest angielski istnieje opcja poproszenia o dodatkowe 30 minut do czasu trwania egzaminu. Przed rejestracją na egzamin wybierz opcję 'Request Exam Accommodations' i wybierz 'ESL +30 MINUTES'. 
* (kwiecień 2020) Uwaga do egzaminów zdalnych prowadzonych przez platformę Pearson Vue: Wybór dodatkowej opcji 'ESL +30 MINUTES' może sprawić, że rejestracja na egzamin zdalny (proctored exam) będzie możliwa tylko przez telefon a nie przez portal. Z opcji można zrezygnować pisząc ticket do supportu Amazonu. Link dostaniemy na portalu rejestracyjnym firmy Pearson Vue.
