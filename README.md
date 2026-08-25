# GTFS Łódź Suburban

**[ENG] Unofficial GTFS Schedule feed for suburban and regional bus services around Łódź, Poland.**

## Aktualny feed GTFS Łódź Suburban

**`gtfs-lodz-suburban.zip`**

Feed jest przygotowywany zgodnie ze specyfikacją **GTFS Schedule**. Obejmuje wybrane połączenia autobusowe z Łodzi do miejscowości i gmin położonych w jej otoczeniu, a także wybrane dalsze połączenia regionalne.

## O projekcie

Celem projektu jest zebranie i udostępnienie w ujednoliconym, maszynowo odczytywalnym formacie GTFS informacji o połączeniach autobusowych związanych z Łodzią i jej obszarem podmiejskim.
Zakres projektu obejmuje w szczególności połączenia pomiędzy Łodzią a okolicznymi miejscowościami i gminami. W przyszłości może być rozszerzany o kolejne kierunki i dalsze połączenia regionalne.

Projekt ma charakter **nieoficjalny i hobbystyczny**. Autor nie jest przewoźnikiem ani organizatorem przewozów.

## Zakres danych

Projekt jest rozwijany stopniowo. W pierwszej wersji obejmuje połączenia na linii Łódź-Tuszyn. 

W przyszłości zakres może zostać rozszerzony o inne miejscowości i połączenia regionalne związane z Łodzią.
Lista miejscowości i linii nie jest zamknięta i będzie zmieniać się wraz z rozwojem projektu. Historię zmian określa plik `CHANGELOG`.

## Źródła danych

Dane zawarte w tym repozytorium są **opracowaniem własnym na podstawie publicznie dostępnych informacji o rozkładach jazdy**.
Źródłem danych mogą być w szczególności:

* oficjalne strony internetowe urzędów miast i gmin,
* strony internetowe przewoźników,
* publicznie dostępne pliki z rozkładami jazdy, w tym PDF i JPG,
* oficjalne profile przewoźników lub organizatorów w mediach społecznościowych,
* inne publicznie dostępne materiały zawierające informacje o rozkładach jazdy.

Informacje te są przetwarzane i porządkowane do postaci danych zgodnych ze specyfikacją **GTFS Schedule**, umożliwiających ich maszynowe odczytywanie i wykorzystywanie przez oprogramowanie oraz aplikacje transportowe.

## Aktualizacja danych

Dane mogą być aktualizowane w przypadku:

* publikacji nowych rozkładów jazdy,
* zmian w istniejących rozkładach,
* dodania kolejnych linii lub połączeń,
* wykrycia błędów w dotychczas opublikowanych danych.

Wersja danych oraz okres ich obowiązywania są określane wewnątrz pliku GTFS.

## Status projektu

Projekt jest aktywnie rozwijany.

Aktualny zakres:
- komunikacja podmiejska wokół Łodzi,
- przygotowanie danych w formacie GTFS Schedule,
- publiczne wydania na GitHub.

Planowane:
- rozszerzenie zasięgu na kolejne linie podmiejskie oraz regionalne z okolic Łodzi,
- rozbudowa danych poprzez dodanie shapes.txt.

## Ważne informacje

Dane zawarte w tym repozytorium **nie są oficjalnym źródłem informacji o rozkładach jazdy**.

Pomimo dokładania starań w celu zachowania zgodności z oficjalnie publikowanymi rozkładami, mogą występować błędy, opóźnienia w aktualizacji danych lub różnice wynikające ze zmian wprowadzonych przez przewoźnika lub organizatora.

W przypadku rozbieżności pomiędzy danymi zawartymi w tym repozytorium a aktualnym oficjalnym rozkładem jazdy **wiążący jest zawsze rozkład opublikowany przez właściwego przewoźnika lub organizatora przewozów**.

Jeżeli zauważysz błąd, nieaktualne dane lub inną rozbieżność, prosimy o zgłoszenie tego faktu na adres e-mail: [qbx.timetables@gmail.com](mailto:qbx.timetables@gmail.com)

## Stabilny adres feedu

Najnowsza wersja feedu GTFS jest zawsze dostępna pod poniższym adresem:

https://raw.githubusercontent.com/qbx-tt/gtfs-lodz-suburban/main/gtfs-lodz-suburban.zip

Adres ten pozostaje niezmienny pomimo kolejnych aktualizacji danych i może być wykorzystywany przez aplikacje oraz serwisy automatycznie pobierające feed GTFS.

**Repozytorium projektu:** 
https://github.com/qbx-tt/gtfs-lodz-suburban

## Licencja

Dane udostępniane w ramach projektu są przeznaczone do dalszego wykorzystywania zgodnie z warunkami określonymi w pliku `LICENSE`.

Należy pamiętać, że niniejszy projekt stanowi opracowanie danych pochodzących z publicznie dostępnych źródeł. Warunki wykorzystania danych źródłowych mogą podlegać prawom lub warunkom określonym przez ich pierwotnych autorów, przewoźników lub organizatorów.

## Kontakt

W sprawach dotyczących danych, zgłaszania błędów oraz propozycji uzupełnienia feedu:

**QBX Timetables** - e-mail: **[qbx.timetables@gmail.com](mailto:qbx.timetables@gmail.com)**

---

### Disclaimer

**QBX Timetables is an independent, unofficial project of Łódź Suburban & Regional transport and is not affiliated with, operated by, or endorsed by any transport operator or public transport authority whose services may be represented in the data.**

**The feed covers suburban bus routes around Łódź and is maintained as an independent community GTFS feed based on publicly available timetable data.**
