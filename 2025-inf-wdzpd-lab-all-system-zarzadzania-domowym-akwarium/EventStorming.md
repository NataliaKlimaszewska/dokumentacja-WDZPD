Zdarzenia (Events)

- **UżytkownikZarejestrowany** - Utworzono nowe konto użytkownika (e-mail lub social media).
- **UżytkownikZalogowany** - Użytkownik pomyślnie przeszedł proces autoryzacji.
- **AkwariumUtworzone** - Utworzono nowy profil akwarium z definicją środowiska.
- **ParametryAkwariumUstawione** - Zdefiniowano początkowe parametry fizykochemiczne wody.
- **AkwariumWspółdzielone** - Użytkownik zaprosił inną osobę do zarządzania akwarium (dodał do kontaktów).
- **GatunekDodanyDoAkwarium** - Dodano nową rybę lub roślinę do profilu.
- **SymulacjaDodaniaRybyWykonana** - Użytkownik sprawdził wpływ potencjalnego nowego gatunku na ekosystem.
- **NiezgodnośćWykryta** - System zidentyfikował konflikt behawioralny lub środowiskowy.
- **ParametryWodyZaktualizowane** - Wprowadzono nowe odczyty pH, temperatury lub zasolenia.
- **ZadanieZaplanowane** - Dodano wpis do harmonogramu (np. karmienie, czyszczenie).
- **PowiadomienieWysłane** - System wysłał alert (e-mail/push) do użytkownika.
- **RekomendacjaAIWygenerowana** - Moduł sztucznej inteligencji zaproponował kompatybilne gatunki.
- **PunktyPrzyznane** - System nagrodził użytkownika za dbanie o stabilność parametrów (grywalizacja).
- **OdznakaZdobyta** - Użytkownik osiągnął kamień milowy w zarządzaniu akwarium.
- **AkcjaUżytkownikaZalogowana** - Zapisano operację w logach audytowych.
- **UżytkownikZablokowany** - Administrator zablokował dostęp użytkownikowi.

### Komendy (Commands)

- **ZarejestrujUżytkownika** - Żądanie utworzenia konta.
- **UtwórzProfilAkwarium** - Żądanie stworzenia nowej instancji akwarium.
- **ZaprośDoWspółdzielenia** - Żądanie dodania użytkownika do listy osób zarządzających danym akwarium.
- **DodajGatunek** - Wprowadzenie danych o rybie/roślinie do systemu.
- **WykonajSymulacjęDecyzyjną** - Uruchomienie algorytmu sprawdzającego wpływ nowego gatunku.
- **ZaktualizujParametryWody** - Wprowadzenie bieżących danych z pomiarów wody.
- **ZaplanujZadanie** - Przypisanie zadania (np. karmienie) do harmonogramu i użytkownika.
- **GenerujRekomendacjeAI** - Wywołanie modułu AI w celu analizy kompatybilności.
- **BlokujUżytkownika** - Administracyjne zablokowanie dostępu.
- **GenerujRaportStanu** - Żądanie stworzenia podsumowania historycznego akwarium.

### Agregaty (Aggregates)

- **Użytkownik (User)** - Przechowuje dane konta, uprawnienia i powiązania z akwariami.
- **Akwarium (Aquarium)** - Główny obiekt grupujący parametry wody, historię i wyposażenie.
- **Ekosystem (Gatunki/Ryby/Rośliny)** - Zbiór organizmów w akwarium wraz z ich wymaganiami środowiskowymi.
- **Harmonogram (Scheduler)** - Zarządza zadaniami pielęgnacyjnymi i przypomnieniami.
- **System AI (AI Module)** - Odpowiada za logikę rekomendacji i analizy predykcyjnej.
- **Panel Administratora** - Scentralizowane miejsce do zarządzania użytkownikami i logami.

### Polityki (Policies)

- **Polityka Bezpieczeństwa Gatunków:** Jeśli _SymulacjaDodaniaRybyWykonana_ wykaże konflikt -> wyemituj zdarzenie _NiezgodnośćWykryta_ i zablokuj sugestię (ostrzeżenie).
- **Polityka Alertów Pielęgnacyjnych:** Jeśli termin zadania z _Harmonogramu_ jest bliski lub _ParametryWody_ przekroczyły normę -> wykonaj _WyślijPowiadomienie_.
- **Polityka Grywalizacji:** Jeśli _ParametryWody_ są stabilne przez określony czas -> wyemituj _PunktyPrzyznane_.
- **Polityka Audytu:** Przy każdej zmianie danych (np. _GatunekDodany_, _UsunięcieProfilu_) -> wykonaj _AkcjaUżytkownikaZalogowana_ (zapisz datę, godzinę, ID).
- **Polityka AI:** Jeśli _StatusAkwariumPrzeanalizowany_ wskazuje na braki w ekosystemie -> _WygenerujRekomendacjeAI_ dla kompatybilnych gatunków.