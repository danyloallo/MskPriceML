# 🇷🇺 Russian Version 

# 🏙️ Анализ цен на жильё в Москве

Этот проект посвящён анализу факторов, влияющих на стоимость жилья в Москве, с использованием данных с платформы [Kaggle](https://www.kaggle.com/). Были проведены: предварительная обработка данных, визуализация, статистический анализ и построение модели прогнозирования цены.

---

## 📊 Описание проекта

**Цель**: определить ключевые факторы, влияющие на цену недвижимости, и построить модель, способную предсказывать стоимость жилья на основе этих факторов.

---

## 🗂️ Используемые данные

- Источник: Kaggle
- Формат: CSV
- Целевая переменная: `price` — цена квартиры
- Основные признаки:
  - `totsp` — общая площадь
  - `livesp` — жилая площадь
  - `kitsp` — площадь кухни
  - `dist` — расстояние до центра
  - `metrdist` — расстояние до метро
  - `brick`, `floor`, `walk` — категориальные признаки (тип дома, этаж, пешая доступность)

---

## ⚙️ Используемые технологии

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

---

## 📈 Основные этапы

1. **Предобработка данных**:
   - Удаление лишних столбцов
   - Проверка и удаление выбросов
   - Проверка типов данных и пропусков

2. **EDA (Exploratory Data Analysis)**:
   - Анализ корреляции между признаками
   - Визуализация распределений и зависимостей
   - Выявление аномалий

3. **Статистический анализ**:
   - Проверка гипотез (t-test) по категориальным признакам
   - Анализ значимости признаков

4. **Построение моделей**:
   - Линейная регрессия (обычная и случайный лес)
   - Сравнение моделей с и без выбросов
   - Оценка по метрикам: R², MSE, MAE

5. **Визуализация результатов**:
   - Предсказанные vs фактические значения
   - Графики важности признаков

---

## 📌 Результаты

- Модель смогла предсказывать цену с адекватной точностью на тестовой выборке.
- Наиболее значимыми признаками оказались: `totsp`, `livesp`, `kitsp`, `dist`, `metrdist`.
- Удаление выбросов улучшило качество модели.

---

## 🚀 Как запустить

1. Клонируйте репозиторий (или просто скачайте):
```bash
git clone https://github.com/danyloallo/MskPriceML.git
cd MskPriceML
```
2. Запустите через Jupyter Notebook или откройте блокнот в Google Collab (рекомендуется Google Collab)
3. Выполняйте код блок за блоком

---

# 🇬🇧 English Version

# 🏙️ Analysis of housing prices in Moscow

This project is dedicated to the analysis of factors affecting the cost of housing in Moscow, using data from the [Kaggle](https://www.kaggle.com/) platform. The following were carried out: data pre-processing, visualization, statistical analysis and building a price forecasting model.

---

## 📊 Project Description

**Goal**: to identify key factors affecting the price of real estate and build a model capable of predicting the cost of housing based on these factors.

---

## 🗂️ Data Used

- Source: Kaggle
- Format: CSV
- Target variable: `price` — apartment price
- Main features:
   - `totsp` — total area
   - `livesp` — living area
   - `kitsp` — kitchen area
   - `dist` — distance to the center
   - `metrdist` — distance to the metro
   - `brick`, `floor`, `walk` — categorical features (house type, floor, walking distance)

---

## ⚙️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

---

## 📈 Main stages

1. **Data preprocessing**:
   - Removing unnecessary columns
   - Checking and removing outliers
   - Checking data types and omissions

2. **EDA (Exploratory Data Analysis)**:
   - Analysis of correlation between features
   - Visualization of distributions and dependencies
   - Detection of anomalies

3. **Statistical analysis**:
   - Hypothesis testing (t-test) for categorical features
   - Analysis of feature significance

4. **Model building**:
   - Linear regression (regular and random forest)
   - Comparison of models with and without outliers
   - Evaluation by metrics: R², MSE, MAE

5. **Result visualization**:
   - Predicted vs. actual values
   - Feature importance graphs

---

## 📌 Results

- The model was able to predict the price with adequate accuracy on the test sample.
- The most significant features were: `totsp`, `livesp`, `kitsp`, `dist`, `metrdist`.
- Removing outliers improved the quality of the model.

---

## 🚀 How to run

1. Clone the repository (or just download):
```bash
git clone https://github.com/danyloallo/MskPriceML.git
cd MskPriceML
```
2. Run via Jupyter Notebook or open the notebook in Google Collab (Google Collab is recommended)
3. Run the code block by block
