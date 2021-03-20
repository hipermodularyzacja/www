# Kurs modualryzacji oprogramowania

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
 
 