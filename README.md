# Ransomware Detection with Ensemble Learning
> **Master's Thesis Project** | 🛡️ Cybersecurity + 🤖 Machine Learning

## 📖 Project Overview (專案概述)
本專案為碩士論文之核心實作，旨在解決傳統單一模型在勒索軟體偵測上的侷限性。透過**多模型集成學習 (Ensemble Learning)** 架構，在惡意行為早期階段達成高精準度的偵測。

This project implements a multi-model ensemble framework to detect ransomware activities in their early stages, addressing the volatility of modern variants.

---

## 📚 Thesis Information (論文資訊)
*   **Title (CN):** 基於多模型集成學習的勒索軟體早期偵測方法
*   **Title (EN):** Multi-Model Ensemble Learning for Early Ransomware Variant Detection
*   **Full Thesis (PDF):** [🔗 臺灣碩博士論文知識加值系統](https://ndltd.ncl.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=Eozur6/record?r1=1&h1=0)
*   **Detailed Technical Notes:** [📝 實驗過程與技術細節 (HackMD)](https://hackmd.io/@fjY06SCpTq2shPG3bDHrOQ/B1TrpAvT1e/%2FuObLGkLbTkCk1ujHf1Pvlw)

---

## 🚀 Key Contributions & Results (關鍵貢獻與成果)
*   **High Accuracy:** 成功將偵測準確率 (Accuracy) 穩定提升至 **90% 以上**。
*   **Performance Optimization:** 相較於單一弱分類器 (如 Decision Tree, Random Forest)，在不同變體測試中展現了 **7% 至 44%** 的顯著效能提升。
*   **Early Detection:** 優化特徵提取演算法，實現於勒索軟體加密行為初期的預警機制。

---

## 🛠 Tech Stack (技術棧)
*   **Language:** Python 3.11+ (Developed & Tested on Google Colab)
*   **Libraries:** 
    *   `Scikit-learn` (Ensemble modeling, evaluation)
    *   `XGBoost` (Gradient boosting implementation)
    *   `Pandas` & `NumPy` (Data preprocessing & feature engineering)
    *   `Matplotlib` / `Seaborn` (Visualizing experimental results)
    
---

## 📂 Core Files (核心程式碼說明)
*   `src/preprocessing.py`: 數據清洗與特徵工程實作。
*   `src/ensemble_model.py`: 多模型集成邏輯與權重分配演算法。
*   `notebooks/experiment_results.ipynb`: 實驗過程紀錄與模型比較分析。
