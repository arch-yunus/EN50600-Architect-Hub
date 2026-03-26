# Level 2: Structural Architecture (EN 50600-2-1)

<p align="center">
  <img src="https://img.shields.io/badge/Standard-EN%2050600--2--1-blue?style=for-the-badge" alt="EN 50600-2-1">
</p>

## 📌 Giriş
EN 50600-2-1, veri merkezinin fiziksel bina yapısını ve iç oda planlamasını kapsar. Bu aşamada verilen kararlar, veri merkezinin ömrü boyunca değiştirilmesi en zor olan unsurlardır.

## 📍 Yer Seçimi ve Çevre Analizi
Bina inşa edilmeden önce sahanın şu kriterlere göre değerlendirilmesi esastır:
- **Doğal Afet Riskleri:** Fay hatlarına uzaklık, sel bölgeleri dışı.
- **Elektromanyetik Parazit (EMI):** Yüksek gerilim hatları veya radyo vericilerine mesafe.
- **Erişilebilirlik:** Lojistik yollar ve data hatlarına yakınlık.

## 🏗️ Bina Tasarımı ve Oda Koordinasyonu
Veri merkezi sadece sunuculardan ibaret değildir. Odalar arası ilişki (Adjacency Matrix) şu mantıkla kurulur:
- **Data Hall (Sunucu Odası):** Merkeze konumlandırılır.
- **Mekanik Alanlar:** Soğutma merkezleri (Chiller, Pompa).
- **Elektrik Alanları:** UPS ve Batarya odaları (Data Hall'a yakın, ancak yangın korumalı ayrı bölme).
- **Staging/Storage:** Yeni ekipmanların kutularından çıkarıldığı ve test edildiği "paketsiz bölge".

## 🛡️ Fiziksel Güvenlik ve Mukavemet
- **Zemin Yük Kapasitesi:** Sunucu kabinlerinin ve soğutma ünitelerinin ağırlığını taşıyacak özel zeminler.
- **Su Baskını Koruması:** Sıvı tesisatının kritik odaların üstünden geçirilmemesi.
- **Yangın Dayanımı:** Duvarların ve kapıların minimum **EI60** (60 dakika yangın dayanımı) standardında olması.

---
[⬅️ Geri Dön](../../README.md)
