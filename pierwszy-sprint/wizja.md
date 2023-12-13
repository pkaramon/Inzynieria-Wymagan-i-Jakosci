# Wizja produktu

## Nazwa produktu

WindCraftAcademy

## Dziedzina problemu

* Dynamiczna rezerwacja i obsługa klientów.
* Planowanie i koordynacja zajęć kitesurfingowych.
* Komunikacja między klientami, instruktorami a szkołą - aktualnie manager musi sam wysyłać SMSy.
* Wpływ warunków pogodowych na odbycie zajęć
* Różne poziomy kursantów - przechowujemy certyfikaty w bazie i automatycznie sprawdzamy.
* Różne wagi kursantów - klienci wprowadzają swoją wagę tydzień przed zajęciami - błędne informacje mogą skutkować odmową prowadzenia zajęć.

## Istniejące rozwiązania na rynku pracy

* [KITE ZONE.com](https://www.kitezone.com/)
* [FUNSURF](https://kitesurfing.pl/)
* [Kite.pl](https://kite.pl/)
* [SURF PEOPLE](https://surfpeople.pl/)

## Cele projektu i oczekiwane korzyści

### Cele projektu

* **Usprawnienie zarządzania harmonogramem zajęć:**
Projekt ma na celu zautomatyzowanie procesu tworzenia harmonogramu zajęć, co pozwala zaoszczędzić czas managera szkoły i zminimalizować ryzyko popełnienia błędów przy ręcznym wprowadzaniu danych.

* **Zoptymalizowanie przydzielania instruktorów:**
System powinien umożliwiać skuteczne przyporządkowanie instruktora do kursanta na podstawie doświadczenia, stopnia zaawansowania kursanta i wagi ucznia oraz instruktora.

* **Zautomatyzowanie powiadamiania o planowanych zajęciach lub o ich odwołaniu:**
System powinien automatycznie informować kursantów i instruktorów o planowanych zajęciach lub o ich odwołaniu w przypadku braku wiatru lub nagłej nieobecności instruktora.

* **Zapewnienie dostępu do istotnych danych:**
Projekt ma na celu umożliwienie łatwego dostępu do istotnych danych o kursantach i instruktorach w celu usprawnienia procesu przydzielania instruktorów.

### Oczekiwane korzyści

* **Oszczędność czasu:**
Automatyzacja procesów, takich jak tworzenie harmonogramu i wysyłanie powiadomień, znacząco zredukuj czas poświęcany przez managera szkoły na te zadania.


* **Zminimalizowanie błędów:**
Eliminacja ręcznego wprowadzania danych może zmniejszyć ryzyko popełniania błędów, co przyczyni się do poprawy dokładności i spójności informacji.

* **Poprawa satysfakcji klientów:**
Dzięki lepszej organizacji zajęć, wcześniejszym powiadomieniom i spersonalizowanemu podejściu do szkolenia można oczekiwać zwiększenia satysfakcji klientów.

* **Efektywniejsze zarządzanie zasobami:**
Skuteczne przydzielanie instruktorów w zależności od ich dostępności i doświadczenia może przyczynić się do lepszego wykorzystania zasobów ludzkich w szkole.

* **Zwiększenie precyzji dokumentacji:**
Automatyczne śledzenie uczestnictwa w zajęciach i wydawanie kart informacyjnych może przyczynić się do zredukowania braków w dokumentacji.

## Problemy do rozwiązania

1. Braki w dokumentacji: instruktorzy zapominają pokierować swoich kursantów do managera i rozchodzą się bez formalnego potwierdzenia odbycia szkolenia.

2. Ustalenie trafnego dopasowania kursantów do instruktorów według ich poziomu zaawansowania, wagi i poprzednich sesji.

3. Ręczne informowanie klientów i instruktorów za pomocą SMSów przez managera.

4. Gdy menedżer ręcznie wpisuje dane do Excela zdarza mu się popełnić błędy.

## Oczekiwany efekt produktu

Aplikacja mobilna, dla kientów i instruktorów
* Łatwa w obsłudze
* Posiadająca czytelny interfejs
* Oferująca przyjazny wizerunek
* Intuicyjna
* Posiadająca kompleksowe funkcje

Aplikacja webowa dla menadżerki, która:
* Łatwa w obsłudze i przejrzysta
* Umożliwiająca szybkie i bezproblemowe odwoływanie zajęć
* Wyświetlająca niezbędne dane w celu podjęcia decyzji

## Aktorzy i zewnętrzne systemy

* **Kursanci:**
  * Składają zgłoszenia na lekcje z uwzględnieniem stopnia IKO i wagi.
* **Instruktorzy:**
  * Przyporządkowywani do kursantów na podstawie ich doświadczenia i wagi.
* **Manager Szkoły:**
  * Osoba odpowiedzialna za zarządzanie szkołą kitesurfingową.
* **System Pogodowy:**
  * Dostarcza informacje na temat aktualnych warunków pogodowych, w tym prędkości wiatru.
* **System Przyporządkowania:**
  * Automatycznie przyporządkowuje instruktora do kursanta na podstawie różnych kryteriów, takich jak doświadczenie, stopień IKO, waga itp.
* **System Komunikacji:**
  * Umożliwia komunikację między kursantami, instruktorami a menedżerem szkoły.
  * Wysyła powiadomienia o zmianach w harmonogramie, dostępności instruktorów itp.
* **System Finansowy:**
  * Zarządza płatnościami za lekcje kitesurfingu.
  * Generuje raporty finansowe związane z działalnością szkoły.
* **API SMSowe:**
  * Pozostaje ta sama forma informowania, ale w sposób zautomatyzowany.

## Główne funkcje systemu

1. **Rejestracja Kursantów:** Przypisanie kursantowi jego imienia, nazwiska, aktualnej wagi, aktualnego stopnia zaawansowania. Stworzenie elektronicznej karty.

2. **Rejestracje Instruktorów:** Przypisanie instruktorom ich imienia, wagi, doświadczenia w latach, oraz godzin dostępności. Stworzenie elektronicznej karty. Instruktor posiada dane swoich kursantów

3. **Zarządzanie Instruktorami:** System przechowuje dane o instruktorach, ich dostępności i doświadczeniu. Przydzielanie instruktora do kursanta odbywa się automatycznie, ale manager może to zmienić manualnie.

4. **Harmonogram Lekcji:** Automatyczne generowanie harmonogramu lekcji na podstawie dostępności instruktorów, preferencji kursantów, stopnia IKO kursanta, wagi kursanta oraz wcześniejszych interakcji z instruktorem. Na podstawie prognozy pogody generuje prawdopodobieństwo odbycia się zajęć.

5. **Powiadomienia SMS:** Informowanie instruktorów i kursantów o planowanych zajęciach dzień wcześniej oraz o ewentualnych zmianach.

6. **Baza Danych Kursantów i Instruktorów:** Bezpieczne przechowywanie danych osobowych kursantów i instruktorów, z kontrolą dostępu do informacji w zależności od uprawnień.

7. **Potwierdzenie Odbycia Lekcji:** System umożliwiający instruktorom potwierdzanie odbycia lekcji i przekazywanie tych informacji do managera.

8. **Monitorowanie Warunków Pogodowych:** Integracja z danymi pogodowymi w celu monitorowania wiatru i automatycznego odwoływania zajęć w przypadku niesprzyjających warunków.

9. **Raportowanie i Analiza:** Generowanie raportów dotyczących uczestnictwa, ocen instruktorów, ewentualnych problemów czy błędów w harmonogramie.

10. **Integracja z Kartami Informacyjnymi:** System umożliwia dostęp do kart informacyjnych kursantów i instruktorów w celu lepszej personalizacji zajęć.

11. **Automatyczne Powiadomienia o Brakach w Dokumentacji:** Powiadomienia dla instruktorów i managerów w przypadku braków w dokumentacji, takich jak brak potwierdzenia odbycia szkolenia.

## Ograniczenia i wymagania niefunkcyjne

1. Bezpieczeństwo danych: 
Dane kursantów, instruktorów i finansowe muszą być przechowywane i przetwarzane zgodnie z najwyższymi standardami bezpieczeństwa.

2. Łatwość obsługi i intuicyjność systemu dla użytkowników.

3. System powinien działać stabilnie i niezawodnie.

4. System powinien być dostępny dla użytkowników w każdym miejscu i czasie, z wykorzystaniem urządzeń mobilnych i komputerów stacjonarnych.