# Hamming Kodu Simülatörü (Hamming Code Simulator)

Bu proje, veri iletimi veya depolanması sırasında meydana gelen hataları (bozulan bitleri) tespit edip düzeltebilen **Hamming Kodu** hata kontrol algoritmasını interaktif olarak görselleştiren ve test etmenizi sağlayan web tabanlı bir simülatördür.


##  Simülatör Ekran Görüntüleri
**1. Ana Ekran**

<img width="1469" height="454" alt="Ekran Resmi 2026-11-11 23 59 19" src="https://github.com/user-attachments/assets/c555693b-75d9-4a1e-8b16-94078b63f011" />
<br><br>

**2. Hatayla Karşılaşılmayan Durum**

<img width="1470" height="827" alt="Ekran Resmi 2026-11-11 23 58 49" src="https://github.com/user-attachments/assets/8c7af121-6a9f-4a99-9f4c-84d3e8f7bbef" />
<br><br>

**3. Hata Bulunan ve Düzeltilen Durum**

<img width="1470" height="828" alt="Ekran Resmi 2026-11-11 23 59 06" src="https://github.com/user-attachments/assets/a2cf9cf2-7b4d-4484-94ee-fe823d9fe7ba" />
<br><br>

##  Özellikler

- **Bit Uzunluğu Seçimi:** Farklı bit uzunluğu seçenekleriyle (8-Bit, 16-Bit, 32-Bit vb.) esnek veri işleme.
- **Dinamik Veri Girişi:** İstenen ikili (binary) veri dizilimini kolayca girebilme.
- **Bellek Görünümü:** Veri (M) ve Parite (K) bitlerinin bellekteki güncel dizilimini canlı takip edebilme.
- **Yapay Hata Enjeksiyonu:** Bellek üzerindeki herhangi bir bit kutusuna tıklayarak manuel (yapay) hata oluşturabilme ve sistemin tepkisini gözlemleme.
- **Sendrom Hesaplama & Hata Tespiti:** Yazılan ve hesaplanan parite bitlerini karşılaştırarak hata konumunu (Sendrom kelimesi ile) otomatik tespit etme.
- **Otomatik Düzeltme:** Hatalı bit konumunu belirleyip tek tıkla "Bitleri Düzelt" mekanizmasıyla temiz veriye ulaşma.


##  Kullanılan Teknolojiler

Proje geliştirilirken aşağıdaki temel web teknolojileri kullanılmıştır:
- **HTML5 / JSX** (Arayüz yapısı)
- **CSS3** (Özel tasarım, modern ve şık bileşenler)
- **JavaScript (ES6+)** (Hamming algoritması ve interaktif simülasyon mantığı)

