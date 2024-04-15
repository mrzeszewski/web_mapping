Materials for the course: **Web Mapping** 

## Why Web Mapping?
During the course, we will learn about techniques for publishing spatial information in the form of dynamic Internet maps. There are many reasons why this form of publication is actually dominant - convenience, the ability to make it available to a wide audience, dynamic content, the possibility of integration with Internet platforms and services (e.g. user geolocation) and, finally, the availability of a wide range of cartographic tools. The popularity of Internet cartography has resulted in the development of numerous technical solutions - the aim of this course is to present one of them. The tangible effect will be the creation of an internet map and its publication on the Internet.

## Topics of the classes
The list below presents a condensed version of what each block of classes includes, along with necessary materials and links to additional content.

1. **Introduction to the [Mapbox Platform](https://www.mapbox.com/) and creating a map style**
    - account registration (email from the university domain required)
    - spatial data structure in Mapbox: data sets, tiles, styles.
    - user interface, [tutorials](https://docs.mapbox.com/help/tutorials/), [examples](https://docs.mapbox.com/mapbox-gl-js/example/), [documentation ](https://docs.mapbox.com/),
    - [Mapbox Studio](https://studio.mapbox.com/) - available resources, map styling using components
    - **Task 1** - *create your own visually consistent style by changing the properties of components. Share as a preview*
2. **Edycja stylu mapy przy pocy warstw i dodawanie własnych danych**
   - zaawansowana edycja stylu przy pomocy warstw
   - dodawanie własnych danych i tworzenie zestawu kafelków
   - metody wizualizacji danych w Mapbox
   - import danych: formaty i wymogi
   - tworzenie i edycja danych przy pomocy [Edytora Mapbox](https://studio.mapbox.com/datasets/)
   - publikacja podglądu mapy
   - **Zadanie 2** - *Stwórz mapę pokazującą rozkład wskaźnika feminizacji na przykładzie Poznania. Wykorzystaj wizualizację 3D. Użyj [zestawu danych demograficznych dla Poznania](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/demography_poznan.geojson)*
3. **Zaawansowana stylizacja warstw**
   - stylizacja warstw liniowych i punktowych
   - stylizacja zależna od danych
   - mapy ciepła
   - grupy warstw
   - ikony i czcionki
   - style zależne od skali
4. **Publikacja mapy przy pomocy strony internetowej - Mapbox GL JS**
   - tworzenie własnej strony z mapą internetową na podstawie [przykładu prostej mapy Mapbox](https://docs.mapbox.com/mapbox-gl-js/example/simple-map/)
   - struktura strony internetowej (CSS, HTML)
   - podstawy skryptów Javascript
   - narzędzia developerskie przeglądarki
   - wprowadzenie do biblioteki Mapbox GL JS
   - **Zadanie 3** - *Opublikuj własny styl w postaci strony internetowej - pliku html*
5. **Dodawanie funkcji interaktywnych do mapy**
   - dodawanie funkcji interaktywnych do mapy - [przykład z popupami](https://docs.mapbox.com/mapbox-gl-js/example/popup-on-click/)
   - przełączanie warstw mapy przy pomocny funkcji Javascript - [przykład](https://docs.mapbox.com/mapbox-gl-js/example/toggle-layers/)
6. **Zadanie zaliczeniowe**
   - **Zadanie 4 - końcowy projekt** - *Zadanie w grupach 1-2 osoby. Stwórz i opublikuj własną stronę internetową zawierającą mapę na wybrany temat. Wykorzystaj dowoolne dane poza używanymi na zajęciach. Oceniane będzie część kartograficzna (czytelność, dobór kolorów i symboli, hierarchia wizulalna etc.) oraz część funkcjonalna (stopień interaktywności, dodane funkcje). *

## Dane przykładowe

1. [Województwa (plik poland_voivodships.geojson)](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/poland_voivodships.geojson)
_Granice województw i przykładowe dane atrybutowe._
2. [Dane demograficzne dla Poznania (plik demography_poznan.geojson)](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/demography_poznan.geojson)
_Dane ze spisu powszechnego 2011: Siatka z liczbą ludności, wiekiem i płcią._
3. [Pomniki przyrody w Poznaniu (plik natural_monuments.csv](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/natural_monuments.csv)
_Pomniki przyrody w okolicach Poznania z  GDOŚ - format CSV_
4. [Ikona oznaczenia pomnika przyrody (plik natural_monument.svg](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/natural_monument.svg)
_Ikona w formacie SVG_
5. [Dane z liczników rowerowych dla Poznania (plik liczniki_rowerowe_Poznan_21032024.geojson](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/liczniki_rowerowe_Poznan_21032024.geojson)
_Ikona w formacie SVG_
6. [Wartość emisji hałasu samochodoowego w Poznaniu - wskaźnik LN (plik halas_samochodowy_LN.geojson)](https://raw.githubusercontent.com/mrzeszewski/kartografia_internetowa/main/dane/halas_samochodowy_LN.geojson)
_Ikona w formacie SVG_

## Publikacja mapy w internecie - serwisy hostingowe
Na pewno w jakimś momencie trzeba stworzona mapę udostępnić publicznie. Do tego potrzebne jest miejsce na serwerze (hosting). Istnieje wiele platform, które umożliwiają darmowy hosting, jednak trzeba być ostrożnym (np. niechciane reklamy) i nie wszystkie są przyjazne dla użytkownika. Osobiście na początek polecam dwa sposoby publikacji:

1. [GitHub Pages](https://pages.github.com/) - bardzo prosty i elastyczny sposób publikacji strony w repozytorium GitHub (takiego jak to)
2. [Gitch](https://glitch.com/) - darmowe konto umożliwiające nie tylko publikacje statycznej strony ale i testowanie budowy aplikacji sieciowych 


## Alternatywne oprogramowanie
Mapbox został wybrany dlatego, że jest w miarę zamknięty rozwiązanie i do stworzenia czytelnej mapy o podstawowej funkcjonalności nie wymaga znajomości żadnego języka programowanie. Ale jeśli chcesz czegoś więcej to wystarczą podstawy Javascript, HTML i CSS a świat map internetowych stoi otworem. Podstawy tych trzech rzeczy potrzebne są również w przypadku wykorzystania Mapboxa w bardzije zaawansowany sposób. Alternatywne dla Mapboxa sposoby tworzenia map internetowych (w przypadkowej kolejności):

1. [Leaflet](https://leafletjs.com/) - jedna najpoularnieszyj bibliotek mapowych. Łatwa w implementacji, wiele rozszerzeń i integracji z oprogramowaniem GIS i nie tylko np.:
   - QGIS + [qgis2web plugin](https://plugins.qgis.org/plugins/qgis2web/) - przyjazna dla użytkownika wtyczka, pozwalająca na eksport projektu QGIS zarówno w postaci mapy wykonanej w Leaflet jak i w OpenLayers (patrz niżej)
   - R + [biblioteka Leaflet](https://rstudio.github.io/leaflet/) bardzo ciekawa opcja dla osób pracujących w środowisku programistycznym R
2. [ArcGIS Online](https://www.arcgis.com/index.html) - właśnościowa platforma umożliwiająca publikowanie map na wielu różnych sposobów (np. Story Maps), również za darmo w ograniczonym zakresie. Zaawansowane możliwości w połączniu z oprogramowanie ArcGIS/
3. [OpenLayers](https://openlayers.org/) - bardzo rozbudowana i bardzo dobrze opisana platforma mapowa, alternatywa dla Leaflet (choć wymaga nieco wiekszych umiejętności programistycznych)
4. [MapLibre](https://maplibre.org/) - Open Source wersja bibliotek programistycznych Mapbox GL JS. Jeśli nie są potrzebne usługi Mapbox takie jak Studio a celem jest stworzenie czytelnej i funkcjonalne mapy na strone to przy posiadaniu znajomości Javascript warto sie zainteresować bezpłatną alternatywą.


## Do poczytania

1. [Kurs HTML W3Schools](https://www.w3schools.com/html/)
2. [Kurs CSS W3Schools](https://www.w3schools.com/css/)
3. [Kurs Javascript W3Schools](https://www.w3schools.com/js/)
