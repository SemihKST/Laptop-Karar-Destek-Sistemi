#  💻 Web Madenciliği Tabanlı Laptop Karar Destek Sistemi
## 📌 Projenin Amacı
Bu projede, Hepsiburada e-ticaret platformundan elde edilen laptop ürün verileri ve kullanıcı yorumları kullanılarak web madenciliği tabanlı bir karar destek sistemi geliştirilmiştir. Çalışmanın temel amacı, teknik özellikler ile kullanıcı yorumlarını birlikte değerlendirerek ürünler hakkında anlamlı bilgiler elde etmek ve kullanıcıların karar verme sürecini desteklemektir.
## 📊 Veri Seti
- Hepsiburada
### Veri Seti Boyutu
- Yaklaşık 300 laptop ürünü
- Toplam 2914 kullanıcı yorumu
### Toplanan Veriler
- Ürün adı
- Marka
- Fiyat
- Teknik özellikler
- Kullanıcı puanı
- Yorum sayısı
- Kullanıcı yorumları
## ⚙ Kullanılan Teknolojiler
- Python
- Pandas
- NumPy
- Selenium
- Matplotlib
- Scikit-Learn
- WordCloud
- OpenPyXL
# 🔧 Metodoloji
## 1. Veri Toplama
Web madenciliği teknikleri kullanılarak Hepsiburada platformundan ürün bilgileri ve kullanıcı yorumları elde edilmiştir.
## 2. Veri Ön İşleme
Veri seti üzerinde aşağıdaki işlemler gerçekleştirilmiştir:
- Eksik değer kontrolü
- Tekrarlanan kayıtların temizlenmesi
- Sayısal dönüşümler
- Metin temizleme işlemleri
## 3. Özellik Çıkarımı
Veri setinden yeni değişkenler elde edilmiştir.
- RAM kapasitesi
- SSD kapasitesi
- Memnuniyet skoru
- Pozitiflik oranı
- Negatiflik oranı
- Risk oranı
## 4. Duygu Analizi
Kullanıcı yorumları analiz edilerek pozitif, negatif ve kararsız yorumların duygu dağılımları incelenmiştir.
## 5. K-Means Kümeleme
Laptop ürünleri benzer özelliklerine göre kümelendirilmiştir.
K-Means algoritması kullanılarak:
- Ekonomik ürünler
- Fiyat-performans ürünleri
- Premium ürünler
- Riskli ürünler
şeklinde anlamlı gruplar oluşturulmuştur.
## 6. Karar Destek Sistemi
Kullanıcılar için:
- En iyi ürünler
- Fiyat-performans ürünleri
- Premium ürünler
- Düşük riskli ürünler
- Riskli ürünler
belirlenmiştir.
# 📈 Görseller
## Duygu Analizi
<img width="2100" height="2100" alt="duygu_pasta_grafigi" src="https://github.com/user-attachments/assets/98eabb57-d6c2-4863-a426-7dba12dce5f3" />

## Korelasyon Isı Haritası
<img width="4200" height="3000" alt="korelasyon_isi_haritasi" src="https://github.com/user-attachments/assets/90745c53-2359-470f-9c91-161b160cd466" />

## Elbow Method
<img width="2400" height="1500" alt="elbow_method" src="https://github.com/user-attachments/assets/69fc3d3f-5b6d-4602-bb42-5340d4efaa14" />

## K-Means PCA Görselleştirmesi
<img width="2700" height="1800" alt="kmeans_pca_grafigi" src="https://github.com/user-attachments/assets/19030088-144c-473d-92bf-84e3bf0864e6" />


## Kelime Bulutu
<img width="3600" height="2100" alt="kelime_bulutu" src="https://github.com/user-attachments/assets/2413ef42-d5fd-4a4c-acd2-7f909eb98dd8" />

## Karar Destek Sistemi
<img width="3600" height="2100" alt="en_iyi_10_urun" src="https://github.com/user-attachments/assets/efbfab3a-5510-459b-aa27-af1ef2e0b3e4" />

#  🚀 Sonuçlar

Bu çalışmada kullanıcı yorumları ile teknik özellikler birlikte değerlendirilerek web madenciliği tabanlı bir karar      destek sistemi geliştirilmiştir. Yapılan duygu analizi sayesinde müşteri memnuniyeti incelenmiş, korelasyon analizi ile
değişkenler arasındaki ilişkiler ortaya çıkarılmıştır. K-Means algoritması kullanılarak laptoplar benzer özelliklerine
göre kümelendirilmiş ve kullanıcılar için ürün önerileri oluşturulmuştur. Bu proje, web madenciliği yöntemlerinin
e-ticaret verileri üzerinde karar verme süreçlerini desteklemede etkili bir şekilde kullanılabileceğini göstermektedir.

# 📂 Proje Yapısı

```text
📁 kodlar
│
├── 01_veri_cekme.py
├── 02_yorum_cekme.py
├── 03_veri_temizleme.py
├── 04_yorum_temizleme.py
├── 05_yorum_ozellikleri.py
├── 06_duygu_analizi.py
├── 07_duygu_grafikleri.py
├── 08_veri_birlestirme.py
├── 09_istatistiksel_analiz.py
├── 10_korelasyon_analizi.py
├── 11_1_elbow_method.py
├── 11_2_kmeans_kumeleme.py
├── 11_3_pca_kume_grafigi.py
├── 12_kelime_bulutu.py
├── 13_marka_karsilastirma.py
├── 14_karar_destek_sistemi.py
└── 14_1_karar_destek_grafikleri.py

📁 grafikler

📁 veri_setleri

