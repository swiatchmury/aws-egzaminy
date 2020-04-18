# AWS Certified Advanced Networking Speciality


### Informacje ogólne i linki

Ten egzamin jest skierowany do osób, które na co dzień zajmują się sieciami w kontekście chmury AWS. Zdecydowanie nie jest dobrym kandydatem do zdawania jeśli nie macie praktycznego doświadczenia z technologiami takimi jak VPC, VPN, podstawy i adresacja sieci IPv4. Według mnie jest to jeden z cięższych egzaminów ponieważ ciężko jest przećwiczyć tematy związane z Direct Connect bez dostępu do fizycznego środowiska, a pytań o tę technologię jest naprawdę dużo.

### Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

* [ACG AWS Certified Advanced Networking - Specialty 2020](https://acloud.guru/learn/aws-networking-specialty) - kurs podstawowy. Zaktualizowany o nowe tematy i naprawdę dobrze nagrany. Jedyny minus to to, że - wg stanu na połowę kwietnia 2020 - ma trochę błędów w testach kończących rozdziały i brak jest testu końcowego. Zaktualizowany o treści zgłaszane przez innych zdających.
* [ACG AWS Certified Advanced Networking - Specialty 2019](https://acloud.guru/learn/aws-certified-advanced-networking-specialty) - starszy kurs z ACG z innym prowadzącym. Według mnie nadal jest to dobre źródło uzupełniające. Uwaga: test kończący kurs nie przypomina tego z egzaminu, więc nie sugerujcie się nim.
* [LinuxAcademy AWS Advanced Networking Specialty](https://linuxacademy.com/cp/modules/view/id/310) - kurs konkurencyjny do tych z ACG. Całkiem dobry poziom merytoryczny jeśli specyficzny charakter prowadzącej Ci nie przeszkadza. Zaleta: według mnie dużo lepszy test końcowy niż ten z ACG.

Dodatkowo:
* Whizlabs - przykładowe pytania. Nie spodziewaj się dokładnie takich samych na egzaminie, ale je można wykorzystać jako dodatkowe źródło do sprawdzenia swojej wiedzy.

### AWS Whitepapers

Koniecznie przeczytaj przed egzaminem:

* [Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-advnetworking-spec/AWS-Certified-Advanced-Networking-Specialty_Exam-Guide.pdf)
* [AWS Security Best Practices](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)
* [AWS Best Practices for DDoS Resiliency](https://d1.awsstatic.com/whitepapers/Security/DDoS_White_Paper.pdf?)
* [Overview of AWS Security - Network Security](https://d1.awsstatic.com/whitepapers/Security/Networking_Security_Whitepaper.pdf)
* [Security at Scale: Governance in AWS](https://d1.awsstatic.com/whitepapers/compliance/AWS_Security_at_Scale_Governance_in_AWS_Whitepaper.pdf)
* [Security at Scale: Logging in AWS](https://d1.awsstatic.com/whitepapers/compliance/AWS_Security_at_Scale_Logging_in_AWS_Whitepaper.pdf)
* [Integrating AWS with Multiprotocol Label Switching](https://d1.awsstatic.com/whitepapers/Networking/integrating-aws-with-multiprotocol-label-switching.pdf)
* [Best Practices for Deploying Amazon WorkSpaces](https://d1.awsstatic.com/whitepapers/workspaces/Best_Practices_for_Deploying_Amazon_WorkSpaces.pdf)


### Usługi AWS, które trzeba znać na wylot

* VPC - architektura sieci private/public, NAT Gateway, NAT Instance, Elastic IP, Elastic Network Interface, routing i kolejność wyboru ścieżek, Flow Logs.
* Security Groups, NACLs - czym się różnią, jak budujemy reguły, troubleshooting łączności sieciowej.
* VPC Peering - do czego służy i jak łączy się z innymi rozwiązaniami sieciowymi. Musisz wiedzeć, co to jest transitive peering i jak będzie przebiegała komunikacja, gdy peering jest zestawiony w sytuacji kiedy mamy łańcuch VPC np. VPC_A <-> VPC_B <-> VPC_C.
* VPC Endpoints - jakie serwisy używają Gateway a jakie Interface endpoints. Jakie informacje musimy posiadać żeby taki endpoint zbudować i jak łączą się one z innymi sieciami (np. z VPN czy Direct Connect). Co to jest AWS VPC Endpoint Services i jak udostępnić usługę klientom (innym kontom).
* VPN - różne scenariusze zestawiania VPN site-2-site i klienckich. Przygotuj się na to, że możesz być zapytany, kiedy lepiej użyć VPN Gateway, a kiedy VPN zestawionego na instancjach EC2.
* Direct Connect - tutaj jest naprawdę ciężko, jeśli nie posiadasz praktycznego doświadczenia. Pytań jest dużo i bez wiedzy na temat tej technologii po prostu nie da się zdać egzaminu. Potrzebna wiedza to m.in. typy połączeń (dedykowane/hostowane), typy interfejsów (private/public), routing pomiędzy siecią lokalną a AWS, limity i wymagania do zestawienia połączenia, routing.
* Architektura - co to jest Transit VPC, CloudHub.
* Podstawy sieci - adresacja IPv4, liczenie ilości dostępnych hostów na podstawie adresu i maski, routing BGP i ASNy - ogólnie jak masz podstawy sieci z kursu Cisco CCNA, to będzie ok.
* Różne serwisy AWS - CloudFormation, Route53, AppStream 2.0, Lambda, CloudWatch, CloudTrail, CloudFront, networking dla EC2-ek, Placement Groups, Load Balancing.

### Pozostałe materiały

Linkuję study guide, które mi pomogły. Nie daję gwarancji, że wszystkie informacje są aktualne i poprawne, ale wiedza z nich się przydaje. Nie demotywujcie się komentarzami mówiącymi, że egzamin jest super-ciężki - jak macie wiedzę, to spokojnie zdacie. Poniżej duża dawka informacji, które powinno się znać:

* [AWS Certified Advanced Networking Specialty: Exam Notes and Observations](https://blog.ashiny.cloud/2018/07/29/aws-certified-advanced-networking-specialty/)
* [AWS Advanced Networking Specialty Exam Tips and Tricks](https://daviseford.com/blog/2018/12/21/aws-advanced-networking-specialty-exam-tips.html)
* [AWS Certified Advanced Networking – Speciality (ANS-C00) Exam Learning Path](https://jayendrapatil.com/aws-certified-advanced-networking-speciality-ans-c00-exam-learning-path/)

FAQ:

* [Amazon VPC FAQs](https://aws.amazon.com/vpc/faqs/)
* [AWS Direct Connect FAQs](https://aws.amazon.com/directconnect/faqs/)
* [AWS VPN FAQs](https://aws.amazon.com/vpn/faqs/)
* [Amazon Route 53 FAQs](https://aws.amazon.com/route53/faqs/)

Dodatkowo ja przeczytałem CAŁĄ dokumentację do wymienionych wcześniej serwisów. Według mnie warto.

### Praktyczne wskazówki odnośnie samego egzaminu

- Egzamin jest trudny, ale spokojnie do zdania. Jeśli miałbym porównać poziom do innych egzaminów, to według mnie jest prostszy niż AWS Certified Architect Pro. Jest mniej serwisów, które trzeba znać, więc łatwiej się skupić na uczeniu się tego, co naprawdę jest potrzebne.
- Upewnij się, że naprawdę dobrze znasz podstawy sieci i routingu. Jak wspomniałem wcześniej, jeśli znasz podstawy z kursu Cisco CCNA, to tutaj raczej nie będze zaskoczenia.
- Musisz naprawdę dobrze znać Direct Connect i jego elementy składowe. Pytań jest dużo i nie warto tutaj liczyć na "strzelanie" odpowiedzi. Jest to najtrudniejszy element egzaminu, bo ciężko tutaj o ćwiczenie na labie.
- Podstawy routingu BGP - znajomość podstawowych terminów i zasady działania zapewni kilka punktów na egzaminie.
- Musisz dobrze wiedzieć, jak zachowuje się routing i komunikacja sieciowa pomiędzy podsieciami używającymi poszczególnych usług AWS, np. jak działa komunikacja pomiędzy siecią on-premises a VPC posiadającym Gateway Endpoint, routing pomiędzy kilkoma VPC podłączonymi DX Gatewayem czy peeringiem.
- Wykorzystaj dodatkowy czas dla osób z wiodącym językiem innym niż angielski (koniecznie poproś o niego przed rejestracją na egzamin);
- Wykorzystaj zniżkę za poprzedni egzamin (jeśli ją jeszcze posiadasz) – po każdym zdanym egzaminie, Amazon daje 50% kupon zniżkowy.
