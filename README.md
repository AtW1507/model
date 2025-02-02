# 📊 Raport projektu: Model LSTM dla analizy danych

📁 Struktura kodu
przetworz_dane(dataset: pd.DataFrame) -> pd.DataFrame
Konwertuje wartości liczbowe i tekstowe do odpowiednich formatów.
normalizuj_dane(trainset: np.ndarray) -> np.ndarray
Skaluje dane do zakresu (0,1).
przygotuj_zestaw_treningowy(data_scaled: np.ndarray, window: int = 70) -> tuple
Tworzy zestawy x_train i y_train dla modelu LSTM.
zbuduj_model_lstm(input_shape: tuple) -> Sequential
Tworzy i kompiluje model LSTM.


✅ Testy jednostkowe
Plik zawiera testy jednostkowe wykorzystujące unittest, które sprawdzają:

Poprawność konwersji danych (przetworz_dane).
Skalowanie wartości (normalizuj_dane).
Struktury danych dla modelu (przygotuj_zestaw_treningowy).
Poprawność warstw modelu LSTM (zbuduj_model_lstm).

📌 Uwagi
Dane powinny być w formacie CSV przed przetwarzaniem.
Testy jednostkowe pomagają w walidacji poszczególnych funkcji.
Model LSTM można dalej optymalizować poprzez dostosowanie hiperparametrów.
