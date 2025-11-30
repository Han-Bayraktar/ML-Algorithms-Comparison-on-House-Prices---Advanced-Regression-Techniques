# 🏠 House Price Prediction Project | Ev Fiyat Tahmini Projesi

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-154360?style=for-the-badge&logo=xgboost&logoColor=white)](https://xgboost.readthedocs.io/)

**🌍 [English](#-project-overview) | 🇹🇷 [Türkçe](#-proje-özeti)**

</div>

---

<a name="english"></a>
## 🇬🇧 Project Overview

This project is a comprehensive **Machine Learning** solution designed to predict house prices using the famous **"House Prices - Advanced Regression Techniques"** dataset from Kaggle. It demonstrates a full end-to-end ML pipeline, ranging from detailed data preprocessing and feature engineering to advanced model tuning and interpretability analysis.

### 🚀 Key Features

*   **🧹 Advanced Preprocessing:** Rigorous outlier detection, missing value imputation strategies, and data cleaning.
*   **🏗️ Feature Engineering:** Creation of new impactful features (e.g., `TotalSF`, `HouseAge`) to improve model performance.
*   **🤖 Multi-Model Approach:** Implementation and comparison of **6 different algorithms**:
    *   Ridge Regression
    *   Lasso Regression
    *   Random Forest Regressor
    *   Gradient Boosting Regressor
    *   XGBoost Regressor
    *   LightGBM Regressor
*   **⚙️ Hyperparameter Optimization:** Extensive tuning using **GridSearchCV**, **RandomizedSearchCV**, and **Optuna** (Bayesian Optimization).
*   **🧠 Model Interpretability:** Deep dive into model decisions using **SHAP (SHapley Additive exPlanations)** analysis.

### 🏆 Results & Insights

*   **Best Performing Model:** 🥇 **Ridge Regression** (RMSE: **0.1186**)
*   **Surprising Insight:** Linear models (Ridge/Lasso) outperformed complex tree-based models (XGBoost/LightGBM). This was attributed to:
    *   Effective feature engineering that linearized relationships.
    *   Strong linear correlations between house features (like area) and price.
    *   Lower risk of overfitting compared to complex ensembles.

### 📂 File Structure

*   `house_price_prediction.ipynb`: The main Jupyter Notebook containing all code, analysis, and explanations.
*   `train.csv` & `test.csv`: The dataset files.
*   `requirements.txt`: List of required Python libraries.

### 🛠️ Installation & Usage

1.  **Clone the repository and install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook house_price_prediction.ipynb
    ```

---

<a name="türkçe"></a>
## 🇹🇷 Proje Özeti

Bu proje, Kaggle'ın ünlü **"House Prices - Advanced Regression Techniques"** veri setini kullanarak ev fiyatlarını tahmin etmek amacıyla geliştirilmiş kapsamlı bir **Makine Öğrenmesi** çözümüdür. Veri ön işlemeden gelişmiş model optimizasyonuna ve model yorumlanabilirliğine kadar uçtan uca bir ML akışını (pipeline) detaylı bir şekilde sunar.

### 🚀 Temel Özellikler

*   **🧹 Gelişmiş Ön İşleme:** Titiz aykırı değer (outlier) tespiti, eksik veri tamamlama stratejileri ve veri temizliği.
*   **🏗️ Özellik Mühendisliği (Feature Engineering):** Model performansını artırmak için yeni ve etkili özelliklerin (`TotalSF`, `HouseAge` vb.) türetilmesi.
*   **🤖 Çoklu Model Yaklaşımı:** **6 farklı algoritmanın** uygulanması ve karşılaştırılması:
    *   Ridge Regresyon
    *   Lasso Regresyon
    *   Random Forest Regressor
    *   Gradient Boosting Regressor
    *   XGBoost Regressor
    *   LightGBM Regressor
*   **⚙️ Hiperparametre Optimizasyonu:** **GridSearchCV**, **RandomizedSearchCV** ve **Optuna** (Bayesian Optimization) kullanılarak yapılan kapsamlı ince ayarlar.
*   **🧠 Model Açıklanabilirliği:** **SHAP** analizi ile modelin karar mekanizmasının ve özellik önem düzeylerinin derinlemesine incelenmesi.

### 🏆 Sonuçlar ve Bulgular

*   **En İyi Performans Gösteren Model:** 🥇 **Ridge Regresyon** (RMSE: **0.1186**)
*   **Önemli Bulgu:** Doğrusal modeller (Ridge/Lasso), karmaşık ağaç tabanlı modellerden (XGBoost/LightGBM) daha iyi performans göstermiştir. Bunun nedenleri:
    *   İlişkileri doğrusallaştıran etkili özellik mühendisliği çalışmaları.
    *   Ev özellikleri (alan vb.) ile fiyat arasındaki güçlü doğrusal korelasyon.
    *   Karmaşık modellere kıyasla daha düşük aşırı öğrenme (overfitting) riski.

### 📂 Dosya Yapısı

*   `house_price_prediction.ipynb`: Tüm kodları, analizleri ve açıklamaları içeren ana Jupyter Notebook dosyası.
*   `train.csv` & `test.csv`: Veri seti dosyaları.
*   `requirements.txt`: Gerekli Python kütüphanelerinin listesi.

### 🛠️ Kurulum ve Kullanım

1.  **Gerekli kütüphaneleri yükleyin:**
    ```bash
    pip install -r requirements.txt
    ```

2.  **Jupyter Notebook'u çalıştırın:**
    ```bash
    jupyter notebook house_price_prediction.ipynb
    ```
