# hipermodularyzacja.pl
Książka HiperModularyzacja.pl

Polskie wydanie, w trakcie jest też wersja angielska: HiperModularity.com


# Początek

Pomysł na książkę zrodził się w trakcie realizacji projektu jLoads, ktróry służy modularyzacji aplikacji napisanej w JavaScript na frontendzie.

# jLoads

Biblioteka jLoads ma za zadanie załadowanie wszystkich potrzebnych mediów na stronę www.

# Modularyzacja
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


i zbieram wiedzę na ten temat, chodzi o modularyzację w wytwarzaniu oprogramowania, produkcji w przemyśle, sprzedaży, marketingu i zarządzaniu projektami i ludzmi.
 
Przykładowe opracowanie korzyści:
https://www.imbigs.pl/sites/default/files/pliki/tiam_1-2019_35-38.pdf


tak, naukowiec, ale to nie ma znaczenia, modularyzacja to jeden z etapów na drodze do automatyzacji, ale to nie dotyczy tylko kodu aplikacji, ale całego otoczenia, definiowania celów biznesowych opartych o moduły a nie sztywne ramy bądź zbyt szerokie definicje trudne do implementacji.

Koszty wytwarzania aplikacji są tym wyższe im bardziej niejednorodne są moduły i trudniejsze do połączenia.

Dlatego operatorzy chmur oferują szybki development ale potem aplikacja jest droga w utrzymaniu, niestety nie ma idelanego rozwiązania, ale długofalowo opłaca się w duchu modularyzacji tworzyć i utrzymywać całą infratsrukturę, gdyż to daje szansę na syzbszy wzrost niż konkurencja.

To nie jest roziwązanie dla szukających oszczędności, bo moudlaryzacja nie jest tania, wymaga przede wszystkim myślenia abstrakcyjnego i podejścia długofalowego. Trzeba rozróżnić wdrożenie modularyzacji w istniejącym projekcie i wykorzystanie gotowych modułów w nowym tak jak ma to miejsce w chmurze.

Dlatego jednorazowe projekty można szybko stworzyć w chmurze, ale to kosztuje więcej niż tradycyjna infrastruktura, z kolei tworzenie tego we własnej organizacji wymaga grupowej synchronizacji w duchu modularyzacji a każdy ma powody by tego nie robić, dopóki nie ma ku temu odpowiednich rozwiązań. 
