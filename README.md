📄 README.md

# 🎓 Öğrenci Başarı Analizi

Bu proje, öğrencilerin başarı durumlarını tahmin etmek amacıyla makine öğrenimi ve yapay sinir ağı (ANN) modelleri kullanılarak geliştirilmiştir. Amaç, belirli özellikler (çalışma süresi, yoklama durumu, önceki notlar vb.) üzerinden öğrencinin başarı durumunu sınıflandırmaktır.

## 🚀 Kullanılan Teknolojiler

- Python 3.x
- Pandas & NumPy
- Scikit-learn
- TensorFlow / Keras (ANN modeli için)
- Matplotlib & Seaborn (veri görselleştirme)

## 🧠 Modeller

- **Makine Öğrenimi**: Lojistik Regresyon, Karar Ağaçları, KNN, SVM gibi temel modeller denendi.
- **Derin Öğrenme**: Basit bir ANN modeli ile başarı durumu tahmin edildi.

## 📊 Veri Seti

Proje, [kendi oluşturduğum / açık veri setlerinden alınan] öğrenci başarı verisi ile çalışmaktadır. Veride yer alan bazı sütunlar:

- Çalışma süresi
- Ders devamsızlığı
- Önceki sınav notları
- Aile durumu
- Ek destek / kurs alma durumu

## ⚙️ Çalıştırmak İçin

1. Gerekli kütüphaneleri kurun:

```bash
pip install -r requirements.txt

    Jupyter Notebook ya da .py dosyasını çalıştırın:

python student_success_model.py
