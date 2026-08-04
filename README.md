# Mieszczuch
Znajdź wymarzone mieszkanie na wynajem (wkrótce również do kupna) w mgnieniu oka!

**Mieszczuch** to aplikacja desktopowa dla systemu Windows, która automatycznie wyszukuje i analizuje ogłoszenia mieszkań z serwisów **OLX** i **Otodom**.

Program pozwala pobierać pojedyncze ogłoszenia, całe wyniki wyszukiwania oraz obserwowane oferty, a następnie generuje przejrzysty raport z najważniejszymi informacjami.

## Najważniejsze funkcje

* pobieranie ofert z OLX i Otodom,
* import linków z pliku `linki.txt`,
* pobieranie całych wyników wyszukiwania OLX,
* import obserwowanych ofert,
* automatyczne pomijanie wcześniej pobranych ofert,
* raport HTML z wyszukiwaniem i filtrami,
* eksport do CSV, XLSX oraz PDF,
* zapisywanie ulubionych ofert,
* automatyczne aktualizacje programu,
* nowoczesny interfejs okienkowy,
* możliwość uruchamiania bez widocznego okna konsoli.

## Wymagania

Program działa na:

* Windows 10 lub Windows 11,
* połączeniu z Internetem.
* obie ręce

Przy pierwszym uruchomieniu aplikacja automatycznie:

* tworzy środowisko Python,
* instaluje wszystkie wymagane biblioteki,
* pobiera przeglądarkę Chromium używaną przez Playwright.

Użytkownik nie musi wykonywać tych czynności ręcznie.

## Wymagane biblioteki

Program korzysta z następujących pakietów Python:

* Playwright,
* BeautifulSoup4,
* lxml,
* openpyxl,
* reportlab,
* colorama.

## Uruchamianie

Uruchomić program przez:

```text
Mieszczuch.exe
```

## Generowane pliki

Po zakończeniu działania program tworzy między innymi:

* `oferty.html`
* `oferty.csv`
* `oferty.xlsx`
* `oferty.pdf`

## Informacja

Program przeznaczony jest do automatycznego zbierania i porównywania ofert mieszkań. Dane pobierane są z publicznie dostępnych ogłoszeń i prezentowane w postaci wygodnego raportu ułatwiającego ich analizę.
