# Level 1: Foundation & General Concepts (EN 50600-1)

<p align="center">
  <img src="https://img.shields.io/badge/Standard-EN%2050600--1-blue?style=for-the-badge" alt="EN 50600-1">
</p>

## 📌 Giriş
EN 50600-1, tüm serinin temelini oluşturur. Bu bölüm, bir veri merkezinin tasarım aşamasından önce yapılması gereken stratejik analizleri ve sınıflandırma kriterlerini tanımlar.

## ⚖️ İş Risk Analizi (Business Risk Analysis)
Bir veri merkezinin tasarımı rastgele yapılmaz. EN 50600-1 standardına göre tasarım, bir "İş Risk Analizi" ile başlar. Bu analiz şunları kapsar:
- **Kritiklik Derecesi:** Verilerin kaybı veya sistemin durması durumunda oluşacak mali/prestij kaybı.
- **Tehdit Analizi:** Doğal afetler, siber saldırılar ve operasyonel hatalar.
- **İş Sürekliliği Hedefleri (RTO/RPO):** Sistemin ne kadar sürede ayağa kalkması gerektiği.

## 📊 Sınıflandırma Metrikleri

### 1. Kullanılabilirlik Sınıfları (Availability Classes)
Sistemin yedeklilik seviyesini belirler:
- **Class 1:** Yedeklilik yok (Single path).
- **Class 2:** Kısmi yedeklilik (Single path with redundant components).
- **Class 3:** Eşzamanlı bakım yapılabilir (Multiple paths, 1 active / 1 standby).
- **Class 4:** Hata toleranslı (Multiple paths, Active/Active, Single failure tolerant).

### 2. Fiziksel Koruma Sınıfları (Protection Classes)
Çevresel tehditlere ve yetkisiz erişime karşı direnci belirler:
- **Class 1:** Genel koruma.
- **Class 2:** Kısıtlı erişim, standart duvarlar.
- **Class 3:** Yüksek güvenlik, yangın ve su korumalı.
- **Class 4:** En yüksek güvenlikli çekirdek bölge (Soğan Kabuğu modelinin merkezi).

## 🚀 Uygulama Adımları
1. İş ihtiyaçlarını belirle.
2. Risk analizini tamamla.
3. Hedeflenen **Availability** ve **Protection** sınıflarını dökümante et.
4. Tasarım ekiplerine (Mimari, Elektrik, Mekanik) bu kriterleri girdi olarak ver.

---
[⬅️ Geri Dön](../../README.md)
