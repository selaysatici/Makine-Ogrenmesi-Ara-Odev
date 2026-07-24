# Müşteri Ayrılma (Churn) Tahmini - Makine Öğrenmesi Ara Ödevi

Bu proje, bir işletmenin müşteri kayıp (churn) durumunu tahmin etmek amacıyla geliştirilmiş uçtan uca bir sınıflandırma hattıdır.

## 📌 Proje Amacı
Derste öğrenilen temel makine öğrenmesi akışını pratik etmektir:
- Sentetik müşteri veri seti oluşturma ve inceleme
- Eksik değer kontrolü ve medyan ile doldurma (Imputation)
- Öznitelik Mühendisliği (Feature Engineering)
- Kategorik değişkenler için One-Hot Encoding ve sayısal değişkenler için StandardScaler uygulaması
- Veriyi Train / Validation / Test olarak ayırma (`stratify` kullanarak)
- Model eğitimi (Logistic Regression, KNN, Decision Tree) ve Validation performansı karşılaştırması
- Seçilen modelin Test seti üzerinde değerlendirilmesi (Accuracy, Precision, Recall, F1-Score, Confusion Matrix)

## 🛠️ Çalıştırma
Projeyi çalıştırmak için gerekli kütüphaneleri yükleyip ana betiği çalıştırabilirsiniz:

```bash
pip install pandas numpy scikit-learn
python main.py
