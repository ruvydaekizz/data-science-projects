# Bank Marketing Prediction - Machine Learning Graduation Project

Bu proje, **Sivas Cumhuriyet Üniversitesi Yönetim Bilişim Sistemleri** bölümü lisans bitirme tezi kapsamında geliştirilmiştir.

## 🎯 Projenin Amacı ve Kapsamı
Bu çalışma, farklı makine öğrenmesi yöntemlerinin sınıflandırma problemleri üzerindeki performanslarını karşılaştırmayı amaçlamaktadır. Proje boyunca çeşitli veri ön işleme adımları, özellik mühendisliği (feature engineering) teknikleri uygulanmış; farklı algoritmalarla modeller eğitilerek sonuçlar analiz edilmiş ve kıyaslanmıştır.

Temel hedef, müşteri verileri üzerinden bir bankanın vadeli mevduat (term deposit) teklifinin kabul edilip edilmeyeceğini en yüksek doğrulukla tahmin etmektir.

## 📊 Veri Seti: Bank Marketing Data Set

Projede, **UCI Machine Learning Repository** üzerinden sağlanan "Bank Marketing" veri seti kullanılmıştır. Veriler, Portekiz'deki bir bankanın doğrudan pazarlama kampanyalarını (telefon görüşmeleri) içermektedir.

* **Veri Kaynağı:** [UCI Machine Learning Repository - Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
* **Problem Türü:** Sınıflandırma (Classification)
* **Hedef Değişken (Target):** Müşterinin vadeli mevduat teklifini kabul edip etmediği (`yes` veya `no`).

## 📂 Proje Süreci ve Raporlama 

Proje 12 haftalık akademik bir takvimde tamamlanmış olup, her aşama ilgili klasörlerde belgelenmiştir:

| Hafta | Aşama | Açıklama |
| :--- | :--- | :--- |
| **Hafta 4** | **Proje & Veri Tanımı** | Proje kapsamının belirlenmesi, UCI veri setinin seçimi ve veri yapısının (CSV) incelenmesi. |
| **Hafta 5** | **EDA (Keşifçi Analiz)** | Veri setinin görselleştirilmesi ve dağılımların analizi. |
| **Hafta 6-7** | **Veri Ön İşleme** | Eksik verilerin temizlenmesi, aykırı değer analizi ve özellik seçimi. |
| **Hafta 8** | **Lojistik Regresyon** | Temel sınıflandırma modelinin kurulması. |
| **Hafta 9** | **KNN (K-Nearest Neighbors)** | Uzaklık temelli sınıflandırma analizi. |
| **Hafta 10** | **Decision Tree** | Karar ağacı modelinin oluşturulması. |
| **Hafta 11** | **Random Forest** | Topluluk (Ensemble) öğrenme ile performans iyileştirme. |
| **Hafta 12** | **Sonuç Karşılaştırması** | Tüm modellerin Accuracy, F1-Score ve ROC eğrilerine göre kıyaslanması. |

## 🛠 Kullanılan Teknolojiler

* **Dil:** Python 3.x
* **Kütüphaneler:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 📈 Sonuçlar
Proje sonucunda, dengesiz veri setleri (imbalanced data) üzerinde farklı algoritmaların başarısı test edilmiştir. Modeller arası karşılaştırma tabloları ve karmaşıklık matrisleri (confusion matrix) ilgili rapor dosyalarında mevcuttur.

## 📝 Yazar

**Rüveyda Ekiz**
* Yönetim Bilişim Sistemleri Mezunu, Data Science Enthusiast

---
*Bu proje akademik amaçlarla geliştirilmiştir.*
