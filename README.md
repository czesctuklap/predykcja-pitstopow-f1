# Predykcja pit stopu w Formule 1

Projekt przedstawia proces budowy modelu uczenia maszynowego przewidującego moment wykonania pit stopu podczas wyścigu Formuły 1. Analiza została przeprowadzona na podstawie danych telemetrycznych oraz strategicznych, a cały proces obejmuje przygotowanie danych, eksploracyjną analizę, trenowanie modelu oraz ocenę jego jakości.

## Cele projektu

- analiza danych dotyczących wyścigów Formuły 1,
- przygotowanie zbioru danych do uczenia maszynowego,
- przewidywanie momentu wykonania pit stopu,
- ocena jakości modelu klasyfikacyjnego,
- interpretacja wpływu poszczególnych cech na predykcję.

## Technologie

Projekt został zrealizowany z wykorzystaniem:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Zakres projektu

### Analiza danych

Projekt rozpoczyna się od eksploracyjnej analizy danych (EDA), obejmującej:

- analizę struktury danych,
- statystyki opisowe,
- identyfikację brakujących wartości,
- wizualizację rozkładów wybranych zmiennych.

### Przygotowanie danych

Przed trenowaniem modelu wykonano:

- podział na zbiór treningowy i testowy,
- kodowanie zmiennych kategorycznych,
- skalowanie danych numerycznych,
- przygotowanie danych do uczenia.

### Model uczenia maszynowego

Do rozwiązania problemu wykorzystano klasyfikator **Random Forest**, który został wytrenowany na przygotowanym zbiorze danych.

Model służy do przewidywania momentu wykonania pit stopu na podstawie cech opisujących przebieg wyścigu.

### Ocena modelu

Skuteczność modelu została oceniona z wykorzystaniem:

- dokładności (Accuracy),
- macierzy pomyłek (Confusion Matrix),
- analizy wyników predykcji.

### Interpretacja wyników

Projekt zawiera analizę ważności cech (Feature Importance), pozwalającą określić, które zmienne mają największy wpływ na decyzję modelu.
