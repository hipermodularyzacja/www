
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



## Modułowość
Co oznacza modułowość?

W inżynierii oprogramowania modułowość odnosi się do zakresu, w jakim oprogramowanie/aplikacja internetowa może zostać podzielona na mniejsze moduły. Modułowość oprogramowania wskazuje, że liczba modułów aplikacji jest w stanie obsłużyć określoną domenę biznesową.

Modułowość jest skuteczna, ponieważ programiści używają gotowego kodu, co oszczędza zasoby. Ogólnie rzecz biorąc, modułowość zapewnia większe możliwości zarządzania rozwojem oprogramowania.
Techopedia wyjaśnia modułowość

Współczesne zagadnienia biznesowe stale rosną – pod względem wielkości, złożoności i popytu. Zwiększone wymagania dotyczące możliwości oprogramowania zmuszają programistów do ulepszania opracowanych systemów o nowe funkcje.

Modułowość inżynierii oprogramowania umożliwia dzielenie typowych aplikacji na moduły, a także integrację z podobnymi modułami, co pomaga programistom korzystać z gotowego kodu. Moduły są podzielone ze względu na funkcjonalność, a programiści nie są zaangażowani w funkcjonalności innych modułów. Dzięki temu nowe funkcjonalności można łatwo zaprogramować w osobnych modułach.


### reusability - reużycie - ponowne użycie

Miernikiem skuteczności modularyzacji jest reużycie.
W momencie powstawania rozwiązania trudno określić ramy projektu i wyznaczyć mapę.
Odseparowanie następuje z czasem na skutek sprecyzowanej definicji, określenia ograniczeń i kompetencji modułu.
To wszystko przychodzi z czasem po którejś iteracji w fazie prototypowania.
Odseparowanie jest lekiem na szukanie kompromisów, ograniczamy w ten sposób koszty powstawania modułu.
Szukamy granic, w których będzie funkcjonował samodzielnie zamiast wpasowywać go w istniejące ramy systemu
przez co staje się karykaturą modułu a bardziej przypminać może adapter, helper, i tym podobne rozwiązania jednorazowego użytku
zależne od większej części.

### Kreatywność

W modularyzacji nie ma miejsca na ograniczanie kreatywności ani na tworzenie pod-modułów zależnych od drugich bezpośrednio.
relacje między modułami są równorzędne.
W rezultacie tworzymy modularną strukturę, łatwą do rekonfiguracji, gdyż nie jest stała i można ją dowolnie zmieniać
używając alternatywnych modułów.


### Autonomiczność

Autonomiczność jest wpisana w naturę i sposób użycia modułu.

Zamiast tworzyć kompromisowe rozwiązania ograniczające twórczość możemy otworzyć się na tworzenie, które w tworzeniu oprogramowania jest tańsze
niż wpasowanie, kształtowanie, migracja, adaptacja, itd
Nie nadajemy ram systemowi a modułom go tworzących.
Dzięki temu możmy zamiast przerabiać moduł stworzyć podobny, który będzie lepiej spełniał zadanie a w kolejnym etapie
podzielić go na kolejne moduły, tak by każda część spełniała najlepiej przydzieloną funkcję i by w połączeniu w większą strukturę były
lepiej reużywalne w różnych zastosowaniach.


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
