# Polski Humanizer

Skill do Claude Code usuwający charakterystyczne ślady pisania AI z polskich tekstów.

## Trigger
Użyj tego skilla gdy użytkownik poprosi o:
- `/humanizer-pl` - uruchom analizę i poprawę tekstu
- "humanizuj tekst", "popraw styl AI", "usuń ślady AI"

## Instrukcje dla Claude

Gdy otrzymasz tekst do humanizacji:

1. **Zidentyfikuj wzorce AI** - przeanalizuj tekst pod kątem 37 wzorców opisanych poniżej
2. **Zaproponuj poprawki** - dla każdego wykrytego wzorca pokaż wersję przed/po
3. **Przepisz tekst** - dostarcz pełną wersję po humanizacji
4. **Zachowaj sens** - nie zmieniaj merytoryki, tylko styl

## Osobowość tekstu po humanizacji

Tekst humanizowany powinien brzmieć jak napisany przez:
- Kompetentnego specjalistę (nie chatbota)
- Osobę z charakterem i opinią
- Kogoś kto pisze zwięźle i konkretnie
- Polaka piszącego naturalnie po polsku (nie tłumaczącego z angielskiego)
- Osobę która pisze różnym rytmem - krótkie zdania przeplatane długimi
- Kogoś kto ma poczucie humoru i używa ironii tam gdzie pasuje
- Specjalistę który podaje konkrety - daty, liczby, nazwy
- Polaka z polską powściągliwością, nie amerykańskim entuzjazmem

---

# 37 POLSKICH WZORCÓW PISANIA AI

## WZORCE TREŚCI (1-7)

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

### 7. Nadmierna wyważoność
AI zawsze prezentuje "obie strony" nawet gdy jedna jest oczywista.

**Przed:** "Z jednej strony rozwiązanie ma wiele zalet, z drugiej strony istnieją również pewne wady i ograniczenia, które należy wziąć pod uwagę."
**Po:** "Rozwiązanie działa, choć instalacja mogłaby być prostsza."

**Konstrukcje do ograniczenia:**
- "Z jednej strony... z drugiej strony..."
- "Ma zarówno zalety, jak i wady"
- "Nie jest pozbawione pewnych ograniczeń"

**Zasada:** Zajmij stanowisko. Nie wszystko wymaga równoważenia argumentów.

---

## WZORCE JĘZYKOWE (8-14)

### 8. Słownictwo charakterystyczne dla AI
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

### 9. Unikanie słowa "jest"
AI nadużywa synonimów "jest".

**Przed:** "Firma stanowi lidera rynku, pełni rolę innowatora i charakteryzuje się elastycznością."
**Po:** "Firma jest liderem rynku i szybko się adaptuje."

**Konstrukcje do uproszczenia:**
- "stanowi" → "jest"
- "pełni rolę" → "jest"
- "charakteryzuje się" → "jest", "ma"
- "wyróżnia się" → "jest", "ma"

---

### 10. Negatywne paralelizmy
AI uwielbia "nie tylko X, ale także Y".

**Przed:** "To nie tylko narzędzie, to także filozofia. Nie chodzi wyłącznie o zysk, ale przede wszystkim o wartości."
**Po:** "Narzędzie opiera się na wartościach, nie tylko zysku."

**Konstrukcje do ograniczenia:**
- "To nie tylko X, to także Y"
- "Nie chodzi wyłącznie o X"
- "To znacznie więcej niż tylko"

---

### 11. Reguła trzech
AI wymusza listy trzech elementów.

**Przed:** "Platforma oferuje szybkość, niezawodność i skalowalność. Zapewnia bezpieczeństwo, wygodę i elastyczność."
**Po:** "Platforma jest szybka i niezawodna. Łatwo ją skalować."

**Uwaga:** Jeśli naprawdę są trzy równie ważne elementy - OK. Ale AI dodaje trzeci element "na siłę".

---

### 12. Cyklowanie synonimów
AI powtarza to samo innymi słowami.

**Przed:** "System jest wydajny, efektywny i produktywny. Oferuje szybkość, prędkość działania i sprawność."
**Po:** "System działa szybko."

**Diagnoza:** Jeśli usunięcie słowa nie zmienia sensu zdania - usuń je.

---

### 13. Fałszywe zakresy
AI wymusza konstrukcje "od X do Y".

**Przed:** "Rozwiązanie sprawdza się w firmach od małych startupów po duże korporacje, od branży IT po sektor finansowy."
**Po:** "Rozwiązanie działa w firmach każdej wielkości."

**Konstrukcje do uproszczenia:**
- "od X do Y" → często wystarczy "różne" lub "wszystkie"
- "począwszy od X, a skończywszy na Y"

---

### 14. Strona bierna i konstrukcje bezosobowe
AI nadużywa formy bezosobowej i strony biernej.

**Przed:** "Można zaobserwować, że wyniki uległy poprawie. Należy zauważyć, iż da się dostrzec rosnący trend."
**Po:** "Wyniki się poprawiły. Trend rośnie."

**Konstrukcje do zamiany:**
| AI pisze | Człowiek pisze |
|----------|---------------|
| Można zaobserwować | Widać |
| Należy zauważyć | (usuń) |
| Warto podkreślić | (usuń lub: Ważne:) |
| Da się dostrzec | Widać, jest |
| Zostało osiągnięte | Osiągnęliśmy |
| Uległo poprawie | Poprawiło się |

---

## WZORCE STYLU (15-20)

### 15. Nadużycie myślników
AI wtrąca za dużo dygresji.

**Przed:** "Firma – założona w 2020 roku – oferuje rozwiązania – głównie dla sektora MŚP – które pomagają – co warto podkreślić – w automatyzacji."
**Po:** "Firma założona w 2020 oferuje automatyzację dla MŚP."

**Zasada:** Maksymalnie jedno wtrącenie w myślnikach na akapit.

---

### 16. Nadużycie pogrubień
AI pogrubia co drugie słowo.

**Przed:** "Nasze **innowacyjne** rozwiązanie oferuje **wyjątkową** jakość i **niezrównaną** wydajność."
**Po:** "Nasze rozwiązanie oferuje wysoką jakość i wydajność."

**Zasada:** Pogrubiaj tylko to, co naprawdę wymaga uwagi (1-2 słowa na akapit).

---

### 17. Listy z nagłówkami
AI robi nagłówek z każdego punktu.

**Przed:**
- **Szybkość:** System działa szybko
- **Niezawodność:** System jest niezawodny
- **Bezpieczeństwo:** System jest bezpieczny

**Po:**
- System działa szybko i niezawodnie
- Dane są szyfrowane end-to-end

---

### 18. Wielkie Litery W Nagłówkach
Angielski styl w polskim tekście.

**Przed:** "Jak Skutecznie Zarządzać Zespołem W Erze Cyfrowej"
**Po:** "Jak skutecznie zarządzać zespołem w erze cyfrowej"

**Zasada:** Po polsku wielką literą piszemy tylko pierwszy wyraz nagłówka.

---

### 19. Emoji w tekście
AI rozsypuje emoji jak konfetti.

**Przed:** "Nasz produkt jest szybki 🚀, bezpieczny 🔒 i innowacyjny ✨! Zapraszamy 🔥💪"
**Po:** "Nasz produkt jest szybki, bezpieczny i nowoczesny."

**Zasada:** Emoji są OK w social media, nie w profesjonalnym tekście.

---

### 20. CamelCase w hashtagach
Angielski styl w polskich hashtagach.

**Przed:** "#TworzenieTreści #ZarządzanieProjektem #TransformacjaCyfrowa"
**Po:** "#tworzenietresci #zarzadzanieprojektem #transformacjacyfrowa"

**Zasada:** Polskie hashtagi małymi literami (CamelCase to konwencja angielska).

---

## WZORCE KOMUNIKACJI (21-23)

### 21. Artefakty chatbota
AI zostawia ślady konwersacyjne.

**Przed:** "Mam nadzieję, że ten artykuł był pomocny! Jeśli masz pytania, chętnie odpowiem w komentarzach."
**Po:** (usuń całkowicie lub zamień na konkretne CTA)

**Frazy do usunięcia:**
- "Mam nadzieję, że to pomoże"
- "Chętnie odpowiem na pytania"
- "Daj znać w komentarzach"
- "Jeśli masz wątpliwości..."

---

### 22. Zastrzeżenia o wiedzy
AI wspomina o swoich ograniczeniach.

**Przed:** "Moja wiedza sięga do 2024 roku, ale wydaje mi się, że trend utrzymuje się."
**Po:** (usuń lub zaktualizuj dane)

**Frazy do usunięcia:**
- "Moja wiedza sięga do..."
- "Nie mam aktualnych danych"
- "Na dzień mojej ostatniej aktualizacji"
- "Mogę się mylić, ale..."

---

### 23. Pochlebczy ton
AI przesadnie chwali pytającego.

**Przed:** "Świetne pytanie! To niezwykle interesujące zagadnienie. Wspaniale, że o to pytasz!"
**Po:** (przejdź od razu do odpowiedzi)

**Frazy do usunięcia:**
- "Świetne pytanie!"
- "To bardzo interesujące"
- "Wspaniale, że..."
- "Cieszę się, że pytasz"

---

## WYPEŁNIACZE I ASEKURACJA (24-26)

### 24. Zbędne frazy
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

### 25. Nadmierna asekuracja
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

### 26. Generyczne zakończenia
AI kończy teksty banałami.

**Przed:** "Przyszłość rysuje się w jasnych barwach. Czas pokaże, jak potoczą się losy branży. Jedno jest pewne – zmiany są nieuniknione."
**Po:** "Branża zmieni się w ciągu 5 lat – pytanie tylko jak bardzo."

**Zakończenia do usunięcia:**
- "Przyszłość rysuje się w jasnych barwach"
- "Czas pokaże"
- "Jedno jest pewne"
- "Pozostaje tylko czekać"

---

## POLSKIE SPECYFICZNE WZORCE (27-33)

### 27. Anglicyzmy AI
AI dosłownie tłumaczy angielskie idiomy.

**Przed:** "Treść jest królem w świecie content marketingu. Musisz być na tej samej stronie z klientem."
**Po:** "Dobra treść sprzedaje. Musisz się z klientem rozumieć."

**Tłumaczenia do poprawy:**
- "content is king" → "dobra treść sprzedaje"
- "be on the same page" → "rozumieć się"
- "think outside the box" → "myśleć kreatywnie"
- "game changer" → "przełom"

---

### 28. Otwieracz "W dzisiejszych czasach"
AI zaczyna teksty tym samym.

**Przed:** "W dzisiejszym dynamicznie zmieniającym się świecie, w erze cyfrowej transformacji..."
**Po:** (zacznij od konkretu)

**Otwieracze do usunięcia:**
- "W dzisiejszych czasach"
- "W erze cyfrowej"
- "W dynamicznie zmieniającym się świecie"
- "Żyjemy w czasach, gdy"

---

### 29. Brak kontekstu kulturowego
AI wstawia amerykańskie realia.

**Przed:** "Jak Super Bowl wpływa na strategie marketingowe polskich firm."
**Po:** "Jak Sylwester wpływa na strategie marketingowe polskich firm."

**Rzeczy do spolszczenia:**
- Black Friday → może zostać (znane w Polsce)
- Thanksgiving → nie ma sensu w polskim kontekście
- College → studia, uczelnia
- High school → liceum

---

### 30. Bezpłciowy styl - brak opinii i emocji
AI pisze bez charakteru, stanowiska i emocji.

**Przed:** "Rozwiązanie oferuje funkcjonalności. Użytkownicy mogą korzystać z opcji. System umożliwia realizację zadań."
**Po:** "Wreszcie CRM, który nie wkurza. Trzy kliknięcia i masz ofertę gotową do wysłania."

**Zasady humanizacji:**
- Dodaj opinię ("moim zdaniem", "uważam, że")
- Użyj potocznych słów (gdzie pasują)
- Napisz, jakbyś mówił do kolegi
- Pokaż emocje (irytację, entuzjazm, sceptycyzm)
- Pozwól sobie na suche poczucie humoru

---

### 31. Brak konkretu
AI używa generycznych przykładów, okrągłych liczb, nienazwanych źródeł.

**Przed:** "Wiele firm odniosło sukces dzięki temu podejściu. Wyniki były imponujące."
**Po:** "InPost zaczynał od 2000 paczkomatów w 2014. Teraz ma 20 000."

**Zasady:**
- Podaj konkretne daty, liczby, nazwy
- Zamiast "wiele firm" - nazwy firm
- Zamiast "duży wzrost" - "wzrost o 34%"
- Zamiast "eksperci" - imię i stanowisko
- Jeśli nie masz konkretów - napisz mniej, ale prawdziwie

---

### 32. Amerykański entuzjazm
AI defaultuje do amerykańskiej egzaltacji. Polacy tak nie piszą.

**Przed:** "To niesamowite rozwiązanie, które rewolucjonizuje branżę! Ekscytujące możliwości!"
**Po:** "Niezłe rozwiązanie. Robi to, co obiecuje."

**Słowa do stonowania:**
| AI pisze | Człowiek pisze |
|----------|---------------|
| Niesamowite! | Niezłe |
| Fantastyczne! | Dobre |
| Ekscytujące! | Ciekawe |
| Rewolucjonizuje! | Zmienia, upraszcza |
| Absolutnie fenomenalne | (usuń, napisz co konkretnie) |

**Zasada:** Polska komunikacja jest powściągliwa. Understatement > hiperbola.

---

### 33. Przecinki po angielsku
AI stosuje angielskie reguły interpunkcji w polskim tekście.

**Przed:** "Dodatkowo, firma oferuje szkolenia, warsztaty, i konsultacje."
**Po:** "Firma oferuje też szkolenia, warsztaty i konsultacje."

**Błędy do poprawy:**
- Przecinek po przysłówku na początku zdania ("Dodatkowo," "Ponadto," "Jednakże,") - w polskim często zbędny
- Oxford comma przed "i" - w polskim nie stosujemy
- Przecinek przed "który/która" - w polskim zawsze jest (AI czasem pomija)
- Przecinek przed "że" - w polskim zawsze jest (AI czasem pomija)

---

## WZORCE RYTMU I STRUKTURY (34-37)

### 34. Monotonny rytm zdań
**NAJWAŻNIEJSZY SYGNAŁ DLA DETEKTORÓW AI.** AI pisze zdania 15-25 słów z minimalną wariacją. Człowiek miesza krótkie (3-5 słów) z długimi (25-40 słów).

**Przed:** "System oferuje wiele funkcji. Użytkownicy mogą korzystać z dashboardu. Raporty generowane są automatycznie. Integracja z innymi narzędziami jest prosta."
**Po:** "System ma wszystko. Dashboard, automatyczne raporty, integracje - działa od razu po wdrożeniu, bez zabawy w konfigurację."

**Diagnoza:** Policz słowa w każdym zdaniu. Jeśli odchylenie standardowe < 5 słów - tekst brzmi jak AI.

**Zasady:**
- Mieszaj krótkie zdania (3-5 słów) z długimi (20-35 słów)
- Używaj zdań jednowyrazowych. Serio.
- Po 2-3 zdaniach średnich wstaw jedno bardzo krótkie lub bardzo długie

---

### 35. Monotonna długość akapitów
AI pisze każdy akapit 3-5 zdań, podobnej długości. Człowiek pisze akapit jednozdaniowy obok ośmiozdaniowego.

**Przed:** (każdy akapit 3-4 zdania, 50-70 słów)
**Po:** Zróżnicuj. Czasem jeden akapit to jedno zdanie. Następny może mieć sześć.

**Zasada:** Jeśli wszystkie akapity mają podobną długość - przepisz. Jeden akapit = jedno zdanie jest OK.

---

### 36. Szablonowa struktura akapitów
AI: zdanie wprowadzające → argument → podsumowanie. Każdy akapit. Ten sam schemat.

**Przed:** "Automatyzacja jest ważna. Firmy korzystające z automatyzacji osiągają lepsze wyniki. Dlatego warto inwestować w automatyzację."
**Po:** "Dlaczego firmy wciąż robią to ręcznie? Automatyzacja jest od lat i kosztuje grosze."

**Zasady:**
- Zacznij od pytania
- Zacznij od środka myśli
- Zakończ pytaniem zamiast podsumowania
- Usuń zdanie podsumowujące jeśli powtarza wstęp

---

### 37. Idealna gramatyka
AI pisze tekst bez błędów, fragmentów, potocznych skrótów. Prawdziwy polski tekst ma naturalne niedoskonałości.

**Przed:** "Należy rozważyć, czy proponowane rozwiązanie spełnia wszystkie wymagania."
**Po:** "Czemu? Bo działa. A reszta - dogadamy po wdrożeniu."

**Zasady:**
- Użyj fragmentów zdań. Świadomie.
- "Czemu? Bo działa." jest bardziej ludzkie niż idealne zdania
- Zdania jednosłowowe są OK: "Dokładnie.", "Właśnie.", "Nie."
- Nie bój się kolokwializmów: "fajnie", "no i co z tego", "da się"

---

## PROCES HUMANIZACJI

Gdy użytkownik poda tekst:

1. **Przeskanuj** tekst pod kątem wszystkich 37 wzorców
2. **Wylistuj** wykryte wzorce z cytatami
3. **Pokaż** poprawki dla każdego wzorca (przed → po)
4. **Przepisz** cały tekst w wersji humanizowanej
5. **Sprawdź rytm (burstiness)** - policz słowa w każdym zdaniu przepisanego tekstu. Jeśli odchylenie standardowe < 5 słów, przepisz ponownie z większą wariacją.
6. **Sprawdź powtórzenia** - wyszukaj powtórzone słowa w sąsiadujących zdaniach (okno 2 zdań). Zamień synonimy lub przebuduj zdanie.
7. **Sprawdź spójność rejestru** - nie mieszaj ultraoficjalnego z potocznym w jednym akapicie. Cały tekst powinien mieć spójny rejestr (chyba że zmiana jest celowa).
8. **Zachowaj** sens i merytorykę oryginału

### Format odpowiedzi

```
## Wykryte wzorce AI

1. **Wzorzec #8 - Słownictwo AI**
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
- #28 "W dzisiejszych czasach"
- #8 "niezwykle istotne", "fundamentalnego"
- #2 "Eksperci zgodnie twierdzą"
- #15 wtrącenie w myślnikach
- #8 "Ponadto warto zauważyć"
- #9 "stanowią"
- #11 sztuczna reguła trzech
- #21 "Mam nadzieję, że pomocny"
- #34 monotonny rytm zdań (wszystkie zdania 12-18 słów)

### Tekst po humanizacji:
"Firmy muszą przejść na cyfrowe rozwiązania albo zostaną w tyle. Chmura to podstawa – skalujesz zasoby w minuty zamiast tygodni. Nie ma już wymówek."

---

## SZYBKA CHECKLISTA

Po humanizacji sprawdź:

- [ ] **Rytm zdań** - czy są krótkie (3-5 słów) i długie (20+ słów)? Nie same średnie.
- [ ] **Długość akapitów** - czy są różnej długości? Nie wszystkie 3-5 zdań.
- [ ] **Opinia** - czy tekst ma stanowisko? Czy autor coś uważa?
- [ ] **Konkrety** - czy są daty, liczby, nazwy? Czy można dodać?
- [ ] **Ton** - czy brzmi jak Polak? Nie jak przetłumaczony Amerykanin?
- [ ] **Powtórzenia** - czy to samo słowo nie pojawia się w sąsiadujących zdaniach?
- [ ] **Strona bierna** - czy można zamienić "można zaobserwować" na "widać"?
- [ ] **Rejestr** - czy styl jest spójny? Nie skacze z potocznego na urzędowy?
- [ ] **Początki** - czy tekst NIE zaczyna się od "W dzisiejszych czasach"?
- [ ] **Zakończenie** - czy NIE kończy się banałem o przyszłości?
