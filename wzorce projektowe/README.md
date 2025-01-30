# Definicje
  ## Wzorzec architektoniczny 
    W inżynierii oprogramowania, uniwersalne, 
    sprawdzone w praktyce rozwiązanie często pojawiających się, powtarzalnych 
    problemów projektowych z zakresu architektury oprogramowania. 
    Wzorce architektoniczne określają ogólną strukturę systemu informatycznego, 
    jego elementy składowe, funkcjonalność tych elementów i zasady komunikacji pomiędzy nimi.  
  * Wzorce architektoniczne dotyczą problemów z komunikacją, tworzeniem lub organizacją 
    systemu informatycznego i jego modułów (wzorce projektowe dotyczą tych samych problemów 
    ale na poziomie niższym tzn. poziomie obiektów i klas).
## Klasowe
  Relacje między klasami i ich podklasami wyznaczane przez dziedziczenie tzn, statyczne (ustalane w czasie kompilacji)
## Obiektowe
  Dynamiczne relacje między obiektami które można zmieniać w czasie wykonywania programu
## Konstrukcyjne (creational)
  Związane z procesem tworzenia obiektów
## Strukturalne (structural)
  Dotyczą składania klas lub obiektów
## Operacyjne/czynnościowe (behavioral)
  Określają sposób współdziałania klas lub obiektów oraz podział zadań między nimi
# Klasyfikacja wzorców projektowych
  ## Klasowe
  ### Konstrukcyjne
  * Factory Method
  ### Strukturalne
  * Adapter (klasowy)
  ### Operacyjne/Czynnościowe
  * Interpreter
  * Template Method
  ## Obiektowe
  ### Konstrukcyjne
  * Abstract Factory
  * Builder
  * Prototype
  * Singleton
  ### Strukturalne
  * Adapter (obiektory)
  * Bridge
  * Composite
  * Decorator
  * Facade
  * Flyweight
  * Proxy
  ### Operacyjne/czynnościowe
  * Chain of Responsibility
  * Command
  * Iterator
  * Mediator
  * Memento
  * Observer
  * State
  * Strategy
  * Visitor
  ## Architektoniczne
  * Layers
  * MVC
  * MVP
  * MVVM
# Charakterystyka Wzorców
  ## Tworzenie obiektów bez specyfikowania klas konkretnych
  * Abstract Factory
  * Factory Method
  * Prototype
  ## Brak zależności od konkretnych operacji
  * Chain of Responsibility
  * Command
  ## Brak zależności od platformy sprzętowej i/lub programowej
  * Abstract Factory
  * Bridge
  ## Brak zależności od reprezentacji i implementacji obiektów
  * Abstract Factory
  * Bridge
  * Memento 
  * Proxy
  ## Brak zależności algorytmicznych
  * Builder
  * Iterator
  * Strategy
  * Template Method
  * Visitor
  ## Luźne sprzężenie
  * Abstract Factory
  * Bridge
  * Chain of Responsibility
  * Command
  * Facade
  * Mediator
  * Observer
  ## Rozszerzanie funkcjonalności bez dziedziczenia
  * Bridge
  * Chain of Responsibility
  * Composite
  * Decorator
  * Observer
  * Strategy
  ## Zdolność do wygodnej modyfikacji klas
  * Adapter
  * Decorator
  * Visitor
