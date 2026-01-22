# Mateusz — Superadmin

> "Użytkownicy kłamią, że 'samo się zepsuło', ale logi zawsze mówią prawdę. Moim celem jest to, żeby serwery nie płonęły w piątek po południu, a dane były bezpieczne jak w sejfie."

## O osobie

- **Wiek:** 34 lata
- **Zawód:** Senior DevOps / Specjalista ds. Bezpieczeństwa
- **Lokalizacja:** Warszawa (Praca zdalna / Home Office)
- **Krótka biografia** Mateusz to doświadczony inżynier, który wyznaje zasadę, że "nudny system to dobry system". Zamiast gasić pożary, woli im zapobiegać poprzez skrupulatne procedury i automatyzację. W zespole pełni rolę mentora i głosu rozsądku, hamując zbyt ryzykowne pomysły programistów. Prywatnie pasjonat rozwiązań chmurowych i optymalizacji kosztów.

## Kontekst techniczny

- **Urządzenia:** Workstation z 3 monitorami, Laptop z Linuxem, Smartfon z podglądem alertów serwerowych.
- **Używane aplikacje/platformy:** Terminal, Jira, Slack (kanały alertów), Grafana, Graylog.
- **Biegłość technologiczna:** Ekspert. 
- 
## Cele i motywacje

- **Główne cele:** Utrzymanie ciągłości działania biznesu (SLA 99.9%) i ochrona danych przed wyciekiem.
- **Cele związane z produktem:** Posiadanie narzędzi, które pozwolą mu szybko zdiagnozować problem bez grzebania w kodzie źródłowym ("Gdzie jest ten log?!").
- **Co go motywuje?** Automatyzacja ("Jeśli muszę coś zrobić 3 razy, piszę do tego skrypt") oraz "święty spokój" w weekendy.

## Frustracje i problemy

- **Główne frustracje:** Użytkownicy używający hasła "12345", brak informacji o błędach ("Wyskoczył błąd" to dla niego za mało), marketing wrzucający posty, które "zabijają" serwer ruchem.
- **Problemy, które Twój produkt może rozwiązać:** Konieczność ręcznego grzebania w bazie danych SQL, aby zresetować komuś uprawnienia lub sprawdzić, dlaczego zdjęcie się nie ładuje.

## Scenariusz użycia

**Jak i kiedy mógłby używać Twojego produktu?**
Jest piątek wieczorem. System monitoringu wysyła alert o błędach 500. Mateusz otwiera Panel Superadministratora na telefonie, sprawdza logi systemowe, widzi, że jeden z użytkowników (bot) próbuje spamować forum. Jednym kliknięciem blokuje adres IP i konto tego użytkownika, po czym wraca do oglądania filmu.

**Kluczowe funkcjonalności dla tej persony:**
- **Centrum Logów (Audit Log):** Kto, co, kiedy i dlaczego usunął.
