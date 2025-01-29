# Wzorce Strukturalne
## Adapter
  Przekształca interfejs klasy na inny, oczekiwany przez klienta  
  Umożliwia współpracę klas, która bez jego zastosowania nie jest możliwa za względu na niezgodność interface'ów
## Bridge (Most)
  Oddzielenie abstrakcji od implementacji w sposób umożliwiający ich zmiany niezależnie od siebie
  Przykład - stworzenie abstrakcji na bibliotekę, po której dziedziczą różne biblioteki
## Kompozyt (Composite)
  Kompozycja obiektów w struktury drzewiaste odzwierciedlające hierarchię całość-całość.
  Wzorzec pozwala klientom na traktowanie w taki sam sposób indywidualnych obiektów i ich złożeń.
  ### Elementy
  * Leaf/Liść - Obiekty które nie posiadają potomków
  * Composite/Kompozyt - Obiekty posiadające potomków
## Decorator (Dekorator)
  Dodanie dodatkowej odpowiedzialności do obiektu w sposób dynamiczny.
  Dekoratory stanowią elastyczną alternatywę dla tworzenia podklas w rozszerzaniu funkcjonalności.
## Facade (Fasada)
  Udostępnia jednolity interfejs dla zbioru interfejsów z podsystemu.
  Fasada określa interfejs wyższego poziomu ułatwiający korzystanie z podsystemów.
## Flyweight (Pyłek)
  Użycie współdzielenia do efektywnej obsługi dużej liczby małych obiektów
## Proxy (Pełnomocnik)
  Dostarczenie zastępnika lub reprezentanta innego obiektu w celu kontrolowania dostępu do tego obiektu.
  ### Remote Proxy (Pośrednik Zdalny)
    Lokalny reprezentant obiektu z innej przestrzeni adresowej
  ### Virtual Proxy (Pośrednik wirtualny)
    Pośrednik tworzący kosztowne obiekty na żądanie
  ### Protection Proxy (Pośrednik zabezpieczający)
    Autoryzujący dostęp do obiektu oryginalnego (gdy obiekty powinny mieć różne prawa dostępu).
  ### Cache Proxy (Pośrednik schowek)
    Składający rezultaty odwołań do zdalnych komponentów do wykorzystania przez wielu lokalnych klientów.
  ### Synchronization Proxy (Pośrednik synchronizujący)
    Współbieżny dostęp do komponentu
  ### Firewall proxy (Pośrednik-ściana ogniowa)
    Chroniący lokalnych klientów przed światem zewnętrznym
  ### Smart reference (Inteligentna referencja)
  Zastępująca zwykłe odniesienie i wykonująca dodatkowe operacje przy dostępie do obiektu, np:
  * Zliczanie referencji do rzeczywistego obiektu tak, że może być on usunięty automatycznie kiedy nie ma już do niego żadnych referencji (tzw. inteligentny wskaźnik - smart pointer)
  * Ładowanie trwałego obiektu do pamięci w momencie pierwszego odwołania tzn. utworzenia pierwszej referencji do niego (tzw. duch - ghost).
  * Sprawdzanie przed dostępem do pierwotnego obiektu, czy jest on zablokowany, by żaden inny obiektu go nie zmienił.
