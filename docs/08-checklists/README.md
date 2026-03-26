# EN 50600 Design & Audit Checklists

<p align="center">
  <img src="https://img.shields.io/badge/Status-Audit%20Ready-success?style=for-the-badge" alt="Audit Ready">
</p>

## 📌 Giriş
Bu bölüm, bir veri merkezinin EN 50600 standartlarına uyumluluğunu doğrulamak için mimarlar ve denetçiler tarafından kullanılabilecek pratik kontrol listelerini içerir.

## 🏗️ Bölüm 1: Genel Mimari & Yerleşke (EN 50600-2-1)
- [ ] İş Risk Analizi dökümante edildi mi?
- [ ] Saha seçiminde doğal afet riskleri (sel, deprem) değerlendirildi mi?
- [ ] Zemin yük taşıma kapasitesi (sunucu ve mekanik yükler için) onaylandı mı?
- [ ] Yangın dayanımlı bölmeler (Fire compartments) EI60/EI120 kriterlerine uygun mu?
- [ ] "Paketsiz Bölge" (Staging area) planlandı mı?

## ⚡ Bölüm 2: Enerji Altyapısı (EN 50600-2-2)
- [ ] Hedeflenen **Availability Class** (1, 2, 3 veya 4) belirlendi mi?
- [ ] Enerji dağıtım topolojisi hedeflenen sınıfa uygun mu? (Örn: Class 3 için 2N).
- [ ] UPS yedekliliği ve batarya otonomi süresi doğrulandı mı?
- [ ] Jeneratörlerin yakıt depolama kapasitesi (Örn: 24h, 48h, 72h) yeterli mi?
- [ ] Enerji ölçüm noktaları (Granularity Level 1, 2 veya 3) tanımlandı mı?

## ❄️ Bölüm 3: İklimlendirme & Çevresel Kontrol (EN 50600-2-3)
- [ ] ASHRAE sıcaklık ve nem sınırlarına uyum planlandı mı?
- [ ] Hava akımı yönetimi (Sıcak/Soğuk koridor kapatma) tasarlandı mı?
- [ ] Soğutma kapasitesi N+1 veya daha yüksek bir yedeklilikte mi?
- [ ] Acil durum soğutma senaryoları (Energy out) test edildi mi?

## 🛡️ Bölüm 4: Fiziksel Güvenlik (EN 50600-2-5)
- [ ] "Soğan Kabuğu" (Defense-in-Depth) güvenlik katmanları tanımlandı mı?
- [ ] Biyometrik erişim ve man-trap sistemleri kritik alanlar için planlandı mı?
- [ ] CCTV kör nokta analizi yapıldı mı?
- [ ] Yangın algılama ve söndürme (Örn: Gazlı söndürme) sistemleri entegre mi?

---
[⬅️ Geri Dön](../../README.md)
