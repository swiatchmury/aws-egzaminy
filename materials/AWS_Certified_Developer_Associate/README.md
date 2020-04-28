# AWS Certified Developer - Associate

W tej sekcji znajdziesz materiały dotyczące egzaminu *AWS Certified Developer - Associate*.

### Informacje ogólne i linki

Oficjalna dokumentacja mówi, że egzamin ten jest skierowany do osób, które od co najmniej roku zajmują się budowaniem i utrzymywaniem rozwiązań bazujących na platformie Amazon AWS. Posiadanie praktycznego doświadczenia jest przydatne, ale w żaden sposób nie jest sprawdzane przed rejestracją na egzamin.

Na tą chwilę (kwiecień 2020) dostępna jest wersja egzaminu oznaczona kodem DVA-C01 i zaktualizowana w styczniu 2019. Otrzymany certyfikat ważny jest przez 3 lata a po upływie tego czasu będzie trzeba recertyfikować się zdając nową wersję tego egzaminu lub egzamin AWS Certified DevOps Engineer - Professional.

Strona egzaminu oraz exam guide:

Poniższe dokumenty zawierają podstawowe informacje o egzaminie oraz zakres materiału, który należy przyswoić. Charakterystyczne dla egzaminów Amazonu jest to, że nie są podawane nazwy konkretnych serwisów, które należy znać a tylko domeny (zakresy tematyczne).

* [AWS Certified Developer - Associate - strona główna egzaminu](https://aws.amazon.com/certification/certified-developer-associate/)
* [Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf)

[@rmandziarz](https://github.com/rmandziarz):

> Jako jedno z wymagań wstępnych dla tego egzaminu pojawia się znajomość jakiegoś języka programowania. Cytując za Amazonem: "In-depth knowledge of at least one high-level programming language". Nie spodziewajcie się jednak pytań testujących waszą znajomość danego języka. Jeśli pojawi się jakiś kawałek kodu to raczej w kontekście znajomości danego API Call w nim zawartego.

### Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

Warto przejść przez jeden z poniższych kursów. Wszystkie dobrze przygotowują do egzaminu. Pozwalają też na odfiltrowanie zakresu wiedzy, która jest wymagana do zdania. Hint: w ramach ACG można założyć sobie darmowy dostęp na tydzień, w ramach którego mamy pełny dostęp do materiału. Ważne, aby wypisać się z dostępu członkowskiego przed upływem 7 dni, inaczej karta zostanie obciążona miesięcznym kosztem. 

[@rmandziarz](https://github.com/rmandziarz):

> 2020-04-28: Na tą chwilę z czystym sumieniem mogę polecić kursy ACG i ten z Udemy. Kurs z Linux Academy jest poprawny, ale rzadziej aktualizowany a dostęp do ich platformy droższy. Nie znaczy to jednak, że kurs LA nie przygotuje Ciebie do egzaminu.

* [ACG AWS Certified Developer - Associate 2020](https://acloud.guru/learn/aws-certified-developer-associate) - kurs aktualizowany na bieżąco o nowe tematy, również te zgłaszane przez zdających. Dobrze pokrywa zakres materiału pojawiającego się podczas egzaminu.
* [Ultimate AWS Certified Developer Associate 2020](https://www.udemy.com/course/aws-certified-developer-associate-dva-c01/) - kurs przygotowany przez Stephane Maarek. Również dobry merytorycznie i aktualizowany, więc kupno w czasie jednej z licznych promocji portalu Udemy jest dobrym pomysłem. 
* [LinuxAcademy AWS Certified Developer - Associate Level](https://linuxacademy.com/cp/modules/view/id/181) - kurs konkurencyjny do tego z ACG. Całkiem dobry poziom merytoryczny, ale są problemy z aktualizacjami.

Dodatkowo:
* [Whizlabs](https://www.whizlabs.com/aws-developer-associate/) - przykładowe pytania. Nie spodziewaj się dokładnie takich samych na egzaminie, ale można wykorzystać jako dodatkowe źródło do sprawdzenia swojej wiedzy.

### Usługi AWS, które trzeba znać w podstawowym zakresie

Jeśli zdawaliście wcześniej inny egzamin z poziomu Associate to spodziewajcie się, że duża część tematów będzie się pokrywać. Niech to jednak nie uśpi Waszej czujności, ponieważ ten egzamin jest nakierowany bardziej na tematy deweloperskie a mniej m.in. na architekturę i projektowanie rozwiązań.

Lista usług i tematów, które powinno się znać:

* IAM:
  * Zabezpieczanie konta root.
  * Tworzenie użytkowników, grup, ról i polityk z uprawnieniami.
  * Generowanie dostępów - klucze API.
  * Polisy: Inline vs AWS Managed vs Custom.
  * Cross Account Access.
  * Policy Simulator.
  * Dobre praktyki związane z bezpieczeństwem - kiedy używamy role, kiedy klucze API, uważanie na to żeby nie zaszywać kluczy w niebezpiecznych miejscach w kodzie.
* S3:
  * Tworzenie bucketów.
  * Bezpieczeństwo i szyfrowanie.
  * Wersjonowanie.
  * Konfiguracja Cross Region Replication.
  * Pricing Tiers, Lifecycle Management, Glacier - zwłaszcza przesuwanie obiektów pomiędzy tierami (typami storage) w kontekście dostępności, backupu i archiwizacji danych.
  * Static Website i CORS.
  * Optymalizacja zapisu i odczytu dużych ilości danych z S3.
* EC2:
  * Tworzenie instancji EC2.
  * Sposoby łączenia się do instancji - generowanie kluczy SSH, EC2 Instance Connect.
  * Security Groups.
  * EBS - tworzenie dysków dla instancji, typy dysków, szyfrowanie i operowanie na nich, m.in. snapshoty, tworzenie obrazów (Images), co zrobić jeśli musimy przenieść dysk do innego AZ/regionu.
  * AMI Images i marketplace.
  * User Data - do czego używamy, przykład: instalowanie aplikacji czy konfigurowanie serwisów podczas deploymentu EC2-ki (np. Apache).
  * IAM Instance Profile.
  * EC2 Instance Meta Data.
  * Elastic Load Balancing - typy load balancerów, do czego służy, zwłaszcza w kontekście zapewnienia wysokiej dostępności.
  * Autoscaling, Launch Configuration/Template.
  * Metody obniżenia kosztów: instancje Spot i Reserved.
* VPC:
  * Budowanie przykładowego VPC z publicznymi i prywatnymi podsieciami.
  * Orientować się do czego służą elementy składowe VPC: np. Routing Tables, Egress-Only Gateway, Internet Gateway itp.
  * Typy adresów IP: Public, Private, Elastic IP - kiedy można je przydzielić i jak mogą się przydać.
  * Co to jest NAT.
  * Network ACLs i ogólnie czym się różni od Security Groups.
  * Bastion host.
  * VPC Flow Logs.
* RDS:
  * Przede wszystkim jakie rodzaje baz danych wchodzą w skład RDS (bazy relacyjne).
  * Tworzenie przykładowej bazy (free tier oferuje opcję tworzenia małej bazy do testów).
  * Backupy.
  * HA, znajomość konceptów Multi-AZ i Read Replica.
  * Aurora.
* Lambda:
  * Podstawowe parametry i zastosowania - ilość równoczesnych wywołań, Throttling, wersjonowanie i aliasy, DLQ, timeouty, dodawanie zewnętrznych dependencji.
  * Uprawnienia Lambdy - Resource Policy i Execution Policy.
  * Dostęp do usług w VPC.
  * Logowanie zdarzeń do CloudWatch. Monitoring parametrów i wydajności.
* API Gateway:
  * Zastosowanie w kontekście usług serverless.
  * Podstawowa architektura, np. Stages, Deploymenty, Mappings, Cache.
  * Monitoring i bezpieczeństwo.
  * Jak to pożenić z Lambdami.
* DynamoDB:
  * Podstawowe koncepcje bazy NoSQL.
  * Podstawowe parametry i właściwości DynamoDB.
  * Spodziewaj się pytań o indeksy: typy, kiedy i jak tworzymy, do czego się przydają.
  * Odpytywanie DynamoDB - m.in. Scan vs Query.
  * Wyliczanie Read/Write Capacity Units.
  * Przykłady użycia transakcji i wartości TTL.
  * Diagnozowanie problemów z wydajnością, przekroczenie ilości RCU/WCU przydzielonej do tabeli, Exponential Backoff.
  * Zastosowania DynamoDB Streams.
  * Do czego służy DAX.
* X-Ray:
  * Wiedzieć jak pomaga w diagnozowaniu problemów z aplikacjami serverless i jak integruje się z innymi serwisami.
* SQS:
  * Usługa kolejek typu Pull.
  * Typy kolejek: Standard i FIFO.
  * Pojęcia, które warto znać: short & long polling, Dead-Letter Queues, Visibility Timeout, Delay Queues, zarządzanie dużymi wiadomościami.
* SNS:
  * Usługa notyfikacji Push.
  * Oparta o subskrypcje.
* Kinesis:
  * Typy usług i co potrafią zrobić - Kinesis Data: Streams, Firehose, Analytics, Kinesis Video Streams.
  * Shardy i Consumers.
* Step Functions:
  * Do czego możemy to użyć i podobieństwa/różnice do podobnych usług, np. SWF.
* SES:
  * Usługa wysyłania emaili.
* SWF:
  * Do czego możemy to użyć i podobieństwa/różnice do podobnych usług, np. Step Functions. Zwróć m.in. uwagę na maksymalny przedział czasu w jakim usługa potrafi działać.
* Code Tools:
  * Teoria CI/CD - automatyzacja za pomocą pipeline'ów.
  * CodeCommit - repozytorium kodu w chmurze AWS.
  * CodeBuild - podstawy budowania kodu w CodeBuild, zastosowanie pliku buildspec.yml.
  * CodeDeploy - podstawy deploymentu, na jakie serwisy może wdrażać CodeDeploy, plik konfiguracji appspec.yml. 
  * CodePipeline - jak działają proste pipeline'y, integracja z innymi usługami Code*
  * CodeStar - tutaj już ogólniej do czego może się przydać.
* Elastic Beanstalk:
  * Przykłady środowisk jakie można wdrożyć w AWS, dostępne technologie i platformy.
  * Aktualizowanie aplikacji Elastic Beanstalk.
  * Zaawansowane środowiska z load balancingiem i RDS.
* CloudFormation & SAM (Serverless Application Model):
  * Tworzenie, aktualizowanie i usuwanie stacków.
  * Szablony CloudFormation, elementy składowe: Resources, Parameters, Mappings, Outputs, Conditions.
  * Intrinsic Functions. 
  * Podstawy yaml i json w kontekście szablonów.
  * SAM jako rozszerzenie CloudFormation dla aplikacji serverless.
* KMS:
  * Do czego służy i jak wykorzystać klucze do zabezpieczenia innych usług.
  * KMS Envelope Encryption.
  * Najważniejsze API calls usługi KMS.
* Route53:
  * Route53 Policies: Simple, Weighted, Latency, Failover itp.
  * Hosted Zones: private & public.
  * Rejestracja domeny.
* CloudWatch & CloudTrail:
  * Podstawowe info o usługach.
  * Wiedzieć co jest zbierane, m.in. logi, metryki. 
  * Konfiguracja alarmów i zdarzeń - odpowiedź na zdarzenia przesyłane z innych serwisów oraz wykorzystanie CW Event Rules jako Crona.
* Web Identity Federation & Cognito:
  * Wiedzieć co to i jak wykorzystać.
  * Co to jest STS AssumeRoleWithWebIdentity.
  * Orientować się w różnicy pomiędzy Cognito User Pools vs Identity Pools.
* ECS:
  * Typy ECS: instancje lub Fargate.
  * Tutaj trzeba znać elementy składowe: klastry, Task/Service Definition.
  * ECR.
* Systems Manager:
  * Parameter Store - do czego wykorzystujemy.
* Secrets Manager:
  * Tutaj podobnie jak dla Parameter Store.
  * Automatyczne rotowanie parametrów.
* CloudFront:
  * Do czego służy.
  * Podstawowe info o architekturze (rozszerza to co mamy w ramach Regionów i AZ).
  * Lambda@Edge.
* Elasticache - tutaj np. strategie użycia cache.
* ACM - podstawy, usługa do generowania i zarządzania certyfikatami SSL/TLS.

Dodatkowo zapoznaj się z podstawowymi informacjami o: 

* Różne sposoby dostępu do AWS: portal, CLI (instalacja, konfigurowanie profilu), SDK.
* Najważniejsze API Calls dla podstawowych serwisów: m.in. EC2, Lambda, DynamoDB, KMS. Nie wymieniam tutaj wszystkich kombinacji, na pewno nie chodzi o uczenie się na pamięć wszystkich możliwości a pamiętanie kluczowych nazw np. dla listowania instancji, odpytywania tabeli DynamoDB itp.
* Co to jest Shared Responsibility Model.
* Dobre praktyki pracy z repozytoriami, kodem źródłowym, pipeline'ami, CI/CD itp. podstawy pracy dewelopera.
* Dobrze jest też znać podstawy architektury AWSa: Regiony, Availability Zones, CDNy CloudFronta. Jak to wpływa na dostępność budowanej usługi, wiedzieć, że są usługi regionalne (jak np. EC2) i globalne (np. IAM). 

Jak widać po powyższej liście usług (nazw) jest dużo. Przygotuj się, że z mniej popularnymi usługami spotkasz się w 1-2 pytaniach. Niektóre usługi łatwo przetestować za darmo w ramach konta AWS, ale niektóre zaczną generować koszty od samego początku lub przeklikanie ich będzie problematyczne. Można sobie założyć darmowe konto (free tier), ale kluczowe jest tutaj pilnowanie generowanych kosztów.

### FAQ dla serwisów AWS oraz pozostałe linki

Link do listy FAQ poszczególnych serwisów jest tutaj: [FAQ - lista](https://aws.amazon.com/faqs/). Zapoznaj się z dokumentami dla popularniejszych usług, ponieważ znajomość informacji w nich zawartych jest przydatna a często kluczowa do zdania.

Dodatkowo zalecane jest zapoznanie się z dokumentacją wymienionych wcześniej serwisów pod kątem podstawowych informacji wymaganych dla roli dewelopera. Nie spodziewajcie się jednak, że będziecie odpytywani ze szczegółów. Poziom Associate to przede wszystkim sprawdzenie znajomości FAQ dla serwisów oraz ogólnych koncepcji związanych z chmurą AWS, jej architekturą oraz ważniejszymi zagadnieniami technicznymi dla popularnych serwisów. Link do dokumentacji: [AWS Documentation](https://docs.aws.amazon.com/).

Pozostałe linki, które mogą się przydać:
* [Tools to Build on AWS](https://aws.amazon.com/tools/)

### Przykładowe pytania testowe

Na pewno nie spotkacie identycznych pytań, ale mogą być podobne.

* [Aktualny egzamin DVA-C01](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Sample-Questions.pdf)

### Praktyczne wskazówki odnośnie samego egzaminu

* Jest to pierwszy egzamin techniczny na ścieżce dewelopera. Poziom jest wyższy niż dla AWS Certified Cloud Practitioner, ale można spokojnie zdać posiadając stosunkowo niewielkie doświadczenie praktyczne lub nie posiadając go wcale - wtedy bardzo ważne jest przeklikanie serwisów w konsoli AWSa korzystając z okresu próbnego (free tier).
* Spodziewaj się pytań testowych jedno- oraz wielokrotnego wyboru. Każde z pytań może zawierać więcej niż jedną odpowiedź, która na pierwszy rzut oka wydaje się prawidłowa. Należy wybrać najlepszą.
* Nie ma karnych punktów za podanie błędnej odpowiedzi, więc jeśli nie znasz poprawnej to zgaduj.
* Możesz natknąć się na pytania dodatkowe - dodane są w celach statystycznych i nie będą wliczane do końcowego wyniku.
* Jest możliwość wykupienia egzaminu praktycznego (kod DVA-P01). Egzamin taki pozwala na zaznajomienie się z przykładowymi pytaniami i mechaniką egzaminu. Przystąpienie do egzaminu praktycznego nie jest też wymagane do rejestracji na właściwy egzamin.
* Dla osób, których wiodącym językiem nie jest angielski istnieje opcja poproszenia o dodatkowe 30 minut do czasu trwania egzaminu. Przed rejestracją na egzamin wybierz opcję 'Request Exam Accommodations' i wybierz 'ESL +30 MINUTES'. 
* (kwiecień 2020) Uwaga do egzaminów zdalnych prowadzonych przez platformę Pearson Vue: Wybór dodatkowej opcji 'ESL +30 MINUTES' może sprawić, że rejestracja na egzamin zdalny (proctored exam) będzie możliwa tylko przez telefon a nie przez portal. Z opcji można zrezygnować pisząc ticket do supportu Amazonu. Link dostaniemy na portalu rejestracyjnym firmy Pearson Vue.
