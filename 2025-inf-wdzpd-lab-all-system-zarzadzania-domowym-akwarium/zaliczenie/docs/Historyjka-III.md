# Historyjka: Lucyna

## Opis

> **Jako** Lucyna (dbająca o dobrostan zwierząt),
> **Chcę** automatycznie porównać wymagania wybranego z bazy gatunku z aktualnymi parametrami mojego akwarium,
> **Aby** system matematycznie ocenił kompatybilność i ostrzegł mnie przed wpuszczeniem zwierzęcia do nieodpowiedniej wody (co skończyłoby się jego śmiercią).

## Kryteria akceptacji

**Lista kontrolna:**
- [ ] System pobiera ostatnie zapisane parametry mojego akwarium (np. pH 7.5).
- [ ] System porównuje je z wymaganiami wybranego gatunku (np. wymaga pH 6.0-6.5).
- [ ] W przypadku niezgodności, aplikacja wyświetla konkretne ostrzeżenie wskazujące **który parametr** jest nieprawidłowy i o ile (różnica).
- [ ] System ocenia zgodność w skali (np. Idealne / Ryzykowne / Zabójcze).

**Scenariusz (Given-When-Then):**
> **Scenariusz:** Weryfikacja krewetek
> - **Mając (Given)** akwarium z wodą o twardości GH 15 (twarda),
> - **Kiedy (When)** wybiorę z bazy krewetkę "Caridina" (wymaga wody miękkiej GH 4-6) i kliknę "Sprawdź kompatybilność",
> - **Wtedy (Then)** otrzymam ostrzeżenie: "Ryzyko śmierci! Twoja woda jest za twarda (GH 15 vs wymagane max 6)".

## Dodatkowe informacje (opcjonalnie)

- **Zależności:** Wymaga wcześniejszego wprowadzenia parametrów swojego akwarium.
- **Wartość:** To oszczędza pieniądze Lucyny (nie kupi zwierząt, które padną) i czas na ręczne porównywanie tabelek.

## Priorytet i estymacja

- **Priorytet:** **Should Have** (Kluczowa funkcja wyróżniająca aplikację dla zaawansowanych).
- **Estymacja (Story Points):** 8 (Logika porównywania wielu parametrów liczbowych).