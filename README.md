# ML Uppgift 1 – Housing project - Spår A

## Beskrivning
Detta projekt bygger en regressionsmodell för att förutsäga `median_house_value`
baserat på områdets egenskaper i Housing-datasetet.

Modeller som används:
- DummyRegressor - baseline
- Ridge
- RandomForestRegressor

Utvärdering sker med MAE och RMSE.

## Python-version
Python 3.13.7

## Reproducerbarhet

1. Skapa virtuell miljö:
   python -m venv .venv

2. Installera beroenden:
   pip install -r requirements.txt

3. Kör notebooken:
   Öppna `main.ipynb` och kör "Restart & Run All"