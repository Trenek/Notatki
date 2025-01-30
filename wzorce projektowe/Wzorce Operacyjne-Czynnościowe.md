# Wzorce Operacyjne/Czynnościowe
## Chain Of Responsibility (Łańcuch odpowiedzialności/zobowiązań)
  Uniknięcie wiązania nadawcy żądania z odbiorcą poprzez umożliwienie większej liczbie obiektów obsłużenia tego żądania.
  Obiekty odbiorcze są łączone w łańcuch, wzdłuż którego przekazywane jest żądanie do momentu obsłużenia go.
## Command (Polecenie)
  Hermetyzacja żądania (komunikatu) w obiekcie.
  Umożliwia to parametryzację klientów przy użyciu różnych żądań, kolejkowanie i rejestrację żądań, jak również realizację cofania operacji.
## Interpreter
  Zdefiniowanie reprezentacji gramatyki języka oraz interpretera, który używa tej reprezentacji do interpretacji zadań z tego języka.
## Iterator
  Dostarcza sekwencyjny dostęp do elementów obiektu złożonego (kolekcji) bez ujawniania jego wewnętrznej reprezentacji.
## Mediator
  Zdefiniowanie obiektu hermetyzującego informację o interakcji pomiędzy obiektami z pewnego zbioru.
  Mediator pomaga zapewnić luźne powiązanie zapobiegając bezpośredniemu odwoływaniu się obiektów do siebie i pozwalając niezależnie modyfikować ich interakcją.
## Memento (Pamiątka)
  Utrwalenie wewnętrznego stanu obiektu w zewnętrznej jednostce bez naruszania hermetyzacji tak, żeby obiekt można było później przywrócić do tego stanu.
## Observer (Obserwator)
  Określenie takiego powiązania jeden-do-wielu między obiektami, że kiedy obiekt zmienia stan, wszystkie obiekty od niego zależne są powiadamiane i aktualizowane automatycznie.
## State (Stan)
  Umożliwienie obiektowi zmiany zachowania w wyniku zmiany wewnętrznego stanu (wygląda to tak, jakby obiekt zmienił klasę).
## Strategy (Strategia)
  Zdefiniowanie rodziny algorytmów, zastosowanie hermetyzacji dla każdego z nich i stosowanie ich wymiennie.
  Strategia pozwala zmieniać algorytmy niezależnie od wykorzystujących je obiektów.
## Template Method (Metoda szablonowa)
  Zdefiniowanie ogólnego szkieletu algorytmu i pozostawienie implementacji niektórych jego kroków klasom pochodnym.
  Dzięki temu można przedefiniować w podklasach pewne kroki algorytmu nie zmieniając jego ogólnej struktury.
## Visitor (Odwiedzający / Wizytator)
  Reprezentacja operacji, które ma być wykonana na elementach struktury obiektów.
  Wzorzec Visitor pozwala zdefiniować nową operację bez zmieniania klas elementów, na których ta operacja działa.
