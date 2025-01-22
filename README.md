Nie działa mi tylko wyświetlanie obrazka 
Opis
To jest prosta aplikacja internetowa stworzona w Spring Boot, która pokazuje podstawowe funkcje frameworka Spring, takie jak obsługa żądań HTTP i generowanie dynamicznych stron HTML za pomocą Thymeleaf.

Funkcje
Endpointy REST:

/: Wyświetla prostą wiadomość powitalną.
/greeting: Przyjmuje parametr name i wyświetla spersonalizowaną wiadomość.
Dynamika dzięki Thymeleaf:

Użyliśmy silnika szablonów Thymeleaf do tworzenia dynamicznych stron HTML, które wstawiają dane z serwera.
Zawartość statyczna:
Strona zawiera również statyczny tekst i obrazek.

Jak uruchomić?
Wymagania:

Java 17+
Maven

Użycie
Spersonalizowanego powitania:

URL: http://localhost:8080/greeting?name=Jakub
Wynik: Hello, Jakub!
Autor
Jakub Czarnecki
