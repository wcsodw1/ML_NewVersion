# ML_NewVersion
Machine Learning new version for theorem and programming


## Fundamental : 
### 1.Prepocessing :
- 1.a Import necessary package|Library
- 1.b Get|Grab data 
- 1.c Data Obserave : 
    - .Describe | 
- 1.d Scaling : 
    - Normalization
        - 常態化的某樣本特徵值 =（常態化前的 x 特徵值 — 所有樣本中最小的特徵值 x）/（所有樣本中最大的特徵值 x — 所有樣本中最小的特徵值 x）
    - Standardization
        - 標準化的某樣本特徵值=（標準化前的 x 特徵值 — 平均數） / 標準差

### 2.Feature Engineering : 
### 3.Modeling :
- XGBoost
- Decision Tree
- Logitic Regression | Linear Regression
- SVM
### 4.Evaluation :    
- K — folds 
- Hyper-Parameter(參數調教): find the best hyper-parameter 找出各模型最適超參數
    - GridSearchCV(best_estimator)
    - Random Search
    - Bayesian Optimization : 建立一個含有目標函數的機率模型, 並且使用它去選擇最佳的超參數去評估正確的目標函數(類似條件機率)
- LossFunction 適用場合 | 計算方式 | 如何調整 
    - MSE | MAE | RMSE : Using in Regression Issue 
    - Cross-Entropy : using in Classification Issue
- Feature Importance : 特徵重要性
[Evaluation Reference](https://ntudac.medium.com/python-%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-%E4%BA%A4%E5%8F%89%E9%A9%97%E8%AD%89%E8%88%87%E8%B6%85%E5%8F%83%E6%95%B8%E8%AA%BF%E6%95%B4-69a752cb6f65)

# Concept : 常見觀念 | 工具
- Overfitting | underfitting
- Gradient Descent | Gradient Boosting 
- Tool : Sklearn | Pandas Numpy SQL | Python | 
- DL Framework : Tensorflow | Pytorch
- Data Visualize : Matplotlib | Seaborn 
