# AWS Certified Security Speciality


### Informacje ogólne i linki

Jeśli nie pracowałeś(aś) z AWS wcześniej, ten egzamin nie jest dla Ciebie. 
Amazon w kontekście Security Speciality wymaga dość określonej wiedzy, mocno popartej realnym doświadczeniem w obszarze IAM, S3, CloudWatch, KMS - i kombinacją tych czterech. Do tego dochodzi zrozumienie działania ataków Denial of Service i ich zapobieganiu.

### Kursy egzaminacyjne i wspomagające przygotowania do egzaminu

* Linux Academy - wyjątkowo dobry, nie pokrywa np. Cognito i Dockera - pytania o ten obszar jadnak się zdarzają. Moim zdaniem, jest to obecnie (03.2020) najlepiej przygotowujący kurs online, pozwalający dobrze zrozumieć zakres.
* acloud.guru - uzupełnia wiedzę, jest bardziej na czasie z zakresem egzaminu - choć mniej dokładny.

[@rmandziarz](https://github.com/rmandziarz):

> 2020-04-28: Przerobiłem oba i jeśli mam być szczery to ciężko polecić mi kurs acloud.guru. Dużo tematów przedstawili pobieżnie. Powiedział bym nawet, że nie wyszli mocno poza poziom associate, gdzie tutaj zakres materiału powinien być większy. Kurs wygląda na robiony "na szybko" i pojawiało się jeszcze sporo nagrań w chwili kiedy ja z niego korzystałem. Kurs Linux Academy powoli się dezaktualizuje, ale poziom merytoryczny jest wyższy.


Dodatkowo 
* Whizlabs - dostarcza przykładowe pytania - bardzo dobrze przygotowane, choć bywają nieaktualne odpowiedzi, patrząc z poziomu aktualnych serwisów (np. AWS pozwala na wykonywanie testów penetracyjnych bez informowania ich o tym, o ile znajdują się w dopuszczonym zakresie - [zerknij tutaj](https://aws.amazon.com/security/penetration-testing#Customer_Service_Policy_for_Penetration_Testing))

### AWS Whitepapers

Koniecznie przeczytaj przed egzaminem

* [Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-security-spec/AWS-Certified-Security-Specialty_Exam-Guide_v1.6_FINAL.pdf)
* [AWS Security Best Practices](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)
* [AWS Best Practices for DDoS Resiliency](https://d1.awsstatic.com/whitepapers/Security/DDoS_White_Paper.pdf?)
* [Overview of AWS Security - Network Security](https://d1.awsstatic.com/whitepapers/Security/Networking_Security_Whitepaper.pdf)


### Usługi AWS, które trzeba znać na wylot

* AWS IAM:
  * Policy, sposób budowania, mechanizm selekcji - tutaj nie ma zmiłuj, nie idź dalej, jeśli nie czujesz, że doskonale rozumiesz zasadę działania. Musisz rozumieć zasadę działania elementu 'Condition' w polisie.
  * Musisz dobrze rozumieć różnicę pomiędzy identity i resource policies oraz to kiedy je używamy.
  * Pamiętaj jak dajemy uprawnienia do zasobów pomiędzy kontami AWS.
* AWS IAM:
  * User, Group, Idenity Pool (wykorzystanie SAML) - Wystarczy ogólna znajomość, best practice.
  * Typowy scenariusz jaki może pojawić się na egzaminie: duża organizacja (np. 5000 kont użytkowników, posiadająca IdP w lokalnej sieci) chce nadać uprawnienia do kont AWS. Jak zbudować federację z AWS (SAML + ADFS).
* AWS KMS:
  * Tę usługę musisz również poznać bardzo dokładnie, budowę uprawnień, jak współpracuje z innymi serwisami w kontekście autoryzacji dostępu do certyfikatów, szyfrowania i deszyfrowania zawartości. Bardziej ogólnie, kiedy wykorzystać CMK, a kiedy CloudHSM.
  * Spodziewaj się pytań o rotowanie kluczy. Musisz wiedzieć, kiedy można ustawić automatyczne rotowanie a kiedy należy rotować klucz ręcznie.
* AWS CloudHSM:
  * Warto wiedzieć, w których scenariuszach się sprawdzi, jakie są różnice w zarządzaniu, jak radzić sobie z Disaster Recovery i multi-region.
* AWS S3:
  * Pomyśl o S3 jako centralnym repozytorium plików/logów - zwróć uwagę na ACL i kopiowanie pomiędzy kontami.
  * Spodziewaj się pytań o szyfrowanie obiektów, replikację pomiędzy bucketami, Glacier Vault Lock.
  * Musisz wiedzieć kiedy lepiej zastosować Bucket Policy, kiedy ACL na poziomie obiektów itp.
* VPC:
  * Bezpieczeństwo dla sieci prywatnych i publicznych, np. routing, NAT.
  * Jak działają Security Groups i NACL - do czego możemy je podłączyć, stateful vs stateless.
  * Różne połączenia pomiędzy sieciami: peering, VPC Endpoints, PrivateLink.
  * Bastion Host.
  * Diagnozowanie problemów z połączeniami sieciowymi np. na podstawie VPC Flow Logs - typowy scenariusz kiedy Security Group zezwala na ruch wchodzący a NACL blokuje ruch wychodzący.
* AWS CloudWatch:
  * Zrozum, jak działa i do czego służy - jak go pożenić z innymi usługami, czy tez wykorzystać jako Cron.
  * Warto wiedzieć jak konfigurować centralne logowanie zdarzeń z różnych serwisów i większej liczby kont AWS.
* AWS CloudFront:
  * Zwróć szczególną uwagę na scenariusze użycia, warto przeklikać i mieć świadomość funkcjonalności. Zwróć uwagę na możliwe opcje ograniczania dostępu do treści, odpłatności za dostęp, wykorzystanie przez aplikacje.
* AWS Lambda:
  * Pobaw się uprawnieniami przy wykorzystania innych serwisów i współpracą z API Gateway, a w tym Cognito i uwierzytelnianie.
  * Powinieneś też wiedzieć kiedy Lambda może się przydać, np. automatyzacja odpowiedzi na zdarzenia.
* AWS Cognito:
  * Warto rozróżniać User Pool vs Identity Pool, co kiedy zastosować i jak się buduje uprawnienia dla użytkowników w oparciu o IAM i Cognito.
* AWS WAF:
  * Zastosowanie z ALB, CloudFront, wykorzystanie marketplace, custom rules.
* AWS Config:
  * Szczególnie jak zbudować automatyzację reagowania na zdarzenia - koniecznie.
  * Znać zasadę: Config służy do sprawdzania 'CO' zostało zmienione, a CloudTrail - głównie 'KTO' coś zmienił.
* AWS SSM:
  * Główne tematy to remediacja i aktualizacja instancji.
  * Warto wiedzieć, że da się skonfigurować połączenia do instancji EC2 bez otwierania portu 22.
* AWS Secrets Manager:
  * Typowy scenariusz to konfiguracja rotowania parametrów składowanych w tej usłudze i rozwiązywanie problemów. Pamiętaj, że po skonfigurowaniu automatycznej rotacji, pierwsza operacja następuje od razu i może to zepsuć działanie innej usługi konsumującej ten parametr.
* AWS Athena:
  * W kontekście przeszukiwania logów.

Warto też zapoznać się z:

* AWS Shield Advanced
* AWS Security HUB
* Amazon GuardDuty
* AWS CloudTrail
* AWS Config
* AWS Inspector
* Trusted Advisor
* AWS Directory Services
* AWS Organizations - do czego służy SCP.
* Amazon ECS - tutaj bardzo ogólnie o bezpieczeństwie hostów i Dockera w kontekście tej usługi, ale bez szczegółów.

Warto przeczytać FAQ dla wszystkich wymienionych powyżej usług oraz mocno skupić się na dokumentacji IAM i KMS. 

### Pozostałe materiały

* [AWS Acceptable Use Policy](https://aws.amazon.com/aup/)
* [AWS Penetration Testing](https://aws.amazon.com/security/penetration-testing/)
* [Paweł Rzepa ogónie o egzaminie EN](https://medium.com/@rzepsky/passing-the-aws-certified-security-speciality-exam-d5ac90b3cdbc)
* [Mapa myśli, autor: Paweł Rzepa - szczególnie przydatna do powtórek](https://coggle.it/diagram/XCx0VU8yTIKcn9xF/t/aws-certified-security-specialty)
* [Condition Keys](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html)

### Materiały video, które warto obejrzeć

* [AWS re:Invent 2017: Best Practices for Managing Security Operations on AWS (SID206)](https://www.youtube.com/watch?v=gjrcoK8T3To)
* [AWS re:Invent 2018: Become an IAM Policy Master in 60 Minutes or Less (SEC316-R1)](https://www.youtube.com/watch?v=YQsK4MtsELU&t=2s)
* [Advanced Security Best Practices Masterclass](https://www.youtube.com/watch?v=zU1x5SfKEzs)
* [AWS re:invent 2017: Best Practices for Implementing AWS Key Management Service (SID330)](https://www.youtube.com/watch?v=X1eZjXQ55ec)
* [AWS re:Invent 2017: A Deep Dive into AWS Encryption Services (SID329)](https://www.youtube.com/watch?v=gTZgxsCTfbk)
* [Encryption and Key Management in AWS](https://www.youtube.com/watch?v=uhXalpNzPU4)
* [Dobre podsumowanie serwisów](https://jayendrapatil.com/aws-certification-security-identity-services-cheat-sheet)


### Praktyczne wskazówki odnośnie samego egzaminu

- Koniecznie poćwicz IAM Policy, KMS policy, policy... policy... nie tylko semantycznie, ale dla zrozumienia zasad działania, powiązań.
- Poświęć czas na dobre zrozumienie AWS Config, AWS Inspector, AWS GuardDuty - co, skąd bierze informacje, w jaki sposób wymienia je między sobą, do czego służy.
- Praktyczna znajomość CloudTrail (szczególnie dostępność danych w czasie), CloudWatch, VPC FLow Log jest niezbędna.
- DDoS - przeciwdziałanie w zależności od serwisu (ALB, CloudFront, EC2) - jest bardzo pomocne na egzaminie ;)
- Warto przed egzaminem przejrzeć suplement z Linux Academy (url w ich kursie).
- Wykorzystaj dodatkowy czas dla osób z wiodącym językiem innym niż angielski (koniecznie poproś o niego przed rejestracją na egzamin);
- Wykorzystaj zniżkę za poprzedni egzamin (jeśli ją jeszcze posiadasz) – po każdym zdanym egzaminie, Amazon daje 50% kupon zniżkowy.


