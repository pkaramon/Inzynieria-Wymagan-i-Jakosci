# Specyfikacja przypadków użycia

**Odwołanie zajęć w przypadku złych warunków pogodowych.**

## Cel:
Odwołanie zajęć w przypadku złych warunków pogodowych i powiadomienie o tym kursantów i instruktorów.

## Główny aktor:
Menedżer szkoły kitesurfingu

## Warunek początkowy (warunki wstępne):
Menedżer jest w zakładce “Harmonogram zajęć”.

## Zdarzenie początkowe (wyzwalacz):
Menedżer klika przycisk odświeżający dane o pogodzie.

## Główny scenariusz sukcesu:
1. System sprawdza aktualne dane pogodowe dla obszaru szkoły kitesurfingu.
2. System automatycznie aktualizuje informacje o warunkach pogodowych na dashboardzie menedżera.
3. Wyświetla się lista zajęć w przypadku niekorzystnych warunków pogodowych, z informacjami o pogodzie podczas zajęć oraz przyciskiem umożliwiającym zaznaczenie danych zajęć do odwołania. Istnieje także opcja zaznaczenia wszystkich zajęć.
4. Menedżer odwołuje zaznaczone zajęcia na podstawie otrzymanych informacji.
5. System wysyła SMSy do instruktorów oraz kursantów. Kursanci otrzymują kalendarz z dostępnymi terminami zajęć.

## Rozszerzenia - Scenariusze Alternatywne:

1.1 System nie może pobrać aktualnych danych pogodowych.
* Menedżer otrzymuje komunikat o problemie z pobieraniem danych.
* Menedżer może spróbować odświeżyć dane ponownie.

3.1 System nie wykrywa problemów z pogodą.
* Menedżer otrzymuje komunikat, że nie wykryto złych warunków pogodowych.

4.1 Menedżer nie odwołuje żadnych zajęć.

5.1 System SMSowy nie zadziałał.
* Wysyłamy powiadomienie do systemu SMSowego (aktor zewnętrzny) o błędzie.
* System po 10 minutach ponawia próbę wysłania powiadomień.