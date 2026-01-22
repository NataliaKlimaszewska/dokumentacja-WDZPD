**COLLEGIUM WITELONA**

**Uczelnia Państwowa**

**Wydział Nauk Technicznych i Ekonomicznych**

**Kierunek Informatyka**

**Specjalność PAM**

**NATALIA KLIMASZEWSKA**  
**MAKSYM WILK**
**BARTOSZ DOBROŚ**  
**ROBERT KUŹBA**  
**JAKUB JANIEC**

# System zarządzania domowym akwarium

**Legnica 2025**
 
# Rozdział 1. Wstęp do projektu

## Opis projektu

Celem projektu jest stworzenie webowego systemu informatycznego do zarządzania
domowym akwarium, który będzie wspomagał użytkowników w utrzymaniu domowej hodowli ryb i roślin akwariowych. System umożliwi rejestrację użytkowników, tworzenie profili akwariów, dodanie ryb i roślin oraz monitorowanie zgodności warunków środowiskowych. System będzie analizował parametry takie jak pH oraz typ wody, temperaturę, a także ostrzeże, gdy w akwarium będą znajdować się gatunki, które nie powinny być trzymane razem.
System będzie wyposażony w panel superadministratora, który umożliwi zarządzanie użytkownikami, kontrolę danych systemowych oraz przeglądanie logów wszystkich akcji wykonywanych w aplikacji. Każde działanie użytkownika będzie rejestrowane wraz z datą, godziną i identyfikatorem użytkownika.

## Funkcjonalności systemu

- Rejestracja i logowanie
    - Rejestracja przez e-mail.
- Zarządzanie akwariami
    - Stworzenie akwariów.
    - Dodanie i edycja akwariów.
    - Zapraszanie do współdzielenia akwarium.
    - Możliwość usuwania i archiwizacji akwariów.
    - Użytkownik może zasymulować dodanie nowych ryb przed faktycznym zakupem.
- Zarządzanie gatunkami
    - Dodawanie ryb i roślin do akwarium.
    - Przechowywanie informacji o parametrach środowiskowych.
    - System ostrzegający o niezgodnościach środowiskowych.
- Statystyki i historia
    - Wyświetlanie liczby gatunków w akwarium.
- Panel SuperAdministratora
    - Zarządzanie użytkownikami (blokowanie, usuwanie, restartowanie haseł).
    - Podgląd logów aplikacji.
    - Edycja oraz nadzór nad danymi systemowymi.

## Tech stack

- Frontend: Javascript + Tailwind + React + Next.js
- Backend: Java + AWS
- Baza danych: Postgres
- Testowanie i automatyzacja testów: Robot framework + playwright

## Grupa projektowa i role w zespole

| Imię i nazwisko | Grupa          | Rola w zespole                                           | Zakres obowiązków                                                                                                                                                                                                                                 |
| --- |----------------|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Maksym Wilk | 1(2)           | Projekt Manager<br><br>Programista backend<br><br>DevOps | Rozdzielanie zadań, koordynowanie działań zespołu, kontakt z prowadzącym zajęcia,implementacja logiki biznesowej, baza danych, API, system logowania akcji użytkowników                                                                           |
| Natalia Klimaszewska | 1(2)           | Tester<br><br>Frontend<br><br>Researcher                 | Sporządzanie dokumentacji projektowej, Testowanie funkcjonalności, opracowanie scenariuszy testowych i przypadków testowych, analiza dot. gatunków ryb, roślin i parametrów środowiskowych, projektowanie i implementacja interfejsu graficznego, |
| Bartosz Dobroś | 1(1)           | Tester                                                   | Testowanie aplikacji, weryfikacja poprawności wprowadzania danych, testowanie zabezpieczeń, sprawdzanie wydajności i stabilności aplikacji.                                                                                                       |
| Robert Kuźba | 1(1)           | Backend                                                  | Logika aplikacji, API, baza danych                                                                                                                                                                                                                |
| Jakub Janiec | 2(1)u | Frontend                                                 | Implementacja interfejsu graficznego, współpraca z testerami i backendem, integracja API                                                                                                                                                          |
| Wszyscy ||  Ogólne                                                  | Udzielanie pomocy, przekazywanie informacji o niedociągnięciach oraz niedziałających funkcjach.                                                                                                                                                   |


