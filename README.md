# Polski Humanizer dla Claude Code

Skill do Claude Code usuwający charakterystyczne ślady pisania AI z polskich tekstów.

Polski fork [blader/humanizer](https://github.com/blader/humanizer) dostosowany do polskich wzorców językowych.

## Instalacja

```bash
git clone https://github.com/clone147/humanizer-pl.git ~/.claude/skills/humanizer-pl
```

Lub dodaj do ustawień Claude Code:
```json
{
  "skills": ["clone147/humanizer-pl"]
}
```

## Użycie

W Claude Code wpisz:
```
/humanizer-pl

[wklej tekst do humanizacji]
```

Lub po prostu:
```
Humanizuj ten tekst:

[wklej tekst]
```

## Co wykrywa?

37 wzorców typowych dla polskich tekstów generowanych przez AI:

### Wzorce treści (1-7)
1. Nadmierne podkreślanie znaczenia ("kluczowy", "przełomowy")
2. Puste odwołania do źródeł ("Eksperci twierdzą...")
3. Nadużycie imiesłowów ("symbolizując", "odzwierciedlając")
4. Język promocyjny ("wyjątkowy", "niezwykły")
5. Niejasne atrybucje ("Wielu uważa", "Powszechnie wiadomo")
6. Formułkowe wyzwania ("Pomimo wyzwań, rozwija się")
7. Nadmierna wyważoność ("Z jednej strony... z drugiej strony...")

### Wzorce językowe (8-14)
8. Słownictwo AI ("Ponadto", "W kontekście", "Niezwykle istotne")
9. Unikanie "jest" ("stanowi", "pełni rolę")
10. Negatywne paralelizmy ("To nie tylko X, to także Y")
11. Wymuszona reguła trzech
12. Cyklowanie synonimów
13. Fałszywe zakresy ("od X do Y")
14. Strona bierna i bezosobowość ("Można zaobserwować" → "Widać")

### Wzorce stylu (15-20)
15. Nadużycie myślników
16. Nadużycie pogrubień
17. Listy z nagłówkami
18. Wielkie Litery W Nagłówkach
19. Emoji w tekście
20. CamelCase w hashtagach

### Wzorce komunikacji (21-23)
21. Artefakty chatbota ("Mam nadzieję, że to pomoże!")
22. Zastrzeżenia o wiedzy ("Moja wiedza sięga do...")
23. Pochlebczy ton ("Świetne pytanie!")

### Wypełniacze i asekuracja (24-26)
24. Zbędne frazy ("ze względu na fakt, że" → "bo")
25. Nadmierna asekuracja ("potencjalnie mógłby ewentualnie")
26. Generyczne zakończenia ("Przyszłość rysuje się w jasnych barwach")

### Polskie specyficzne (27-33)
27. Anglicyzmy AI ("treść jest królem")
28. Otwieracz "W dzisiejszych czasach"
29. Brak kontekstu kulturowego
30. Bezpłciowy styl - brak opinii i emocji
31. Brak konkretu (generyczne przykłady zamiast dat, liczb, nazw)
32. Amerykański entuzjazm ("Niesamowite!" → "Niezłe")
33. Przecinki po angielsku (Oxford comma, przecinek po przysłówku)

### Wzorce rytmu i struktury (34-37)
34. Monotonny rytm zdań (najważniejszy sygnał detektorów AI!)
35. Monotonna długość akapitów
36. Szablonowa struktura akapitów
37. Idealna gramatyka (brak fragmentów, kolokwializmów)

## Przykład

### Przed (tekst AI):
> W dzisiejszych dynamicznie zmieniających się czasach niezwykle istotne jest zrozumienie fundamentalnego znaczenia transformacji cyfrowej. Eksperci zgodnie twierdzą, że firmy muszą się adaptować. Ponadto warto zauważyć, że rozwiązania chmurowe stanowią klucz do sukcesu.

### Po (humanizowany):
> Firmy muszą przejść na cyfrowe rozwiązania albo zostaną w tyle. Chmura to podstawa – skalujesz zasoby w minuty zamiast tygodni.

## Licencja

MIT - jak oryginał
