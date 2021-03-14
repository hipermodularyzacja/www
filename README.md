# hipermodularyzacja.pl

Polskie wydanie, Wersja Polska: HiperModularyzacja.pl
+ [www. Hiper Modularyzacja .pl](https://www.hipermodularyzacja.pl/)


W trakcie jest też wersja angielska: HyperModularity.com
+ [www. Hyper Modularity .com](http://www.hypermodularity.com/)

# Początek

Pomysł na książkę zrodził się w trakcie realizacji projektu jLoads, ktróry służy modularyzacji aplikacji napisanej w JavaScript na frontendzie.

# jLoads

Biblioteka jLoads ma za zadanie załadowanie wszystkich potrzebnych mediów na stronę www.

# Modularyzacja

[WebStream](https://www.webstream.dev/)

Po wykonaniu prototypu udało się określić strukturę biblioteki w kontekście użycia, czyli zmodularyzować.

Wydzieliłem nawet biblioteki do ładowania, definicji JSON oraz do Ładowania i routowania mediów

+ letJson() - pobieranie samego jsona

+ jsonDef() - okreslanie oczekiwanej struktury oraz podłączenie każdego elementu JSON pod konrketną funkcję

+ jLoads() - ładowanie konkretnych url do formatu wyświetlanego w HTML bez okreslenia miejsca gdzie ma być załadowane, pliki będą tylko definiowały same zależnosci:


      {
        "/form/field/text.css",
        "/form/field/email.css",
        "/form/field/submit.css",
        "newsletter.html": [
            "submit.js"
        ]
      }

+ jRoutes() - pipelines (event, from, to) definicja miejsc, gdzie i co ma być z czym połączone z jLoads na HTML

# Modularyzacja i domeny internetowe



Każda z tych funkcji ma własną domenę: .com

Każda może być używana oddzielenie w innych projektach, ale razem tworzą mały zbiór funkcji do celów prototypowania bezpośrednio w przeglądarce.



### Warstwa modułu
ładowanie pliku konfigruacyjnego JSON, definiującego co ma być ładowane w kontekście modułu
+ funkcja letJson()


+ ładowanie definicji w zależności od użycia tego modułu w jLoads z funkcjami odpowiedzialnymi za ładowanie mediów

### warstwa aplikacji 
+

## Modularyzacja w wielu branżach

i zbieram wiedzę na ten temat, chodzi o modularyzację w wytwarzaniu oprogramowania, produkcji w przemyśle, sprzedaży, marketingu i zarządzaniu projektami i ludzmi.
 
Przykładowe opracowanie korzyści:
https://www.imbigs.pl/sites/default/files/pliki/tiam_1-2019_35-38.pdf

Język w tym opracowaniu nie jest łatwy, bo pisał je naukowiec, dl;atego postaram się jeszcze poszerzyć to o bliskie mi tematy.

Modularyzacja to jeden z etapów na drodze do automatyzacji, ale to nie dotyczy tylko kodu aplikacji, ale całego otoczenia, definiowania celów biznesowych opartych o moduły a nie sztywne ramy bądź zbyt szerokie definicje trudne do implementacji.

## Modularyzacja a koszty

Koszty wytwarzania aplikacji są tym wyższe im bardziej niejednorodne są moduły i trudniejsze do połączenia.

Dlatego operatorzy chmur oferują szybki development ale potem aplikacja jest droga w utrzymaniu, niestety nie ma idelanego rozwiązania, ale długofalowo opłaca się w duchu modularyzacji tworzyć i utrzymywać całą infratsrukturę, gdyż to daje szansę na syzbszy wzrost niż konkurencja.

To nie jest roziwązanie dla szukających oszczędności, bo moudlaryzacja nie jest tania, wymaga przede wszystkim myślenia abstrakcyjnego i podejścia długofalowego. Trzeba rozróżnić wdrożenie modularyzacji w istniejącym projekcie i wykorzystanie gotowych modułów w nowym tak jak ma to miejsce w chmurze.

Dlatego jednorazowe projekty można szybko stworzyć w chmurze, ale to kosztuje więcej niż tradycyjna infrastruktura, z kolei tworzenie tego we własnej organizacji wymaga grupowej synchronizacji w duchu modularyzacji a każdy ma powody by tego nie robić, dopóki nie ma ku temu odpowiednich rozwiązań. 

## Cel

Dla mnie modularyzacja to naturalny odruch, mam to od zawsze i dlatego wiążę z tym swoją przyszłość, chcę się tym dzielić dając długofalowa wartość na konsultacjach oraz przy wdrożeniach.

Mój cel jest najpierw napisać darmowy e-book po polsku o hipermodularyzacji, potem o modularyzacji w szerszym kontekście z innymi specjalistami w tym aspekcie i następnie wersję angielską: HyperModularity .com



## Jak rozmawiać o modularyzacji?
+ jakiego rodzaju oprogramowania dotyczy modualryzacja?

Głównie rozwiązania szyte na miarę, gdzie jest plan i miejsce do rozwoju projektu.

Czy widzisz sens mówić o tym czego nie widać?
Modularyzacja nie musi być głównym celem projektu, ale bywa elementem projektu i trudno wydzielić modularyzację, 
gdyż w continuous development te etapy się zlewają w cykl wytwarzania i trudno je rozdzielić. 

+ Gdzie i kiedy modularyzacja pomoże?
tam, gdzie fin-y z jednej strony chcą mieć coś swojego a z drugiej boją się uwiązania do jednego dostawcy?


właśnie po to jest modularyzacja, aby znaleźć balans pomiędzy tym co jest już wymyślone i tym co chcesz sam spiąć

Modularyzacja to sposób myślenia dążący do wykorzystania -reużycia a nie uwiązania się, nic mbardziej mylnego. to chmury wiążą, one są zmodularyzwowane wewnętrznie, ale każą płacić sobie za to sporo.

W przypadku praktywkowania modularyzacji, będziesz szedł własną drogą niezaleznie od dostawcy, bo twoje oprogramowanie będzie modularne, czyli możliwe do przepięcia na innego usługodawcę

Chmura robi to za Ciebie, ale chce Ciebie uwiązać własnym kontekstem, językiem programowania, czy no-codem

+ Modularyzacja daje poczucie niezależności a nie przywiązania

Dlatego uważam, że w obecnych czasach to bardzo istotne aby umieć się odnależć w tej mnogości rozwiązań a jednocześnie nie dać się uwiązać, właśnie dzięki modularyzowaniu, ubieraniu wszystkich rozwiazań w klocki pozwalając im się replikować w dowolnym środowisku i konfiguracji

+ Co jest rezultatem modularyzacji?

Rezultattem modularyzacji nie jest wykorzystywanie konkretnego dostawcy, a odpoworność na jednolitość, budowanie naturalnej struktury, pozwalającej na natywne zarządzanie strukturą całego biznesu

Chmury narzucają rozwiązania, modularyzacja otwiera Cię na nie

mikroseriwsy są ewolucją i jak widać na nich ona się nie zakończyła, modularyzacja daje wybór: monolit, mikroserwis, itd


## Biznes
To początek drogi, dlatego potrzebna jest baza do komunikacji z klientami chcącymi wdrożyć modularyzację u siebie na wyższym poziomie.
Uwzględniajać długofalową przewagę konkurencyjną.
Zgodnie z misją firmy Softreck: Leadership Through Software Development
Oraz wizją która nawiązuje do bardzo spersonalizowanego wytwarzania oprogramowania i modularyzacja jest środkiem do tego celu.



Modularyzacja zawsze jest elementem projektu i trudno wydzielić modularyzację, gdyż w continuous development te etapy się zlewają w cykl wytwarzania i trudno je rozdzielić. 

## Zapraszam do współpracy
Jestem optymistą i chciałbym mieć kontakt z ludźmi krytycznymi, którzy pomogą w rozwoju tego projektu, bo pierwszy e-book będzie tylko o oprogramowaniu i to ma być zaczątkiem dyskusji.



# Kursy
Z uwagi na niszowy temat, podjęte zostaną prace nad tworzeniem stałej bazy dla chcących zwiększyć swoje kwalifikacje w sferze modularyzacji.

Kurs będzie przeznaczony zarówno do osób początkujących, jak i doświadczonych programistów, którzy pragną poszerzyć swoją wiedzę związaną z tworzeniem modularnego oprogramowani.


## Monolit, Mikroserwisy a Modularyzacja


+ Czym jest, a czym nie jest modularne oprogramowanie?
+ Czy mikroserwisy to jedyna droga na tworzenie autonomicznych, modularnych aplikacji?
      + Modularny Monolit
      + Modularny Mikroserwis
+ Analiza procesów i wyodrębnianie niezależnych modułów
+ Jak i kiedy wydzielać moduł do mikroserwisu?
+ Jak projektować i wdrażać  niezależnie od siebie autonomiczne moduły?


## Architektura

+ Jaka jest różnicą pomiędzy architekturą horyzontalną, a wertykalną?
+ Czym jest vertical slice?

## Moduły

+ Jak zaimplementować niezależne od siebie moduły z dowolnym stylem architektonicznym?
+ Czym jest w ogóle ten Software Craftsmanship w praktyce?
+ W jaki sposób możemy komunikować, oraz integrować ze sobą moduły?
+  Wyodrębnienie pojedynczego modułu do dedykowanego mikroserwisu


## Software Development

+ Jakie wady i zalety ma podejście oparte na kodzie współdzielonym, a jakie na lokalnych kontraktach?
+ Czy możemy osiągnąć transakcyjność i spójność danych w niezależnych modułach?
+ Jak implementować globalne procesy przecinające różne moduły?
+ Implementacja modułów w oparciu o vertical slice
+ Wydzielenie wspólnej części w oparciu o współdzielone abstrakcje
+ Osiągnięcie pełnej autonomii modułów z wykorzystaniem lokalnych kontraktów


## Transakcje 

+ Rodzaje spójności i transakcyjności danych w modularnym monolicie
+ Event-driven architecture w aplikacji monolitycznej
  
## Komunikacja

+ Wewnętrzna komunikacja pomiędzy modułami na wzór Web API
+ Wewnętrzna integracja pomiędzy modułami z wykorzystaniem brokera wiadomości
+ Synchroniczna, a asynchroniczna obsługa komunikatów


## Wdrożenie
+ Metody dynamicznego wdrożenia aplikacji i wybranych modułów  
  
## Wzorce, środowisko,  
+ Dobór odpowiednich stylów architektonicznych do klasy złożoności modułu
+ Domain-Driven Design, CQRS, ES, CRUD 
   + Wykorzystanie różnych wzorców w zależności od klasy problemu
   + Jak stosować DDD, CQRS, ES, CRUD


## Testowanie

+ Jak testować moduły w środowiskach: lokalnym i globalnym?
+ Testowanie na róznych poziomach (jednostkowe, integracyjne etc.)
 
 
 
Masz wątpliwości dotyczące kodu źródłowego? Chcesz sprawdzić aplikację, zanim podejmiesz decyzję o zakupie kursu?
Nie ma problemu! 

Wszystko jest open source! 


Cały kod źródłowy, który zaimplementujemy wspólnie podczas kursu, jest dla Ciebie dostępny za darmo na GitHub!

## Gitter, Dołącz do otwartej społeczności

Zapraszamy Cię do otwartej społeczności HiperModularzyacja.pl dostępnej za pomocą popularnego komunikatora Gitter,
używanego przez programistów na całym świecie. 

Niezależnie od tego, czy zdecydujesz się (bądź nie) na zakup kursu

Zachęcamy Cię do zadawania pytań oraz dyskusji na wybrane zagadnienia dotyczące kursu (i nie tylko).

