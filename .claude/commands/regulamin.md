# Regulamin — wytyczne redakcji i przeglądu

Skill do tworzenia i przeglądu polskich regulaminów wydarzeń sportowych — w szczególności wirtualnych wyzwań kolarskich/biegowych z weryfikacją aktywności przez Stravę i podobne platformy. Używaj przy każdej edycji plików `terms-*.md` oraz załączników do nich.

## 1. Workflow przeglądu regulaminu

Przy każdej edycji lub review wykonuj kroki w kolejności:

1. **Zidentyfikuj typ wydarzenia** — masowe vs niemasowe, stacjonarne vs wirtualne, jednorazowe vs cykliczne (sezonowe). To determinuje obowiązki.
2. **Sprawdź ramy prawne** (sekcja 2) — czy wszystkie obowiązujące akty są uwzględnione.
3. **Zweryfikuj strukturę** (sekcja 3) — czy wszystkie obowiązkowe sekcje są obecne.
4. **Przeskanuj pod kątem klauzul abuzywnych** (sekcja 7) — to jest zawsze największe ryzyko prawne.
5. **Sprawdź checklist publikacyjny** (sekcja 10) — przed wypchnięciem zmiany.
6. **Sprawdź spójność** z załącznikami (nagrody, progi, terminy) i z formularzem rejestracji.
7. **Zaktualizuj datę "Ostatnia zmiana"** i — jeśli zmiana jest istotna — zaplanuj 7-dniowe powiadomienie uczestników.

## 2. Ramy prawne (obowiązkowe)

Regulamin sportowy/eventowy w Polsce podlega przede wszystkim:

- **Kodeks cywilny art. 384 i nast.** — wzorzec umowy; musi być doręczony lub udostępniony przed zawarciem umowy w sposób umożliwiający jego przechowywanie i odtwarzanie.
- **Kodeks cywilny art. 3851** — klauzula generalna: postanowienia nieuzgodnione indywidualnie nie wiążą konsumenta, jeśli kształtują jego prawa i obowiązki sprzecznie z dobrymi obyczajami i rażąco naruszają jego interesy.
- **Kodeks cywilny art. 3853** — szara lista klauzul niedozwolonych (24 punkty); szczególnie istotne dla regulaminów sportowych: pkt 1 (wyłączenie odpowiedzialności za szkody na osobie), pkt 2 (wyłączenie odpowiedzialności za niewykonanie umowy), pkt 12 (brak zwrotu opłaty za świadczenie niezrealizowane), pkt 19 (jednostronna zmiana wzorca bez ważnej przyczyny), pkt 23 (sąd właściwy dla siedziby przedsiębiorcy).
- **Ustawa z 18.07.2002 o świadczeniu usług drogą elektroniczną (UŚUDE) art. 8** — regulamin musi być nieodpłatnie udostępniony przed zawarciem umowy w sposób umożliwiający jego pozyskanie, odtwarzanie i utrwalanie (np. PDF do pobrania, możliwość wydruku).
- **Ustawa z 30.05.2014 o prawach konsumenta art. 38 pkt 12** — przy umowach zawieranych na odległość uczestnikowi NIE przysługuje prawo odstąpienia od umowy o świadczenie usług związanych z wydarzeniami sportowymi, jeżeli w umowie oznaczono dzień lub okres świadczenia. Mimo to nie wolno wyłączać prawa do zwrotu wpisowego za świadczenie niewykonane (art. 3853 pkt 12 KC).
- **RODO (rozporządzenie 2016/679) art. 13** — pełna klauzula informacyjna jako sekcja regulaminu lub osobny dokument z linkiem; minimalne elementy w sekcji 6 poniżej.
- **Ustawa z 20.03.2009 o bezpieczeństwie imprez masowych** — dotyczy TYLKO imprez masowych (progi: ≥1000 osób na stadionie, ≥300 w hali sportowej dla imprez sportowych). Dla typowych wirtualnych wyzwań i lokalnych wydarzeń kolarskich NIE ma zastosowania.
- **Ustawa o ochronie konkurencji i konsumentów** — bezskuteczność klauzul abuzywnych z mocy prawa, kary do 10% rocznego obrotu nakładane przez Prezesa UOKiK.
- **Kodeks cywilny art. 81 ust. 1 ustawy o prawie autorskim i prawach pokrewnych** — zgoda na rozpowszechnianie wizerunku jest wymagana; zgoda powinna być wyraźna i wyrażona dobrowolnie.

### 2.1. Impreza masowa vs niemasowa

| Cecha | Masowa | Niemasowa |
|---|---|---|
| Próg uczestników (sport, hala) | ≥300 | <300 |
| Próg uczestników (sport, stadion) | ≥1000 | <1000 |
| Zezwolenie wójta/burmistrza | wymagane | nie |
| Obowiązkowe OC organizatora | tak | nie (zalecane dobrowolne) |
| Służby porządkowe i informacyjne | wymagane | nie (ale odpowiedzialność cywilna pozostaje) |
| Ustawa o bezpieczeństwie imprez masowych | stosuje się | nie stosuje się |

Wirtualne wyzwania (np. comiesięczne wbijanie kilometrów na Stravie) **nie są imprezami masowymi w rozumieniu ustawy** — uczestnicy nie gromadzą się fizycznie w jednym miejscu. Reguluje je natomiast pełen zakres prawa cywilnego, RODO, UŚUDE i ochrony konsumenta.

## 3. Obowiązkowe sekcje regulaminu wydarzenia sportowego

1. **Postanowienia ogólne** — nazwa, organizator (pełne dane: nazwa, adres, NIP, REGON, KRS jeśli dotyczy, e-mail kontaktowy, numer telefonu), cel wydarzenia, sezon/daty obowiązywania.
2. **Definicje pojęć** — kluczowe terminy: Uczestnik, Aktywność, Trasa, Sezon, System, Strava, Webhook, Klasyfikacja, Punkty.
3. **Uczestnictwo i rejestracja** — kto może uczestniczyć (wiek, ograniczenia), procedura rejestracji, ważność rejestracji (bieżący i kolejne sezony), wymóg posiadania konta na platformie zewnętrznej (Strava), wyrejestrowanie ze wskazaniem strony `/unregister`.
4. **Małoletni** — granica wieku, wymóg pisemnej zgody przedstawiciela ustawowego, odpowiedzialność rodzica/opiekuna, sposób przekazania zgody.
5. **Zasady weryfikacji aktywności** — wymagania techniczne (urządzenie z GPS), procedura automatyczna (webhook), tolerancje GPS, dryf, minimalna liczba punktów śladu, wymóg ciągłości zapisu, zasady ręcznej weryfikacji.
6. **System punktowy / klasyfikacja** — tabele punktów, bonusy, mnożniki sezonowe, rozstrzyganie remisów, klasyfikacje pomocnicze.
7. **Nagrody i wyróżnienia** — kryteria, terminy ogłoszenia, zasady odbioru, ekwiwalent pieniężny lub jego brak, wartości nagród (kwestia podatkowa — art. 30 ust. 1 pkt 2 ustawy o PIT, zwolnienie do 2280 zł dla nagród w sportach amatorskich, jeśli dotyczy).
8. **Wizerunek uczestnika** — wyraźna zgoda na utrwalanie i rozpowszechnianie wizerunku z wydarzenia (zdjęcia, filmy), zakres (strona, social media, materiały promocyjne), prawo wycofania zgody, podstawa: art. 81 prawa autorskiego.
9. **Ochrona przed nadużyciami** — mechanizmy (np. detekcja silnika elektrycznego po prędkości średniej, anomalia kadencji, dryfy GPS), procedura podejrzenia, prawo do ręcznej weryfikacji, sankcje proporcjonalne (ostrzeżenie → unieważnienie aktywności → wykluczenie z sezonu), prawo odwołania.
10. **Reklamacje** — kanał zgłoszenia (e-mail, formularz), termin rozpatrzenia max **30 dni** (zgodnie z art. 7a ustawy o prawach konsumenta), forma odpowiedzi, niedopuszczalność narzucania formy pisemnej jako jedynej.
11. **Klauzula informacyjna RODO** — zgodnie z art. 13 RODO, elementy w sekcji 6 poniżej.
12. **Zasady przekazywania danych do państw trzecich** — jeśli używana jest Strava lub inne usługi z USA, należy poinformować o transferze danych do państw trzecich i podstawie prawnej (np. standardowe klauzule umowne, decyzja Komisji o adekwatności — Data Privacy Framework).
13. **Postanowienia końcowe** — zmiana regulaminu (z wyprzedzeniem 7 dni i zamkniętym katalogiem powodów), siła wyższa, ograniczenie odpowiedzialności (NIE wyłączenie), prawo właściwe (polskie), jurysdykcja ogólna (NIE narzucanie sądu organizatora), data wejścia w życie.

## 4. Wirtualne wyzwania i weryfikacja Strava — wytyczne specjalne

Dla wyzwań opartych o automatyczną weryfikację aktywności należy zawrzeć:

- **Wymóg konta na platformie zewnętrznej** (Strava) jako warunek techniczny uczestnictwa.
- **Wymóg autoryzacji webhooka** — uczestnik wyraźnie autoryzuje organizatora do odbierania danych aktywności przez Strava API.
- **Obowiązki uczestnika**: nagrywanie aktywności od początku do końca, brak edycji ręcznej trasy, brak importu z innych źródeł, ustawienie aktywności jako co najmniej "Followers" (nie "Only You", bo wtedy webhook nie zadziała).
- **Tolerancje techniczne**:
  - Dopuszczalny dryf GPS (np. ±5% długości trasy referencyjnej).
  - Minimalna gęstość punktów śladu.
  - Maksymalna luka czasowa w zapisie.
- **Powody odrzucenia aktywności** — zamknięty katalog: brak GPS, edycja po fakcie, niezgodność z trasą, prędkość średnia poza progiem fizycznym dla danej dyscypliny, brak punktów kontrolnych.
- **Procedura odwołania** — uczestnik ma prawo zażądać ręcznej weryfikacji w terminie X dni od decyzji systemu.
- **Awaria platformy zewnętrznej** — co się dzieje, gdy Strava webhook nie działa po stronie Stravy. Organizator nie ponosi odpowiedzialności za awarię platformy zewnętrznej, ale zobowiązuje się do podjęcia próby ręcznej weryfikacji.
- **Brak gwarancji ciągłości usługi Strava** — informacja, że organizator nie ma wpływu na zmiany API Stravy lub jej regulaminu.

## 5. Procedura zmiany regulaminu (wymagana)

- **Zamknięty katalog powodów zmiany** — np. zmiana przepisów prawa, zmiana technologii weryfikacji, korekta błędów redakcyjnych, doprecyzowanie zasad. To kluczowy wymóg, by uniknąć abuzywności (zgodnie z art. 3853 pkt 19 KC).
- **Powiadomienie uczestników z co najmniej 7-dniowym wyprzedzeniem** — e-mail i ogłoszenie na stronie głównej.
- **Prawo wyrejestrowania się** przed wejściem zmian w życie bez konsekwencji.
- **Zachowanie nabytych praw** — punkty zdobyte przed zmianą zasad nie są retroaktywnie unieważniane.

## 6. RODO — minimalna treść klauzuli informacyjnej (art. 13 RODO)

Sekcja musi zawierać:

1. **Administrator danych** — pełne dane organizatora.
2. **Inspektor ochrony danych** — dane kontaktowe, jeśli wyznaczony (dla podmiotów publicznych obowiązkowy).
3. **Cele przetwarzania i podstawy prawne**:
   - Realizacja umowy o uczestnictwo — art. 6 ust. 1 lit. b RODO.
   - Wypełnienie obowiązków prawnych (np. księgowość) — art. 6 ust. 1 lit. c RODO.
   - Marketing własny i wizerunek — art. 6 ust. 1 lit. a (zgoda).
   - Uzasadniony interes (np. dochodzenie roszczeń) — art. 6 ust. 1 lit. f.
4. **Kategorie odbiorców** — Strava, dostawca hostingu, dostawca poczty, ewentualnie partnerzy nagrodowi.
5. **Transfer do państw trzecich** — Strava (USA), podstawa transferu.
6. **Okres przechowywania** — konkretny: np. „do końca sezonu i przez 5 lat po jego zakończeniu w celach archiwizacji wyników historycznych".
7. **Prawa uczestnika** — dostęp, sprostowanie, usunięcie, ograniczenie, przenoszenie, sprzeciw, cofnięcie zgody.
8. **Prawo skargi do PUODO** — Prezes Urzędu Ochrony Danych Osobowych, ul. Stawki 2, 00-193 Warszawa.
9. **Profilowanie i automatyczne decyzje** — czy występuje (np. automatyczne odrzucenie aktywności przez system) i jak uczestnik może je zakwestionować.
10. **Dobrowolność lub wymóg podania danych** — informacja, że bez podanych danych uczestnictwo nie jest możliwe.

## 7. Klauzule abuzywne — czego unikać

Klauzula abuzywna jest bezskuteczna z mocy prawa i naraża organizatora na karę UOKiK do 10% rocznego obrotu.

| Niedozwolony zapis | Problem | Podstawa |
|---|---|---|
| „Organizator zastrzega prawo do zmiany regulaminu w dowolnym czasie." | Brak powodów + brak prawa do rezygnacji uczestnika. | art. 3853 pkt 19 KC |
| „Organizator nie ponosi żadnej odpowiedzialności." | Całkowite wyłączenie — niedopuszczalne; ograniczyć do siły wyższej i działań osób trzecich. | art. 3853 pkt 1 i 2 KC |
| „Wpisowe nie podlega zwrotowi w żadnym wypadku." | Wyłącza zwrot za świadczenie niewykonane. | art. 3853 pkt 12 KC |
| „Reklamacje wyłącznie pisemnie w 7 dni." | Skrócenie terminu ustawowego; narzucenie formy. | art. 7a ustawy o prawach konsumenta |
| „Spory rozstrzyga sąd w Komornikach." | Klauzula abuzywna wobec konsumentów. | art. 3853 pkt 23 KC |
| „Organizator dokonuje wiążącej interpretacji regulaminu." | Jednostronna interpretacja umowy. | art. 3853 pkt 9 KC |
| „Akceptując regulamin, uczestnik akceptuje również regulamin Stravy." | Związanie regulaminem podmiotu trzeciego bez możliwości zapoznania. | decyzja UOKiK RKT-... |
| „Udział na własną odpowiedzialność, organizator nie odpowiada za szkody na zdrowiu." | Wyłączenie odpowiedzialności za szkody osobiste — bezwzględnie niedozwolone. | art. 3853 pkt 1 KC |
| „Organizator może wykluczyć uczestnika bez podania przyczyny." | Arbitralne rozwiązanie umowy. | art. 3853 pkt 14 KC |

**Ważne**: oświadczenie „udział na własną odpowiedzialność" jest dopuszczalne jako element informacyjny i deklaracja zdrowotna, ale **nie wyłącza** odpowiedzialności organizatora za jego własne zaniedbania.

## 8. Język i styl

- **Prosty, zrozumiały język** — czytelny dla przeciętnego uczestnika, nie tylko prawnika.
- **Strona czynna** — „Organizator wyśle e-mail" zamiast „e-mail zostanie wysłany".
- **Konkrety z liczbami** — daty, terminy, progi punktowe, mierzalne wartości; unikaj ogólników jak „w rozsądnym czasie", „odpowiednio", „w miarę możliwości".
- **Krótkie zdania** — jedna myśl na zdanie.
- **Formatowanie** — ponumerowane paragrafy, tabele dla danych liczbowych, wypunktowania dla list.
- **Definicje przed użyciem** — wyjaśniaj termin zanim po raz pierwszy go użyjesz.
- **Zwykłe myślniki** — nie używaj `—` w tekście regulaminu, jedynie `-`.
- **Spójność terminologii** — jeśli zdefiniowałeś „Uczestnik" wielką literą, używaj konsekwentnie wielkiej litery przy każdym odwołaniu.
- **Zasada: paragraf, ustęp, punkt**:
  - Paragraf (§): Podstawowa jednostka. Zapis: § 1. (w tekście), powołanie: „w § 1" (bez kropki).
  - Ustęp (ust.): Dzieli paragraf. Zapis: 1., 2. (cyfra z kropką). Powołanie: „§ 1 ust. 1".
  - Punkt (pkt): Dzieli ustęp. Zapis: 1), 2) (cyfra z nawiasem). Powołanie: „§ 1 ust. 1 pkt 1".
  - Litera (lit.): Dzieli punkt. Zapis: a), b). Powołanie: „§ 1 ust. 1 pkt 1 lit. a".

## 9. Dostępność i akceptacja regulaminu

- **Udostępnienie przed rejestracją** — link do regulaminu musi być widoczny przed kliknięciem „Zarejestruj się".
- **Możliwość pobrania** — wersja PDF lub możliwość zapisania strony.
- **Aktywna akceptacja** — checkbox „Zapoznałem się z regulaminem i akceptuję jego postanowienia" niezaznaczony domyślnie. Osobny checkbox dla zgody na wizerunek (jeśli wymagana) i osobny dla marketingu.
- **Log akceptacji** — zapisanie timestampu, wersji regulaminu i identyfikatora uczestnika w bazie danych jako dowód zawarcia umowy.
- **Wersjonowanie** — każda zmiana regulaminu = nowa wersja z numerem (np. 2.1.0) i datą; ponowna akceptacja przy istotnych zmianach.

## 10. Checklist przed publikacją

- [ ] Dane organizatora kompletne (nazwa, adres, NIP, REGON, KRS jeśli dotyczy, e-mail, telefon).
- [ ] Daty sezonu i wejścia w życie regulaminu podane wprost.
- [ ] Wskazany typ wydarzenia (masowe / niemasowe).
- [ ] Ważność rejestracji (bieżący + kolejne sezony) i możliwość wyrejestrowania ze wskazaniem strony `https://komornicka100.pl/unregister`.
- [ ] Sekcja dotycząca małoletnich (jeśli mogą uczestniczyć) z wymogiem zgody opiekuna.
- [ ] Sekcja techniczna weryfikacji aktywności z konkretnymi tolerancjami GPS.
- [ ] RODO: administrator, podstawy prawne (z numerami artykułów), prawa uczestnika, kontakt do PUODO, okres przechowywania, transfer do państw trzecich (Strava/USA).
- [ ] Zgoda na wizerunek wyraźnie wydzielona, z prawem wycofania.
- [ ] Reklamacje: kanał + termin max 30 dni + brak narzucenia formy pisemnej.
- [ ] Tryb zmian regulaminu: zamknięty katalog powodów, min. 7 dni wyprzedzenia, prawo wyrejestrowania.
- [ ] Sankcje za nadużycia proporcjonalne, z prawem odwołania.
- [ ] Brak klauzul abuzywnych (przejrzeć tabelę z sekcji 7).
- [ ] Prawo właściwe i jurysdykcja zgodne z ustawą (brak narzucania sądu organizatora).
- [ ] Spójność z formularzem rejestracyjnym (checkboxy zgodne z sekcjami regulaminu).
- [ ] Numer wersji i data „Ostatnia zmiana" aktualne.

## 11. Dobre praktyki cykliczne

- **Audyt roczny** — przed startem nowego sezonu pełny review pod kątem zmian w przepisach.
- **Monitorowanie rejestru klauzul UOKiK** — sprawdzaj nowe decyzje Prezesa UOKiK w bazie decyzji (rejestr historyczny zamknięty po 2026, aktualne decyzje na stronie UOKiK).
- **Konsultacja z DPO/IOD** — przy każdej zmianie sposobu przetwarzania danych.
- **Test usability** — czy uczestnik znajdzie odpowiedź na typowe pytanie w mniej niż 60 sekund.
- **Wersjonowanie w git** — każda zmiana to commit z opisem powodu.


## Specyfika Komornicka 100

- Regulamin obowiązuje przez cały sezon; **jedna rejestracja jest ważna bezterminowo** (bieżący sezon i wszystkie kolejne), chyba że uczestnik się wyrejestruje.
- Dane aktywności sportowej (GPS, tętno) mogą stanowić dane dotyczące zdrowia w rozumieniu RODO — przetwarzaj z odpowiednią podstawą prawną (zgoda lub wykonanie umowy).
- Strava jest zewnętrzną platformą — regulamin powinien wskazywać, że Organizator nie ponosi odpowiedzialności za awarie lub zmiany polityki Stravy.
