# Pandas-Practice-Exercises-Titanic-Tips
# 🐼 Pandas Data Analysis Practice with Titanic & Tips Datasets

<img src="https://pandas.pydata.org/static/img/pandas_white.svg" width="400">

---

## 🎯 Amaç

Bu proje, Python’un **Pandas** kütüphanesini kullanarak veri manipülasyonu ve temel analiz işlemleri üzerinde pratik yapmak amacıyla hazırlanmıştır. Kullanılan veri setleri, **seaborn** kütüphanesinden gelen **Titanic** ve **Tips** veri setleridir.

---

## 📊 Kullanılan Veri Setleri

### 🚢 Titanic Dataset

Yolculara ait yaş, cinsiyet, sınıf, ücret ve hayatta kalma durumu gibi bilgileri içerir.

- `sex`: Kadın/Erkek
- `age`: Yaş
- `pclass`: Yolcu sınıfı (1, 2, 3)
- `survived`: Hayatta kalma bilgisi (0/1)
- `embarked`, `fare`, `deck`, `who` gibi birçok değişken

### 🍽️ Tips Dataset

Restoran bahşiş verilerinden oluşur. Farklı günlerde ve öğünlerde yapılan ödemelerle ilgilidir.

- `total_bill`: Toplam hesap
- `tip`
- ---

## 📚 Öğrenilen Konular

Bu alıştırmalar sırasında pandas ve veri analizine dair şu konularda pratik yapılmıştır:

- DataFrame yapısını tanıma ve özelliklerine hâkim olma
- Filtreleme işlemleri (`loc`, koşullu sorgular)
- Gruplama (`groupby`) ve toplulaştırma (`agg`)
- Yeni değişken oluşturma (`apply`, `lambda`)
- Eksik değerlerin tespiti ve doldurulması (`fillna`, `isnull`)
- Kategorik veri türleriyle çalışma (`astype("category")`)
- Sıralama ve slicing işlemleri
---

## 🖼️ Örnek Görseller

| Titanic Dataset Yaş Dağılımı | Tips Dataset Bahşiş Analizi |
|-----------------------------|------------------------------|
| <img src="images/titanic_age_dist.png" width="400"> | <img src="images/tips_tip_by_day.png" width="400"> |

> Görselleri `images/` klasörüne ekleyerek README'de bu şekilde görsel olarak sergileyebilirsin.
---

## 🚀 Geliştirme Fikirleri

Bu projeyi daha ileriye taşımak isteyenler için bazı öneriler:

- Matplotlib veya Seaborn ile grafikler oluşturulabilir.
- Dash veya Streamlit gibi araçlarla etkileşimli paneller yapılabilir.
- Eksik değerleri doldurmak için istatistiksel modelleme kullanılabilir.
- Daha büyük veri setleriyle benzer analizler yapılabilir.
---

## ❓ Sık Sorulan Sorular

### 1. Veri setini indirmeme gerek var mı?
Hayır. Titanic ve Tips veri setleri `seaborn` kütüphanesinin içinde gömülüdür, otomatik olarak yüklenir.

### 2. Kodları Jupyter Notebook'ta da çalıştırabilir miyim?
Evet. Kod yapısı Jupyter Notebook’a tamamen uygundur.

### 3. Bu proje ne düzeyde kullanıcılar için uygun?
Temel ve orta seviye Python/Pandas kullanıcıları için uygundur.
---

## 🔖 Etiketler

`#python` `#pandas` `#verianalizi` `#dataanalysis` `#seaborn`  
`#titanicdataset` `#tipsdataset` `#groupby` `#apply` `#lambda`  

