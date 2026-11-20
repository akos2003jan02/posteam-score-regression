# NFL Posteam Score Regression

Kísérleti regressziós projekt NFL play-by-play adatokon: a notebook a csapat aktuális pontszámának (`posteam_score`) becslését vizsgálja.

## Tartalom

- `GépiLátásNFL.ipynb` – adatok előkészítése, jellemzők képzése és regressziós modell tanítása (HistGradientBoostingRegressor)
- `index.html` – egyszerű, statikus böngészős demó a predikciós felülethez

A notebook eredményei és a webes demó különállók: a demóban látható képlet szemléltető, nem a notebookban tanított modellhez kapcsolódik. A HTML-ben megjelenített metrikák statikus minták.

## Adatforrás

A notebook a [Kaggle NFL play-by-play 2009–2016 adatkészletét](https://www.kaggle.com/datasets/maxhorowitz/nflplaybyplay2009to2016) használja. Az adatokat külön kell letölteni; a dataset nincs a repóban. Kaggle hitelesítő adatot ne tölts fel a repóba.

## Futtatás

Nyisd meg a notebookot Google Colabban vagy Jupyterben, majd telepítsd a szükséges csomagokat, ha hiányoznak (`pandas`, `numpy`, `scikit-learn`, `matplotlib`). A Kaggle-adatkészlet eléréséhez állítsd be a saját Kaggle hozzáférést a környezetben.

A statikus demó megnyitható közvetlenül az `index.html` fájlból.
