# Model Przewidywania Cen Akcji

## Opis projektu
Ten projekt implementuje model uczenia maszynowego do przewidywania cen akcji przy użyciu sieci neuronowych LSTM (Long Short-Term Memory). Model wykorzystuje dane historyczne cen akcji i dokonuje prognozy na podstawie wcześniejszych wartości.

## Technologie
- Python
- Jupyter Notebook
- TensorFlow / Keras
- scikit-learn
- NumPy
- Pandas
- Matplotlib

## Jak uruchomić projekt?
### Klonowanie repozytorium
```sh
git clone https://github.com/TwojaNazwaUzytkownika/Model_Przewidywania_Cen_Akcji.git
cd Model_Przewidywania_Cen_Akcji
```
### Instalacja wymaganych bibliotek
```sh
pip install -r requirements.txt
```
### Uruchomienie notebooka
```sh
jupyter notebook
```
### Załadowanie danych
Załaduj dane historyczne (np. CSV) i uruchom wszystkie komórki w `Model_przewidywania_cen_akcji.ipynb`.

## Wyniki
- Model wizualizuje rzeczywiste i przewidywane ceny akcji.
- Wykorzystuje metryki oceny, takie jak RMSE, aby ocenić dokładność predykcji.

## Możliwe ulepszenia
- Dodanie danych fundamentalnych (np. raporty finansowe firm).
- Integracja z API giełdowymi (np. Alpha Vantage, Yahoo Finance).
- Testowanie innych architektur sieci neuronowych.
