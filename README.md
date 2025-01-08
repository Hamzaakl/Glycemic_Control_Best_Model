# Diyabetik Kontrol ve Tahmin Projesi

Bu proje, diyabet hastalarının glisemik kontrolünü anlamak, analiz etmek ve tahmin etmek için geliştirildi. Çeşitli makine öğrenimi ve derin öğrenme modelleri kullanılarak, elde edilen veriler üzerinden anlamlı sonuçlar çıkarılmış ve model performansları değerlendirilmiştir.

---

## 🚀 **Proje Özeti**

- **Amaç**: Diyabetik kontrol seviyesini tahmin etmek ve bu süreçte etkili olan önemli faktörleri belirlemek.
- **Veri Seti**: Proje, diyabet hastalarına ait klinik verilerden oluşan bir veri seti kullanır.
- **Hedef Değişken**: `Glycemic_control` (glisemik kontrol seviyesi).

---

## 🛠️ **Adımlar ve Metodoloji**

### 1. **Veri Ön İşleme**
- Eksik değer analizi ve doldurma.
- Sayısal ve kategorik değişkenlerin ayrıştırılması.
- Uç değer analizi (IQR yöntemiyle).
- Nadir sınıfların tespiti ve işlenmesi.
- Özellik mühendisliği ve gereksiz değişkenlerin çıkarılması.

### 2. **Özellik Seçimi ve Azaltma**
- Korelasyon analizi ile önemli özelliklerin belirlenmesi.
- PCA (Principal Component Analysis) ile boyut indirgeme.

### 3. **Modelleme**
Birden fazla makine öğrenimi ve derin öğrenme modeli kullanılmıştır:
- **Makine Öğrenimi Modelleri**
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - Support Vector Machine (SVM)
- **Derin Öğrenme Modelleri**
  - Çok Katmanlı Perceptron (MLP)
  - TabNet
  - Dikkat (Attention) Mekanizması

### 4. **Model Değerlendirme**
- ROC eğrisi ve AUC skoru.
- Doğruluk, F1-Skoru, Hassasiyet ve Kappa metrikleri.
- En iyi modelin belirlenmesi.

### 5. **Model Kaydetme ve Tahmin**
- En iyi model ve standardizasyon için scaler kaydedildi.
- Yeni veriler üzerinde tahmin yapmak için tahmin fonksiyonu geliştirildi.

---
