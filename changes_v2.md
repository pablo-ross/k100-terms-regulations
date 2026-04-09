## Zmiana v2: zakończenie całego wydarzenia 30.05.2026 godz. 21:59

Data zmiany: 10 kwietnia 2026 r.

### Powód zmiany

Całe wyzwanie Komornicka 100 musi się zakończyć 30 maja 2026 r. o godz. 21:59 (nie tylko klasyfikacja medalowa). Jest to konieczne z powodu okresu niezbędnego na przejście na nowy sezon, z nowymi zasadami, bez konieczności rozliczania aktywności z poprzedniego sezonu dodanych w okresie nowego sezonu.

### Kluczowa zmiana koncepcyjna

Twardy deadline 30.05.2026 godz. 21:59 dotyczy teraz **całego wydarzenia i wszystkich klasyfikacji**, nie tylko medali. W poprzedniej wersji regulaminu wydarzenie trwało do 31 maja, a jedynie rywalizacja medalowa kończyła się wcześniej (30 maja godz. 21:59). Teraz nie ma rozróżnienia - wszystko kończy się jednocześnie.

### Szczegółowe zmiany w regulaminie

**§ 3 ust. 2** - Wydarzenie trwa do 30.05.2026 godz. 21:59 (było: 31.05.2026). Dodane odesłanie do § 10 ust. 3 ws. szczegółów zamknięcia klasyfikacji.

**§ 3 ust. 3** - Usunięty. Nie ma już osobnego wcześniejszego terminu zakończenia rywalizacji medalowej, bo cały event kończy się w tym samym momencie.

**§ 7 ust. 2 pkt 7** - Dodano zdanie o twardym terminie końca wydarzenia (§ 10 ust. 3), który jest nadrzędny wobec standardowego okna 72h na przesłanie aktywności do Stravy.

**§ 7 ust. 2 pkt 8** - Usunięty (dotyczył szczególnych zasad medalowych, które teraz nie istnieją jako odrębna kategoria).

**§ 7 ust. 6 pkt 6** - Zmienione z odwołania do rywalizacji medalowej na ogólne odwołanie do twardego terminu końca sezonu.

**§ 9 ust. 2 pkt 4** - Okres wiosenny: do 30 maja 2026 godz. 21:59 (było: 31 maja 2026).

**§ 9 ust. 3 pkt 2** - Okres rywalizacji medalowej = okres trwania wydarzenia (odesłanie do § 3 ust. 2), zamiast osobnej definicji dat.

**§ 9 ust. 3 pkt 3** - Drobna korekta redakcyjna: "do godz. 21:59" zamiast "godz. 21:59".

**§ 9 ust. 4 pkt 1** - Klasyfikacja roczna: do 30 maja 2026 godz. 21:59 (było: 31 maja 2026).

**§ 10 ust. 3** - Przebudowany z "Szczególne zasady rywalizacji o medal okolicznościowy" na **"Zasady zamknięcia klasyfikacji"**:
- Dotyczą teraz WSZYSTKICH klasyfikacji, nie tylko medali.
- Usunięty pkt 4 (o zaliczaniu aktywności do innych klasyfikacji mimo niezaliczenia do medali) - nieaktualny, bo wszystkie klasyfikacje kończą się jednocześnie.
- Usunięty pkt 6 z rekomendacją adresowaną do "Uczestników rywalizujących o medal" - teraz dotyczy wszystkich Uczestników.
- Zachowane reguły: jazda musi się zakończyć do 21:59, upload do Stravy do 21:59, brak 72h okna po zakończeniu wydarzenia.

**§ 10 ust. 4** - "w okresie rywalizacji medalowej" zmienione na "w okresie trwania wydarzenia".

**§ 13 ust. 5** - "rywalizacji o medal okolicznościowy" zmienione na "klasyfikacji końcowych".

**Data ostatniej zmiany** - zaktualizowana na 10 kwietnia 2026 r.

### Kompatybilność z systemem

Zmiana upraszcza logikę systemu. Zamiast dwóch osobnych terminów (event do 31.05, medal do 30.05 21:59) obowiązuje jeden twardy deadline dla wszystkiego: 30.05.2026 godz. 21:59. Po tym terminie system nie przyjmuje i nie weryfikuje żadnych nowych aktywności, niezależnie od klasyfikacji.

Filtr końcowy: `activity_end_time <= 2026-05-30 21:59:59 Europe/Warsaw AND strava_upload_time <= 2026-05-30 21:59:59 Europe/Warsaw` - stosowany teraz globalnie, nie tylko dla listy medalowej.
