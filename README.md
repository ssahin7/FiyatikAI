# 🚗 FIYATIK AI
**Makine Öğrenmesi Tabanlı Araç Fiyat Tahmin Sistemi**

---

## 📌 Proje Hakkında
FIYATIK AI, araçlara ait teknik özellikler ve geçmiş satış verileri kullanılarak, **gerçekçi ve veri odaklı araç fiyat tahminleri** üretmeyi amaçlayan bir makine öğrenmesi projesidir.

Sistem; ikinci el araç piyasasında fiyat tutarsızlıklarını azaltmayı, kullanıcıya **objektif ve açıklanabilir fiyat öngörüleri** sunmayı hedefler.

---

## 🎯 Amaç
- Araç özelliklerine dayalı **doğru fiyat tahmini** yapmak
- İkinci el araç piyasasında **veri temelli karar destek sistemi** oluşturmak
- Makine öğrenmesi modelleri ile **fiyat dalgalanmalarını analiz etmek**

---

## 🧠 Kullanılan Teknolojiler

- **Python 3.x**
- **Scikit-learn**
- **Pandas, NumPy**
- **XGBoost / Random Forest**
- **Matplotlib, Seaborn** (analiz ve görselleştirme)

---

## 📂 Veri Seti
Model, aşağıdaki bilgileri içeren araç verileri ile eğitilmiştir:
- Marka, model, yıl
- Motor hacmi, yakıt türü
- Vites tipi, kilometre
- Geçmiş satış fiyatları

📌 Veri seti:
- Temizlenmiş ve normalize edilmiştir  
- Eksik ve aykırı değerler işlenmiştir  

---

## ⚙️ Proje Akışı

1. **Veri Ön İşleme**  
   Eksik değer analizi, aykırı değer temizleme ve ölçeklendirme.

2. **Özellik Mühendisliği**  
   Fiyatı etkileyen yeni değişkenlerin oluşturulması.

3. **Model Eğitimi**  
   Random Forest ve XGBoost algoritmaları ile regresyon modellerinin eğitilmesi.

4. **Model Değerlendirme**  
   RMSE, MAE ve R² metrikleri kullanılarak performans analizi.

---

## 📤 Çıktılar
- Araç bazlı **tahmini satış fiyatı**
- Model performans karşılaştırmaları
- Fiyat dağılımı ve hata analizleri

---

## 📊 Değerlendirme Metrikleri
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🔮 Gelecek Çalışmalar
- Gerçek zamanlı veri entegrasyonu
- Web tabanlı kullanıcı arayüzü
- Explainable AI (SHAP) entegrasyonu

---

## ⚖️ Not
Bu proje akademik ve uygulamalı amaçlarla geliştirilmiştir.  

