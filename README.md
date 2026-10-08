# Miejsca nalotów · Bochnia

Mobilna mapa punktów z warstw `bochnia.parki` i `bochnia.parki2` w bazie `gisss`.

## Mapa

Strona jest statyczna i hostowana przez GitHub Pages. Zawiera 11 lokalizacji zapisanych w `index.html`, przełączniki warstw, trzy podkłady mapowe (OpenStreetMap, ortofotomapa Geoportal/GUGiK i Esri World Imagery) oraz linki do Google Street View i wyznaczania trasy.

Warstwy zostały odczytane z bazy 8 października 2026 r. Punkty `parki2` mają w źródle jedynie `id` i geometrię, dlatego na mapie używają nazw „Punkt parki2 1–4”. Geometria tej warstwy jest zapisana w EPSG:2180 i na potrzeby mapy została przeliczona do WGS84 (EPSG:4326). Strona zawiera migawkę danych; ponowny odczyt bazy nie aktualizuje jej automatycznie.

## Publikacja

Workflow `.github/workflows/pages.yml` publikuje stronę po zmianie gałęzi `main`. W repozytorium należy wybrać **Settings → Pages → Source: GitHub Actions**. Po uruchomieniu publikacji strona będzie dostępna pod adresem `https://xoogklastry.github.io/bosnia/`.

