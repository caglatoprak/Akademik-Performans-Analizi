# Akademik-Performans-Analizi

Veri Kümesi Özellikleri: Çok Değişkenli

Örnek Sayısı: 480

Alan: E-öğrenme, Eğitim, Tahminli modeller, Eğitim Veri Madenciliği

Özellik Karakteristikleri: Tamsayılı / Kategorik

Özelliklerin Sayısı: 16

Tarih: 2016-11-8

İlişkili Görevler: Sınıflandırma

Kayıp değerler? Yok hayır

Dosya formatları: xAPI-Edu-Data.csv

  # **İçindekiler**
<a id ="toc"></a>

1. [Veriyi Hazırlama & Tanıma](#Veriyi-Hazırlama-&-Tanıma)

2. [Veri Görselleştirme](#Veri-Görselleştirme)

  2.1. [İlgili Kütüphanelerin Yüklenmesi](#İlgili-Kütüphanelerin-Yüklenmesi)
  
  2.2. [Sınıflara Göre Öğrenci Sayısı](#Sınıflara-Göre-Öğrenci-Sayısı)
  
  2.3. [Eğitim Alan Öğrencilerin Cinsiyet Dağılımı](#Eğitim-Alan-Öğrencilerin-Cinsiyet-Dağılımı)
  
  2.4. [Sınıflara Göre Cinsiyet Dağılımı](#Sınıflara-Göre-Cinsiyet-Dağılımı)
  
  2.5. [Genel Veli Dağılımı](#Genel-Veli-Dağılımı)
  
  2.6. [Sınıflara Göre Veli Dağılımı](#Sınıflara-Göre-Veli-Dağılımı)
  
  2.7. [Anketi Cevaplayan Veliler](#Anketi-Cevaplayan-Veliler)
  
  2.8. [Ebeveyn okul memnuniyeti](#Ebeveyn-Okul-Memnuniyeti)
  
  2.9. [Vatandaşı Oldukları Ülkeye Göre Öğrenci Yüzdesi](#Vatandaşı-Oldukları-Ülkeye-Göre-Öğrenci-Yüzdesi)
  
  2.10. [İki dönem boyunca öğrencilerin toplam el kaldırma adedi](#İki-Dönem-Boyunca-Öğrencilerin-Toplam-El-Kaldırma-Adedi)
  
  2.11. [Kadın- Erkek Öğrencilerin Aldığı Derslerin Dağılımı ve Kadın-Erkek Öğrencilerin Ülkelerine Göre Dağılımları](#Kadın---Erkek-Öğrencilerin-Aldığı-Derslerin-Dağılımı-ve-Kadın-Erkek-Öğrencilerin-Ülkelerine-Göre-Dağılımları)
  
  2.12. [Sınıf Seviyesine Göre Dağılımlar](#Sınıf-Seviyesine-Göre-Dağılımlar)
  
  2.13. [Sınıfa Göre Takip Edilen Kaynaklar- Sınıfa Göre Duyuru Takibi- Sınıfa Göre El Kaldırma- Sınıfa Göre Tartışmalara Katılım](#Sınıfa-Göre-Takip-Edilen-Kaynaklar---Sınıfa-Göre-Duyuru-Takibi---Sınıfa-Göre-El-Kaldırma---Sınıfa-Göre-Tartışmalara-Katılım)
  
  2.14. [Sayısal Özellikler Arasındaki İlişkiler](#Sayısal-Özellikler-Arasındaki-İlişkiler)
 
3. [Model Seçimi & Uygulanması](#Model-Seçimi-&-Uygulanması)
  
  3.1. [İstatiksel Normalleştirme](#İstatiksel-Normalleştirme)
  
  3.2. [Eğitim ve Test Verilerinin Belirlenmesi](#Eğitim-ve-Test-Verilerinin-Belirlenmesi)
  
  3.3. [Modelin Uygulanması](#Modelin-Uygulanması)
  
  3.3.1. [Support Vektor Machine(SVM) Classification](#Support-Vektor-Machine(SVM)-Classification)
  
  3.3.2. [Logistic Regression Classification](#Logistic-Regression-Classification)
  
  3.3.3. [Random Forest Classification](#Random-Forest-Classification)
  
  3.3.4. [Naive Bayes  Classification](#Naive-Bayes-Classification)
  
  3.3.5. [Decision Tree Classification](#Decision-Tree-Classification)
