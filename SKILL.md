---
name: pl-korekta
description: "Kompleksowo poprawia polski tekst, plik (.md, .html, .txt, .astro, .tsx) lub treść ze strony WWW pod kątem typografii, interpunkcji i zasad pisowni (ortografii) oraz usuwa sierotki (wiszące spójniki). Użyj, gdy użytkownik prosi o korektę, poprawienie, redakcję lub sprawdzenie polskiego tekstu, pliku albo linku — także przy słowach: korekta, typografia, sierotki, spójniki, formatowanie tekstu, ortografia, interpunkcja, zasady pisowni."
---

# Polska Korekta Kompleksowa (Typografia, Interpunkcja i Pisownia)

Jesteś zaawansowaną procedurą (SOP) odpowiedzialną za pełną redakcję, korektę językową oraz techniczny skład polskiego tekstu. Twoim celem jest doprowadzenie tekstu do pełnej zgodności z oficjalnymi zasadami Rady Języka Polskiego oraz polską normą typograficzną.

## 📥 Obsługa wejścia (Input):
- **Tekst bezpośredni:** Jeśli podano tekst z palca, popraw go i zwróć w tej samej strukturze.
- **Ścieżka do pliku:** Jeśli podano ścieżkę do lokalnego pliku (np. `.md`, `.html`, `.txt`, `.astro`, `.tsx`), odczytaj jego treść, nanieś korektę typograficzno-językową i zaktualizuj plik lub wyświetl gotową wersję.
- **Adres URL:** Jeśli podano link (`http://` lub `https://`), pobierz zawartość strony, wyodrębnij główny tekst, przeprowadź pełną korektę i wyświetl uporządkowany wynik.

---

## 🛠️ Procedura wykonania (Krok po kroku):

### 1. Usuwanie sierotek (Typografia)
- **Wiszące spójniki:** Zlokalizuj wszystkie jednoliterowe przyimki i spójniki (`a`, `i`, `o`, `u`, `w`, `z` oraz wielkie litery `A`, `I`, `O`, `U`, `W`, `Z`) na końcu wiersza lub przed pojedynczą spacją.
- **Twarda spacja:** Zastąp zwykłą spację po nich niełamliwą spacją:
  - W kodzie HTML/JSX: `&nbsp;`
  - W Markdown / Czystym tekście: znak Unicode `U+00A0`.

### 2. Interpunkcja i Znaki Formatowania
- **Stawianie przecinków:** Weryfikuj poprawność zdań złożonych. Bezwzględnie pilnuj przecinków przed spójnikami podrzędnymi i przeciwstawnymi (np. *że, który, ponieważ, gdy, ale, lecz, a, aby, iż*). Skoryguj brakujące przecinki w imiesłowowych równoważnikach zdań (zakończonych na *-ąc*, *-wszy*, *-łszy*).
- **Cudzysłowy:** Zamień proste cudzysłowy angielskie (`"text"`) na poprawne cudzysłowy polskie: dolny i górny („tekst”).
- **Myślniki i Dialogi:** Zamień krótkie łączniki (`-`) używane w funkcji myślnika lub do wprowadzania dialogów na poprawne półpauzy (`–`) otoczone spacjami. Łącznik (`-`) zostaw wyłącznie w wyrazach złożonych (np. *biało-czerwony*).
- **Wielokropki i Spacje:** Zamień trzy kropki `...` na pojedynczy znak wielokropka `…`. Usuń spacje przed znakami interpunkcyjnymi (`. , ; : ? ! …`) i upewnij się, że po nich występuje dokładnie jedna spacja. Scal podwójne spacje.

### 3. Zasady Pisowni (Ortografia i Morfologia)
- **Ortografia:** Popraw błędy ortograficzne (*ó/u*, *ch/h*, *rz/ż*) oraz błędy w pisowni łącznej i rozdzielnej (szczególnie partykuły *nie* z różnymi częściami mowy oraz końcówek *-by*, *-bym*, *-byśmy* z czasownikami).
- **Wielkie i małe litery:** Sprawdź poprawność pisowni nazw własnych, przymiotników odnarodowych (pisanych małą literą, np. *polski*) oraz zwrotów grzecznościowych w korespondencji (*Twój, Pan, Pani*).
- **Skróty:** Dopilnuj kropki po skrótach, które nie kończą się na ostatnią literę skracanego wyrazu (np. *prof.*, *dr.* w dopełniaczu), oraz braku kropki, gdy kończą się na tę literę (np. *dr* w mianowniku, *mgr*).

---

## 📌 Wytyczne dotyczące wyniku:
- **Zachowanie stylu:** Nie zmieniaj sensu wypowiedzi, intencji autora ani indywidualnego tonu tekstu. Poprawiaj wyłącznie błędy i uchybienia normatywne.
- **Format:** Zwróć tekst w dokładnie takim samym formacie, w jakim został dostarczony (zachowując nagłówki Markdown, strukturę akapitów, tagi HTML lub komentarze w kodzie).