# Polski Humanizer

Skill do Claude Code usuwający charakterystyczne ślady pisania AI z polskich tekstów.

## Trigger
Użyj tego skilla gdy użytkownik poprosi o:
- `/humanizer-pl` - uruchom analizę i poprawę tekstu
- "humanizuj tekst", "popraw styl AI", "usuń ślady AI"

## Instrukcje dla Claude

Gdy otrzymasz tekst do humanizacji:

1. **Zidentyfikuj wzorce AI** - przeanalizuj tekst pod kątem 28 wzorców opisanych poniżej
2. **Zaproponuj poprawki** - dla każdego wykrytego wzorca pokaż wersję przed/po
3. **Przepisz tekst** - dostarcz pełną wersję po humanizacji
4. **Zachowaj sens** - nie zmieniaj merytoryki, tylko styl

## Osobowość tekstu po humanizacji

Tekst humanizowany powinien brzmieć jak napisany przez:
- Kompetentnego specjalistę (nie chatbota)
- Osobę z charakterem i opinią
- Kogoś kto pisze zwięźle i konkretnie
- Polaka piszącego naturalnie po polsku (nie tłumaczącego z angielskiego)

---

# 28 POLSKICH WZORCÓW PISANIA AI

## WZORCE TREŚCI (1-6)

### 1. Nadmierne podkreślanie znaczenia
AI uwielbia nadawać wszystkiemu "przełomowe znaczenie".

**Przed:** "Ten kluczowy moment stanowi przełomowe osiągnięcie o nieocenionym znaczeniu dla dalszego rozwoju."
**Po:** "To ważny krok w rozwoju projektu."

**Słowa do usunięcia:** kluczowy, przełomowy, nieoceniony, fundamentalny, transformacyjny, paradigm-shifting

---

### 2. Puste odwołania do źródeł
AI cytuje nieistniejące badania i ekspertów.

**Przed:** "Eksperci zgodnie twierdzą, że badania jednoznacznie pokazują rosnące zainteresowanie tematem."
**Po:** "Zainteresowanie tematem rośnie." (lub dodaj konkretne źródło)

**Frazy do usunięcia:**
- "Eksperci twierdzą"
- "Badania pokazują"
- "Według specjalistów"
- "Jak wynika z analiz"

---

### 3. Powierzchowne analizy z imiesłowami
AI nadużywa imiesłowów przysłówkowych (-ąc) do pseudoanalizy.

**Przed:** "Marka rozwija się, symbolizując innowacyjność, odzwierciedlając trendy i podkreślając jakość."
**Po:** "Marka rozwija się dzięki innowacyjności i jakości produktów."

**Problematyczne konstrukcje:**
- "symbolizując wartości"
- "odzwierciedlając potrzeby"
- "podkreślając znaczenie"
- "uosabiając ideały"

---

### 4. Język promocyjny
AI pisze jak folder reklamowy.

**Przed:** "To wyjątkowe, niezwykłe i fascynujące rozwiązanie o imponujących możliwościach."
**Po:** "Rozwiązanie ma trzy przydatne funkcje: X, Y, Z."

**Słowa do wymiany:**
- wyjątkowy → konkretny
- niezwykły → inny niż X
- fascynujący → ciekawy
- imponujący → duży/szybki/tani (co konkretnie?)

---

### 5. Niejasne atrybucje
AI ukrywa brak wiedzy za ogólnikami.

**Przed:** "Wielu uważa, że powszechnie wiadomo, iż nie da się ukryć rosnącego znaczenia tematu."
**Po:** "Temat zyskuje na znaczeniu." (lub podaj kto tak uważa)

**Frazy do usunięcia:**
- "Wielu uważa"
- "Powszechnie wiadomo"
- "Nie da się ukryć"
- "Trudno zaprzeczyć"
- "Każdy wie"

---

### 6. Formułkowe wyzwania
AI ma szablon na "trudności i sukces".

**Przed:** "Pomimo licznych wyzwań firma dynamicznie się rozwija. Mimo trudności sektor prosperuje."
**Po:** "Firma rośnie o 20% rocznie mimo kryzysu w branży."

**Szablony do usunięcia:**
- "Pomimo wyzwań, rozwija się"
- "Mimo trudności, prosperuje"
- "Wbrew przeciwnościom, odnosi sukces"

---

## WZORCE JĘZYKOWE (7-12)

### 7. Słownictwo charakterystyczne dla AI
Te słowa to sygnatury modeli językowych.

**Przed:** "Ponadto warto zauważyć, że w kontekście analizy niezwykle istotne jest zrozumienie fundamentalnych aspektów."
**Po:** "Ważne jest też zrozumienie podstaw."

**Słowa AI do wymiany:**
| AI pisze | Człowiek pisze |
|----------|---------------|
| Ponadto | Też, także |
| Co więcej | Też |
| Warto zauważyć | (usuń) |
| W kontekście | W, przy |
| Niezwykle istotne | Ważne |
| Fundamentalny | Podstawowy |
| Kluczowy | Ważny |
| Innowacyjny | Nowy |

---

### 8. Unikanie słowa "jest"
AI nadużywa synonimów "jest".

**Przed:** "Firma stanowi lidera rynku, pełni rolę innowatora i charakteryzuje się elastycznością."
**Po:** "Firma jest liderem rynku i szybko się adaptuje."

**Konstrukcje do uproszczenia:**
- "stanowi" → "jest"
- "pełni rolę" → "jest"
- "charakteryzuje się" → "jest", "ma"
- "wyróżnia się" → "jest", "ma"

---

### 9. Negatywne paralelizmy
AI uwielbia "nie tylko X, ale także Y".

**Przed:** "To nie tylko narzędzie, to także filozofia. Nie chodzi wyłącznie o zysk, ale przede wszystkim o wartości."
**Po:** "Narzędzie opiera się na wartościach, nie tylko zysku."

**Konstrukcje do ograniczenia:**
- "To nie tylko X, to także Y"
- "Nie chodzi wyłącznie o X"
- "To znacznie więcej niż tylko"

---

### 10. Reguła trzech
AI wymusza listy trzech elementów.

**Przed:** "Platforma oferuje szybkość, niezawodność i skalowalność. Zapewnia bezpieczeństwo, wygodę i elastyczność."
**Po:** "Platforma jest szybka i niezawodna. Łatwo ją skalować."

**Uwaga:** Jeśli naprawdę są trzy równie ważne elementy - OK. Ale AI dodaje trzeci element "na siłę".

---

### 11. Cyklowanie synonimów
AI powtarza to samo innymi słowami.

**Przed:** "System jest wydajny, efektywny i produktywny. Oferuje szybkość, prędkość działania i sprawność."
**Po:** "System działa szybko."

**Diagnoza:** Jeśli usunięcie słowa nie zmienia sensu zdania - usuń je.

---

### 12. Fałszywe zakresy
AI wymusza konstrukcje "od X do Y".

**Przed:** "Rozwiązanie sprawdza się w firmach od małych startupów po duże korporacje, od branży IT po sektor finansowy."
**Po:** "Rozwiązanie działa w firmach każdej wielkości."

**Konstrukcje do uproszczenia:**
- "od X do Y" → często wystarczy "różne" lub "wszystkie"
- "począwszy od X, a skończywszy na Y"

---

## WZORCE STYLU (13-18)

### 13. Nadużycie myślników
AI wtrąca za dużo dygresji.

**Przed:** "Firma – założona w 2020 roku – oferuje rozwiązania – głównie dla sektora MŚP – które pomagają – co warto podkreślić – w automatyzacji."
**Po:** "Firma założona w 2020 oferuje automatyzację dla MŚP."

**Zasada:** Maksymalnie jedno wtrącenie w myślnikach na akapit.

---

### 14. Nadużycie pogrubień
AI pogrubia co drugie słowo.

**Przed:** "Nasze **innowacyjne** rozwiązanie oferuje **wyjątkową** jakość i **niezrównaną** wydajność."
**Po:** "Nasze rozwiązanie oferuje wysoką jakość i wydajność."

**Zasada:** Pogrubiaj tylko to, co naprawdę wymaga uwagi (1-2 słowa na akapit).

---

### 15. Listy z nagłówkami
AI robi nagłówek z każdego punktu.

**Przed:**
- **Szybkość:** System działa szybko
- **Niezawodność:** System jest niezawodny
- **Bezpieczeństwo:** System jest bezpieczny

**Po:**
- System działa szybko i niezawodnie
- Dane są szyfrowane end-to-end

---

### 16. Wielkie Litery W Nagłówkach
Angielski styl w polskim tekście.

**Przed:** "Jak Skutecznie Zarządzać Zespołem W Erze Cyfrowej"
**Po:** "Jak skutecznie zarządzać zespołem w erze cyfrowej"

**Zasada:** Po polsku wielką literą piszemy tylko pierwszy wyraz nagłówka.

---

### 17. Emoji w tekście
AI rozsypuje emoji jak konfetti.

**Przed:** "Nasz produkt jest szybki 🚀, bezpieczny 🔒 i innowacyjny ✨! Zapraszamy 🔥💪"
**Po:** "Nasz produkt jest szybki, bezpieczny i nowoczesny."

**Zasada:** Emoji są OK w social media, nie w profesjonalnym tekście.

---

### 18. CamelCase w hashtagach
Angielski styl w polskich hashtagach.

**Przed:** "#TworzenieTreści #ZarządzanieProjektem #TransformacjaCyfrowa"
**Po:** "#tworzenietresci #zarzadzanieprojektem #transformacjacyfrowa"

**Zasada:** Polskie hashtagi małymi literami (CamelCase to konwencja angielska).

---

## WZORCE KOMUNIKACJI (19-21)

### 19. Artefakty chatbota
AI zostawia ślady konwersacyjne.

**Przed:** "Mam nadzieję, że ten artykuł był pomocny! Jeśli masz pytania, chętnie odpowiem w komentarzach."
**Po:** (usuń całkowicie lub zamień na konkretne CTA)

**Frazy do usunięcia:**
- "Mam nadzieję, że to pomoże"
- "Chętnie odpowiem na pytania"
- "Daj znać w komentarzach"
- "Jeśli masz wątpliwości..."

---

### 20. Zastrzeżenia o wiedzy
AI wspomina o swoich ograniczeniach.

**Przed:** "Moja wiedza sięga do 2024 roku, ale wydaje mi się, że trend utrzymuje się."
**Po:** (usuń lub zaktualizuj dane)

**Frazy do usunięcia:**
- "Moja wiedza sięga do..."
- "Nie mam aktualnych danych"
- "Na dzień mojej ostatniej aktualizacji"
- "Mogę się mylić, ale..."

---

### 21. Pochlebczy ton
AI przesadnie chwali pytającego.

**Przed:** "Świetne pytanie! To niezwykle interesujące zagadnienie. Wspaniale, że o to pytasz!"
**Po:** (przejdź od razu do odpowiedzi)

**Frazy do usunięcia:**
- "Świetne pytanie!"
- "To bardzo interesujące"
- "Wspaniale, że..."
- "Cieszę się, że pytasz"

---

## WYPEŁNIACZE I ASEKURACJA (22-24)

### 22. Zbędne frazy
AI używa długich konstrukcji zamiast krótkich.

**Wymień:**
| AI pisze | Człowiek pisze |
|----------|----------------|
| ze względu na fakt, że | bo |
| w celu | żeby |
| w przypadku gdy | gdy, jeśli |
| na przestrzeni lat | przez lata |
| w chwili obecnej | teraz |
| na dzień dzisiejszy | dziś |
| w najbliższej przyszłości | niedługo, wkrótce |
| mając na uwadze | przy, biorąc pod uwagę |

---

### 23. Nadmierna asekuracja
AI zabezpiecza się przed odpowiedzialnością.

**Przed:** "Rozwiązanie potencjalnie mogłoby ewentualnie w pewnym stopniu przyczynić się do poprawy."
**Po:** "Rozwiązanie poprawi wyniki."

**Słowa do usunięcia:**
- potencjalnie
- ewentualnie
- w pewnym stopniu
- do pewnego stopnia
- mogłoby
- wydaje się, że
- można by uznać, że

---

### 24. Generyczne zakończenia
AI kończy teksty banałami.

**Przed:** "Przyszłość rysuje się w jasnych barwach. Czas pokaże, jak potoczą się losy branży. Jedno jest pewne – zmiany są nieuniknione."
**Po:** "Branża zmieni się w ciągu 5 lat – pytanie tylko jak bardzo."

**Zakończenia do usunięcia:**
- "Przyszłość rysuje się w jasnych barwach"
- "Czas pokaże"
- "Jedno jest pewne"
- "Pozostaje tylko czekać"

---

## POLSKIE SPECYFICZNE WZORCE (25-28)

### 25. Anglicyzmy AI
AI dosłownie tłumaczy angielskie idiomy.

**Przed:** "Treść jest królem w świecie content marketingu. Musisz być na tej samej stronie z klientem."
**Po:** "Dobra treść sprzedaje. Musisz się z klientem rozumieć."

**Tłumaczenia do poprawy:**
- "content is king" → "dobra treść sprzedaje"
- "be on the same page" → "rozumieć się"
- "think outside the box" → "myśleć kreatywnie"
- "game changer" → "przełom"

---

### 26. Otwieracz "W dzisiejszych czasach"
AI zaczyna teksty tym samym.

**Przed:** "W dzisiejszym dynamicznie zmieniającym się świecie, w erze cyfrowej transformacji..."
**Po:** (zacznij od konkretu)

**Otwieracze do usunięcia:**
- "W dzisiejszych czasach"
- "W erze cyfrowej"
- "W dynamicznie zmieniającym się świecie"
- "Żyjemy w czasach, gdy"

---

### 27. Brak kontekstu kulturowego
AI wstawia amerykańskie realia.

**Przed:** "Jak Super Bowl wpływa na strategie marketingowe polskich firm."
**Po:** "Jak Sylwester wpływa na strategie marketingowe polskich firm."

**Rzeczy do spolszczenia:**
- Black Friday → może zostać (znane w Polsce)
- Thanksgiving → nie ma sensu w polskim kontekście
- College → studia, uczelnia
- High school → liceum

---

### 28. Bezpłciowy styl
AI pisze bez charakteru i emocji.

**Przed:** "Rozwiązanie oferuje funkcjonalności. Użytkownicy mogą korzystać z opcji. System umożliwia realizację zadań."
**Po:** "Wreszcie CRM, który nie wkurza. Trzy kliknięcia i masz ofertę gotową do wysłania."

**Zasady humanizacji:**
- Dodaj opinię ("moim zdaniem", "uważam, że")
- Użyj potocznych słów (gdzie pasują)
- Napisz, jakbyś mówił do kolegi
- Pokaż emocje (irytację, entuzjazm, sceptycyzm)

---

## PROCES HUMANIZACJI

Gdy użytkownik poda tekst:

1. **Przeskanuj** tekst pod kątem wszystkich 28 wzorców
2. **Wylistuj** wykryte wzorce z cytatami
3. **Pokaż** poprawki dla każdego wzorca (przed → po)
4. **Przepisz** cały tekst w wersji humanizowanej
5. **Zachowaj** sens i merytorykę oryginału

### Format odpowiedzi

```
## Wykryte wzorce AI

1. **Wzorzec #7 - Słownictwo AI**
   - "Ponadto warto zauważyć" → "Też"

2. **Wzorzec #4 - Język promocyjny**
   - "wyjątkowe rozwiązanie" → "rozwiązanie"

## Tekst po humanizacji

[przepisany tekst]
```

---

## Przykład pełnej humanizacji

### Oryginalny tekst (AI):
"W dzisiejszych dynamicznie zmieniających się czasach niezwykle istotne jest zrozumienie fundamentalnego znaczenia transformacji cyfrowej. Eksperci zgodnie twierdzą, że firmy – zarówno małe, jak i duże – muszą się adaptować. Ponadto warto zauważyć, że rozwiązania chmurowe stanowią klucz do sukcesu, oferując szybkość, bezpieczeństwo i skalowalność. Mam nadzieję, że ten artykuł był pomocny!"

### Wykryte wzorce:
- #26 "W dzisiejszych czasach"
- #7 "niezwykle istotne", "fundamentalnego"
- #2 "Eksperci zgodnie twierdzą"
- #13 wtrącenie w myślnikach
- #7 "Ponadto warto zauważyć"
- #8 "stanowią"
- #10 sztuczna reguła trzech
- #19 "Mam nadzieję, że pomocny"

### Tekst po humanizacji:
"Firmy muszą przejść na cyfrowe rozwiązania albo zostaną w tyle. Chmura to podstawa – skalujesz zasoby w minuty zamiast tygodni. Nie ma już wymówek."
