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

28 wzorców typowych dla polskich tekstów generowanych przez AI:

### Wzorce treści (1-6)
1. Nadmierne podkreślanie znaczenia ("kluczowy", "przełomowy")
2. Puste odwołania do źródeł ("Eksperci twierdzą...")
3. Nadużycie imiesłowów ("symbolizując", "odzwierciedlając")
4. Język promocyjny ("wyjątkowy", "niezwykły")
5. Niejasne atrybucje ("Wielu uważa", "Powszechnie wiadomo")
6. Formułkowe wyzwania ("Pomimo wyzwań, rozwija się")

### Wzorce językowe (7-12)
7. Słownictwo AI ("Ponadto", "W kontekście", "Niezwykle istotne")
8. Unikanie "jest" ("stanowi", "pełni rolę")
9. Negatywne paralelizmy ("To nie tylko X, to także Y")
10. Wymuszona reguła trzech
11. Cyklowanie synonimów
12. Fałszywe zakresy ("od X do Y")

### Wzorce stylu (13-18)
13. Nadużycie myślników
14. Nadużycie pogrubień
15. Listy z nagłówkami
16. Wielkie Litery W Nagłówkach
17. Emoji w tekście
18. CamelCase w hashtagach

### Wzorce komunikacji (19-21)
19. Artefakty chatbota ("Mam nadzieję, że to pomoże!")
20. Zastrzeżenia o wiedzy ("Moja wiedza sięga do...")
21. Pochlebczy ton ("Świetne pytanie!")

### Wypełniacze i asekuracja (22-24)
22. Zbędne frazy ("ze względu na fakt, że" → "bo")
23. Nadmierna asekuracja ("potencjalnie mógłby ewentualnie")
24. Generyczne zakończenia ("Przyszłość rysuje się w jasnych barwach")

### Polskie specyficzne (25-28)
25. Anglicyzmy AI ("treść jest królem")
26. Otwieracz "W dzisiejszych czasach"
27. Brak kontekstu kulturowego
28. Bezpłciowy styl

## Przykład

### Przed (tekst AI):
> W dzisiejszych dynamicznie zmieniających się czasach niezwykle istotne jest zrozumienie fundamentalnego znaczenia transformacji cyfrowej. Eksperci zgodnie twierdzą, że firmy muszą się adaptować. Ponadto warto zauważyć, że rozwiązania chmurowe stanowią klucz do sukcesu.

### Po (humanizowany):
> Firmy muszą przejść na cyfrowe rozwiązania albo zostaną w tyle. Chmura to podstawa – skalujesz zasoby w minuty zamiast tygodni.

## Licencja

MIT - jak oryginał
