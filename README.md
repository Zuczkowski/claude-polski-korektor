# claude-polski-korektor

Skill dla Claude do kompleksowej korekty polskiego tekstu: typografia, interpunkcja i ortografia w jednym przebiegu.

## Co robi

- **Sierotki** — usuwa jednoliterowe spójniki/przyimki (`a, i, o, u, w, z`) osierocone na końcu wiersza, wstawiając twardą spację (`&nbsp;` w HTML, `U+00A0` w Markdown/tekście).
- **Interpunkcja i skład** — poprawia cudzysłowy (na polskie „ ”), myślniki (łącznik vs. półpauza), wielokropek, spacje wokół znaków interpunkcyjnych.
- **Ortografia** — koryguje typowe błędy (*ó/u*, *ch/h*, *rz/ż*, pisownia łączna/rozdzielna, wielkie/małe litery, kropki po skrótach).
- **Wejście** — działa na wklejonym tekście, lokalnym pliku (`.md`, `.html`, `.txt`, `.astro`, `.tsx`) albo adresie URL.

Nie zmienia sensu, stylu ani intencji autora — poprawia wyłącznie błędy normatywne i techniczny skład.

## Instalacja

Skopiuj `SKILL.md` do katalogu skilli Claude (np. przez panel skilli w Claude/Cowork) albo dodaj to repo jako skill w swoim projekcie.

## Licencja

MIT — patrz [LICENSE](LICENSE).
