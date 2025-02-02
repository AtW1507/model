# 📌 Opis projektu
Celem projektu jest analiza danych przy użyciu sieci neuronowej LSTM. Notebook zawiera kroki przetwarzania danych, normalizację, przygotowanie zestawu treningowego oraz budowę modelu. Kod zawiera również testy jednostkowe do weryfikacji poprawności funkcji.

📁 Struktura kodu
Przetwarzanie danych

Konwersja wartości liczbowych i tekstowych na odpowiednie typy danych.
Zamiana przecinków na kropki w wartościach liczbowych.

Normalizacja danych

Skalowanie wartości do zakresu (0,1) przy użyciu MinMaxScaler.
Przygotowanie zestawu treningowego

Tworzenie macierzy x_train i y_train w oparciu o okno czasowe.
Budowa modelu LSTM

Warstwy modelu:
Dwie warstwy LSTM (50 jednostek każda)
Dropout (0.2) dla regularizacji
Warstwa Dense do generowania wyników


📌 Uwagi
Dane powinny być w formacie CSV przed przetwarzaniem.
Model LSTM można dalej optymalizować poprzez dostosowanie hiperparametrów.
