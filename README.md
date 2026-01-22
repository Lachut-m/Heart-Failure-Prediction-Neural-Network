# Predykcja niewydolności serca z wykorzystaniem sieci neuronowych (MLP)

Repozytorium zawiera projekt zaliczeniowy z przedmiotu **Podstawy Sieci Neuronowych**.
Celem pracy było stworzenie i optymalizacja modelu klasyfikacyjnego przewidującego wystąpienie choroby serca na podstawie 11 parametrów klinicznych.

## 👥 Autorzy
* **Michał Łachut** (280106)
* **Dawid Pajor** (280067)
* *Politechnika Wrocławska, W4*

## 📄 Zawartość repozytorium
Zgodnie z wymaganiami (Wariant #1), w repozytorium znajdują się:
1. **`Heart_Failure_Prediction_Model.ipynb`** – Główny kod projektu (Jupyter Notebook) zawierający preprocessing, modelowanie i eksperymenty.
2. **`Sprawozdanie_Koncowe.pdf`** – Szczegółowy raport z przebiegu prac inżynierskich.
3. **`Prezentacja_Projektu.pdf`** – Slajdy podsumowujące projekt.
4. **`heart.csv`** – Zbiór danych wykorzystany do treningu.

## 📊 Najważniejsze wyniki
* **Architektura:** MLP (64 -> Dropout(0.3) -> 32 -> 1)
* **Dokładność (Accuracy):** 89%
* **Czułość (Recall):** 91% (Wysoka skuteczność wykrywania chorych)
* **Wniosek:** Zastosowanie regularyzacji (Dropout) skutecznie wyeliminowało problem przeuczenia (Overfitting).

## 🛠️ Technologie
* Python 3.10
* TensorFlow / Keras
* Scikit-learn
* Pandas & NumPy
* Matplotlib & Seaborn
