# Predykcja odejścia klienta z banku (churn)

[Raport](https://bartoszoleszek.github.io/bank_churn_project/projekt_walidacja_churn.html)

Projekt został zrealizowany w ramach przedmiotu **Metody walidacji modeli statystycznych**, przy wykorzystaniu języka R. Celem było zbudowanie i ocena modeli predykcyjnych umożliwiających przewidywanie odejścia klienta z banku (`churn`) na podstawie jego cech demograficznych, finansowych i behawioralnych.

## Opis projektu

W projekcie wykorzystano rzeczywisty zbiór danych **Bank Customer Churn Prediction** (Kaggle), zawierający 10 000 obserwacji i 12 zmiennych. 

Zakres prac obejmował:

- eksploracyjną analizę danych,
- testy statystyczne (korelacje, testy U Manna–Whitneya, chi-kwadrat),
- selekcję cech z użyciem **Mutual Information** oraz **Boruta**,
- porównanie 5 klasyfikatorów (XGBoost, SVM, las losowy, regresja logistyczna, naiwny Bayes),
- ocenę wpływu metod balansowania (SMOTE, ROSE, oversampling, undersampling, brak balansowania),
- tuning hiperparametrów modelu **XGBoost** oraz walidację końcową na niezależnym zbiorze testowym.
