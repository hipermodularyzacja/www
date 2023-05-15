
![hipermodularyzacja](https://logo.hipermodularyzacja.pl/2/cover.png)

# [Modularyzacja przy wytwarzaniu oprogramowania](https://www.hipermodularyzacja.pl/)


Polskie wydanie, Wersja Polska: HiperModularyzacja.pl
+ [książka: Hiper Modularyzacja](https://book.hipermodularyzacja.pl/)

Polskie wydanie, Wersja Polska: HiperModularyzacja.pl
+ [Blog: blog.HiperModularyzacja.pl](https://blog.hipermodularyzacja.pl/)


W trakcie jest też wersja angielska: HyperModularity.com
+ [www. Hyper Modularity .com](http://www.hypermodularity.com/)

+ [muzyka: Hiper Modularyzacja](https://www.hipermodularyzacja.pl/tekst.html)

Metamoduły bazujące na tym:
+ [docs.metamodule.org](https://docs.metamodule.org/)

## Wstęp


### Początek

Pomysł na książkę zrodził się w trakcie realizacji projektu jLoads, który służy modularyzacji aplikacji napisanej w JavaScript na frontendzie.
To pierwszy E-book po polsku o hipermodularyzacji.
Kolejny powstaje o modularyzacji w szerszym kontekście z innymi specjalistami w tym aspekcie również wersję angielska:
[Hyper Modularity .com](https://www.hypermodularity.com/)




## DLA KOGO JEST TA KSIĄŻKA


Drogi czytelniku, jeśli w codziennej pracy stawiasz sobie poniższe pytania, to zapraszam do lektury:

+ Jak wykorzystać kontekst presji w powstawaniu projektów IT?
+ Jak wykorzystać rywalizację w przyśpieszeniu rezultatów?
+ Jak rozumieć kontekst czasu i planowania na dekadę?
+ Jak tworzyć re-używalny kod i usługi?
+ Jak uzyskiwać dodatkowe zyski z już raz powstałego kodu?

Na co dzień realizujemy projekty pod presją czasu w środowiskach, technologiach, które dopiero zgłębiamy, stale się uczymy.

Niezależnie od tego, czy jesteśmy ograniczeni kosztami, czasem, wiedzą, potrzebujemy lepszych narzędzi do tworzenia.

+ [PlainEdit - PoC learning tool, deployment during editing](https://www.plainedit.com/)


### Komu to potrzebne?

Dla osób, które nie mają (notorycznie) czasu, którzy ewentualnie dysponują kwadransem w ciągu dnia, albo w ciągu tygodnia

Dla inżynierów, architektów, programistów, administratorów i specjalistów wspierających działy IT. 


Które nie mają zdolności skupienia się na projekcie dłużej niż kwadrans, które szukają wyzwań, ale poddają się po napotkaniu pierwszych problemów.

Kołcz, psycholog, psychiatra, wszyscy oni są pomocni, ale to Ty musisz skończyć projekt, 
bo to Twój projekt.

Jak to zrobić nie posiadając wsparcia z zewnątrz?
Skąd wziąć determinację (nie mylić z motywacją)?

O tym nie będę pisał tej książce, bo to nie poradnik.

Książka napisana przez inżyniera dla umysłów otwartych na logiczne rozwiązania, które działają a ponadto są sprawdzone przez wieloletnią praktykę autora.

Dzięki temu, że istnieją publiczne i darmowe systemy wersjonowania, nikt nie może powiedzieć, że nie stać go by zademonstrowac swoje wyniki publicznie.

Każda osoba z IT zna takie protale jak github, gitlab, bitbucket, itd 
Każdy może zamieścić tam swój kod źródłowy, więc jak cenisz swój czas, zwyczajnie zajrzyj na źródło autora książki, czy kursu
aby upewnić się, ze ta oosba wie co mówi bo wykorzysdtuję wiedzę w praktyce.

Inaczej może okazać się, że jest tylko kolejnym mówcą, sprzedawcą marzeń.


## CEL

```mermaid
flowchart LR  
  informacja -- z internetu --> wiedza -- z edukacji --> doświadczenie -- z praktyki --> E[mądrość - z podejmowania dobrych moralnie decyzji]
```
informacja --> wiedza -> doświadczenie -> mądrość

informacja jest w internecie, wiedza jest z edukacji, doświadczenie z praktyki, mądrość z podejmowania dobrych (moralnie) decyzji


Mówi się, że posiadanie jasnego celu jest tak kluczowe

W praktyce sam cel to trochę mało, motywacja nie starcza na dłużej, jak wytworzyć warunki do realizacji długoterminowej strategii? 
Jak pozostać zdeterminowanym latami?

Moja odpowiedź to modularyzacja rzeczywistości, łączenie rzeczy w sieć rozwojowych obiektów, nazywam to hipermodularyzacją. Nie uciekam od zadań, ale czasem nie mam czasu, chęci i poprostu przyjmuję, że z punktu strategicznego te małe problemy nie ważą na długoterminowej strategii. Zawsze dało by się szybciej, tylko nie zawsze jesteśmy dyspozycyjni.

Sztuczna inteligencja zarządzająca zmoduloaryzowaną rzeczywistością pozwoli nam osiągać cele szybciej nawet ze spora stratą czasu


## Kwadrans

Jeśli aktualnie potrzebujesz godzin do zgłębienia projektu, czy wytworzeniu gotowego dzieła
to zapraszam do poznania metod, które pozwalają "dowozić" w ciągu kwadransów.

Osoby, które nie mają zdolności skupienia się na projekcie dłużej niż kwadrans
Osoby szukające wyzwań, ale nie dysponują wystarczającymi zasobami, jak energia, wiedza, czas.

+ Jak to zrobić nie posiadając wsparcia z zewnątrz?
+ Skąd wziąć determinację (nie mylić z motywacją)?

Książka napisana przez inżyniera dla umysłów otwartych na logiczne rozwiązania, które działają a ponadto są sprawdzone przez wieloletnią praktykę autora na setkach projektów.

Dzięki temu, że istnieją publiczne i darmowe systemy wersjonowania, można utrzymywać, demonstrować a także uruchamiać swoje projekty publicznie.

Każda osoba z IT zna takie protale jak github, gitlab, bitbucket, itd.
Każdy może zamieścić tam swój kod źródłowy, więc jak cenisz swój czas, zwyczajnie zajrzyj na źródło autora książki, czy kursu aby upewnić się, ze ta oosba wie co mówi bo wykorzystuję wiedzę w praktyce.


## Modularyzacja

Modularyzacja to proces dzielenia dużego systemu lub programu na mniejsze, samodzielne bloki, które mogą być łatwo zmieniane lub wymieniane bez wpływu na pozostałe elementy systemu. Modularizacja może zwiększyć produktywność, skracać czas tworzenia aplikacji i pomagać w tworzeniu bardziej elastycznych systemów.


## Struktura folderów a subdomeny

- Dlaczego subdomeny a nie foldery tworzą strukturę?

chodzi o to by nie tworzyć zależnych od siebie bytów
bo zależność stwarza problemy (refaktoryzacja) i ogranicza rozwój (kreatywnosć)

W hiermodualryzacji jesteś wolny, jesteś kreatywny, każda myśl musi być wolna, niezlaęzna, struktura ja zabija

jak robisz coś sam, to od Ciebie zależy rozgałęzienie a jeśli robisz coś w kontekście, np tworzysz kolejne pod-foldery, to musisz liczyć się ze strukturą powyżej

i zawsze ktoś może zwrócić uwagę, że to do siebie nie pasuje, ze coś trzeba skasować
a my nie kasujemy, my wyodrębniamy do kolejnego nowego bytu
i tak w koło
dzięki czemu możesz narobić takich stron tysiące
i potem je rozwijać w swoim tempie
nie dbasz o strukturę, bo ona nie jest potrzebna a tylko ogranicza Twoją kreatywnosć


### Dekady przeszłości

Po czasie szybkiego rozwoju różnych jezyków programoweania,
technolgoii dopasowanych do natury rzeczy w jakiej są rozwiazawyane problemy

Dochodzimy do ściany, 
W obszarze dostarczania rozwiązań biznesowych bardziej przydatne jest 
szersze spojrzenie, wykorzystanie możliwości 
w konkretnych rozwiąszaniach an iżeli budowanie
w jednym tech-stacku
nie trzeba znać dogłębnie konkretnej technologii a raczej przydatniejsze 
jest efektywne wykorzystanie gotowców
a one sa dostępne w najróżniejszych językach programowania
dlatego warto znać w kontekście modularyzacji wiele jezyków programowania
oczywiści na poziomie podstawowym , juniora programowania,
gdyż w modularyzacji liczy się skuteczność budowania sieci modułów
a one mogą być już napisane i istotne jest umiejętne wykorzystanie 
pewnych natywnych rozwiązaqń zamiast refaktoryzacji czy dopasowaywania
migracji rozwiązań pomiędzy technologiami.

 

### Jak rozmawiać o modularyzacji?

+ jakiego rodzaju oprogramowania dotyczy modularyzacja?

Głównie rozwiązania szyte na miarę, gdzie jest plan i miejsce do rozwoju projektu.

Czy widzisz sens mówić o tym czego nie widać?
Modularyzacja nie musi być głównym celem projektu, ale bywa elementem projektu i trudno wydzielić modularyzację,
gdyż w continuous development te etapy się zlewają w cykl wytwarzania i trudno je rozdzielić.

+ Gdzie i kiedy modularyzacja pomoże?
  tam, gdzie fin-y z jednej strony chcą mieć coś swojego a z drugiej boją się uwiązania do jednego dostawcy?


właśnie po to jest modularyzacja, aby znaleźć balans pomiędzy tym co jest już wymyślone i tym co chcesz sam spiąć

Modularyzacja to sposób myślenia dążący do wykorzystania -reużycia a nie uwiązania się, nic mbardziej mylnego. to chmury wiążą, one są zmodularyzwowane wewnętrznie, ale każą płacić sobie za to sporo.

W przypadku praktwkowania modularyzacji, będziesz szedł własną drogą niezależnie od dostawcy, bo twoje oprogramowanie będzie modularne, czyli możliwe do przepięcia na innego usługodawcę

Chmura robi to za Ciebie, ale chce Ciebie uwiązać własnym kontekstem, językiem programowania, czy no-codem

+ Modularyzacja daje poczucie niezależności a nie przywiązania

Dlatego uważam, że w obecnych czasach to bardzo istotne aby umieć się odnależć w tej mnogości rozwiązań a jednocześnie nie dać się uwiązać, właśnie dzięki modularyzowaniu, ubieraniu wszystkich rozwiazań w klocki pozwalając im się replikować w dowolnym środowisku i konfiguracji

+ Co jest rezultatem modularyzacji?

Rezultatem modularyzacji nie jest wykorzystywanie konkretnego dostawcy, a odporność na jednolitość, budowanie naturalnej struktury, pozwalającej na natywne zarządzanie strukturą całego biznesu

Chmury narzucają rozwiązania, modularyzacja otwiera Cię na nie

mikroseriwsy są ewolucją i jak widać na nich ona się nie zakończyła, modularyzacja daje wybór: monolit, mikroserwis, itd



## [KURS](WSTEP/KURS.md)

Z uwagi na niszowy temat, podjęte zostaną prace nad tworzeniem stałej bazy dla chcących zwiększyć swoje kwalifikacje w sferze modularyzacji.

Kurs będzie przeznaczony zarówno do osób początkujących, jak i doświadczonych programistów, którzy pragną poszerzyć swoją wiedzę związaną z tworzeniem modularnego oprogramowani.


Masz wątpliwości dotyczące kodu źródłowego? Chcesz sprawdzić aplikację, zanim podejmiesz decyzję o zakupie kursu?
Nie ma problemu!

Wszystko jest open source!


Cały kod źródłowy, który zaimplementujemy wspólnie podczas kursu, jest dla Ciebie dostępny za darmo na GitHub!



## Monolit, Mikroserwisy a Modularyzacja

Kurs modularyzacji oprogramowania

+ Czym jest, a czym nie jest modularne oprogramowanie?
+ Czy mikroserwisy to jedyna droga na tworzenie autonomicznych, modularnych aplikacji?
  + Modularny Monolit
  + Modularny Mikroserwis
+ Analiza procesów i wyodrębnianie niezależnych modułów
+ Jak i kiedy wydzielać moduł do mikroserwisu?
+ Jak projektować i wdrażać  niezależnie od siebie autonomiczne moduły?


### Architektura

+ Jaka jest różnicą pomiędzy architekturą horyzontalną, a wertykalną?
+ Czym jest vertical slice?

### Moduły

+ Jak zaimplementować niezależne od siebie moduły z dowolnym stylem architektonicznym?
+ Czym jest w ogóle ten Software Craftsmanship w praktyce?
+ W jaki sposób możemy komunikować, oraz integrować ze sobą moduły?
+  Wyodrębnienie pojedynczego modułu do dedykowanego mikroserwisu


### Software Development

+ Jakie wady i zalety ma podejście oparte na kodzie współdzielonym, a jakie na lokalnych kontraktach?
+ Czy możemy osiągnąć transakcyjność i spójność danych w niezależnych modułach?
+ Jak implementować globalne procesy przecinające różne moduły?
+ Implementacja modułów w oparciu o vertical slice
+ Wydzielenie wspólnej części w oparciu o współdzielone abstrakcje
+ Osiągnięcie pełnej autonomii modułów z wykorzystaniem lokalnych kontraktów


### Transakcje

+ Rodzaje spójności i transakcyjności danych w modularnym monolicie
+ Event-driven architecture w aplikacji monolitycznej

### Komunikacja

+ Wewnętrzna komunikacja pomiędzy modułami na wzór Web API
+ Wewnętrzna integracja pomiędzy modułami z wykorzystaniem brokera wiadomości
+ Synchroniczna, a asynchroniczna obsługa komunikatów


### Wdrożenie
+ Metody dynamicznego wdrożenia aplikacji i wybranych modułów

### Wzorce, środowisko,
+ Dobór odpowiednich stylów architektonicznych do klasy złożoności modułu
+ Domain-Driven Design, CQRS, ES, CRUD
    + Wykorzystanie różnych wzorców w zależności od klasy problemu
    + Jak stosować DDD, CQRS, ES, CRUD


### Testowanie

+ Jak testować moduły w środowiskach: lokalnym i globalnym?
+ Testowanie na róznych poziomach (jednostkowe, integracyjne etc.)
 
 
# Warsztaty modularyzacji oprogramowania

## Dla kogo?

Dla mniejszych grup zainteresowanych praktycznym wykorzystaniem w swojej organizacji metodyki hipermodularyzacji:

## Zadania 

Przygotowanie, dokumentacja techniczna

+ Wybór projektu
+ Audyt
  + Określenie ram środowiska
  + Zbadanie głębokości zależności
  + Określenie punktu ciężkości
+ Określenie kryteriów wydzielania obszarów do modularyzacji
+ Utworzenie kryteriów dynamicznej mapy podziału
+ Kryteria sposobu tworzenia i łączenia zależności


Zespół, dokumentacja kompetencji

+ określenie kompetencji
+ priorytety doboru członków zespołu do prac
+ priorytety obszarów systemu do modularyzacji
  + od zewnątrz, od wewnątrz, frontend, backend, api
+ określenie kryteriów odbioru prac code-review
+ definicja dokumentacji
+ zdefiniowanie automatyzacji dla wykonywania zadań
  + przydzielanie autonomicznych obszarów na czas wykonywania modułu
  + określanie spodziewanych rezultatów funkcjonalnych
  + generowanie makiet wstępnych z definicją na podstawie dokumentacji


### Modularyzacja

+ Określenie moduł na mapie ekosystemu
+ Tworzenie definicji modułu
  + nazwa
  + zastosowanie
  + ograniczenia
  + skojarzenia
  + tagi
  + zależności
+ Dokumentacja funkcjonalna
+ Tworzenie testów i kodu
+ Deployment 
  + lokalny
  + docker

## KONTAKT

### Zapraszam do współpracy
Jestem optymistą i chciałbym mieć kontakt z ludźmi krytycznymi, którzy pomogą w rozwoju tego projektu, bo pierwszy e-book będzie tylko o oprogramowaniu i to ma być zaczątkiem dyskusji.



### Gitter, Dołącz do otwartej społeczności

Zapraszamy Cię do otwartej społeczności HiperModularzyacja.pl dostępnej za pomocą popularnego komunikatora Gitter,
używanego przez programistów na całym świecie.

Niezależnie od tego, czy zdecydujesz się (bądź nie) na zakup kursu

Zachęcamy Cię do zadawania pytań oraz dyskusji na wybrane zagadnienia dotyczące kursu (i nie tylko).


### Inne projekty powiązane

#### Flow

https://github.com/js-func/win-ticket-version-flow

https://github.com/programista-de/CycloneGenesis

#### Narzędzia

+ scenariusze Given-When-Then
  https://www.michalbartyzel.pl/po-co-mi-gherkin/





## Modularyzacja i Hipermodularyzacja w dostarczaniu rozwiązywań

Hipermodularyzacja to droga dojścia do celu, a nie szczegółowy plan.
Rezultatem są setki, tysiące współpracujących ze sobą modułów jednego lub wielu systemów.

Modularyzacja pomaga w ponownym użyciu już istniejących elementów.

Hipermodularyzacja pomaga w tworzeniu wyspecjalizowanych rozwiązań tworząc kolejne wyspecjalizowane elementy systemu.

W architekturze modularnej kierunkiem jest ciągłe mnożenie standaryzowanych i wyspecjalizowanych detali.


## Projekty IT i deadline

Hipermodularyzacja ułatwia zamykanie każdego etapu projektu w skończonych ramach już na etapie koncepcji i prototypu.


### Planowanie, Architektura

!!! Architektura jest rezultatem poszukiwania rozwiązania problemów warstwy biznesowej a nie rozwiązaniem samym sobie !!!

Skończona ilość modułów może tworzyć skończoną ilość rozwiązań poprzez zmianę układów połączeń.


### Presja


Każdy projekt i jego etap powinien zostać ukończony w zaplanowanym terminie, budżecie, co jednak zrobić, gdy tenże plan kolejny raz okazał się niewystarczająco dokładny?


Pytanie jest zasadnicze i warto zweryfikować faktory brane pod uwagę przy planowaniu, wzory i szczegóły obliczeń z przykładami znajdują się na stronie [www.estymacja.pl - estymacja w projektach IT](https://www.estymacja.pl/)

### Ograniczenia

Jest co najmniej kilka ograniczeń z jakimi musimy się zmierzyć:
+ ograniczenie czasu na wykonanie - deadline
+ ograniczenie kosztów
+ ograniczenie liczebności zespołu tworzącego rozwiązania
+ ograniczenia kompetencji poszczególnych osób
+ ograniczenia postrzegania związane z wiedzą domenową, skutkuje też błędnymi implementacjami, podatność na błędy
+ ograniczenia w zdolności planowania wywołane np deficytem wyobrażenia, np. zbyt małym doświadczeniem 


### Cechy - Kreatywność

W modularyzacji nie ma miejsca na ograniczanie kreatywności ani na tworzenie pod-modułów zależnych od drugich bezpośrednio.
relacje między modułami są równorzędne.
W rezultacie tworzymy modularną strukturę, łatwą do rekonfiguracji, gdyż nie jest stała i można ją dowolnie zmieniać
używając alternatywnych modułów.


### Cechy - Autonomia


Autonomiczność jest wpisana w naturę i sposób użycia modułu.

Zamiast tworzyć kompromisowe rozwiązania ograniczające twórczość możemy otworzyć się na tworzenie, które w tworzeniu oprogramowania jest tańsze
niż wpasowanie, kształtowanie, migracja, adaptacja, itd
Nie nadajemy ram systemowi a modułom go tworzących.
Dzięki temu możmy zamiast przerabiać moduł stworzyć podobny, który będzie lepiej spełniał zadanie a w kolejnym etapie
podzielić go na kolejne moduły, tak by każda część spełniała najlepiej przydzieloną funkcję i by w połączeniu w większą strukturę były
lepiej reużywalne w różnych zastosowaniach.


## Cechy - Modułowość

Co oznacza modułowość?

W inżynierii oprogramowania modułowość odnosi się do zakresu, w jakim oprogramowanie/aplikacja internetowa może zostać podzielona na mniejsze moduły. Modułowość oprogramowania wskazuje, że liczba modułów aplikacji jest w stanie obsłużyć określoną domenę biznesową.

Modułowość jest skuteczna, ponieważ programiści używają gotowego kodu, co oszczędza zasoby. Ogólnie rzecz biorąc, modułowość zapewnia większe możliwości zarządzania rozwojem oprogramowania.
Techopedia wyjaśnia modułowość

Współczesne zagadnienia biznesowe stale rosną – pod względem wielkości, złożoności i popytu. Zwiększone wymagania dotyczące możliwości oprogramowania zmuszają programistów do ulepszania opracowanych systemów o nowe funkcje.

Modułowość inżynierii oprogramowania umożliwia dzielenie typowych aplikacji na moduły, a także integrację z podobnymi modułami, co pomaga programistom korzystać z gotowego kodu. Moduły są podzielone ze względu na funkcjonalność, a programiści nie są zaangażowani w funkcjonalności innych modułów. Dzięki temu nowe funkcjonalności można łatwo zaprogramować w osobnych modułach.


### Kształt/Obraz modułu

Jeśli moduł jest (od strony technicznej) poprawnie zbudowany to rezultatem jest (bądź powinna być) żywotność i użyteczność w konkretnym kotekście.

Jeśli ta cząstka będzie spełniała oczekiwania w kontekście jej samej, jako samodzielnego bytu, możliwe jest jej wykorzystanie do kolejnego etapu prac.


### Rozmnażanie poprzez podział

Proces powstawania kolejnych modułów:
1. Definicja modułu
2. Praktyczny przykład zastosowania
3. Powstanie modelu
4. Prototypowanie
5. Zbadanie ograniczeń
6. Określenie kompetencji
7. Stworzenie kolejnego modułu, który uzupełnia kompetencje wcześniejszego ograniczonego modułu
   kontynuacja od punkt numer 1


Magia ciągłego podziału modułów na mniejsze sprawia, że każdy z nich jest określony w aktualnym kontekście.




### Cechy - Natywność

Trendy w technologii pokazują specjalizację
każdy jezyk znajduje odpolwiednie do jego specyfiki zastosowanie
gdyż jest szeroki wachrlarz rozwiązńą
i szkoda zasobów na wyważanie już otwartych drzwi


### Cechy - Generyczność

## Cechy - Ponowne użycie - reusability

Miernikiem skuteczności modularyzacji jest reużycie.
W momencie powstawania rozwiązania trudno określić ramy projektu i wyznaczyć mapę.
Odseparowanie następuje z czasem na skutek sprecyzowanej definicji, określenia ograniczeń i kompetencji modułu.
To wszystko przychodzi z czasem po którejś iteracji w fazie prototypowania.
Odseparowanie jest lekiem na szukanie kompromisów, ograniczamy w ten sposób koszty powstawania modułu.
Szukamy granic, w których będzie funkcjonował samodzielnie zamiast wpasowywać go w istniejące ramy systemu
przez co staje się karykaturą modułu a bardziej przypminać może adapter, helper, i tym podobne rozwiązania jednorazowego użytku
zależne od większej części.

## Cechy - Zarządzalność

## Filozofia


### Personalizacja hipermodularyzacji

Aby w pełni opisać sens hipermopdualryzacji warto posłużyć się porównaniem.

### Hipermodularyzacja jako osobowość

Hieprmodularyzacja pochodzi z rodziny gdzie perfekcjonizm jest normą.
Jednak dorastała w atmosferze braku możliwości, dlatego nie mogła dać wyrazu realizacji perfekcyjnej stronie osobowości
co by wpłynęło negatywnie na zdolność do przetrwania, z powodu kosztownego procesu uzyskania perfekcjyjnych wyników.
Jakie rezultaty uzyskamy niekontrolując perfekcjonizmu?
Ile może kosztować perfekcjonizm nie liczący się z naturą rzeczy i środowiska?


### Hipermodularyzacja w praktyce

Modularyzacja jako skupienie się na mniejszych elementach systemu wchodzących w większą całość
polega na uzyskaniu większych elementów poprzez tworzenie i dobór tych mniejszych.

Hipermodularyzacja skupia się na uzyskaniu możliwie największej ilości modułów,
gdyż tak jak obrazy widziane w monitorach LCD są lepszej jakości, gdy jest więcej pixeli, czyli poszczególnych cząstek
tak i systemy budowane w oparciu o mniejsze i lepiej wyspecjalizowane i dopasowane elementy będzie bardziej efktywny.

Perfekcjonizm w Hipermodularyzacji udziela się w momencie podziału, gdy konieczna jest decyzja
klarowna filozofia podziału z uwzględnieniem aktualnych możliwości i alternatyw.

Dlatego mimo, że temat perfekcjonizmu został poruszony jako kluczowy to jest to kontrolowany perfekcjonizm,
który kontroluje tylko sposób wyodrębniania kolejnych modułów, gdyż ta część cyklu powstawania modułów
jest bardzo istotna z punktu szybkiej ewolucji całej sieci.



## koszt

Co do samego rozbijania modułu w procesie hipermodularyzacji warto brać pod uwagi koszta tego procesu 
zakładam, że będzie tam: ilość alternatywnych modułów, koszt zasobów: czasu, energii, wdrożenia
ale te są zależne też od samej strategii, więc trudno to ująć samymi parametrami ilościowymi




## Pryncypia

Dostawa
Delivery

Modularity
Modularność

Improvement
Poprawa


Modularization
Modularyzacja

Continuous Modularization
Ciągła modularyzacja
## ARCHITEKTURA

służy pivot-owaniu, cyzli architekturze wertykalnej, pionowej, która jest łatwo adaptowalna,
skupia się na stream-owaniu i transportowaniu jak najszybciej
bez obsługi danych lokalnie a jedynie przekazywaniu ich dalej
wówczas wązkim gardłem jest propagacja infrastruktury
ale w lokalnych systemach jest ona ograniczone głównie sprzętem.

wertykalne usługi pozwalają na synchroniczne i asynchroniczne przesyłanie danych w strumieniu bezpośrednio do klienta, bez potrzeby obsługi i konfigurowania procesów wspierających
służących obsłudze specyficznych dla technologii procesów.

## Kontekst


Czym jest Hipermodularyzacja?

**Hipermodularyzacja jest sposobem myślenia, gdzie deklarujemy wiadome i niewiadome, istotny jest stan faktyczny, to co wiemy
a następnie rozbijamy te elementy na mniejsze.**

Czym jest kontekst?

+ celem, kierunkiem, lokalizacją
+ zamysłem, planem, intencją, wiedzą zespołu
+ typ aktywności, stanem rzeczywistości, relacji

Kontekst określa wektory punktów (w rzeczywistości), do których zdążamy. 
Kontekst rysuje mapę połączeń z określeniem sił tych zależności.
Z praktyki wiemy, że kontekst dyskusji, rozmowy, intencji nadaje inne znaczenie tym samym słowom.



Myślenie w kontekście (czegoś) jest motorem napędowym.
Nie wiemy jak coś zostanie wykonane, ale wiemy, że musimy w kontekście aktualnej sytuacji dostarczyć brakującą cegiełkę do powstającej budowli,
czyli w kontekście powstającego projektu dostarczamy moduł.

Dlaczego kontekst jest tak istotny?
To on stawia oczekiwania i daje informację o oczekiwaniach.

Mobilizujące konteksty do szybszego powstania rozwiązania, mogą być inne konteksty lub wszystkie razem:
+ rywalizacja na rynku - determinuje szybsze, lepsze rezultaty
+ rywalizacja w branży - determinuje zdobycie pozycji lidera
+ rywalizacji w osiąganiu zysków - determinuje zapobieganie marnotrawieniu zasobów

Charakterystyczne dla kontekstu powstawania rozwiązania są liczby, które pozwalają na ocenę sytuacji:
+ rywalizacja na rynku - zyski organizacji
+ rywalizacja w branży - rozpoznawalnośći, wybór statytyscznego konsumenta
+ rywalizacji w jak najwyższej marży - procent zysku ze sprzedaży

Kontekstem może być presja wysokich kosztów, do tego stopnia, że z probelmu może stać się wyróżnikiem oferty firmy,
gdzie klient otrzymuje dobre rozwiązanie za niższą cenę niż konkurencja.

Niestety na rynku IT trudno o porównianie, trudno o statystyki kosztów, a cena wyjściowa to za mało.


### Przykład kontekstu

Na przykładzie budynku kontekstem jest plac budowy, na którym się znajdujemy

+ widzimy stan i etap budowy
+ znamy infrastrukturę otoczenia
+ znamy pogodę, temperaturę, wilgotność
+ wiemy z planu budowy czego oczekujemy i rozumiemy jakich etapów nie przeskoczymy, co trzeba zrobić w kolejnym etapie

Jak widać, nie skupiamy się na planie za 10 lat, tylko na technicznej i drobiazgowej analizie tgo co mamy tu i teraz przed sobą.

Przykład budowy domu nie odzwierciedla wszystkich korzyści stosowania hipermodularyzacji, gdyż budowa domu to duże przedsięwzięcie, które trudno podzielić na etapy, gdzie jedna część będzie
w pełni funkcjonalna w ciągu 1 czy kilku dni.
Tym różni się projekt w architekturze monolitu i modularnych serwisów, tzw. mikro-serwisów API i mikro-frontenu oraz idące za tym korzyści jak:
+ reusability - możliwość ponownego wykorzystania


Trafniejsze odniesienie ze świata IT zmodularyzowanych autonomicznych modułów to budowa środków transportu.
Samochód można zbudować z różnych dostępnych elementów i można je poprawiać



## Pułapki kontekstu

Gdy tworzymy w architekturze modularnej, tworzymy generyczne moduły

Na początku projekt może trwać latami, ale korzyścią jest brak kontekstu w przypadku skupieniu na modułach.
To wyzbycie się kontekstu w przypadku budowania systemu daje większą reużywalność
Gdybyśmy wszystkie klasy, funkcje budowali w kontekście niegenerycznej całośći
każda część nie będzie mogła funkcjonować samodzielnie, gdyż beðzie logiczną częścia całego systemu

Dlatego dla dobra efektu końcowego jakim ma być reużycie modułów warto najpierw budowałąc moduły
aby były wyspecjalizowane
i dopiero potem opierać o nie system,
jeśli będzie zapotrzebowanie na inną funckjonoalość
to zamiast dopasowywać
tworzymy nowy moduł,
dzięki temu mamy jeden moduł więcej, który działa w określonych warunkach
i nie jesteśmy zmuszeni do ciągłego doskonalenia jednego modułu, który stale by podlegał zmianom.

### Refaktoryzować czy zlecać nowy moduł?

W branży IT opłaca się znacznie bardziej tworzenie na nowo niż przerabianie, refaktoryzacja kodu, gdyż ona wymaga głebszego zrozumienia
nie tylko przeznaczsenia ale też aktualnej implementacji, co generuje większsze koszty
i wymaga dobrze zgranego zespołu, zamiast tego zlecamy na zewnątrz konkretną funkcjonalność i zapoominamy o problemeach refaktoringu
który w przypadku błędów można poddać reklamacji autorowi.



## Cechy - Perfekcjonizm


### Perfekcyjna rodzina

Perfekcjonizm narzuca sztuczne ramy na wszystko, nie bacząc na naturalne z góry wcześniej ustalone zasady i mechanizmy kierujące światem.
Motyw i rezultaty przypominają szaleńcze metody prowadzące do destrukcji modelu, który nie jest gotowy na nienatrulaną strukturę.
Perfekcjonizm nie liczy się z naturą otoczenia.
Dlatego warto mieć na względzie noszone ryzyko pędem perfekcjonizmu, gdyż pełnia perfekcjonizmu ma szansę realizacji kosztem dobrobytu, swojego i otoczenia.


### Perfekcjonizm w praktyce

Perfekcjonizm wprowadzany w firmie Toyota w odniesieniu do automatyzacji w 100% nie powiódł się kilkadziesiąt lat temu
a kilka lat temu w firmie Tesla ponownie mimo wielkiego postępu technologicznego nie udało się uzyskąc 100% automatyzacji w produkcji samochodów.

Jak widać perfekcjonizm jest metodą uzyskania ekstremalnie nienaturalnych wyników, np. produkcji bez udziału człwoieka.
Jest to trudne i dlatego trzeba charakteryzować się wysoką dozą perfekcjonizmu by uzyskliwać znacznie lepsze rezultaty
niż są aktualnie uzyskiwane przez konkurencję.


## Faktory

+ model środowiska, w którym będzie funkcjonuje system oparty o architekturę hipermodularną 
+ model architektury systemu w środowisku dla elementów w nich funkcjonujących
+ model elementu w systemie sieci modułów

Istotne jest rozumienie zasad działania środowisko, dopasowanie architektury i połączeń między modułami.

W warstwach wysokiego poziomu wszystko może wydawać się proste
ale każdy element jest oparty o inną technologię.






## Zasoby

Mamy ograniczone zasoby: wiedzę, kontakty-relacje, czas wolny, pieniędze, ...

Bez czego te powyższe nie mają znaczenia?

+ bez Energii!

Z fizyki wiemy, że aby wykonana była praca W potrzebna jest energia/moc P i czas.

Moc P obliczmy dzieląc pracę przez czas, w którym ta praca została wykonana: P = W / t, gdzie P – to moc, W – praca, t – czas.

Bez energii nawet majaąc czas nie wykonamy żadnej pracy.

Kluczem jest zarządzanie w taki sposósb, by nie ograniczać posiadanej energii a prowadzić projekty tak, by rezultaty nie były porzucane, marnowane z uwagi na złe zaplanowanie.

Dlatego z technicznego punktu widzenia lepiej tworzyć rozwiązania modularne, gdzie każdy moduł może być wykorzystany w różnym kontekście,
czyli posłużyć do użycia wielokrotnie!

### Mapa Zasobów

Tworzenie mapy zasobów jest pomocne w określaniu możliwości ekspansji

+ [Wardley Mapping - Growing Adaptive Organizations](https://growing-adaptive-organizations.org/article/wardley-mapping/)



## CZAS 

### Dostarczenie modułu, dziś!

Czy to trudne stworzenie modułu, pojedynczego elementu na dziś?
w ciągu kilku godzin?
Jeśli mamy informację o kontekście to możemy zrobić mały krok do przodu.

Zamiast skupiać się na tworzeniu idealnej całości, skupiamy się na dostarczeniu minimum w minimalnej skali, tak by bazując na takich małych elementach
dostarczyć krok po korku oczekiwany system połączonych elementów.

Nie potrzebujemy przy tym w jednym momencie precyzować ilości elementów ekosystemu, nie jest to potrzebne,
gdyż skupiamy się na jakościowym wytwarzaniu i dostarczaniu rozwiązań w mniejszej skali.

Taki modularny system wzajemnie połączonych modułów, można rozbudowywać i przebudowywać i to jest siła tej metodolgii.

### kwadrans

Hipermodularyzacja to tworzenie pojedynczych modułów w kwadrans

Jak to w praktyce wygląda?

1. Tworzę projekt na github, np organizacja/nowy modul
2. plik reamde.md z opisem, co chcę zrobić
3. strukturę plików
4. w każdym pliku na początku piszę co ma w nim się znajodwać i jak działać
5. dopisuję kod zaczynając od tego co wiem
6. weryfikuję pisząc pojedyncze testy konkretnych funkcji
7. tworzę kolejne iteracje ulepszajac kod, 
8. Wyodrębniam wychodzące poza zakres tego modułu do następnego modułu i powtarzam od punktu nr 1

Każdy moduł jest budowany wedle podobnego wzorca

Celem jest zbudowanie czegokolwiek co można dalej rozwijać,


Całościowo to trwa dłużej, ale ma strukturę i pozwala na rozbudowę
w oderwaniu od konkretnego projektu a skupione na pojedynczych rezultatach funkcjach



## ENERGIA 

hipermodularyzacja oszczędza zasoby, w kontekście pracy człowieka to głównie energię, jaką musiałby włożyć w wyatwarzanie często już inaczej zaplementowanych elementów systemu

pivotowa architektura i reużycie dają szansę na szybszą implementację i oszczędność pracy w kolejnych implementacjach.


## KOSZT MODULARYZACJI 

Koszty wytwarzania aplikacji są tym wyższe im bardziej niejednorodne są moduły i trudniejsze do połączenia.

Dlatego operatorzy chmur oferują szybki development ale potem aplikacja jest droga w utrzymaniu, niestety nie ma idelanego rozwiązania, ale długofalowo opłaca się w duchu modularyzacji tworzyć i utrzymywać całą infratsrukturę, gdyż to daje szansę na syzbszy wzrost niż konkurencja.

To nie jest rozwązanie dla szukających oszczędności, bo modularyzacja nie jest tania, wymaga przede wszystkim myślenia abstrakcyjnego i podejścia długofalowego. Trzeba rozróżnić wdrożenie modularyzacji w istniejącym projekcie i wykorzystanie gotowych modułów w nowym tak jak ma to miejsce w chmurze.

Dlatego jednorazowe projekty można szybko stworzyć w chmurze, ale to kosztuje więcej niż tradycyjna infrastruktura, z kolei tworzenie tego we własnej organizacji wymaga grupowej synchronizacji w duchu modularyzacji a każdy ma powody by tego nie robić, dopóki nie ma ku temu odpowiednich rozwiązań. 


### Koszty w długiej perspektywie

Koszty te zależą nie tylko od aktualnych kosztów zatrudnienia czy energii oraz dostępności i cen podzespołów i zasobów.

Istotne jest to jak robimy, jaką metodą
i tutaj ograniczają nas zasoby.
wobec tego musimy określić jakie zasoby są krytyczne,
Następnie określić jakie dodatkowe korzyści e chcielibysmy uzyskać


## Kreatywność

Kreatywność jest jak nieokiełznany żywioł, który można ukierunkować i to od metodyki zależy rezultat.

Która metodyka wytwarzania oprogramowania pozwala wytwarzać setki projektów rocznie?

...

Czy wystarczy rozumieć (znać) problem i chcieć go rozwiązać?
+ Czy motywacja i determinacja są wystarczające?
+ Czy wystarczy znajomość tech-stack'a?
+ Czy wystarczy znaleźć metodę finansowania, by projekt z czasem sam się finansował?

...
Warto wziąć pod uwagę to co się lubi i co się potrafi, aby się nie męczyć nieskończonością prac, by mieć chęć do nauki mimo trudności


### Hipermodularyzacja - lek na perfekcjonizm


Osoba kreatywna może brnąć w drobiazgowość lub skupiać się na całości.

    Każdy element projektu jest skończony, ale tworzy nieskończoną sieć połączeń z innymi.

Hipermodularyzacja pozwala na zachowanie ram każdego elementu projektu.
Sprzyja to szybszemu i efektywniejszemu ukończeniu etapów, które na drodze perfekcjonizmu są blokowane poszukiwaniem złotego środka.

Złoty środek istnieje dla każdego specyficznego punktu i zamykając go w ramach każdego wyspecjalizowanego elementu zamiast większej całości zyskujemy możliwość definiowania aktualnego stanu jako docelowego, zamiast stale poszukiwać lepszej wersji.

Lepsza wersja może a nie musi powstać, ale już w ramach kolejnego projektu/elementu systemu.




### Kreatywne tworzenie z pomocą hipermodularyzacji

Kreatywność można realizować na drodze tworzenia w oparciu o już istniejące elementy bądź tworzyć dzieło za każdym razem od nowa z określonego budulca,


    np: lepienie nowej rzeźby z gliny a budowanie z gotowych modułów - klocków.


Mówiąc o Hipermodularyzacji możemy wyobrazić sobie nieskończoną ilość idei z których tworzone są kolejne.

W ten sposób tworzenie rozległej sieci zaawansowanych idei jest praktycznym skutkiem stosowania hipermodularyzacji.



## Kontekst


Czym jest Hipermodularyzacja?

**Hipermodularyzacja jest sposobem myślenia, gdzie deklarujemy wiadome i niewiadome, istotny jest stan faktyczny, to co wiemy
a następnie rozbijamy te elementy na mniejsze.**

Czym jest kontekst?

+ celem, kierunkiem, lokalizacją
+ zamysłem, planem, intencją, wiedzą zespołu
+ typ aktywności, stanem rzeczywistości, relacji

Kontekst określa wektory punktów (w rzeczywistości), do których zdążamy. 
Kontekst rysuje mapę połączeń z określeniem sił tych zależności.
Z praktyki wiemy, że kontekst dyskusji, rozmowy, intencji nadaje inne znaczenie tym samym słowom.



Myślenie w kontekście (czegoś) jest motorem napędowym.
Nie wiemy jak coś zostanie wykonane, ale wiemy, że musimy w kontekście aktualnej sytuacji dostarczyć brakującą cegiełkę do powstającej budowli,
czyli w kontekście powstającego projektu dostarczamy moduł.

Dlaczego kontekst jest tak istotny?
To on stawia oczekiwania i daje informację o oczekiwaniach.

Mobilizujące konteksty do szybszego powstania rozwiązania, mogą być inne konteksty lub wszystkie razem:
+ rywalizacja na rynku - determinuje szybsze, lepsze rezultaty
+ rywalizacja w branży - determinuje zdobycie pozycji lidera
+ rywalizacji w osiąganiu zysków - determinuje zapobieganie marnotrawieniu zasobów

Charakterystyczne dla kontekstu powstawania rozwiązania są liczby, które pozwalają na ocenę sytuacji:
+ rywalizacja na rynku - zyski organizacji
+ rywalizacja w branży - rozpoznawalnośći, wybór statytyscznego konsumenta
+ rywalizacji w jak najwyższej marży - procent zysku ze sprzedaży

Kontekstem może być presja wysokich kosztów, do tego stopnia, że z probelmu może stać się wyróżnikiem oferty firmy,
gdzie klient otrzymuje dobre rozwiązanie za niższą cenę niż konkurencja.

Niestety na rynku IT trudno o porównianie, trudno o statystyki kosztów, a cena wyjściowa to za mało.


### Przykład kontekstu

Na przykładzie budynku kontekstem jest plac budowy, na którym się znajdujemy

+ widzimy stan i etap budowy
+ znamy infrastrukturę otoczenia
+ znamy pogodę, temperaturę, wilgotność
+ wiemy z planu budowy czego oczekujemy i rozumiemy jakich etapów nie przeskoczymy, co trzeba zrobić w kolejnym etapie

Jak widać, nie skupiamy się na planie za 10 lat, tylko na technicznej i drobiazgowej analizie tgo co mamy tu i teraz przed sobą.

Przykład budowy domu nie odzwierciedla wszystkich korzyści stosowania hipermodularyzacji, gdyż budowa domu to duże przedsięwzięcie, które trudno podzielić na etapy, gdzie jedna część będzie
w pełni funkcjonalna w ciągu 1 czy kilku dni.
Tym różni się projekt w architekturze monolitu i modularnych serwisów, tzw. mikro-serwisów API i mikro-frontenu oraz idące za tym korzyści jak:
+ reusability - możliwość ponownego wykorzystania


Trafniejsze odniesienie ze świata IT zmodularyzowanych autonomicznych modułów to budowa środków transportu.
Samochód można zbudować z różnych dostępnych elementów i można je poprawiać



## Pułapki kontekstu

Gdy tworzymy w architekturze modularnej, tworzymy generyczne moduły

Na początku projekt może trwać latami, ale korzyścią jest brak kontekstu w przypadku skupieniu na modułach.
To wyzbycie się kontekstu w przypadku budowania systemu daje większą reużywalność
Gdybyśmy wszystkie klasy, funkcje budowali w kontekście niegenerycznej całośći
każda część nie będzie mogła funkcjonować samodzielnie, gdyż beðzie logiczną częścia całego systemu

Dlatego dla dobra efektu końcowego jakim ma być reużycie modułów warto najpierw budowałąc moduły
aby były wyspecjalizowane
i dopiero potem opierać o nie system,
jeśli będzie zapotrzebowanie na inną funckjonoalość
to zamiast dopasowywać
tworzymy nowy moduł,
dzięki temu mamy jeden moduł więcej, który działa w określonych warunkach
i nie jesteśmy zmuszeni do ciągłego doskonalenia jednego modułu, który stale by podlegał zmianom.

### Refaktoryzować czy zlecać nowy moduł?

W branży IT opłaca się znacznie bardziej tworzenie na nowo niż przerabianie, refaktoryzacja kodu, gdyż ona wymaga głebszego zrozumienia
nie tylko przeznaczsenia ale też aktualnej implementacji, co generuje większsze koszty
i wymaga dobrze zgranego zespołu, zamiast tego zlecamy na zewnątrz konkretną funkcjonalność i zapoominamy o problemeach refaktoringu
który w przypadku błędów można poddać reklamacji autorowi.


## Strategia

W zalezności od przyjętej strategi zostają przyjęte luib nie zasady prowadzenia codziennych zadań
oraz główny cel jaki długofalowo chcemy osiągnąć, w skórcie określamy specyfikę uzyskiwania długofalowaych rezultatwó
co nazywamy strategią.

W takiej wielomiesięcznej czy wieloletniej perspektywie możemy określić preferencje
które pozwolą na szybsze uzyskanie oczekiwanego rezultatu.

Może to być strategia poszukiwania słabych punktów biznesu od strony:
+ bezpieczeństwa
+ marży,
+ konkurencyjności

Perzy wytwarzaniu oprgoramowania liczy się  zdolność do szybiekgo adaptowania do potrzeb biznesowych
co sprowadza się do efektywnego czyli najniższym kosztem dostarczenia technicznego rozwiazania.


### Jakie korzyci daje długofaowa astrategia hipermodularyzacji?

Korzystanie z już wytworzonych modułów

poprzez korzystanie z natywnych i jak jak szczupelyjszych zależności można ułatwić łączenie rozwiazań
krtóre beda w przyszłości opeirały się o inne rozwiażania, technologie, jezyki programowania,
gdzie nawet można wziąć pod uwagę translację z jedno na drugi jezyk



## [PROTOYPOWANIE](PROTOYPOWANIE.md)


## hiperprogramowanie

W hiperprogramowaniu korzyściami jest obszerna i dopasowana biblioteka modułów.

można znaleźć i dopasować, kształtować te już istniejące, lub szukać lepszych.

Jeśli koszty pracy są niskie to można poświęcić czas na tworzenie własnych rozwiazań
w innej sytuacji łatwiej zdobyć już otwarto źródłowe rozwiazania lub zlecić wykonanie,
wówczas trzeba umieć sprecyzować oczekiwania:

+ modele danych
+ procesy
+ środowisko
+ zależności
+ testy
+ uruchomienie
+ wdrożenie

Do tego dokumentacja


## [BIZNES](BIZNES.md)

Konkurencja nie śpi, liczy się czas wdrożenia,

W czasie kryzysu utrzymanie się na rynku może być dla części wyzwaniem.
Dostarczenie zadowalającego produktu ma tym większe znaczenie.

To początek drogi, dlatego potrzebna jest baza do komunikacji z klientami chcącymi wdrożyć modularyzację u siebie na wyższym poziomie.
Uwzględniać długofalową przewagę konkurencyjną.
Zgodnie z misją firmy Softreck: Leadership Through Software Development
oraz wizją, która nawiązuje do bardzo spersonalizowanego wytwarzania oprogramowania i modularyzacja jest środkiem do tego celu.

Modularyzacja zawsze jest elementem projektu i trudno wydzielić modularyzację, gdyż w continuous development te etapy się zlewają w cykl wytwarzania i trudno je rozdzielić.


### Innowacja

Dużo się mówi o innowacyjności, skojarzenia dotyczą kreatywności, tworzenia nowych rozwiązań na stare problemy.

+ Jak budować drogę ku innowacyjności?
+ Jak kontrolować, zwiększając udział innowacyjności w oczekiwanych obszarach organizacji?
+ Jak personalizować rezultaty tej innowacyjności?
+ Jak dostosować do specyfiki przedsiębiorstwa?

Trudno odpowiedzieć jednoznacznie, jest tyle zmiennych, które muszą jescze być odkryte.
Czy jest jednak szansa na zdefiniowanie samej drogi jaką należy podążać, bez ryzyka?

Tak, jest nim modularyzacja, która w organizacjach nastawionych na wzrost organiczny daje dużą przewagę w dłuższej perspektywie czasowej.
+ [Wzrost Organiczny Firmy - Polska 2021](https://wzrostorganiczny.pl/)



### Modularyzacja w wielu branżach

i zbieram wiedzę na ten temat, chodzi o modularyzację w wytwarzaniu oprogramowania, produkcji w przemyśle, sprzedaży, marketingu i zarządzaniu projektami i ludzmi.

Przykładowe opracowanie korzyści:
https://www.imbigs.pl/sites/default/files/pliki/tiam_1-2019_35-38.pdf

Język w tym opracowaniu nie jest łatwy, bo pisał je naukowiec, dl;atego postaram się jeszcze poszerzyć to o bliskie mi tematy.

Modularyzacja to jeden z etapów na drodze do automatyzacji, ale to nie dotyczy tylko kodu aplikacji, ale całego otoczenia, definiowania celów biznesowych opartych o moduły a nie sztywne ramy bądź zbyt szerokie definicje trudne do implementacji.




#### Wiedza

wiedza o rozwiazaniach konkurencji,
czy sposobu użycia narzędzia jest tutaj jedną z kluczowych
Gdyż najlepsze narzędzie musi być proste w użyciu nawet jeśli obsługuje je profesjonalista.

Warto zadbać o warstwę komunikacji UX z klientem chociażby w formie Chat, by była szansa na interakcje w ramach odstarczania usługi/produktu.

Jak powyżej zarysowano sam, fakt uzyskania rezultatu nie jest wystarczający do sprzedaży

W ramach wytwarzania, dostarczania narzędzi dla innych konieczna jest znajomość sposobu użyciu przez docelowych użytkowników
Temu służy tak samo jak przy wytwazraniu oprogramowanie wiele wzorców projektowych.

Wzorzec pozwala na świadome używanie, istotna jest świadomość skutków konrketnych zdarzeń.
Warto wobec tego używać znanych użytkownikowi wzorców.

Np. każdy kto kupuje w internecie rozumie sposób działania sklepu internetowwego, nawet gdy nie zna platformy, to wie czego od oczekuje.
Celem klienta jest wybranie towaru i zapłata za niego, po czym oczekuje informacji zwrotnej o przebiegu tych procesów z platformy zakupowej.


## Proces dostarczania w modelu SaaS

W celu zautomatyzawania biznesu możemy zastosować model SaaS, którego zadaniem jest ciągłe doskonalenie sposobie dostarczania usługi klientowi.

Tak działa marketing online, który opiera się o personalizację AI czy inne:
+ [23 Software as a Service (SaaS) Examples you NEED to know in 2022](https://userguiding.com/blog/saas-examples/)

+ [SaaS is King](https://www.saasisking.com/)



## Narzędzia


**Czy mamy odpowiednie narzędzia do codziennej pracy nad wieloletnim projektem?**


Jest coś więcej w codziennym życiu co pozwala na zauważenie w bliskiej i odległej przeszłości, setki lat wstecz by upewnić się, że to co wytworzone przez człowieka jest charakterystyczne dla istot zamiekszujących tę planętę poprzez samą metodologię wytwarzania.


Jeśli sposób wytwarzania ma wpływ na jakość i żywotność rezultatu to warto przyjrzeć się narzędziom jakie używamy i metodologiom, wedle których powstają te dzieła.

Hipermodularyzacja jako sposób wytwarzania i kierunkowania kreatywności jest skupiony na detalach, rozbijaniu problemów i rozwiązań na modularne cząstki.

Tak jak pył, czy atom był uważany za najmniejszą cząstkę, którą po czasie udało się też odkryć i ponazywać, tak i każdy element systemu, który rozwijamy
krok po kroku jest odkrywany i trudno byśmy dziś zrobili plan na kolejne 10 lat nie znając przyszłości, która dla nas może nie nadejść.

Jak wobec tego ukierunkować działania twórcze, by były efektywniejsze doprowadzając do lepszych jakościowo rezultatów?



## Modularyzacja na frontendzie
+ [WebStream](https://www.webstream.dev/)

Projekt obecnie nazywa się WebStream, jest zbiorem kilku modularnych funkcji, pozwalających na wykorzystanie potencjału jaki leży w protokole http
i naturalnej predyspozycji jezyka JavaScript do prototypowania.

Biblioteka jLoads była jednym z pierwszym implementacji podejścia modułowego w software developmencie, miała za zadanie załadowanie wszystkich potrzebnych mediów na stronę www.
Obecnie jest częścią standardu [WebStream](https://www.webstream.dev/)


## Frameworks and Microfrontends

If you think that Microfrontends are the solution of all your problems, think twice.

It is easy to fall into a hype-trap.
When new technology comes up and it seems like you have all the reasons to refactor your code base to the new approach because it is for sure the silver-bullet for all your problems!

Well Microftontends can be very good approach, but with it, you might get thousends of other problems that will start to rot your code base.
when using a modular monolith front end application with lazy loading ?

how to make best architecture choice for your application?


## Jakość, czysty kod, legacy kod, re-użycie

Jednym z elementów, mogących decydować o długoterminowym sukcesie jest jakość kodu.
Tworząc szybki prototyp, możemy nie odczuć skutków na dłuższą metę. Niestety pod przykrywką
prototypu często dostarczamy tak naprawdę MVP (Minimum Viable Product), który będziemy rozwijać.
O czym często zapominamy, jakie błędy popełniamy i o czym powinniśmy pamiętać?




## Modularyzacja BACKEND



## Modularyzacja DEVOPS

DevOps, DevSecOps czy Admin
posługują się na co dzień skryptami bash
działają nie tylko w powłoce shell ale też w chmurowwej abstrakcji
gdzie często jest możliwość korzystania z API
ale by możliwa była intergacja, czy migracja konieczne jest nadal używanie powłoki shella
i tutaj znajomość basha z wykorzystaniem starego ale nadal użytecznego CURL
wydaje się oczywista


Dlatego mając na uwadze fakt, że korzystanie ze skryptów basha jest intyicyjnym rozwiązaniem
które zawsze działa, warto po prostu wykorzystać ten potencjał przy migracji
zwłaszcza w konetkcie zewnetrznego API
i wysyłaniu, przetwarzaniu i konwersji strumieni danych do innnych API na zewnątrz systemu.


Aby ta droga korzystania z bash w celu integracji była łatwiejsza do testowania przygotowałem narzedzie do szybkiego debugowania

plainEdit.com

To tylko jedno z anrzedzi, ale tez ma bardzo szerokie możliwości zastosowania w kazdym dostępnym w środowisku jezykiem programowania





## Modularyzacja i domeny internetowe

Każda z tych funkcji ma własną domenę: .com

Każda może być używana oddzielenie w innych projektach, ale razem tworzą mały zbiór funkcji do celów prototypowania bezpośrednio w przeglądarce.


### Warstwa modułu
ładowanie pliku konfigruacyjnego JSON, definiującego co ma być ładowane w kontekście modułu
+ funkcja letJson()

+ ładowanie definicji w zależności od użycia tego modułu w jLoads z funkcjami odpowiedzialnymi za ładowanie mediów


### Warstwa aplikacji
+


### Warstwa architektury
+




### Warstwa sprzętowa
+


---
+ [edit](https://github.com/hipermodularyzacja/www/edit/main/README.md)
+ [hipermodularyzacja/www](https://github.com/hipermodularyzacja/www)
+ 

