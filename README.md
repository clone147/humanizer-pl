# Humanizer PL

Skill do Claude Code, który redaguje polskie teksty tak, żeby przestały brzmieć jak AI, ale nadal brzmiały jak autor.

Ta druga część jest ważniejsza. Większość humanizerów wygładza tekst do jednej neutralnej papki, a to też czyta się jak model. Ten skill najpierw ustala, jak pisze konkretna osoba, i dopiero potem wycina to, co dopisał do niej generator.

## Co jest w środku

52 wzorce pisania AI po polsku, dwa tryby pracy i eval, który skill przejeżdża sam na sobie przed oddaniem tekstu.

Katalog obejmuje warstwy, których angielskie humanizery nie łapią, bo po polsku wyglądają inaczej albo w ogóle nie mają odpowiednika:

| Warstwa | Przykład |
|---------|----------|
| Rzeczownikowość i styl urzędowy | „dokonać analizy” zamiast „przeanalizować” |
| Zbędne zaimki | „my oferujemy”, „otwórz swój laptop” |
| Kalki składniowe | „Ja uważam, że”, angielski szyk zdania |
| Polska typografia | proste cudzysłowy, em dash, 1,000,000 zamiast 1 000 000 |
| Wielkie litery po angielsku | „w Lutym”, „Poniedziałek”, „Internet” |
| Amerykański entuzjazm | „niesamowite!” tam, gdzie Polak napisze „niezłe” |
| Interpunkcja po angielsku | oxford comma, przecinek po „Ponadto” |

Do tego rzeczy uniwersalne: kontrasty binarne, odchrząkiwanie na wejściu, dwukropek z rewelacją, pseudogłęboka puenta, zakończenie-streszczenie, puste odwołania do źródeł, monotonny rytm zdań.

## Instalacja

```bash
git clone https://github.com/clone147/humanizer-pl.git ~/.claude/skills/humanizer-pl
```

Albo wklej do Claude Code:

> Zainstaluj ten skill globalnie: https://github.com/clone147/humanizer-pl

## Użycie

### Redakcja

```
/humanizer-pl

[twój tekst]
```

Dostajesz cały poprawiony tekst i sekcję **Co zmieniłem** z numerami wzorców.

### Wykrywanie

```
/humanizer-pl czy to brzmi jak AI?

[tekst]
```

Dostajesz listę wzorców z zacytowanymi linijkami i krótką poprawką dla każdej. Bez przepisywania, bez procentów, bez wyroku „to napisała AI”. Detektory zgadują, a nazwany wzorzec możesz sprawdzić sam.

## Czego skill nie robi

- nie dopisuje faktów, liczb, dat, nazw ani opinii, których w tekście nie było; jeśli akapit wisi w próżni, zostawia znacznik `[dane?]` i pyta
- nie zmienia formy zwracania się do czytelnika (Pan/Pani, ty, wy, bezosobowo)
- nie zmienia rodzaju gramatycznego autora
- nie wstawia sztucznych fragmentów zdań i potocyzmów, żeby „brzmiało ludzko”
- nie ściera opinii, przekleństw ani szorstkości, jeśli należą do autora

Poprzednia wersja skilla robiła pierwsze i czwarte. Wzorce 30, 31 i 37 kazały modelowi dopisywać konkretne liczby, nazwy firm i celowe niedoskonałości gramatyczne. To był najszybszy sposób na tekst, który brzmi ludzko i kłamie.

## Przykład

Przed:

> W dzisiejszym dynamicznie zmieniającym się świecie niezwykle istotne jest zrozumienie fundamentalnego znaczenia transformacji cyfrowej. Eksperci zgodnie twierdzą, że firmy muszą się adaptować. Ponadto warto zauważyć, że rozwiązania chmurowe stanowią klucz do sukcesu.

Po:

> Firmy muszą przejść na cyfrowe rozwiązania albo zostaną w tyle. Chmura to podstawa, bo zasoby skalujesz w minuty zamiast w tygodnie.

Wykryte wzorce: #28 otwieracz, #8 słownictwo AI, #2 puste odwołanie do źródeł, #1 nadmuchane znaczenie, #9 „stanowią”.

## Pliki

| Plik | Zawartość |
|------|-----------|
| `SKILL.md` | tryby, zasady redakcji, listy słów, indeks 52 wzorców, przebieg pracy |
| `wzorce.md` | pełny katalog z przykładami przed i po |
| `eval.md` | pass/fail, które skill przejeżdża na własnej redakcji |
| `agents/openai.yaml` | konfiguracja dla Codex |

## Skąd to się wzięło

Zaczęło się jako polski fork [blader/humanizer](https://github.com/blader/humanizer).

Zasady redakcji, tryb wykrywania i pomysł na eval pochodzą z [petergyang/no-ai-slop](https://github.com/petergyang/no-ai-slop). Wzorce 38-46 to polskie odpowiedniki jego katalogu retorycznego. Wzorce 47-52 dopisałem od zera, bo dotyczą fleksji, szyku i typografii, a tam angielski oryginał nie ma czego przenosić.

## Licencja

MIT
