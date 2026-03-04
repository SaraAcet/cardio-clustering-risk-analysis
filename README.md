## Kümeleme Yöntemleri ile Kardiyovasküler Risk Analizi
# Kümeleme Yöntemleri ile Kardiyovasküler Hastalık Risk Analizi 

Bu proje, kardiyovasküler sağlık verilerini kullanarak bireyleri benzer sağlık özelliklerine göre gruplamak amacıyla **gözetimsiz makine öğrenmesi (kümeleme)** yöntemlerini kullanır.

Proje **Python ve Google Colab** ortamında geliştirilmiştir.

---

## Proje Özeti

Veri seti yaklaşık **70.000 bireye ait sağlık verilerini** içermektedir. Veri setinde aşağıdaki gibi **13 farklı sağlık ve yaşam tarzı özelliği** bulunmaktadır:

- Yaş
- Cinsiyet
- Boy
- Kilo
- Kan basıncı (tansiyon)
- Kolesterol seviyesi
- Glikoz seviyesi
- Sigara kullanımı
- Alkol tüketimi
- Fiziksel aktivite

Projenin amacı, bu veriler kullanılarak **benzer sağlık özelliklerine sahip bireyleri kümelere ayırmak** ve olası **risk gruplarını belirlemektir**.

---

## Kullanılan Yöntemler

Projede aşağıdaki veri bilimi ve makine öğrenmesi teknikleri uygulanmıştır.

### Veri Ön İşleme
- Yaş değerinin **gün cinsinden yıl cinsine dönüştürülmesi**
- Mantıksız ve aşırı değerlerin temizlenmesi
- Verilerin **StandardScaler** ile ölçeklendirilmesi

### Kümeleme Algoritmaları
Projede üç farklı kümeleme yöntemi kullanılmıştır:

- **K-Means Kümeleme**
- **DBSCAN (Yoğunluk Tabanlı Kümeleme)**
- **Agglomerative Clustering (Hiyerarşik Kümeleme)**

### Görselleştirme Teknikleri

- **Elbow yöntemi** ile optimal küme sayısının belirlenmesi
- **PCA (Principal Component Analysis)** ile verinin 2 boyutta görselleştirilmesi
- **Dendrogram grafiği** ile hiyerarşik kümeleme analizi
- Küme bazlı **istatistiksel özet tabloları**

---

## Analiz Çıktıları

Bu proje aşağıdaki analiz çıktıları üretmektedir:

- K-Means için **optimal küme sayısının belirlenmesi**
- **PCA ile küme görselleştirmesi**
- **DBSCAN ile aykırı (outlier) veri tespiti**
- Küme bazlı **ortalama sağlık değerlerinin analizi**
- Potansiyel **kardiyovasküler risk gruplarının belirlenmesi**

---

## Proje Yapısı

cardio-clustering-risk-analysis
│
├── notebooks
│ └── cardio_clustering.ipynb
│
└── README.md


---

## Veri Seti

Bu projede kullanılan veri seti Kaggle üzerinden alınmıştır.

Dataset bağlantısı:

https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

Not:  
Veri seti boyut nedeniyle GitHub reposuna eklenmemiştir.  
Veri setini doğrudan Kaggle üzerinden indirebilirsiniz.

---

## Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy
- Google Colab

---

## Projeyi Çalıştırma

1. Veri setini Kaggle üzerinden indiriniz.
2. Veri setini **Google Colab** veya **Google Drive** ortamına yükleyiniz.
3. Notebook içinde veri seti dosya yolunu güncelleyiniz.
4. Notebook içindeki tüm hücreleri çalıştırınız.

---

## Geliştirici

Sara Acet  
Yazılım Mühendisliği Öğrencisi

GitHub:  
https://github.com/SaraAcet















# Cardiovascular Disease Clustering Analysis

# Cardiovascular Disease Risk Analysis using Clustering 

This project analyzes cardiovascular health data using **unsupervised machine learning (clustering)** techniques to identify groups of individuals with similar health characteristics and potential risk profiles.

The project was developed using **Python and Google Colab**.

---

## Project Overview

The dataset contains health information from approximately **70,000 individuals** with 13 medical and lifestyle-related features such as:

- Age
- Gender
- Height
- Weight
- Blood pressure
- Cholesterol level
- Glucose level
- Smoking habits
- Alcohol consumption
- Physical activity

The goal is to discover **hidden patterns and risk groups** within the dataset using clustering algorithms.

---

## Methods Used

The following techniques were applied in the project:

### Data Preprocessing
- Converting age from **days to years**
- Removing unrealistic values (outliers)
- Feature scaling using **StandardScaler**

### Clustering Algorithms
- **K-Means Clustering**
- **DBSCAN (Density-Based Clustering)**
- **Agglomerative Clustering (Hierarchical Clustering)**

### Visualization Techniques
- **Elbow Method** to determine optimal cluster number
- **PCA (Principal Component Analysis)** for 2D visualization
- **Dendrogram visualization** for hierarchical clustering
- **Cluster-based statistical analysis**

---

## Analysis Outputs

The project produces several analytical outputs including:

- Optimal cluster selection using the **Elbow Method**
- Visualization of clusters using **PCA**
- Detection of **outliers using DBSCAN**
- **Cluster summaries** showing average health metrics
- Identification of **potential cardiovascular risk groups**

---

## Project Structure


cardio-clustering-risk-analysis
│
├── notebooks
│ └── cardio_clustering.ipynb
│
└── README.md


---

## Dataset

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

Note:  
The dataset is **not uploaded to this repository** due to size considerations.  
Please download it directly from Kaggle.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy
- Google Colab

---

## How to Run

1. Download the dataset from Kaggle.
2. Upload the dataset to **Google Colab or Google Drive**.
3. Update the dataset file path inside the notebook.
4. Run all notebook cells.

---

## Author

Sara Acet  
Software Engineering Student  

GitHub:  
https://github.com/SaraAcet


