# Historyjka: Mateusz

> "Wiem, że użytkownik kłamie, że 'nic nie klikał'. W logach widzę wszystko. Moim celem jest to, żeby serwer nie płonął, a dane były bezpieczne."

---

## Opis

> **Jako** Mateusz (Superadministrator),
> **Chcę** mieć pełną kontrolę nad wszystkimi kontami w systemie,
> **Aby** móc natychmiast zablokować podejrzanego użytkownika, zresetować akwarium osobie.

## Kryteria akceptacji

**Lista kontrolna:**
- [ ] Widok tabelaryczny wszystkich zarejestrowanych użytkowników z ich rolami.
- [ ] Przycisk "Banuj / Zablokuj", który natychmiast wylogowuje użytkownika i blokuje ponowny dostęp.
- [ ] Możliwość wymuszenia resetu akwarium.

**Scenariusz (Given-When-Then):**
> **Scenariusz:** Blokowanie spamera
> - **Mając (Given)** użytkownika, który zachowuje się podejrzanie,
> - **Kiedy (When)** wejdę w panel zarządzania użytkownikami i kliknę "Zablokuj",
> - **Wtedy (Then)** status jego konta zmieni się na "Inactive".

## Priorytet i estymacja
- **Priorytet:** **Must Have** (Bezpieczeństwo systemu).
- **Estymacja:** 8

---
