1\. Zadanie B

A. Funkcjonalności

- Rejestracja i logowanie:

<!-- -->

- rejestracja przez e-mail

- rejestracja przez konto Facebook

- logowanie z użyciem hasła lub autoryzacji zewnętrznej (OAuth)

<!-- -->

- Zarządzanie akwariami:

<!-- -->

- Stworzenie akwariów,

- dodanie i edycja akwariów,

- zapraszanie do współdzielenia akwarium,

- możliwość usuwania i archiwizacji akwariów,

- użytkownik może zasymulować dodanie nowych ryb przed faktycznym
  > zakupem

<!-- -->

- Zarządzanie gatunkami:

<!-- -->

- dodawanie ryb i roślin do akwarium,

- przechowywanie informacji o parametrach środowiskowych,

- system ostrzegający o niezgodnościach środowiskowych

<!-- -->

- Statystyki i historia:

<!-- -->

- wyświetlanie liczby gatunków w akwarium,

- obliczanie średniej długości życia ryb,

- historia dodawania i usuwania ryb,

- raporty stanu akwarium

<!-- -->

- Sugestie AI:

<!-- -->

- moduł sztucznej inteligencji rekomendujący kompatybilne gatunki ryb i
  > roślin,

- analiza bieżącego stanu akwarium i proponowanie usprawnień w
  > środowisku

<!-- -->

- Panel SuperAdministratora:

<!-- -->

- zarządzanie użytkownikami (blokowanie, usuwanie, restartowanie haseł)

- podgląd logów aplikacji,

- edycja oraz nadzór nad danymi systemowymi

<!-- -->

- System poziomów i osiągnięć (gamefication)

<!-- -->

- użytkownik może zbierać punkty za:

1.  utrzymanie stabilnych parametrów wody,

2.  regularne karmienie,

3.  brak uśmierconych rybek

- System powiadomień i planner:

<!-- -->

- użytkownik może utworzyć harmonogram zadań i przypisać użytkownika,

- powiadomienia e-mail / push o:

1.  karmieniu ryb,

2.  przekroczeniu temperatury / ph wody,

3.  urodzinach ryb oraz czyszczeniu akwarium

B. Technologie i narzędzia

I.  Java + Azure - Java została wybrana jako główny język backendowy ze
    względu na chęć nauki oraz rozwój kompetencji członków zespołu w tej
    technologii. Azure zapewnia gotową infrastrukturę do hostowania
    aplikacji, zarządzania bazą danych oraz integracji z innymi usługami
    (np. logowaniem, analizą, bezpieczeństwem).

II. Tailwind CSS - Wybraliśmy Tailwind CSS ze względu na szybkie
    tworzenie nowoczesnych interfejsów i spójny wygląd aplikacji bez
    pisania dużej ilości własnego kodu CSS.

III. [Autoryzacja: Azure App Service and Azure Functions - Zastosowanie
     tej technologii pozwala uniknąć tworzenia własnego systemu
     uwierzytelniania, co zwiększa bezpieczeństwo aplikacji i skraca
     czas implementacji logowania.]{.mark}

[]{.mark}

IV. JavaScript - JavaScript został wybrany jako podstawowy język
    frontendu ze względu na swoją popularność, uniwersalność i znajomość
    wśród członków zespołu.

V.  Azure SQL Database - Wybrano Azure SQL Database, ponieważ łatwo
    integruje się z usługami Azure i zapewnia bezpieczne, skalowalne
    przechowywanie danych.

VI. [Logowanie zdarzeń: Azure Monitor Logs - Technologia ta pozwala
    monitorować działanie aplikacji i analizować błędy bez tworzenia
    własnych narzędzi do logowania.]{.mark}

[]{.mark}

VII. [Testowanie i automatyzacja testów: Robot framework + Playwright -
     Zespół wybrał te narzędzia, ponieważ umożliwiają automatyzację
     testów i szybkie wykrywanie błędów w interfejsie użytkownika, co
     przyspiesza proces weryfikacji działania aplikacji.]{.mark}

[]{.mark}

VIII. [Next.js - Wybrano ze względu na prostą integrację z Reactem,
      wysoką wydajność oraz możliwość łatwego tworzenia dynamicznych
      stron i komponentów.]{.mark}

[]{.mark}

IX. Visual Studio Code - VS Code został wybrany ze względu na prostotę,
    dużą liczbę rozszerzeń i wcześniejsze doświadczenie zespołu z tym
    edytorem.
