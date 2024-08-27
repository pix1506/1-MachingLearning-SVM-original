# SVM原理與實作   

本篇為支援向量機 SVM (Support Vector Machine) 原始論文的導讀與實作，  
文章取向不是懶人包介紹，而是從原始論文解析 SVM 的原理，適合有興趣的開發者閱讀。

原始論文：A Training Algorithm for Optimal Margin Classifiers  
網址為：[https://dl.acm.org/doi/pdf/10.1145/130385.130401](https://dl.acm.org/doi/pdf/10.1145/130385.130401)

## 目錄  
1.  

## 撰寫動機
SVM是一種經典且有重要影響力的機器學習之一，最早被發明於1990年代。當時雖然已誕生出各類型的機器學習演算法，但仍無法有效解決很多分類問題。因此SVM誕生，他有下列特點：  

1.最大化分類間隔(Margin)  
2.有效處理非線性的分類問題  
3.高維度的分類任務  
