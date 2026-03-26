# 🏗️ EN50600 Architect Hub

<p align="center">
  <img src="assets/banner.png" alt="EN50600 Architect Hub Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Standard-CENELEC%20EN%2050600-blue?style=for-the-badge&logo=engineering" alt="EN 50600 Standard">
  <img src="https://img.shields.io/badge/Domain-Data%20Center%20Architecture-darkgreen?style=for-the-badge" alt="Domain">
  <img src="https://img.shields.io/badge/Status-Apotheosis%20Edition-gold?style=for-the-badge" alt="Status">
</p>

---

## 🏛️ Executive Manifesto
**EN50600 Architect Hub**, modern veri merkezlerinin tasarımı, inşası ve işletilmesi için Avrupa'nın en kapsamlı standardı olan **CENELEC EN 50600** serisini temel alan, dünya standartlarında bir mühendislik ve mimari portalıdır. Bu platform, sadece bir dokümantasyon havuzu değil; iş sürekliliğini, enerji verimliliğini ve fiziksel güvenliği maksimize etmeyi hedefleyen **otonom bir mühendislik ekosistemidir**.

> "Mükemmellik bir eylem değil, bir alışkanlıktır. Veri merkezi mimarisinde ise bu alışkanlık, EN 50600 standartlarının titizlikle uygulanmasıdır."

---

## 🛡️ Defense-in-Depth: Derinlemesine Savunma (Soğan Kabuğu)
Güvenlik mimarimiz, varlıkları merkeze alan ve dışarıdan içeriye doğru daralan kısıtlayıcı bir katman yapısını (**Onion Model**) esas alır:

*   **Zone 1 (Perimeter):** Genel erişim ve dış çevre güvenliği.
*   **Zone 2 (Building):** Bina girişi ve ortak alanlar.
*   **Zone 3 (Data Hall):** Sunucu odaları ve kritik teknik alanlar.
*   **Zone 4 (Safe Room):** En hassas verilerin ve kritik altyapı bileşenlerinin bulunduğu çekirdek bölge.

---

## 🎓 EN 50600 Academic Curriculum (7-Level Roadmap)

Bu rehber, bir veri merkezi mimarının uzmanlaşması gereken 7 kritik seviyede yapılandırılmıştır:

### 🟢 [Level 1: Foundation & General Concepts (EN 50600-1)](docs/01-foundation/README.md)
*   Temel terminoloji ve standartlar hiyerarşisi.
*   İş Risk Analizi (Business Risk Analysis) metodolojileri.
*   Kullanılabilirlik (Availability) ve Koruma (Protection) sınıflarının belirlenmesi.

### 🔵 [Level 2: Structural Architecture (EN 50600-2-1)](docs/02-structural/README.md)
*   Yerleşke seçimi ve bina tasarımı.
*   Oda planlaması: Data Hall, UPS odası, Soğutma merkezi koordinasyonu.
*   Yangın koruma ve deprem dayanıklılığı kriterleri.

### ⚡ [Level 3: Energy Orchestration (EN 50600-2-2)](docs/03-power/README.md)
*   Güç dağıtım sistemleri ve yedekleme (N+1, 2N, 2N+1).
*   UPS teknolojileri ve batarya yönetim sistemleri.
*   Jeneratör setleri ve yakıt depolama stratejileri.

### ❄️ [Level 4: Environmental Precision (EN 50600-2-3)](docs/04-environmental/README.md)
*   Sıcak/Soğuk koridor yapılandırmaları.
*   Hassas kontrollü iklimlendirme sistemleri (CRAC/CRAH).
*   Su soğutmalı (Chiller) vs. Hava soğutmalı sistemlerin verimlilik analizi.

### 🌐 [Level 5: Connectivity & Security (EN 50600-2-4 & 2-5)](docs/05-infrastructure/README.md)
*   Telekomünikasyon kablolama altyapısı (Tiering levels).
*   Fiziksel erişim kontrol sistemleri (Biometrik, Man-trap).
*   CCTV ve çevre güvenlik sensörleri entegrasyonu.

### ⚙️ [Level 6: Operational Mastery (EN 50600-3-1)](docs/06-operations/README.md)
*   Veri merkezi yönetim ve işletim prosedürleri.
*   Bakım takvimleri ve SLA yönetimi.
*   Kapasite planlama ve varlık yönetimi (DCIM).

### 📈 [Level 7: Performance Optimization (EN 50600-4-x)](docs/07-optimization/README.md)
*   **PUE** (Power Usage Effectiveness) ölçümü ve optimizasyonu.
*   **REF** (Renewable Energy Factor) entegrasyonu.
*   **ERF** (Energy Reuse Factor) uygulamaları.

---

## 📊 Key Performance Indicators (KPI) Matrix

| Kategori | EN 50600 Sınıfı | Tanım | Hedef |
| :--- | :---: | :--- | :--- |
| **Availability** | Class 1 - 4 | Sistemin yedeklilik ve hata toleransı. | Max Uptime (99.999%) |
| **Protection** | Class 1 - 4 | Tehditlere karşı fiziksel direnç. | Zero Breach |
| **Granularity** | Level 1 - 3 | Enerji ölçüm ve izleme detayı. | Real-time Precision |

---

## 🛠️ Core Design Principles
*   **Hata Toleransı (Fault Tolerance):** Tek bir bileşen arızasında sistemin kesintisiz çalışması.
*   **Eşzamanlı Bakım (Concurrent Maintainability):** Operasyonu durdurmadan altyapı bakımı yapabilme.
*   **Sürdürülebilirlik (Sustainability):** Minimum karbon ayak izi, maksimum enerji verimliliği.

---

### 📑 [Specialized Content: Audit & Design Checklists](docs/08-checklists/README.md)
*   Bina, Enerji, Soğutma ve Güvenlik için denetim hazır kontrol listeleri.
*   EN 50600 Uyumluluk Matrisi.

---

## 🛡️ Cyber-Physical Security Integration Matrix
Veri merkezlerinde fiziksel güvenlikle siber güvenlik arasındaki entegrasyon, saldırı yüzeyini minimize etmek için hayatidir:

| Fiziksel Kontrol | Siber Katman Karşılığı | EN 50600 Focus |
| :--- | :--- | :--- |
| **Zone 4 Safe Room** | Zero Trust Network Segments | Physical Hardening |
| **Biometric Access** | MFA (Multi-Factor Authentication) | Access Control |
| **CCTV Analytics** | IDS (Intrusion Detection System) | Monitoring |
| **Man-trap Gates** | Web Application Firewall (WAF) | Perimeter Defense |

---

## 🏆 Apotheosis Edition - Architectural Seal
Bu hub, **Bahattin Yunus Çetin** tarafından veri merkezi mimarisinde otorite ve mükemmellik için tasarlanmıştır. Tüm dökümantasyon, teknik raporlar (CLC/TR 50600-99-x) ve en iyi uygulama kılavuzlarıyla (Best Practices) desteklenmektedir.

---

## 🤝 Contribution & Governance
Bu proje bir topluluk girişimidir. Katkıda bulunmak için lütfen [CONTRIBUTING](CONTRIBUTING.md) belgesini inceleyin.

*   **Maintainer:** [Bahattin Yunus Çetin](https://github.com/bahattinyunus)
*   **License:** [MIT](LICENSE)

---

<p align="center">
  <i>"Architecture is the art of how to waste space; Data Center Architecture is the science of how to use every millimeter for mission-critical reliability."</i>
</p>
