# CLAUDE.md — Projekt: Kredito (strona internetowa dla Moniki Buchacz)

> Baza wiedzy projektu. Używaj tego pliku jako kontekstu we wszystkich sesjach Claude Code. Ostatnia aktualizacja: 25.08.2026 | Prowadzący: Cezary Kutwin (Verseo)

---

## 1\. KLIENTKA

**Monika Buchacz** — pośrednik finansowy B2B, specjalizacja: pożyczki hipoteczne dla firm (nieruchomość jako zabezpieczenie).

- 20 lat doświadczenia na rynku  
- Dostęp do 30–40 instytucji (banki, fundusze, private debt, rynki zagraniczne m.in. Szwajcaria)  
- KNF: zarejestrowana  
- Model pracy: wyłącznie telefoniczny, bez spotkań stacjonarnych  
- Minimum ticket: **1 000 000 PLN**  
- Wstępna ocena sprawy: **2–3 minuty** przez telefon  
- Private debt: decyzja w **2 dni**, bez BIK, bez wizyty w banku

---

## 2\. NAZWA FIRMY (ROBOCZA)

**Kredito** — nazwa robocza zatwierdzona do pracy projektowej. Możliwa zmiana po konsultacji z klientką. Docelowy model: **"Kredito by Monika Buchacz"** → stopniowe wycofanie "by Monika" gdy marka nabierze rozpoznawalności.

**Aktualizacja 25.08.2026:** przygotowana short-lista nowych nazw (kredito.pl/credito.pl zajęte, brzmienie zbyt masowe): **Fineza / Rezolva / Kapitero** (wolne domeny .pl, brak kolizji) + zapas Findera, Credovia, Kredona. Szczegóły i uzasadnienia: `content-plan.md` §4. Decyzja: Monika po teście rynkowym.

---

## 3\. GRUPY DOCELOWE

### PRIMARY — Spółki i JDG

Firmy potrzebujące finansowania pod nieruchomość, min. 1M PLN. Szczególnie "trudne przypadki" odrzucone przez banki lub potrzebujące szybkiej decyzji.

### SECONDARY — Pośrednicy kredytowi

Brokerzy z klientem poza swoją kompetencją. Zgłaszają gotowego klienta: "Ej Monika, teraz ty coś zrób".

### FUTURE (Faza 2+) — Inwestorzy prywatni

Osoby z kapitałem szukające lokowania w private debt. Potencjalnie osobna spółka i strona — poza zakresem MVP.

---

## 4\. CEL STRONY GŁÓWNEJ

**Faza 1 (2026) — wizerunek, nie lead gen.** Monika ma nadmiar klientów. Strona \= legitymizacja i "oficjalny adres" dla istniejącej sieci kontaktów.

Cel dla użytkownika: przekonać właściwą firmę, że Kredito to ostatnia rozmowa jakiej potrzebują w sprawie finansowania — i skłonić do wykonania telefonu.

Formularz kontaktowy: tak, ale jako **narzędzie badawcze** (kto się zgłasza i z czym).

---

## 5\. NAWIGACJA STRONY

```
Logo (Kredito)
├── Strona główna
├── O firmie
├── Pożyczki hipoteczne
├── Oferta dla pośredników kredytowych
├── Oferta dla spółek
└── Kontakt
+ sticky CTA button: "Zadzwoń" / "Umów rozmowę"
```

---

## 6\. STRUKTURA STRONY GŁÓWNEJ — SEKCJE

| \# | Sekcja | Cel | Kategoria szablonu |
| :---- | :---- | :---- | :---- |
| 01 | Nawigacja | Sticky header, logo \+ menu \+ CTA | Sekcja nawigacyjna |
| 02 | Hero | Pierwsza sekunda decyzji, mocna headline, CTA | Sekcja otwierająca / hero |
| 03 | Kwalifikacja | 3 karty — filtr: "czy jesteś we właściwym miejscu?" | Sekcja oparte na kartach / boxach |
| 04 | Liczby / Unfair Advantage | 4 metryki z kontekstem: 20 lat, 30–40 instytucji, 2–3 min, 2 dni | Sekcja oparte na kartach / boxach |
| 05 | Private debt — wyróżnik | Kontrast: bank \= 2 tygodnie, Kredito \= 2 dni bez BIK | Sekcja tekstowe / treściowe |
| 06 | O Monice | Brand story, zdjęcie, kontrast z AI/chatbotami | Sekcja tekstowe / treściowe |
| 07 | Jak pracujemy | 4 kroki procesu, klient nie biega po urzędach | Sekcja list / procesów |
| 08 | Social proof | Testimoniale lub case studies trudnych spraw | Sekcja listmonów / rateów |
| 09 | Dla pośredników | Teaser B2B2B, CTA do podstrony | Sekcja CTA-formularz |
| 10 | Kontakt | Formularz \+ telefon, ton: "Poznajmy się" | Sekcja kontaktowe |
| 11 | Footer | Logo, linki, KNF info, dane, copyright | Footery |

---

## 7\. SITEMAP — PEŁNA STRONA

### MVP (2026)

- Strona główna  
- O firmie  
- Pożyczki hipoteczne  
- Oferta dla pośredników kredytowych  
- Oferta dla spółek  
- Kontakt

### Faza 2 (2027+)

- Kredyty dla firm \+ kalkulator  
- Blog / FAQ rozbudowane  
- CRM, lejki sprzedażowe  
- Chatbot / Smart Sub / Voice Chat  
- Inwestorzy (osobna strona / spółka)

---

## 8\. IDENTYFIKACJA WIZUALNA

### Paleta kolorów — Wersja A (zatwierdzona)

- Dominanta: **głęboki burgund → ciemna czekolada → ciemny brąz**  
- Akcent: ciepły pomarańcz (\#FF6B35 orientacyjnie)  
- Tło: bardzo ciemne (near-black)  
- **ODRZUCONE:** niebieski ("zamknijmy tę stronę" — decyzja Moniki)  
- **UNIKAĆ:** dokładna paleta Mastercard (czerwień \+ żółty razem)

### Typografia (z moodboardów FigJam)

- Font 1 (primary): styl "unearth" — cienki, elegancki sans-serif  
- Font 2 (secondary): styl "Reason Enough" — bardziej seryfowy, editorial  
- Dwa fonty w kombinacji

### Logo — kierunki do propozycji

1. **Logotyp z akcentem** (NOBU-style) — czysta typografia, jeden wyróżniony element w literze  
2. **Logotyp \+ symbol** — abstrakcyjna marka graficzna (kompas, węzeł, strzałka) \+ logotyp  
3. **Wordmark z gradientem** — ciepły gradient wpisany w liternictwo

### Styl ogólny

- Premium, boutique, B2B  
- Minimalistyczny z WOW effectem i animacjami scroll  
- NIE bankowy, NIE korporacyjny-chłodny  
- Energia \+ klasa (Monika: "jestem osobą energiczną")

---

## 9\. WARTOŚCI MARKI

| Wartość | Znaczenie |
| :---- | :---- |
| Niezależność | 30–40 instytucji, nie na pasku jednego banku |
| Nieustępliwość | Doprowadzanie spraw do końca, tam gdzie inni odpuszczają |
| Ambicja | Skalowanie, nowe instrumenty, ciągła nauka |
| Relacje | Klienci od 20 lat, ludzki kontakt, AI-proof |
| Wiedza | 20 lat know-how, relacje z decydentami (nie infoliniami) |

### Antywartości

- Pasywność  
- Zostawianie bez rozwiązania  
- Niekorzystne rozwiązania dla klienta

### Misja

> Rozwiązywanie trudnych spraw kredytowych, dzielenie się doświadczeniem tam, gdzie inni pośrednicy rozkładają ręce.

### Wizja

> Rynek, na którym przedsiębiorcy świadomie i chętnie korzystają z dostępnych możliwości finansowania. Wiedzą, że dzięki naszej pomocy mądre zarządzanie finansami przypomina układanie puzzli.

---

## 10\. ARCHETYPY MARKI

| Archetyp | Rola | Priorytet |
| :---- | :---- | :---- |
| 🦸 Superbohater | Gdzie inni się poddali, tu jest odpowiedź | PRIMARY |
| 🪄 Czarodziej | Finansowa kompleksowość staje się prosta | PRIMARY |
| 🦉 Mędrzec | 20 lat wiedzy i kompetencji | wspierający |
| 🧭 Odkrywca | Odwaga, nowe rynki, "pieprz" w komunikacji | wspierający |
| 👑 Władca | Premium, selektywność, klasa | wspierający |

---

## 11\. TONE OF VOICE

### TAK — pisz tak

- Pewny siebie, stwierdza (nie pyta)  
- Ekspercki ale ludzki — rozmawia, nie wykłada  
- Bezpośredni, jak w rozmowie telefonicznej  
- Konkretny — liczby, fakty, nie ogólniki  
- Premium — nie masowy, nie dyskontowy  
- Trochę odważny / "pieprz" odkrywcy

### NIE — unikaj

- "Oferujemy kompleksowe rozwiązania finansowe"  
- Korporacyjny chłód bez konkretów  
- Nadmiar żargonu technicznego  
- "Profesjonalny" jako główny wyróżnik  
- KNF jako główna przewaga (to minimum, nie wyróżnik)

---

## 12\. KLUCZOWE PRZEWAGI (UNFAIR ADVANTAGES)

1. **20 lat relacji** z decydentami w bankach (nie z infoliniami)  
2. **30–40 instytucji** vs 3–4 u przeciętnego brokera  
3. **2–3 minuty** — wstępna ocena przy pierwszym telefonie  
4. **2 dni** — decyzja o finansowaniu przez private debt (bez BIK, bez wizyty)  
5. **"Niemożliwe przypadki"** — specjalizacja w sprawach odrzuconych gdzie indziej  
6. **Ludzki kontakt** — kontrast z AI i chatbotami

---

## 13\. PYTANIA DO KLIENTKI (przed copywritingiem)

Kluczowe pytania, które muszą zostać zadane Monice zanim powstaną teksty:

1. Czy "Kredito" to zatwierdzona nazwa? (blokuje logo i copy)  
2. Jak chce się tytułować? ("pośrednik finansowy", "ekspert finansowy"?)  
3. Jedno zdanie opisujące co robi — jak mówi o sobie na ulicy  
4. Dosłowne słowa klientów przy pierwszym kontakcie (złoto dla headline'a)  
5. Co ją wyróżnia — jednym zdaniem, bez owijania w bawełnę  
6. Czy mówić wprost "minimum milion"?  
7. Dlaczego 20 lat temu wybrała tę branżę?  
8. Jedna historia anonimizowana: sprawa uratowana gdy inni odpuścili  
9. Czego klienci NIE spodziewają się po pierwszej rozmowie  
10. Jak wyjaśnia różnicę pożyczka hipoteczna vs kredyt bankowy  
11. Jak wyjaśnia private debt (2 dni, bez BIK) żeby klient nie uciekł  
12. Lista wymagań wejściowych (do sekcji kwalifikacji)  
13. Co oferuje pośrednikom kredytowym  
14. Czy ma 2–3 klientów chętnych do testimoniali?  
15. Co klienci mówią po zakończonej sprawie (SMS, mail?)  
16. Ile spraw obsłużyła przez 20 lat / ile miesięcznie teraz  
17. Jak szybko oddzwania — czy możemy dać obietnicę na stronie  
18. Jakie pola potrzebuje w formularzu  
19. Czy numer telefonu ma być publicznie widoczny

---

## 14\. DECYZJE TECHNICZNE (MVP)

| Element | Decyzja |
| :---- | :---- |
| Formularz kontaktowy | TAK — narzędzie badawcze |
| Kalkulatory | NIE (Faza 2\) |
| Chatbot | NIE (Faza 2\) |
| CRM | NIE (Faza 2\) |
| Blog | NIE (Faza 2\) |
| Wersje językowe | NIE na start |
| Sesja zdjęciowa Moniki | Po ustaleniu strategii |

---

## 15\. FAZY PROJEKTU

### Faza 1 — 2026 (bieżący projekt)

Cel: wizerunek, legitimizacja, fundament marki Zakres: strona główna \+ 5 podstron MVP

### Faza 2 — 2027+

Cel: lead gen, skala, kampanie Zakres: SEO, lejki, kalkulatory, CRM, doradcy online

---

## 16\. KONKURENCJA — INSPIRACJE STRON

### Bezpośredni rynek (private debt / broker B2B PL)

- [Private Debt Partners](https://www.pdpartners.pl/) — najbliższy competitor  
- [Direct Debt](https://directdebt.pl/) — B2B, pożyczki pod nieruchomości

### Masowi brokerzy (czego NIE robić)

- [Expander](https://expander.pl/)  
- [Notus Finanse](https://notus.pl/)  
- [mFinanse](https://mfinanse.pl/)  
- [Credipass](https://credipass.pl/)

### Design inspiration

- [Awwwards — Business/Corporate](https://www.awwwards.com/websites/business-corporate/)  
- [Behance — Investment Broker](https://www.behance.net/search/projects/investment%20broker)  
- [Behance — Financial Website Design](https://www.behance.net/search/projects/financial%20website%20design)

---

## 17\. PLIKI PROJEKTU

| Plik | Zawartość |
| :---- | :---- |
| `content-plan.md` | **PLAN TREŚCI CAŁEGO SERWISU** (25.08.2026) — docelowe copy wszystkich sekcji i podstron, propozycje nazw, wytyczne wizualne, pytania otwarte |
| `hero-e.html` | **GŁÓWNY PLIK ROBOCZY** — strona główna MVP (single-file HTML) |
| `index.html` | **Live homepage na Vercelu: https://czarkovsky1-mbuchacz.vercel.app/** (projekt Vercel `czarkovsky1-mbuchacz`, od 21.10.2026) — kopia `home3.html`. Zmiany rób w `home3.html` i kopiuj do `index.html` przed deployem (push na `master` = deploy produkcyjny). Do repo podpięty jest też starszy projekt `mbuchacz` (mbuchacz.vercel.app) — też deployuje z `master`, ale 21.10 aktualizował się z dużym opóźnieniem; główny link do pracy = czarkovsky1-mbuchacz |
| `home3.html` | Strona główna "Monolith Finance" 1:1 z Figmy (`2bbo1vBni1ROFxluOJqlTY`, node `1:4`), 06.10.2026. Assety w `assets/home3/`, formularz = makieta. Podgląd: `.claude/launch.json` → `monika-static-site` (port 8090) |
| `kontakt3.html` | Podstrona "Kontakt" z Figmy (node `4:689`), 06.10.2026. Linkowana z przycisku "Umów rozmowę" i stopki "Kontakt". **Nie mylić z `kontakt.html`** — to podstrona starszej wersji (`home2`) |
| `o-mnie.html` | Podstrona "O mnie" — od 21.10.2026 przebudowana wg monolith-finance.pl (oś kompetencji, wartości, CTA) |
| `pozyczki-hipoteczne.html`, `dla-spolek-i-jdg.html`, `private-debt.html`, `dla-posrednikow-kredytowych.html` | "Strona w przygotowaniu" — jak na monolith-finance.pl (21.10.2026). Menu "Współpraca" → `dla-posrednikow-kredytowych.html` |
| `polityka-prywatnosci.html` | Polityka prywatności 1:1 z monolith-finance.pl (21.10.2026) |
| `pozyczki1.html` … `pozyczki4.html` | **Warianty podstrony „Pożyczki hipoteczne” do oceny** — od 27.10.2026 kompletne: cała treść Google Doc klienta (`1r1ZhNMFH_2R6zI8tABK8I0ClPRMEbTFu1SNFurExpg0`) w 9 sekcjach (hero, finansowanie + metryki, przeznaczenie środków, rodzaje nieruchomości, LTV, BIK/KRD, proces + CTA, FAQ, kontakt `#kontakt` z formularzem-makietą: kwota, rodzaj, lokalizacja, wartość nieruchomości). 1 = kontynuacja systemu, 2 = sprzedaż, 3 = premium, 4 = połączenie (rekomendowany). Teksty 1:1 (jedyna korekta: „pod uwagę bierzemy również”), `noindex`, pływający przełącznik wariantów. Tymczasowe linki „Pożyczki1–5” w stopce `home3`/`index` — usunąć po wyborze; wybrany wariant przenieść do `pozyczki-hipoteczne.html` (zdjąć `noindex`, przełącznik, title „Pożyczki hipoteczne \| Monolith Finance”) |
| `pozyczki5.html` | **Wariant złożony z wyboru Cezarego (29.10.2026)** — kandydat na finalną podstronę „Pożyczki hipoteczne”. Hero jak w `private-debt1` (zielone „Umów rozmowę” + obrys „Zadzwoń”). Z `pozyczki2` (zmiana 29.10, 2. runda): „Finansowanie zabezpieczone nieruchomością” — tekst + biała karta z 3 metrykami na złotej płycie, znaki przy liczbach zmniejszone 25 → 18 px (16 px na telefonie), przycisk obrysowy. Z `pozyczki3`: „Na co możesz przeznaczyć środki?” (znaki 22 px, bez złotej linii łączącej, hover linii biały), kafelek obok zdjęcia bez ikony, nagłówek 18 px, tekst od górnej krawędzi z paddingiem 20 px: „W przypadku spłaty zobowiązań istotny jest realny plan spłaty.” (tekst od Cezarego, przecinek po „zobowiązań” usunięty), LTV bez paska i bez znaku w białej karcie, BIK/KRD (oba przyciski obrysowe) i proces. Z `pozyczki4`: karty nieruchomości (zdanie o stanie prawnym jako sam tekst na tle, bez karty) i biały box CTA — bez paska zdjęcia przed nim. FAQ jak w `kontakt3` (jedna kolumna, bez przycisków). Kontakt: tekst z dokumentu + formularz 1:1 ze strony głównej (od 29.10 — wcześniej jasna karta z polami nieruchomości i „Umów rozmowę”). Odstępy ujednolicone 29.10 (jak w `private-debt3`): padding sekcji `--sec` 120 px (≤1024: 96, ≤680: 72), między treściami sąsiednich sekcji 2 × `--sec`, intro pod hero ma u góry 2 × `--sec`; dawne osobne paddingi procesu (140/160 px) i BIK/KRD (150 px) zastąpione `--sec` (na telefonie BIK/KRD zostaje 236 px u góry na zdjęcie) |
| `spolki1.html`, `spolki2.html` | **Warianty podstrony „Dla spółek i JDG” do oceny** (27.10.2026) — treść 1:1 z Google Doc klienta (`1EaSmonpG1e3pjQlMlvBxUqjCdPrdhX5Z1r4hpn8ekT8`): hero, finansowanie dopasowane, „Z czym możesz się do nas zgłosić?” + callout, możliwości (5), „Masz już finansowanie?”, Spółka czy JDG, współpraca (3 kroki), FAQ, kontakt `#kontakt` z formularzem-makietą (forma działalności, cel, kwota, notatka). 1 = klasyczny (blisko pozyczki4), 2 = sprzedażowy/premium. `noindex`, przełącznik wariantów, tymczasowe linki „Spółki1–2” w stopce `home3`/`index`. Po wyborze: przenieść do `dla-spolek-i-jdg.html` jak przy pożyczkach. **27.10.2026:** w `spolki2` sekcja „Jakie możliwości możemy sprawdzić?” przebudowana (była asymetryczna, na dużej złotej płycie, z ikonami i strzałką): 5 równych kafli w rzędzie → 3 + 2 wyśrodkowane (≤1100 px) → kolumna (≤680 px), link do pożyczek tylko podkreśleniem |
| `spolki3.html` | **Wariant „Dla spółek i JDG” złożony z uwag Cezarego (29.10.2026)** — kandydat na finalną podstronę. Hero jak w `private-debt1` (zielone „Umów rozmowę” + obrys „Zadzwoń”). Ze `spolki2`: intro „Finansowanie dopasowane…” bez złotego paska nad nagłówkiem (złota płyta pod kadrem została, bo sekcja zaakceptowana; przycisk obrysowy; tekst w rozmiarze pozostałych tekstów pod nagłówkami — `.lead` 18/30 px, uwaga 29.10 „Tylko headery zostawiamy Space Grotesk”) i „Nie musisz wiedzieć…” na sylwecie Warszawy bez złotego paska („Zadzwoń” obrysowy). „Z czym możesz się do nas zgłosić?” — 4 karty jak karty nieruchomości w `pozyczki2`: zdjęcie u góry (te same co w `spolki2`), tekst na jasnym tle, bez gradientu; ≤760 px zdjęcie z lewej. „Jakie możliwości możemy sprawdzić?” jak „Co warto przygotować…” w `kontakt3`: znak + tytuł w 2 kolumnach (3 + 2), znaki 18 px jak przy „Przeanalizujemy:” (uwaga 29.10), wszystkie pozycje zwykłym tekstem, bez linku do pożyczek (uwaga 29.10) — dokument klienta nie ma opisów tych pozycji. Ze `spolki1`: „Masz już finansowanie?” bez białej karty na złotej płycie („Przeanalizujemy:” i lista ze znakami jasnym tekstem na ciemnym tle), „Spółka czy JDG?”, oś czasu współpracy (bez zdjęcia w tle) i FAQ. Kontakt: tekst z dokumentu + formularz 1:1 ze strony głównej. Odstępy (uwagi 29.10 „więcej oddechu” i „jeszcze większe marginesy”): padding sekcji `--sec` 160 px (≤1024: 120, ≤680: 80) — więcej niż w `private-debt3` i `pozyczki5` (120 px); między treściami sąsiednich sekcji 2 × `--sec` (320 px na desktopie), także od krawędzi zdjęć — intro po hero i „Jakie możliwości…” po pasie „Nie musisz wiedzieć…” mają u góry 2 × `--sec`, karty przed tym pasem — u dołu. `noindex`, przełącznik 1–3, linki „Spółki3” w stopkach `home3`/`index`/`spolki1–2`/`private-debt1–2` |
| `private-debt1.html`, `private-debt2.html` | **Warianty podstrony „Private Debt” do oceny** (27.10.2026) — treść 1:1 z Google Doc klienta (`1uUMWhkqEczc0WOV19dxYZF2ilRyON4UC4D53MPpXuHM`): hero, „Kapitał poza standardową ścieżką bankową”, sytuacje (4) + callout, „Co analizujemy?” (6), „Bank czy Private Debt?” + callout, proces (3) + callout, FAQ, kontakt `#kontakt` z formularzem-makietą na jasnej karcie (cel, kwota, planowany sposób spłaty, opis projektu; przycisk „Umów rozmowę”). 1 = klasyczny (blisko spolki1/pozyczki4), 2 = sprzedażowy/premium (blisko spolki2). Zbudowane wg zasad z 27.10 (niżej). `noindex`, przełącznik wariantów, tymczasowe linki „Private debt1–2” w stopce `home3`/`index`/`spolki1–2`. Po wyborze: przenieść do `private-debt.html` jak przy pożyczkach |
| `private-debt3.html` | **Wariant „Private Debt” złożony z uwag Cezarego (29.10.2026)** — kandydat na finalną podstronę. Hero jak w `private-debt1`. Z `private-debt2`: intro (kadr do prawej krawędzi okna z cienką białą ramką; od 29.10 bez białej kreski nad nagłówkiem) — lead „Planujesz dużą inwestycję…” w Space Grotesk 300 (wyróżnienie 500; zostaje decyzją Cezarego z 29.10, inaczej niż w `spolki3`, gdzie lead jest w Open Sans), przycisk „Porozmawiajmy o finansowaniu” biały wypełniony (`.btn--light`, na prośbę Cezarego); karty „W jakich sytuacjach…” bez cieniującego gradientu: ostre zdjęcie 4:3 u góry, jasny dół (`--card`) z tekstem, jak „Spółka czy JDG?” w `spolki1`; „Bank czy Private Debt?” (50/50, wniosek tekstem pod spodem). Z `private-debt1`: „Private Debt nie jest finansowaniem wyłącznie…” (pasek panoramy + biały box), „Co analizujemy?” (lista 2×3; od 29.10 bez poziomych linii — pozycje ze znakiem `icon-mark` 18 px jak „Przeanalizujemy:” w `spolki3`), proces bez zdjęcia w tle, „Private Debt wymaga realnego planu spłaty” jako sam tekst na tle (bez białego kafelka). FAQ jak w `kontakt3` (nagłówek nad listą). Kontakt: tekst z dokumentu + formularz 1:1 ze strony głównej (od 29.10; wcześniej pola PD: cel, kwota, sposób spłaty, opis projektu). Odstępy ujednolicone na całej podstronie: między treściami sąsiednich sekcji zawsze 2 × `--sec` = 240 px (≤1024: 192, ≤680: 144), także od krawędzi zdjęć — stąd podwójny padding u góry intro (pod hero) i pod kartami „W jakich sytuacjach…” (nad pasem panoramy). `noindex`, przełącznik 1–3, linki „Private debt3” w stopkach `home3`/`index`/`pozyczki5`/`spolki1–3`/`private-debt1–2` |
| `assets/private-debt/` | **Placeholdery zdjęć podstrony Private Debt** — kopie istniejących zdjęć projektu nazwane wg slotów (podmiana pliku = podmiana w obu wariantach): `pd-intro.jpg` (wieżowce o zmierzchu), `pd-inwestycja.jpg` (wieżowce, pion), `pd-pomost.jpg` (most Brookliński — „finansowanie pomostowe”), `pd-deweloper.jpg` (dźwigi), `pd-transakcja.jpg` (analiza dokumentów, podgląd Adobe Stock), `pd-panorama.webp` (panorama Warszawy) |
| `assets/spolki/` | Zdjęcia podstrony spółek. Unsplash License: `inwestycja-dzwigi`, `magazyn-regaly`, `transport-ciezarowki`, `spolki-wiezowce-zmierzch`, `biurowiec-noc`, `jdg-piekarz`, `jdg-ceramik`. **Adobe Stock — podglądy ze znakiem wodnym (1000 px), do podmiany na licencjonowane pełne wersje** (numer zdjęcia w nazwie pliku `…-as<ID>.jpg`): 1866022187, 1978094482, 239643607, 1192931441, 2061885659, 2047688676, 1835267863, 2188493733 |
| `assets/pozyczki/` | Zdjęcia podstrony pożyczek (stock, Unsplash License): `kamienica.jpg` (intro), `mieszkalne-apartamentowiec.jpg` (Łódź), `komercyjne-wiezowce-noc.jpg` (Warszawa), `grunty-pole.jpg` (Polska) |
| `assets/monolith/` | Grafiki pobrane z monolith-finance.pl (hero, logo menu/stopki/hero, zdjęcie Moniki, tła, ikona, favicon, logo Verseo) |
| `LOGO.svg` | Logo Kredito (ciemna wersja, na białe tła) |
| `LOGO-WHITE.svg` | Logo Kredito (biała wersja, na ciemne tła) |
| `assets/` | Zdjęcia i wideo — patrz sekcja 19 |
| `CLAUDE.md` | Ten plik — baza wiedzy projektu |

> **Stan 21.10.2026:** strony `home3`/`index`, `o-mnie`, `kontakt3` + 5 nowych podstron są odwzorowaniem 1:1 (treść i wygląd) produkcyjnej strony **https://monolith-finance.pl/** (WordPress/Kadence): pływające menu-belka, hero ze statycznym logo (`assets/monolith/hero-logo.svg`), kontener 1210 px, nagłówki 34 px, tekst Open Sans 300 16 px, przyciski Space Grotesk 700. Wysokości sekcji sprawdzone pomiarem względem WP. Wideo kafelków (`assets/home3/plate-*.mp4`) nie jest już używane. Telefony jak na WP: +48 601 200 302 w treści, +48 722 649 938 w stopce i przycisku "Zadzwoń" w hero kontaktu.

> **Zasady projektowe od 27.10.2026 (Cezary, przy podstronie Private Debt):** złoto tylko jako drobne akcenty (znak `icon-mark`, plakietki osi czasu) — żadnych dużych złotych płyt, paneli, kafli i długich złotych linii; w przyciskach (i elementach udających przyciski) bez ikon i strzałek; zielony przycisk `.btn--dark` wyłącznie dla „Umów rozmowę” i zawsze tam, gdzie jest dobrze widoczny (biała nawigacja, zdjęcie hero, jasne karty), pozostałe przyciski secondary (`.btn--outline` / `.btn--outline-dark`), bez białych wypełnionych `.btn--light`; grupy elementów symetryczne (równe szerokości, pełne rzędy albo wyśrodkowane 3 + 2). Starsze warianty (`pozyczki1–4`, `spolki1–2`) powstały przed tymi zasadami.

> **Doprecyzowania z wyboru `pozyczki5` (29.10.2026):** kafelek informacyjny (callout) bez ikon i znaków, z nagłówkiem mniejszym niż tytuły kart (~18 px); krótkie stwierdzenie pod grupą kart jako sam tekst na tle sekcji, nie w dużej białej karcie; znaki `icon-mark` w listach małe (~22 px); bez złotych linii łączących elementy i bez złotych pasków pod liczbami; sekcje rozdzielać przestrzenią zamiast wstawianych pasów zdjęć; FAQ w układzie ze strony Kontakt (nagłówek nad listą, jedna kolumna).

> **Doprecyzowania z uwag do Private Debt (`private-debt3`, 29.10.2026):** biały wypełniony przycisk (`.btn--light`) dopuszczony jako CTA na ciemnym tle (wyjątek od zasady z 27.10); między sekcjami więcej przestrzeni, żeby treści wizualnie się oddzielały — jednakowy odstęp między treściami sąsiednich sekcji na całej podstronie (240 px na desktopie = 2 × 120 px paddingu), także od krawędzi zdjęć full-bleed (hero, pasy zdjęć); karty ze zdjęciem: zdjęcie ostre, bez gradientu i zaciemnienia, tekst na jasnym dole karty; bez krótkiej białej kreski nad nagłówkiem sekcji; listy pozycji z małymi znakami `icon-mark` (18 px) zamiast poziomych linii oddzielających.

> **Formularz kontaktowy na podstronach (Cezary, 29.10.2026):** „Formularz kontaktowy ma być na wszystkich podstronach taki sam, jak na stronie głównej” (`kontakt3`, `pozyczki5`, `spolki3`, `private-debt3`; starsze warianty 1–4 / 1–2 zostają bez zmian jako materiał porównawczy) — 1:1 z `home3` `#kontakt`: ciemna półprzezroczysta karta, pola Imię*, Telefon*, E-mail*, Orientacyjna kwota finansowania, Notatka, zgoda, biały przycisk „Wyślij zgłoszenie” (wyjątek od zasady „bez `.btn--light`”). Tekst obok formularza zostaje z dokumentu danej podstrony. Przy spółkach FAQ zostaje w układzie `spolki1` (nagłówek z lewej, lista z prawej).

> **Uwaga:** `index.html` i `hero-variants.html` to wcześniejsze wersje robocze — nie są aktywnie rozwijane.

### Źródła wiedzy

| Plik/Link | Opis |
| :-- | :-- |
| `assets/MONIKA BUCHACZ - transkrypcja spotkania 02.07.2026.pdf` | Transkrypcja warsztatu 1 (~151k znaków, wiarygodna) |
| `MONIKA BUCHACZ - transkrypcja spotkania - 07.07.2026.pdf` | Transkrypcja warsztatu 2 (~117k znaków, wiarygodna) |
| [FigJam — Monika Buchacz Finance](https://www.figma.com/board/k02JxpkksjMILBvLsihAiO/MONIKA-BUCHACZ-FINANCE) | Wyniki warsztatów discovery — moodboardy, wartości, grupy docelowe |
| Figma projekt (design): `RWnZ8hbwF5eyEgGlg4y08m` | Projekt wizualny strony |

> **Uwaga dot. transkrypcji:** Notatki Gemini z tych samych spotkań są **niewiarygodne** — zawierają treści niezwiązane z projektem (wzmianki o Wietnamie, Maroku, integracji AI, e-commerce). Używaj wyłącznie PDF-ów wymienionych wyżej.

---

## 18\. ZESPÓŁ PROJEKTU

| Osoba | Rola |
| :---- | :---- |
| Monika Buchacz | Klientka |
| Cezary Kutwin | UX / Web Designer (Verseo) |
| Mateusz (Speaker 6\) | Facilitator warsztatów |
| Franek (Speaker 7\) | UX (warsztaty) |
| Przemek (Speaker 8\) | Designer (warsztaty, moodboardy) |
| Katarzyna (Speaker 4\) | Verseo (warsztaty) |

---

---

## 19\. STAN BUDOWY STRONY (na 02.08.2026)

### Plik główny: `hero-e.html`

Single-file HTML z inline CSS. Brak frameworka. Fonty: Google Fonts (Montserrat + Lato).

#### CSS custom properties

```css
--ink: #0C0907        /* tło near-black */
--burg: #7A1F1F       /* burgund */
--ember: #FF6B35      /* ciepły pomarańcz */
--nav-h: 72px
--gap: 1.25rem
--font-d: 'Montserrat', sans-serif   /* display / nagłówki */
--font-b: 'Lato', sans-serif         /* body */
```

#### Zbudowane sekcje (kolejność na stronie)

| # | ID w kodzie | Sekcja | Status |
| :-- | :-- | :-- | :-- |
| 01 | `.nav` | Nawigacja sticky — logo + menu + CTA | ✅ Gotowe |
| 02 | `.hero` | Hero z wideo w tle (plik `assets/hf_*.mp4`) | ✅ Gotowe |
| 03 | `.statement` | "Rozwiązujemy sprawy finansowe..." — biały | ✅ Gotowe |
| 04 | `.qualify` | Kwalifikacja — 3 karty na gradiencie bordowym | ✅ Gotowe |
| 05 | `.about` | Liczby / Unfair Advantage — 4 metryki + zdjęcie | ✅ Gotowe |
| 06 | `.private-debt` | Private Debt — "finansowanie w 2 dni bez BIK" | ⚠️ Do przebudowy — sekcja ma pozostać wyróżnioną usługą, ale nie może być nazywana "Private Debt" (decyzja 07.08.2026). Docelowa nazwa/koncepcja do ustalenia z klientką. |
| 07 | `.about-monika` | O Monice — zdjęcie, tekst, sieć relacji | ✅ Gotowe |

#### Do zbudowania (Faza 1 MVP)

- Sekcja: Jak pracujemy (4 kroki)  
- Sekcja: Social proof / testimoniale  
- Sekcja: Dla pośredników (teaser)  
- Sekcja: Kontakt + formularz  
- Footer  
- Podstrony: O firmie, Pożyczki hipoteczne, Dla pośredników, Dla spółek, Kontakt

### Assety w `assets/`

| Plik | Użycie |
| :-- | :-- |
| `hf_20260802_154146_*.mp4` | Wideo hero (tło) |
| `unsplash_puwdjzA1-AQ.png` | Sekcja About — obrócone zdjęcie mostu |
| `colton-duke-UGw4owZlPD8-unsplash.jpg` | Private Debt — baner szeroki |
| `unsplash_PSmDDeXaEWE.png` | Private Debt — zdjęcie prawe (wieżowiec) |
| `monika-portrait.jpg` | O Monice — zdjęcie Moniki w karcie |
| `monika-network.jpg` | O Monice — zdjęcie sieci relacji |
| `subtract-orange-1/2/3.svg` | Kształty dekoracyjne kart kwalifikacji |
| `subtract-white-1/3.svg` | Kształty dekoracyjne kart kwalifikacji |

### Kluczowe decyzje techniczne (sesja 02.08.2026)

- Zdjęcia Moniki: `object-position: 55% 100%` — dolna krawędź zdjęcia wyrównana do ramki  
- Kafelek Moniki wychodzi poza górną krawędź sekcji: `margin-top: -95px` na `.am-photo`, `padding-top: 50px` na sekcji, `overflow: visible`  
- Dekoracyjne kwadraty (pomarańcz/burgund) w sekcji "O Monice" są za zdjęciem sieci (`z-index: 0` vs `z-index: 1` na `.am-network`)  
- SVG assety muszą mieć rozszerzenie `.svg` (nie `.png`) — MIME type mismatch blokuje ładowanie  
- Wideo hero: `background: transparent` na `.he-card` — eliminuje bordowe narożniki przy ładowaniu

---

---

## 20\. WIEDZA Z TRANSKRYPCJI — STATUS PYTAŃ §13

> Obie transkrypcje zostały przeczytane w całości (07.08.2026). Poniżej rzeczywisty status — nie dokumentacyjna luka, a realny stan wiedzy.

### Pytania odpowiedziane w transkrypcjach

| # | Pytanie | Status | Źródło |
| :-- | :-- | :-- | :-- |
| Q11 | Jak wyjaśnia private debt (2 dni, bez BIK) | ✅ Gotowe | Warsztat 2, ~1:33–1:34 |
| Q12 | Lista wymagań wejściowych | ⏳ Częściowe | Warsztat 1, ~1:13 |
| Q18 | Cel formularza kontaktowego | ⏳ Częściowe | Warsztat 2, ~1:14 |

**Q11 — gotowy cytat do copy:** Monika opisuje private debt jako serwis premium-wygoda, nie ryzyko: *"nie było raportowane do BIK-u... nie tłumaczył się przed doradcą... nie biegał po urzędach"*

**Q12 — częściowy cytat:** *"przygotuj nam dokumenty, potrzebujemy BIK, potrzebujemy twoją finansówkę i potrzebujemy dwa dni"* — lista może być niepełna.

**Q18 — cel potwierdzony:** formularz jako narzędzie badawcze "kto się zgłasza" od dnia 1 (zgodne z §14), ale konkretnych pól brak.

### Pytania nadal otwarte (nie padły w żadnym warsztacie)

Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10, Q13, Q14, Q15, Q16, Q17, Q19 — **muszą być zadane Monice bezpośrednio**. Nie zakładaj, że gdzieś są ukryte — sprawdzono kompletne transkrypcje.

### Aktualizacja 25.08.2026 — plik "Monika Buchacz - informacje.pdf" (odpowiedzi klientki)

Nowe źródło (w katalogu nadrzędnym `MONIKA-B/`) domyka znaczną część luk. Kluczowe fakty:

- **Q6 zamknięte, z twistem:** próg 1 mln NIE jest sztywny — *"Nie musimy trzymać się sztywno kwoty 1 milion, ale tak żeby charakter strony/firmy ściągał klienta na wyższe wolumeny"*. Najwięcej klientów: 100k–1,5M; docelowe segmenty: 300k–2,5M i 2,5–10M+. W copy: "typowe sprawy od 1 mln PLN" + gwiazdka "inny temat? i tak zadzwoń".
- **Q10/Q11 zamknięte:** pełny opis pożyczki pozabankowej — LTV 40–60%, okres 6–24 mies., exit strategy = refinansowanie bankowe, brak raportowania do BIK, wymagane tylko nr KW + podstawa nabycia.
- **Q12 zamknięte:** pełne listy — akceptowane/odrzucane nieruchomości, branże wykluczone, dokumenty NIE-wymagane.
- **Czasy urealnione:** decyzja 24–48 h, wypłata 2–5 dni roboczych (skrajnie 48 h); harmonogram dzień-po-dniu D1–D4. **Standard w copy: 2–3 min ocena / 24–48 h decyzja / 2–5 dni wypłata.**
- **FAQ gotowe:** 4 dosłowne skrypty rozwiewania obaw ("Fundusz zarabia na pieniądzu, nie na betonie" itd.) + rama kosztowa (instrument pomostowy/naprawczy, nie drogi kredyt).

Nadal otwarte (lista w `content-plan.md` §6): nazwa firmy, nazwa sekcji "szybka ścieżka", numer telefonu publicznie, CTA nawigacji, tytułowanie, pola formularza (akceptacja), testimoniale.

### Decyzje projektowe 25.08.2026 (plan zatwierdzony przez Cezarego)

- Pełna architektura treści serwisu + docelowe copy: **`content-plan.md`** (strona główna 12 sekcji + 5 podstron).
- Sekcja "Private Debt" → rekomendowana nazwa **"Szybka ścieżka: pieniądze w 48 godzin"** (warianty B/C w content-plan §1.3).
- Hero: H1 rekomendowany **"Bank powiedział „nie"? To dopiero początek rozmowy."**; obecny sub jest kopią 1:1 z LoanHub — do wymiany.
- Metryki: 3 → 4 (20 lat / 30–40 instytucji / 2–3 min / 48 h); "minimum 1 000 000" schodzi z metryk do treści.
- Karty kwalifikacji: przebudowa z pozycjonowania absolutnego (px) na flex/grid.
- **Nowa strona główna budowana jako `home2.html`** (decyzja 25.08): obecna strona główna (`index.html`/`hero-e.html`) pozostaje bez zmian poza linkiem "Home2" w menu; wszystkie zmiany treści i nowe sekcje trafiają do `home2.html`.
- **Formularz kontaktowy: wyłącznie makieta graficzna** — żadnych funkcjonalności (bez wysyłki, bez walidacji, bez backendu). Decyzja 25.08.2026.

### Kluczowe ustalenia z transkrypcji (poza listą pytań)

**Red flag — pojemność Moniki (Warsztat 1, ~1:42):**
Monika powiedziała wprost: *"nie wyrabiam się z liczbą klientów... nie nadążam z oddzwanianiem"*. Przed umieszczeniem jakiejkolwiek obietnicy szybkości oddzwonienia na stronie (Q17) potrzebna jest rozmowa o procesie i pojemności — twarda obietnica może się obrócić przeciwko niej.

**Nazwa "Kredito" — niezatwierdzona przez Monikę (Warsztat 2, ~53:46):**
Monika powiedziała *"nie wiem, proszę o wasze wskazówki, ja się zdaję tutaj na was"* — sama nazwa pochodzi z propozycji zespołu jako przykład ilustracyjny, a nie decyzja klientki. §2 już to hedguje, ale traktuj nazwę jako **realnie niezatwierdzoną**, nie tylko formalnie-oczekującą.

**Sekcja Private Debt — decyzja 07.08.2026:**
Sekcja `.private-debt` w `hero-e.html` ma pozostać jako wyróżniona usługa, ale **nie może być nazywana "Private Debt"** — decyzja po konsultacji. Docelowa nazwa/koncepcja do ustalenia z Moniką przed kolejną sesją.

---

*Plik generowany na podstawie transkrypcji dwóch warsztatów discovery (02.07 i 07.07.2026) oraz sesji roboczych z Cezarym Kutwinem.*  
