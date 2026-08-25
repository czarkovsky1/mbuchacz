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
| `hero-e.html` | **GŁÓWNY PLIK ROBOCZY** — strona główna MVP (single-file HTML) |
| `LOGO.svg` | Logo Kredito (ciemna wersja, na białe tła) |
| `LOGO-WHITE.svg` | Logo Kredito (biała wersja, na ciemne tła) |
| `assets/` | Zdjęcia i wideo — patrz sekcja 19 |
| `CLAUDE.md` | Ten plik — baza wiedzy projektu |

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

### Kluczowe ustalenia z transkrypcji (poza listą pytań)

**Red flag — pojemność Moniki (Warsztat 1, ~1:42):**
Monika powiedziała wprost: *"nie wyrabiam się z liczbą klientów... nie nadążam z oddzwanianiem"*. Przed umieszczeniem jakiejkolwiek obietnicy szybkości oddzwonienia na stronie (Q17) potrzebna jest rozmowa o procesie i pojemności — twarda obietnica może się obrócić przeciwko niej.

**Nazwa "Kredito" — niezatwierdzona przez Monikę (Warsztat 2, ~53:46):**
Monika powiedziała *"nie wiem, proszę o wasze wskazówki, ja się zdaję tutaj na was"* — sama nazwa pochodzi z propozycji zespołu jako przykład ilustracyjny, a nie decyzja klientki. §2 już to hedguje, ale traktuj nazwę jako **realnie niezatwierdzoną**, nie tylko formalnie-oczekującą.

**Sekcja Private Debt — decyzja 07.08.2026:**
Sekcja `.private-debt` w `hero-e.html` ma pozostać jako wyróżniona usługa, ale **nie może być nazywana "Private Debt"** — decyzja po konsultacji. Docelowa nazwa/koncepcja do ustalenia z Moniką przed kolejną sesją.

---

*Plik generowany na podstawie transkrypcji dwóch warsztatów discovery (02.07 i 07.07.2026) oraz sesji roboczych z Cezarym Kutwinem.*  
