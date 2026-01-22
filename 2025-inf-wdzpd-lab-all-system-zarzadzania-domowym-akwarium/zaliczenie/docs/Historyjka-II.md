# Historyjka: Kasia

## Opis

> **Jako** Kasia (mama amator),
> **Chcę** szybko wpisać nazwę ryby, którą syn widzi w sklepie i porównać ją z naszymi obecnymi rybami,
> **Aby** dowiedzieć się natychmiast, czy mogą żyć razem, zanim syn zdąży się przywiązać do pomysłu zakupu.

## Kryteria akceptacji

**Lista kontrolna:**
- [ ] Użytkownik może wybrać z listy rybę, którą już posiada (np. Błazenek "Nemo").
- [ ] Użytkownik może wyszukać drugą rybę (tę ze sklepu).
- [ ] System wyświetla **jednoznaczny** wynik w formie koloru (Zielony = OK, Czerwony = NIE).
- [ ] Wynik jest widoczny na pierwszy rzut oka, bez konieczności czytania długiego tekstu.

**Scenariusz (Given-When-Then):**
> **Scenariusz:** Weryfikacja niepasującej ryby
> - **Mając (Given)** dodanego do "Mojego Akwarium" Błazenka (ryba słonowodna),
> - **Kiedy (When)** wyszukam "Welonka" (ryba słodkowodna) i kliknę "Sprawdź",
> - **Wtedy (Then)** ekran podświetli się na czerwono z ikoną smutnej buźki lub znakiem "STOP".

## Dodatkowe informacje (opcjonalnie)

- **Makiety/Projekty graficzne:** Interfejs musi być maksymalnie uproszczony (duże przyciski).
- **Przypadki brzegowe:** Jeśli użytkownik wpisze nazwę ryby z literówką, system powinien podpowiedzieć poprawną nazwę (auto-sugestia).

## Priorytet i estymacja

- **Priorytet:** **Must Have** (Kluczowa funkcja dla tej persony)
- **Estymacja (Story Points):** 8

---

# Historyjka: Wyjaśnienie przyczyny konfliktu (Edukacja dziecka)

## Opis

> **Jako** Kasia (mama "Małego Odkrywcy"),
> **Chcę** zobaczyć proste, jednozdaniowe uzasadnienie, dlaczego ryby do siebie nie pasują (np. "Tej rybce będzie za zimno"),
> **Aby** móc przeczytać to synowi i wytłumaczyć mu odmowę zakupu w sposób, który zrozumie.

## Kryteria akceptacji

**Lista kontrolna:**
- [ ] Pod wynikiem negatywnym (czerwonym) pojawia się krótki tekst wyjaśniający.
- [ ] Tekst unika żargonu (zamiast "niezgodne pH", komunikat: "Ta ryba lubi inną wodę").
- [ ] System wskazuje konkretny parametr konfliktu (temperatura, agresja, wielkość akwarium).

**Scenariusz (Given-When-Then):**
> **Scenariusz:** Tłumaczenie dziecku
> - **Mając (Given)** wynik negatywny porównania ryb,
> - **Kiedy (When)** kliknę w szczegóły lub rozwinę komunikat,
> - **Wtedy (Then)** zobaczę prosty komunikat w stylu: "Błazenek potrzebuje słonej wody, a Welonka słodkiej. Nie mogą pływać razem".

## Dodatkowe informacje (opcjonalnie)

- **Notatki techniczne:** Wykorzystanie bazy wiedzy o parametrach życiowych ryb do generowania prostych komunikatów.
- **Kontekst:** Kasia używa aplikacji jako "autorytetu" dla dziecka.

## Priorytet i estymacja

- **Priorytet:** **Should Have** (Bardzo przydatne, buduje wartość edukacyjną).
- **Estymacja (Story Points):** 3