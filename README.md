# Kurs do INF 04

## Aplikacje konsolowe (Python)

### Do nauczenia:
- [ ] Obsługa wejścia/wyjścia (`input()`, `print()`)
- [ ] Typy danych: `int`, `float`, `str`, `bool`
- [ ] Struktury danych: `list`, `dict`, `tuple`, `set`
- [ ] Pętle: `while`, `for`
- [ ] Instrukcje warunkowe: `if`, `elif`, `else`
- [ ] Operacje na plikach tekstowych: `read()`, `readlines()`, `write()`, `with open()`
- [ ] Funkcje: parametry, argumenty, zwracane wartości, funkcje zagnieżdżone
- [ ] Obiektowość: klasy, metody, dziedziczenie, `__init__`
- [ ] Operacje na stringach: `split()`, `join()`, `replace()`, `find()`, `isdigit()`
- [ ] Algorytmy: sortowanie (bąbelkowe, przez wybór), wyszukiwanie liniowe, algorytm Euklidesa
- [ ] Walidacja danych (np. PESEL, adres e-mail)
- [ ] Podstawy testowania: `assert`, tworzenie prostych przypadków testowych

### Zadania do przerobienia:
- [ ] Program do obliczania największego wspólnego dzielnika (NWD) dla dwóch liczb
- [ ] Program do sortowania listy imion w kolejności alfabetycznej i zapisu do pliku
- [ ] System logowania – użytkownik podaje login i hasło, program weryfikuje dane z pliku tekstowego
- [ ] Generator haseł – tworzy losowe hasło o zadanej długości
- [ ] Program, który sprawdza poprawność numeru PESEL i wypisuje datę urodzenia


## Aplikacje mobilne (Android Studio)

### Do nauczenia:
- [ ] Podstawowe tagi XML: `<LinearLayout>`, `<Button>`, `<TextView>`, `<ImageView>`, `<ScrollView>`
- [ ] Atrybuty tagów XML: `android:layout_width`, `android:layout_height`, `android:id`, `android:text`, `android:gravity`, `android:orientation`, `android:layout_margin`, `android:padding`
- [ ] Java: zmienne i typy danych: `int`, `double`, `boolean`, `String`
- [ ] Instrukcje warunkowe: `if`, `else`, `switch-case`
- [ ] Pętle: `for`, `while`, `for-each`
- [ ] Struktury danych: tablice, listy (`ArrayList`), klasy, obiekty i metody (OOP)
- [ ] Obsługa wyjątków: `try`, `catch`
- [ ] Activity, Intents, `findViewById`, EventListeners (`onClickListener`), Lifecycle (`onCreate()`, `onStart()`, ...)
- [ ] Przechowywanie danych: `SharedPreferences`
- [ ] Podstawy RecyclerView i Adapterów
- [ ] Proste style i motywy w XML

### Zadania do przerobienia:
- [ ] Kółko i krzyżyk (dwóch graczy)
- [ ] Formularz rejestracyjny walidujący dane (np. e-mail, hasło)
- [ ] Aplikacja lista zakupów (dodawanie, usuwanie elementów – RecyclerView)
- [ ] Notatnik – zapisywanie notatek do `SharedPreferences`
- [ ] Aplikacja licznik kroków lub timer (wyświetla czas po kliknięciu start/stop)


## Aplikacja webowa (React)

### Do nauczenia:
- [ ] HTML, CSS (CSS Modules), Bootstrap
- [ ] Podstawy JavaScript: typy danych, struktury danych, pętle, metody tablicowe (`map`, `filter`, `reduce`)
- [ ] React: komponenty funkcyjne, propsy
- [ ] Hooki: `useState`, `useEffect`
- [ ] React Router: nawigacja między stronami
- [ ] Obsługa formularzy i walidacja danych
- [ ] Fetch API (GET, POST), obsługa JSON
- [ ] Podstawy stylowania komponentów (CSS modules)

### Zadania do przerobienia:
- [ ] Kółko i krzyżyk (React, useState)
- [ ] Aplikacja pobierająca kursy walut z NBP API i wyświetlająca tabelę
- [ ] Walidacja formularzy (np. rejestracja)
- [ ] Mini-galeria zdjęć (pobiera dane z API lub z pliku JSON)
- [ ] Lista zadań (TODO) z możliwością filtrowania wykonanych


## API (Express.js)

### Do nauczenia:
- [ ] Instalacja i konfiguracja Express.js
- [ ] Tworzenie serwera, obsługa routingu (`GET`, `POST`, `PUT`, `DELETE`)
- [ ] Obsługa danych JSON (`express.json()`)
- [ ] Zwracanie odpowiedzi HTTP i obsługa statusów (`res.status()`)
- [ ] Walidacja danych wejściowych (np. `express-validator`)
- [ ] Prosta obsługa błędów (`try/catch`, middleware)
- [ ] Baza danych w postaci pliku `json` lub tablicy/obiektu
- [ ] Podstawy REST API i CRUD

### Zadania do przerobienia:
- [ ] Stworzenie API obsługującego listę produktów (CRUD)
- [ ] Endpoint rejestracji i logowania użytkownika (walidacja danych)
- [ ] Endpoint zwracający dane pogodowe (np. z pliku JSON)
- [ ] API TODO listy z zapisem do tablicy w pamięci
- [ ] Middleware logujący każde żądanie do konsoli


## Aplikacje desktopowe (C# WPF .NET)

### Do nauczenia:
- [ ] Podstawy C#: typy danych, instrukcje warunkowe, pętle, klasy
- [ ] Podstawy WPF: `Window`, `Grid`, `StackPanel`, `Button`, `TextBox`, `Label`, `ListBox`, `DataGrid`
- [ ] Obsługa zdarzeń: `Click`, `SelectionChanged`
- [ ] Binding danych (prosty, np. `ItemsSource`)
- [ ] Tworzenie modeli danych, prosta logika (np. klasa `Produkt` z polami)
- [ ] Obsługa plików (odczyt, zapis)
- [ ] Podstawy MVVM (choć na egzaminie wystarczy code-behind)
- [ ] Walidacja danych w formularzu

### Zadania do przerobienia:
- [ ] Lista zakupów (dodawanie/usuwanie produktów)
- [ ] Kalkulator BMI (pola tekstowe + wyświetlanie wyniku)
- [ ] Aplikacja kontaktowa – lista osób z możliwością dodania, usunięcia i zapisu do pliku
- [ ] Notatnik – zapis i odczyt z pliku tekstowego
- [ ] Aplikacja do obliczania średniej ocen z listy wpisów

## Testowanie w Pytest

### Do nauczenia:
- [ ] Instalacja `pytest` (`pip install pytest`)
- [ ] Prosta struktura pliku testowego: plik zaczyna się od `test_` (np. `test_main.py`)
- [ ] Użycie `assert` do sprawdzania wyniku funkcji
- [ ] Uruchamianie testów w terminalu: `pytest` lub `pytest -v`
