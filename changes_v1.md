## Propozycja zmian v1: twardy deadline tylko dla medalu, reszta klasyfikacji bez zmian

Podsumowanie wprowadzonych zmian:

**§ 3 ust. 2** (nowy) - wzmianka, że rywalizacja medalowa kończy się 30.05.2026 o 21:59, z odesłaniem do szczegółów.

**§ 6 ust. 3** (nowy) + **ust. 6** - jednorazowa rejestracja, ważna w kolejnych edycjach. Konto pozostaje aktywne, chyba że zostanie usunięte (samodzielnie albo wg § 7 ust. 5).

**§ 7 ust. 2 pkt 8** + **ust. 6 pkt 6** (uzupełnienie) - wskazówki, że dla rywalizacji medalowej obowiązują twardsze terminy z § 10 ust. 3.

**§ 9 ust. 3** (przebudowany) - nazwa „nagroda roczna" zmieniona na „medal okolicznościowy", dodane jednoznaczne wyliczenie 12 miesięcy (z zaznaczeniem, że maj to 1–29 maja 2026), data wręczenia 31 maja 2026 wpisana wprost (zamiast samych „Dni Komornik 2026").

**§ 9 ust. 6 pkt 6** - analogicznie, data wręczenia medali wpisana wprost.

**§ 10 ust. 3** (nowy, kluczowy) - szczegółowe zasady rywalizacji medalowej:

- Jazda musi się zakończyć do 30.05.2026 21:59 (Europe/Warsaw)
- Aktywność musi być widoczna w Stravie do 30.05.2026 21:59 (wyłączenie 72h okna)
- Aktywności wgrane po terminie, ale spełniające pozostałe warunki, **nadal liczą się do rankingu rocznego i klasyfikacji majowej**
- Lista medalowa zamykana i publikowana 31 maja przed ceremonią
- Rekomendacja synchronizacji z zapasem czasu

**§ 11 ust. 5** - dostosowanie klauzuli RODO do jednorazowej rejestracji (przechowywanie danych również przez kolejne edycje).

**§ 12 ust. 5** (nowy) - termin na reklamacje medalowe: do 12:00 w niedzielę 31 maja, żeby dało się je rozpatrzyć przed ceremonią.

**Kompatybilność z systemem:** logika aplikacji nie wymaga zmian dla 99% przypadków - standardowe okno 72h zostaje. Jedyne, co aplikacja musi zrobić ekstra, to przy generowaniu listy medalowej 30 maja zastosować dodatkowy filtr: `activity_end_time <= 2026-05-30 21:59:59 Europe/Warsaw AND strava_upload_time <= 2026-05-30 21:59:59 Europe/Warsaw`. Reszta klasyfikacji (ranking roczny, maj jako miesiąc) używa tych samych zweryfikowanych aktywności bez modyfikacji.

Pytania dodatkowe - np. czy „widoczna dla systemu" w § 10 ust. 3 pkt 2 ppkt 2 powinno być sformułowane inaczej (bo technicznie webhook Stravy może mieć opóźnienie kilku minut - może warto dać margines, np. „przesłana do Stravy do 23:59, a system zweryfikuje do 01:00 dnia 30 maja"?).