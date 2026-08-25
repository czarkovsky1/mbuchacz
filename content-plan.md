# CONTENT PLAN — pełna architektura serwisu i docelowe treści

> Projekt: strona dla Moniki Buchacz (nazwa robocza: Kredito — do zmiany, patrz §6)
> Autor: Cezary Kutwin (Verseo) + analiza AI | Data: 25.08.2026
> Źródła: transkrypcje warsztatów 02.07 i 07.07.2026 (przeczytane w całości), „Monika Buchacz — informacje.pdf" (odpowiedzi klientki), CLAUDE.md, briefy, benchmark: mBank / PKO BP / Revolut / Notus / LoanHub.
> Status treści: **docelowe propozycje copy** — do akceptacji Cezarego, potem Moniki. Fakty wyłącznie ze źródeł; cytaty Moniki oznaczone „(M)".

---

## §1. RDZEŃ STRATEGICZNY — decyzje spinające całość

1. **Próg kwotowy.** Pozycjonowanie premium zostaje („typowe sprawy od 1 mln PLN"), ale bez twardej bramki — Monika w informacje.pdf: *„Nie musimy trzymać się sztywno kwoty 1 milion, ale tak żeby charakter strony/firmy ściągał klienta na wyższe wolumeny"*. Wszędzie, gdzie pada kwota, dodajemy zatwierdzoną na warsztacie „gwiazdkę": **„Masz inny temat? I tak się odezwij."**
2. **Obietnice czasowe — jeden standard w całym serwisie:**
   **wstępna ocena w 2–3 minuty przez telefon · decyzja w 24–48 h · pieniądze na koncie w 2–5 dni roboczych.**
   Bez obietnicy czasu oddzwonienia (red flag pojemności: „nie nadążam z oddzwanianiem" — W1).
3. **Sekcja „Private Debt" zmienia nazwę** (decyzja 07.08.2026). Rekomendacja: **„Szybka ścieżka: pieniądze w 48 godzin"** (warianty do wyboru Moniki: „Finansowanie poza bankiem", „Dyskretne finansowanie premium"). Sekcja zostaje wyeksponowana — zalecenie z warsztatu: „bold, duży, wytłuszczony, wyżej".
4. **Zakazy twarde:** brak prowizji/cennika; ŻADNEJ wzmianki o wynagrodzeniu przy produktach hipotecznych konsumenckich (ryzyko KNF); zero logotypów banków/funduszy (zamiast nich case studies); zero kalkulatora przy pożyczkach pod nieruchomość; zero wrażenia B2C; KNF wyłącznie w stopce/formalnościach.
5. **Ton:** pewny, stwierdza; „debiloodporne 2–3 bullet pointy"; liczby zamiast przymiotników; Superbohater + Czarodziej; kontra-AI („odbieramy telefon osobiście"); premium, ale nie wieża z kości słoniowej.

---

## §2. STRONA GŁÓWNA — docelowa struktura (12 sekcji)

Kolejność: Nav → Hero → Statement → Kwalifikacja → Liczby → Szybka ścieżka → Jak pracujemy → O Monice → Historie klientów → Dla pośredników → Kontakt → Footer.

### 01 · Nawigacja (zbudowana — korekty)
**Cel:** dostęp do podstron + CTA telefoniczne zawsze widoczne.
- CTA „Kontakt" → **„Umów rozmowę"** (wariant: „Zadzwoń" — jeśli Monika zgodzi się na publiczny numer, obok CTA klikalny numer telefonu; to największa pojedyncza dźwignia przy modelu 100% telefonicznym).
- Menu bez zmian: O firmie · Pożyczki hipoteczne · Dla pośredników kredytowych · Dla spółek.

### 02 · Hero (zbudowana — wymiana copy)
**Cel:** decyzja w pierwszą sekundę — „to strona dla mnie".
**Problem obecny:** H1 to generyczny superlatyw („Najlepsze pożyczki…"), a podtytuł jest skopiowany 1:1 z LoanHub — do bezwzględnej wymiany.

**H1 (rekomendacja, wzór ból→odwrócenie):**
> **Bank powiedział „nie"? To dopiero początek rozmowy.**

**H1 (wariant B, opisowo-premium):**
> **Finansowanie dla firm, których sprawy nie mieszczą się w bankowej procedurze.**

**Sub:**
> Od 20 lat znajduję finansowanie tam, gdzie standardowa ścieżka się kończy — w 30–40 bankach, funduszach i instytucjach zagranicznych. Wstępną ocenę swojej sprawy usłyszysz w 2–3 minuty. Przez telefon, bez wniosków i bez wizyt.

**CTA:** „Umów rozmowę" (primary) · „Zobacz, jak pracuję" (secondary, kotwica do sekcji 07).

### 03 · Statement (zbudowana — drobna korekta)
**Cel:** natychmiastowe pozycjonowanie względem banku; sekcja-most.
> **Jesteśmy niezależnym pośrednikiem finansowym — tam gdzie bank mówi „nie".**
> Pożyczki pod zastaw nieruchomości, kredyty firmowe, finansowanie z funduszy i instytucji zagranicznych. Nie jesteśmy na pasku żadnego banku — wybieramy z całego rynku.
**CTA:** „Poznaj nas" → O firmie.

### 04 · Kwalifikacja — 3 karty (zbudowana — nowe copy + przebudowa techniczna)
**Cel:** filtr „czy jestem we właściwym miejscu" w 3 segmentach.
**Technika:** karty mają dziś pozycjonowanie absolutne w px — przebudować na flex/grid (responsywność).

**Karta 1 — Firmy:**
> **Finansowanie dla firm — typowe sprawy od 1 mln PLN**
> Pożyczki pod zastaw nieruchomości, kredyty firmowe, faktoring, finansowanie zagraniczne. Prowadzę sprawę od pierwszego telefonu do podpisania umowy — Ty nie odwiedzasz żadnego banku.
> CTA: „Oferta dla firm"

**Karta 2 — Trudna historia:**
> **Spółka z trudną historią kredytową?**
> Czerwony BIK, wpisy w KRD, strata na dokumentach — w banku to koniec rozmowy, u mnie jej początek. O finansowaniu decyduje nieruchomość i plan spłaty, nie przeszłość w bazach.
> CTA: „Oferta dla spółek"

**Karta 3 — Pośrednicy:**
> **Jesteś pośrednikiem i masz temat nie do zrobienia?**
> Tam, gdzie kończy się Twoja lista instytucji, zaczyna się moja. Zgłaszasz temat, prowadzę sprawę, po sukcesie dzielimy się prowizją — a klient wraca do Ciebie.
> CTA: „Oferta dla pośredników"

**Pod gridem (gwiazdka Franka):**
> *Masz temat, który nie pasuje do żadnej karty? I tak się odezwij — podejmuję sprawy, przy których inni odpadli.*

### 05 · Liczby / Unfair Advantage (zbudowana — rozszerzenie 3→4 metryki)
**Cel:** dowód w liczbach, zero przymiotników. Dwie najmocniejsze liczby projektu (2–3 min, 48 h) są dziś schowane w tekście — wychodzą na wierzch.

| Liczba | Podpis |
|---|---|
| **20 lat** | na rynku finansowania firm — relacje z decydentami, nie z infoliniami |
| **30–40 instytucji** | banki, fundusze, rynki zagraniczne (przeciętny pośrednik: 3–4) |
| **2–3 minuty** | tyle trwa wstępna ocena Twojej sprawy przy pierwszym telefonie |
| **48 godzin** | decyzja o finansowaniu szybką ścieżką — bez wizyty w banku |

**Tekst towarzyszący:** obecny akapit „Rozwiązujemy sprawy finansowe, których inni nie podejmują…" zostaje; frazę „minimum 1 000 000" zastępujemy: *„Typowe sprawy, które prowadzę, zaczynają się od 1 mln PLN — a kończą na dziesiątkach milionów."*

### 06 · Szybka ścieżka (zbudowana jako „Private Debt" — rename + nowe copy)
**Cel:** wyróżnik kontrastowy — konkurencja o tym milczy, my mówimy wprost.
**H2 (rekomendacja):**
> **Pieniądze na koncie w 48 godzin. Bez BIK, bez wizyt, bez tłumaczenia się.**
**Body (na bazie dosłownego cytatu M):**
> Kiedy czas decyduje o kontrakcie, jest ścieżka, o której większość pośredników milczy: finansowanie z funduszy prywatnych. Rozmawiasz ze mną, ja rozmawiam z decydentem funduszu — i w 48 godzin masz decyzję, a pieniądze na koncie w 2–5 dni. Nie siedzisz w banku, nie spowiadasz się z wyników finansowych, nie biegasz po urzędach. Ta pożyczka nie jest raportowana do BIK, więc nie obniża zdolności Twojej firmy przy kolejnych kredytach. To usługa premium: droższa niż bank, zawierana na krótko — i właśnie dlatego działa, gdy bank potrzebuje ośmiu tygodni.
**CTA:** „Sprawdź szybką ścieżkę" → podstrona Pożyczki hipoteczne · „Umów rozmowę".

### 07 · Jak pracujemy (DO ZBUDOWANIA)
**Cel:** rozbroić „tylko telefon" — pokazać, że to przewaga, nie brak.
**H2:** **Cały proces przez telefon i mail. Ty nie jeździsz nigdzie.**
**Lead:** *Kto ma dziś czas zebrać trzech udziałowców i obejść z nimi pięć banków? Cały ten ogrom pracy wykonuję ja — Ty odbierasz telefon z gotowym rozwiązaniem.*

| Krok | Treść |
|---|---|
| **1 · Telefon** | Opowiadasz o sprawie. Po 2–3 minutach wiesz, czy temat jest do zrobienia — i mniej więcej na jakich warunkach. |
| **2 · Dokumenty mailem** | Przy pożyczce pod nieruchomość: numer księgi wieczystej i podstawa nabycia. Przy kredycie: BIK i dokumenty finansowe. Bez zaświadczeń z ZUS i US, bez biznesplanów. |
| **3 · Decyzja w 24–48 h** | Rozmawiam bezpośrednio z analitykami i decydentami instytucji. Wracam z konkretem: gdzie, ile i za ile. |
| **4 · Umowa i wypłata** | Podpisanie u notariusza (często w Twojej okolicy), pieniądze na koncie w 2–5 dni roboczych od kompletu dokumentów. |

**CTA:** „Zacznij od telefonu".

### 08 · O Monice (zbudowana — wzmocnienie)
**Cel:** brand story + kontra-AI.
Zostaje: „Nazywam się Monika Buchacz i jestem po drugiej stronie telefonu" + sieć relacji.
**Dodać (2 elementy):**
- Aspiracja „pierwszego telefonu" (parafraza W2): *„Chcę, żeby ta firma działała jak dobry adwokat od spraw beznadziejnych: masz trudny temat — wiesz, do kogo dzwonisz. A jeśli ja nie znajdę rozwiązania, to znaczy, że ono nie istnieje."*
- Kontra-AI: *„Możesz złożyć wniosek przez stronę banku albo zapytać czata. Przy dużych sprawach rzadko kończy się to dobrze. U mnie po drugiej stronie telefonu jest człowiek, który zna odpowiedź, zanim skończysz zdanie."*
**Fix:** akapit o sieci relacji powtarza się dziś dosłownie w części górnej i dolnej sekcji — dolny wymienić na wątek aspiracji.

### 09 · Historie klientów / Social proof (DO ZBUDOWANIA)
**Cel:** dowód, nie deklaracja. Wariant startowy = 2 anonimizowane case'y (zamiast logotypów banków — decyzja warsztatowa). Format: sytuacja → przeszkoda → rozwiązanie → wynik.
**H2:** **Sprawy, przy których inni rozłożyli ręce.**

**Case 1 — „Dwóch pośredników odmówiło":**
> Spółka technologiczna z dużym obrotem. Dwóch pośredników nie znalazło finansowania i odpuściło. Usiedliśmy z prezesem do struktury od nowa: przełożyliśmy zabezpieczenia między nieruchomościami, zmieniliśmy produkty, połączyliśmy dwie instytucje. Finansowanie spięte. Nie było magii — była układanka, którą trzeba było chcieć ułożyć.

**Case 2 — „Hotel za 60 mln":**
> Właściciel hotelu potrzebował 60 mln PLN. Znał jednego doradcę w jednym banku — samodzielne obejście rynku zajęłoby mu pół roku. Ja rozmawiam z analitykami wszystkich banków, które w ogóle mogły ten temat udźwignąć. Pełna mapa możliwości w dwa dni.

**Trust-bar pod case'ami:** Pośrednik zarejestrowany w KNF · 20 lat na rynku · klienci, którzy wracają od 15–20 lat.
**Do pozyskania od Moniki:** dosłowne testimoniale (trop z W2: ma opinie/artykuły u większych pośredników — do odzyskania i zacytowania).

### 10 · Dla pośredników — teaser (DO ZBUDOWANIA)
**Cel:** hak dla segmentu SECONDARY, ton „między swoimi".
**H2:** **„Ej, Monika, teraz ty coś zrób."**
**Body:** *Tak zaczyna się większość telefonów od pośredników. Masz klienta z tematem poza Twoją specjalizacją? Nie zostawiaj go bez rozwiązania — zgłoś temat do mnie. Po sukcesie dzielimy się prowizją, a klient pamięta, że to Ty mu pomogłeś.*
**CTA:** „Zobacz zasady współpracy" → podstrona.

### 11 · Kontakt + formularz (DO ZBUDOWANIA)
**Cel:** domknięcie + narzędzie badawcze („kto się zgłasza i z czym" — intencja M).
**H2:** **Poznajmy się.**
**Lead:** *Pierwsza rozmowa nic nie kosztuje i do niczego nie zobowiązuje. W 2–3 minuty powiem Ci, czy temat jest do zrobienia.*
**Pola formularza (propozycja do akceptacji Moniki):**
1. Imię · 2. Telefon · 3. E-mail · 4. Kim jesteś? [prowadzę firmę / jestem pośrednikiem] · 5. Orientacyjna kwota finansowania · 6. Czy zabezpieczeniem może być nieruchomość? [tak/nie/nie wiem] · 7. Opisz sprawę w 2–3 zdaniach (opcjonalne) · zgody RODO.
**Bez obietnicy czasu oddzwonienia.** Zamiast niej: *„Oddzwaniam osobiście — to zawsze będę ja, nie call center."*

### 12 · Footer (DO ZBUDOWANIA)
Logo · sitemap (6 pozycji) · blok formalny: *„[Nazwa] — pośrednik finansowy zarejestrowany w rejestrze KNF. Możesz nas sprawdzić po imieniu i nazwisku."* · dane firmy · polityka prywatności/RODO · copyright. Tu — i tylko tu — formalności.

---

## §3. PODSTRONY — układ, cel, treści

### 3.1 POŻYCZKI HIPOTECZNE (core; główne źródło: informacje.pdf)

| # | Sekcja | Cel |
|---|---|---|
| 1 | Hero | pozycjonowanie produktu + czas |
| 2 | Dla kogo / parametry | samokwalifikacja kwotowa |
| 3 | Zabezpieczenie | filtr nieruchomości (oszczędza telefony) |
| 4 | Czego NIE musisz dostarczać | kontrast bankowy — główny wyróżnik |
| 5 | Proces dzień po dniu | transparentność, „klienci firmowi nie lubią niespodzianek" |
| 6 | Po co firmy to biorą | reframing kosztu: instrument, nie dług |
| 7 | FAQ / obiekcje | neutralizacja lęków (skrypty M) |
| 8 | CTA | telefon |

**1 · Hero:**
> **Pożyczka pod zastaw nieruchomości dla firm. Decyzja w 24–48 godzin.**
> O finansowaniu decyduje wartość nieruchomości i plan spłaty — nie historia w BIK, nie zaległości w ZUS, nie zeszłoroczna strata.

**2 · Dla kogo / parametry (dane z informacje.pdf):**
- Kwoty: standardowo **300 tys.–2,5 mln PLN** (finansowanie pomostowe, grunty, deweloperka, towar); **2,5–10 mln+ PLN** z funduszy i podmiotów private equity (obiekty komercyjne, restrukturyzacje, duże projekty).
- **LTV 40–60%** wartości nieruchomości (grunty: 30–50%).
- Okres: **6–24 miesiące** (fundusze do 4 lat) — z założenia pomost, nie kredyt na życie.
- Forma: **firmy (B2B)** — JDG i spółki.
- Cel: **dowolny** — spłata ZUS/US, zatrzymanie egzekucji, konsolidacja, zakup, płynność.
- Gwiazdka: *inna kwota, inny układ? I tak zadzwoń.*

**3 · Zabezpieczenie:**
**Przyjmujemy:** mieszkania z KW (najchętniej — duże miasta), domy (deweloperski/wykończony, aglomeracje), kamienice i budynki mieszkalne, lokale użytkowe i handlowe, magazyny i hale (dobry dojazd, uniwersalna konstrukcja), obiekty hotelowe (wyspecjalizowane fundusze, niższe LTV), działki budowlane i inwestycyjne z MPZP/WZ, grunty pod deweloperkę.
**Nie przyjmujemy:** nieruchomości bez księgi wieczystej, z nieuregulowanym stanem prawnym (spadki, spory, brak zgody współwłaścicieli), obiektów sakralnych; ostrożnie: grunty rolne.
**Branże wykluczone przez instytucje finansujące:** hazard, przemysł erotyczny, broń, nieregulowane krypto/finanse bez licencji, dopalacze, składowiska odpadów niebezpiecznych.

**4 · Czego NIE musisz dostarczać:**
> W banku najpierw dokumenty, potem rozmowa. Tutaj odwrotnie.
- ❌ zaświadczenia o niezaleganiu ZUS/US (pożyczka często służy właśnie ich spłacie)
- ❌ wyciągi z konta z 3–6 miesięcy
- ❌ biznesplany, prognozy, kosztorysy, faktury dokumentujące cel
- ❌ czysty BIK — raporty bywają sprawdzane, ale **zła historia nie dyskwalifikuje**; wpisy w KRD to dla finansującego mapa zadłużenia do wyprostowania, nie powód odmowy
- ✅ wymagane: **numer księgi wieczystej** + **podstawa nabycia** (akt notarialny, darowizna, spadek); przy części instytucji dokumenty dochodowe (PIT)
- ✅ bonus: pożyczka **nie jest raportowana do BIK** — nie obniża zdolności firmy pod przyszłe kredyty bankowe
- ℹ️ po restrukturyzacji? W banku blokada na lata (wpis widoczny 5 lat, potem „kwarantanna") — tutaj restrukturyzacja bywa odczytywana jako dowód odpowiedzialności.

**5 · Proces dzień po dniu (harmonogram z informacje.pdf):**
| Dzień | Co się dzieje |
|---|---|
| **Dzień 1** | Przesyłasz numer KW i zdjęcia nieruchomości. Analityk sprawdza stan prawny w elektronicznym rejestrze — wstępna decyzja w **2–4 godziny**. |
| **Dzień 2** | Dostarczasz dokumenty uzupełniające (podstawa nabycia, zdjęcia wnętrza). |
| **Dzień 3** | Notariusz — umowa pożyczki i wniosek o wpis hipoteki, ok. 1,5–2 h. Projekt umowy dostajesz **2–3 dni wcześniej** do konsultacji z dowolnym prawnikiem. |
| **Dzień 4** | Wypłata — przelew zlecany od razu po akcie, często Express Elixir. |
> Wycenę nieruchomości wykonuje zwykle instytucja finansująca. Notariusz — w zależności od instytucji — w dużym mieście lub w Twojej okolicy.
> Dla porównania: identyczna procedura w banku trwa **3–8 tygodni**.

**6 · Po co firmy to biorą (reframing kosztu):**
> To nie jest „drogi kredyt". To narzędzie, które kupuje czas — a czas w biznesie ma cenę.
- **Ratujesz majątek:** koszt pożyczki to ułamek strat z licytacji komorniczej czy sprzedaży nieruchomości pod presją.
- **Ratujesz płynność:** zatrzymujesz blokadę kont przez ZUS/US, firma dalej generuje przychód.
- **Łapiesz okazję:** okazyjny grunt, duży kontrakt, towar w dobrej cenie — koszt kapitału wkalkulowany w marżę transakcji.
- **Wychodzisz na prostą (Exit Strategy):** pożyczka na 12–24 miesiące → spłacasz wierzycieli → wpisy znikają z KRD w 14 dni, BIK się czyści → wracasz do taniego kredytu bankowego i nim spłacasz pożyczkę. **Bilet powrotny do banku — nie podpisuję umowy, dopóki wspólnie nie ustalimy, jak ją spłacisz.**

**7 · FAQ / obiekcje (odpowiedzi = skrypty M z informacje.pdf):**
- *Czy fundusz chce przejąć moją nieruchomość?* → **„Fundusz zarabia na pieniądzu, nie na betonie."** Przejęcie nieruchomości to dla niego koszt, sąd i zamrożona gotówka na lata. Zarabia wtedy, gdy spłacasz w terminie i wracasz do banku.
- *Czy tracę własność?* → **Wpis w księdze to nie utrata własności.** Hipoteka w dziale IV KW — dokładnie tak samo zabezpiecza się PKO BP czy mBank. Przez cały okres umowy pozostajesz jedynym właścicielem.
- *Boję się kruczków w umowie.* → Projekt aktu dostajesz **minimum 2–3 dni przed notariuszem** — pokaż go dowolnemu prawnikowi. U notariusza każdy paragraf jest odczytywany na głos. Zero drobnego druku.
- *Co jeśli coś pójdzie nie tak?* → **Wspólnie budujemy Exit Strategy.** Jeśli czyszczenie baz się przedłuża, umowę można aneksować. Partner, nie instytucja czekająca na potknięcie.
- *Mogę spłacić wcześniej?* → Zwykle tak; standardem w umowach B2B jest minimalny okres odsetkowy (np. 3–6 miesięcy) — mówię o tym wprost przed podpisaniem.
- *Ile to kosztuje?* → Drożej niż bank, taniej niż brak działania. Konkretne warunki zależą od nieruchomości i instytucji — usłyszysz je w pierwszej rozmowie, zanim cokolwiek podpiszesz.

**8 · CTA:**
> **Masz pod ręką numer księgi wieczystej? To wystarczy na start.**
> Resztę sprawdzę w trakcie rozmowy. [Umów rozmowę]

### 3.2 OFERTA DLA SPÓŁEK

| # | Sekcja | Cel |
|---|---|---|
| 1 | Hero | rozszerzenie perspektywy: nie tylko „ratunek" |
| 2 | Dwie sytuacje | autodiagnoza persony |
| 3 | Zakres produktów | katalog + gwiazdka |
| 4 | Dlaczego my | przewaga dostępu i tempa |
| 5 | Jak pracujemy (skrót) + CTA | domknięcie |

**1 · Hero:**
> **Finansowanie dla spółek. Od spraw pilnych po sprawdzenie, czy nie przepłacasz.**
> Jedna rozmowa zamiast obchodzenia pięciu banków.

**2 · Dwie sytuacje:**
- **Pali się.** Czerwony BIK, wpisy w KRD, strata na papierze, komornik na horyzoncie — bank nie podejmie rozmowy. Ja tak: o finansowaniu może zdecydować majątek spółki, nie jej przeszłość w bazach.
- **Nic się nie pali — i właśnie dlatego warto.** Masz kredyty, linię, faktoring i leasing w trzech bankach? „Sprawdźmy, czy masz najtaniej." Zdarzało się, że jedna taka rozmowa oznaczała 200 tys. zł mniej odsetek. Rozmowa jest darmowa — płacisz tylko od sukcesu, gdy zdecydujesz się na zmianę.

**3 · Zakres produktów (karty):** kredyty firmowe · pożyczki pod zastaw nieruchomości (→ podstrona) · faktoring · linie w rachunku bieżącym · leasing · konsolidacja i refinansowanie · restrukturyzacja · obligacje · finansowanie zagraniczne (m.in. bank szwajcarski, transakcje transgraniczne).
> *Nie widzisz swojego tematu? Podejmuję sprawy, przy których inni odpadli — zadzwoń.*

**4 · Dlaczego my:**
> Nie wysyłam wniosków „w eter". Rozmawiam bezpośrednio z analitykami i decydentami — to ludzie, z którymi pracuję od lat. Wracam do Ciebie z gotowym porównaniem: „w banku A dostaniesz 500 tys., w banku B — 800". Ty wybierasz, ja domykam.
> Właściciel hotelu szukający 60 mln obchodziłby rynek pół roku. Ja sprawdzam wszystkie realne instytucje w dwa dni.

**5 · Jak pracujemy (4 kroki — wersja skrócona z §2/07) + CTA „Umów rozmowę".**

### 3.3 OFERTA DLA POŚREDNIKÓW KREDYTOWYCH (B2B2B — „ma być wytłuszczone", M)

| # | Sekcja | Cel |
|---|---|---|
| 1 | Hero | rozpoznanie sytuacji w 1 sekundę |
| 2 | Jak to działa | 3 kroki, zero niejasności |
| 3 | Co zyskujesz | korzyści + obiekcja „podbierze mi klienta" |
| 4 | Jakie tematy biorę | zakres kompetencji |
| 5 | CTA | dedykowany kanał |

**1 · Hero:**
> **Masz temat, którego nie zrobisz? Znasz kogoś, kto zrobi.**
> Pośrednicy wymieniają się klientami od zawsze. Różnica jest taka, że ja biorę te tematy, których nie chce nikt.

**2 · Jak to działa:**
1. **Zgłaszasz temat** — telefonicznie, z tym co masz; nie potrzebuję kompletu dokumentów na start.
2. **Prowadzę sprawę** — albo układamy schemat rozmowy i robimy ją razem; Ty decydujesz, jak blisko chcesz być.
3. **Dzielimy się prowizją po sukcesie** — zasady ustalamy z góry, przed pierwszym krokiem.

**3 · Co zyskujesz:**
- **Nie zostawiasz klienta bez rozwiązania.** On to zapamięta — i wróci do Ciebie z następnym tematem.
- **Zarabiasz na sprawie spoza swojej specjalizacji**, nie kiwając palcem w produkcie, którego nie znasz.
- **Klient pozostaje Twój.** Mam portfel klientów, którzy są ze mną po 15–20 lat — nie buduję go na cudzych kontaktach. Robię temat i odsyłam klienta do Ciebie.

**4 · Jakie tematy biorę:** sprawy odrzucone przez banki i innych pośredników · pożyczki pod nieruchomość 1 mln+ · finansowanie z funduszy w 48 h · obligacje · restrukturyzacje · finansowanie zagraniczne (Szwajcaria, transakcje transgraniczne).
> *Zasada jest jedna: nie zostawiam tematu. Szukam rozwiązań, aż je znajdę.*

**5 · CTA:**
> **Masz temat? Zadzwoń — oboje na tym skorzystamy.**
> [telefon / formularz z zaznaczeniem „jestem pośrednikiem"]

### 3.4 O FIRMIE (etap 1: wizerunkowo, przez osobę; przepisanie na „usługową" w 2027 — decyzja warsztatowa)

| # | Sekcja | Cel |
|---|---|---|
| 1 | Hero-misja | jedno zdanie, które pozycjonuje |
| 2 | Historia Moniki | wiarygodność przez biografię |
| 3 | Wartości (5) | charakter firmy |
| 4 | Misja + wizja | zatwierdzone na warsztacie |
| 5 | Jak pracujemy — filozofia | butik, telefon, kontra-AI |
| 6 | Liczby + KNF + CTA | domknięcie |

**1 · Hero:**
> **Rozwiązujemy trudne sprawy kredytowe tam, gdzie inni pośrednicy rozkładają ręce.**

**2 · Historia:**
> Zaczynałam w bankach — i awansowałam razem z ludźmi, którzy dziś zasiadają w zarządach funduszy. Dlatego kiedy dzwonię w sprawie klienta, po drugiej stronie nie ma infolinii. Jest ktoś, kto wie, że jeśli dzwonię, to sprawa jest poważna.
> Przez 20 lat nauczyłam się najwięcej na sprawach, których nikt nie chciał. Nudzą mnie łatwe tematy. Trudne — układam jak puzzle: przekładam zabezpieczenia, zestawiam produkty, łączę instytucje, aż wszystko zagra.
> Nieraz dźwignęłam firmę, w którą nikt już nie wierzył — także wtedy, gdy komornik był już w drodze. Klienci to pamiętają: wracają po 15 i 20 latach. To jest dla mnie miara sukcesu. Wynagrodzenie jest drugorzędne.

**3 · Wartości (5 kart):**
- **Niezależność** — nie jesteśmy na pasku żadnego banku ani funduszu; mamy wejście wszędzie, więc wybieramy to, co najlepsze dla Ciebie.
- **Nieustępliwość** — doprowadzamy sprawy do końca. Nie ma „nie da się" — jest „jeszcze nie znalazłam jak".
- **Wiedza** — 20 lat na rynku i szkolenia niemal codziennie; o nowych produktach wiemy, zanim dowie się rynek.
- **Relacje** — klient to nie rekord w CRM. Osobisty doradca od A do Z, w czasach gdy inni chwalą się botami na infolinii.
- **Ambicja** — nowe instrumenty, nowe rynki, Szwajcaria, obligacje. Tam, gdzie inni widzą ścianę, my widzimy zadanie.

**4 · Misja i wizja (dosłowne, zatwierdzone):**
> **Misja:** Rozwiązywanie trudnych spraw kredytowych, dzielenie się doświadczeniem tam, gdzie inni pośrednicy rozkładają ręce.
> **Wizja:** Rynek, na którym przedsiębiorcy świadomie i chętnie korzystają z dostępnych możliwości finansowania. Wiedzą, że dzięki naszej pomocy mądre zarządzanie finansami przypomina układanie puzzli.

**5 · Jak pracujemy — filozofia:**
> Wszystkie sprawy prowadzę telefonicznie i mailowo. Nie dlatego, że nie lubię ludzi — dlatego, że szanuję Twój czas. Rozmawiamy, kiedy masz spokój, także po południu i w sobotę. Dyskretnie: o finansach firmy nie rozmawia się przy otwartych drzwiach.
> I nie jesteśmy porównywarką z botem. Po drugiej stronie zawsze jest człowiek, który zna Twoją sprawę.

**6 · Liczby (4 metryki z §2/05) + KNF:**
> Jesteśmy pośrednikiem zarejestrowanym w KNF — możesz nas sprawdzić po imieniu i nazwisku. [CTA: Poznajmy się]

### 3.5 KONTAKT

| # | Sekcja | Cel |
|---|---|---|
| 1 | Hero „Poznajmy się" | telefon pierwszym kanałem |
| 2 | Formularz | badawczy (pola z §2/11) |
| 3 | Czego się spodziewać po 1. rozmowie | komfort zamiast obietnicy oddzwonienia |
| 4 | Formalności | RODO, KNF, dane |

**1 · Hero:**
> **Poznajmy się.**
> Najszybsza droga to telefon: [numer — jeśli Monika zaakceptuje publikację]. Wolisz napisać? Formularz poniżej — oddzwonię osobiście.

**3 · Czego się spodziewać po pierwszej rozmowie:**
- Potrwa 2–3 minuty, jeśli masz pod ręką podstawowe informacje (przy nieruchomości: numer KW albo choć lokalizację i szacunkową wartość; kwotę, której potrzebujesz).
- Usłyszysz wstępną ocenę: czy temat jest do zrobienia, gdzie i na jakich warunkach.
- Nic nie podpisujesz i nic nie płacisz — wynagrodzenie pojawia się dopiero przy sukcesie, po umowie.

---

## §4. NAZWA FIRMY — propozycje

**Kryteria z warsztatów:** działa bez nazwiska w perspektywie 1–2 lat (ścieżka: Monika Buchacz → NAZWA by Monika Buchacz → NAZWA); brzmi premium i „przesiewa" drobne tematy; wyrazista („nie chcę no-name'u"); rozszerzalna o spółkę inwestorską (np. „X Capital"); rezonuje wśród pośredników; nie brzmi ani bankowo, ani chwilówkowo.

**Ocena obecnych roboczych:** Kredito/Credito — czytelna kategoria, ale brzmienie masowo-pożyczkowe (bliżej chwilówki niż premium 1 mln+), silna generyczność, **kredito.pl i credito.pl zajęte**.

| Nazwa | Uzasadnienie | Domena .pl | Kolizje (web) |
|---|---|---|---|
| **Fineza** ⭐ | od „finezji" — trudne sprawy układane z klasą; polskie słowo o premium brzmieniu; naturalna para: „Fineza Capital" dla spółki inwestorskiej; koresponduje z metaforą puzzli z wizji | **wolna** (fineza.pl; wolna też fineza.finance) | czysto w PL-finansach |
| **Rezolva** ⭐ | od „rozwiązywać" — misja wprost („rozwiązujemy trudne sprawy"); dynamiczne, kobieca energia | **wolna** (rezolva.pl) | czysto |
| **Kapitero** | kapitał + premium końcówka; czytelna kategoria bez „kredytowej" taniości | **wolna** (kapitero.pl) | czysto |
| **Findera** | „znajduję finansowanie — a jak nie mam dostępu, to je pozyskam" | **wolna** (findera.pl) | findera.com zajęta (wyszukiwarka firm, USA) — kolizja umiarkowana |
| **Credovia** | jeśli klientka chce zostać przy „kredytowym" rdzeniu — łagodniejsza, mniej masowa wersja | **wolna** (credovia.pl) | drobne kolizje: credovia.in (Indie), credovia.pro (USA) |
| **Kredona** | wariant swojski, blisko kategorii | **wolna** (kredona.pl) | drobna: Kredona Internationál (Słowacja, turystyka) |

Odrzucone po weryfikacji (zajęte domeny/marki): Solvero, Pontero, Pontis, Meritia, Altero, Solvia, Solventia, Credento, Finezo, Credana.

**Rekomendacja:** short-lista **Fineza / Rezolva / Kapitero** + test rynkowy Moniki na znajomych decydentach z branży i 2–3 klientach (rekomendacja procesowa z warsztatu; 2–3 tygodnie). Domeny wolnych kandydatek warto zarezerwować od razu po decyzji — są tanie, a znikają szybko.

---

## §5. WYTYCZNE WIZUALNE (z benchmarków i warsztatów)

- **Kierunek:** ciemne premium (burgund→czekolada→near-black, akcent pomarańcz) — jak dotychczas; energia + klasa. Revolut = wzór motion i odważnej typografii; mBank/PKO = wzór porządku architektury informacji i stopki formalnej; Notus/LoanHub = wzór sekcji zaufania (proces, opinie, FAQ) — przenosimy strukturę, nie masowy ton.
- **Most jako motyw:** obecne zdjęcia mostów (Manhattan/Brooklyn) przypadkowo trafiają w sedno — finansowanie pomostowe, „pomost do banku" (Exit Strategy). Zostawić świadomie jako motyw przewodni; docelowo sesja Moniki (jest sesja sprzed 2 lat do użycia roboczo).
- **Responsywność:** karty kwalifikacji przebudować z pozycjonowania absolutnego (px) na flex/grid — obecny kod jest kruchy na innych szerokościach ekranu.
- **Typografia:** Montserrat/Lato to placeholdery — docelowa para z moodboardów (cienki elegancki sans + editorial serif), dwa fonty w kombinacji.
- **Animacje scroll:** tak, ale z umiarem (Przemek: w referencjach „miejscami zbyt dużo").
- **Zero logotypów instytucji, zero kalkulatorów** na etapie 1 (kalkulator kredytów firmowych: etap 2, spec z warsztatu: 0–10 mln, 2 parametry, aktualizacja 1–2×/rok).

---

## §6. PYTANIA OTWARTE DO MONIKI (do najbliższej rozmowy)

1. **Nazwa firmy** — wybór z short-listy (Fineza / Rezolva / Kapitero) lub decyzja o pozostaniu przy Kredito mimo zajętych domen; potem rezerwacja domeny.
2. **Nazwa sekcji „szybka ścieżka"** — akceptacja rekomendacji (A) czy wariant B/C (§1 pkt 3).
3. **Numer telefonu publicznie** — tak/nie; jeśli tak: nav + hero + kontakt.
4. **CTA nawigacji** — „Umów rozmowę" czy „Zadzwoń".
5. **Tytułowanie** — „pośrednik finansowy" (tak w KNF) czy „ekspertka finansowania firm"?
6. **Pola formularza** — akceptacja listy z §2/11.
7. **Testimoniale** — namiar na opinie/artykuły u większych pośredników (W2) + 2–3 klientów do cytatu; akceptacja anonimizowanych case'ów (Pan Adam, hotel 60 mln).
8. **Akceptacja ujednoliconych obietnic czasowych** (2–3 min / 24–48 h / 2–5 dni) — te liczby będą wszędzie.
