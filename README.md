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
**EN50600 Architect Hub**, modern veri merkezlerinin uçtan uca tasarımı, inşası ve sürdürülebilir işletilmesine yönelik Avrupa'nın en prestijli ve kapsamlı mühendislik normu olan **CENELEC EN 50600** serisini temel alan, dünya standartlarında bir mimari bilgi portalıdır. Bu platform, teorik standart dökümanlarının ötesine geçerek; modülerlik, ölçeklenebilirlik ve yüksek kullanılabilirlik (High Availability) prensiplerini gerçek dünya mühendislik pratikleriyle harmanlayan otonom bir bilgi ekosistemidir. Temel vizyonumuz, "Standardization as a Strategy" yaklaşımıyla, teknik riskleri minimize eden ve operasyonel verimliliği (PUE/REF) maksimize eden bütünsel bir tasarım disiplini oluşturmaktır.

> "Veri merkezi mimarisi, statik bir inşaat projesi değil; dinamik, evrimleşen ve hata payı sıfır olan bir teknoloji orkestrasyonudur. Bu hub, bu orkestrasyonun kusursuz şefi olmayı hedefler."

---

## 🛡️ Defense-in-Depth: Derinlemesine Savunma (Soğan Kabuğu)
Modern veri merkezi güvenliği, sadece dijital duvarlarla değil, aynı zamanda fiziksel katmanların birbirini desteklediği kısıtlayıcı bir hiyerarşiyle sağlanır. Bu hub, varlıkları (kritik veri ve donanım) merkeze alan ve dışarıdan içeriye doğru daralan **Defense-in-Depth** (Soğan Kabuğu) modelini temel mimari prensip olarak kabul eder:

*   **Zone 1 (Perimeter Security):** Veri merkezi yerleşkesinin dış sınırlarını temsil eder. Burada odak noktası; çevre çitleri, anti-ram bariyerler, termal çevre kameraları ve sismik sensörler ile yetkisiz girişleri fiziksel katmanda durdurmaktır.
*   **Zone 2 (Building Integrity):** Bina giriş noktaları, yükleme rampaları ve teknik servis girişlerini kapsar. Bu bölge, biometrik erişim kontrolü, tekil geçiş sistemleri (Man-trap) ve x-ray tarama üniteleri ile personelin yetki seviyesinin ilk kez doğrulandığı kritik bir kontrol bariyeridir.
*   **Zone 3 (Data Hall Isolation):** Sunucu odalarının kapılarını ve teknik koridorları içerir. Burada sadece en yüksek yetki seviyesine sahip personelin biometrik kimlik doğrulamasıyla girişine izin verilir. Bu bölge aynı zamanda yangın ve su algılama sistemlerinin en yoğun olduğu alandır.
*   **Zone 4 (Safe Room Core):** En hassas verilerin, HSM (Hardware Security Module) cihazlarının ve kritik ağ omurgasının bulunduğu çekirdek bölgedir. Bu bölge, bağımsız iklimlendirme ve güç yedekliliğinin yanı sıra, Faraday kafesi prensipleriyle elektromanyetik saldırılara karşı da korunur.

---

## 🎓 EN 50600 Academic Curriculum (7-Level Roadmap)

Bu rehber, bir veri merkezi mimarının (Data Center Architect) uzmanlaşması gereken yedi temel disiplini, akademik bir titizlikle yapılandırılmış bir yol haritası (Roadmap) olarak sunar:

### 🟢 [Level 1: Foundation & Strategic Readiness (EN 50600-1)](docs/01-foundation/README.md)
*   **Analiz:** İş ihtiyaçlarının dökümantasyonu ve kritiklik seviyelerinin (Criticality Levels) akademik bir yaklaşımla belirlenmesi.
*   **Risk:** Business Risk Analysis (BRA) metodolojileri ile dış tehditlerin ve operasyonel risklerin kantitatif olarak ölçülmesi.
*   **Klasifikasyon:** Hedeflenen Availability ve Protection sınıflarının (Class 1-4) tasarım girdisi olarak tanımlanması.

### 🔵 [Level 2: Structural Architecture & Site Selection (EN 50600-2-1)](docs/02-structural/README.md)
*   **Seçim:** Jeolojik riskler, elektromanyetik kirlilik ve lojistik erişilebilirlik üzerine kurulu saha seçim kriterleri.
*   **Tasarım:** Room-in-room konseptleri, yangın kompartmanizasyonu ve sismik dayanıklılığı optimize edilmiş bina mimarisi.
*   **Planlama:** Teknik odaların (UPS, Battery, Chillers) Data Hall ile olan mesafe ve yangın koruma koordinasyonu.

### ⚡ [Level 3: Power Distribution & Energy Resilience (EN 50600-2-2)](docs/03-power/README.md)
*   **Topoloji:** Class 3 (2N) ve Class 4 (2(N+1)) yedeklilik modellerinin enerji dağıtımındaki kritik önemi ve anahtarlama süreleri.
*   **Süreklilik:** UPS teknolojilerinin (Rotary vs. Static) ve jeneratör yakıt depolama stratejilerinin otonomi süresiyle ilişkisi.
*   **Kalite:** Enerji kalitesi (THD), harmonik filtreleme ve topraklama sistemlerinin donanım ömrü üzerindeki etkisi.

### ❄️ [Level 4: Environmental Precision & Cooling Mastery (EN 50600-2-3)](docs/04-environmental/README.md)
*   **Isı Yönetimi:** ASHRAE Class A1 sınırları içerisinde, dinamik soğutma yüklerine göre optimize edilmiş CFD (Computational Fluid Dynamics) analizleri.
*   **Verimlilik:** Sıcak/Soğuk koridor kapatma (Containment) teknolojileri ve Free-Cooling sistemlerinin PUE üzerindeki dramatik etkisi.
*   **Kontrol:** Hassas nem dengesi, çiğ noktası (Dew Point) takibi ve hava filtrasyon (ISO ISO 14644-1) standartları.

### 🌐 [Level 5: Connectivity & Physical Security (EN 50600-2-4 & 2-5)](docs/05-infrastructure/README.md)
*   **Ağ:** Telekomünikasyon kablolama hiyerarşisi (MDA, HDA, EDA) ve omurga yedekliliğinin (Path redundancy) fiziksel planlaması.
*   **Güvenlik:** CCTV analitiği, sinsiz tespit sistemleri (IDS) ve biometrik veri güvenliğinin bina genelindeki entegrasyonu.
*   **İzolasyon:** Enerji ve data yollarının EMI/RFI parazitlerini önlemek için fiziksel olarak ayrıştırılması (Sanitization).

### ⚙️ [Level 6: Operational Mastery & Lifecycle Management (EN 50600-3-1)](docs/06-operations/README.md)
*   **İşletim:** Bakım takvimlerinin (Preventive vs. Predictive) yönetimi ve SLA (Service Level Agreement) taahhütlerinin karşılanması.
*   **Metodoloji:** Kritik müdahaleler için MOP (Method of Procedure) ve kriz anları için EOP (Emergency Operating Procedures) dökümantasyonu.
*   **Yönetim:** DCIM (Data Center Infrastructure Management) sistemleri ile kapasite, güç ve soğutmanın dijital ikiz üzerinden takibi.

### 📈 [Level 7: Performance Optimization & Green KPIs (EN 50600-4-x)](docs/07-optimization/README.md)
*   **Metrikler:** PUE (Güç), REF (Yenilenebilir Enerji), ERF (Enerji Geri Kazanımı) ve CUE (Karbon) metriklerinin bilimsel ölçümü.
*   **Granularity:** Enerji ölçümünde "Level 3 Granularity" ile sunucu bazlı gerçek zamanlı güç tüketimi ve verimlilik analizi.
*   **Sürdürülebilirlik:** Yeşil veri merkezi vizyonuyla, atık ısı kullanımı ve düşük GWP (Global Warming Potential) akışkan tercihlerinin optimizasyonu.

---

## 📊 Key Performance Indicators (KPI) Matrix

| Kategori | EN 50600 Sınıfı | Mimari Tanım ve Mühendislik Gereksinimi | Performans Hedefi (SLA) |
| :--- | :---: | :--- | :--- |
| **Availability** | Class 1 - 4 | Bileşen ve yol yedekliliğinin (N+1, 2N, 2N+1) hata toleransı kapasitesi. | Max Uptime (99.999% Tier IV Equiv.) |
| **Protection** | Class 1 - 4 | Çevresel (Deprem, Su, Yangın) ve insan tabanlı tehditlere fiziksel direnç. | Zero Security Breach & Full Integrity |
| **Granularity** | Level 1 - 3 | Enerji tüketimi ve verimlilik ölçümünün derinliği (Bina -> Oda -> Kabin -> Server). | Real-time Precision Monitoring |

---

## 🛠️ Core Design Principles: Mimari Sütunlar
Data center tasarımı, birbirine bağımlı üç ana sütun üzerinde yükselir:
*   **Hata Toleransı (Fault Tolerance):** Mimari, kritik bir hata anında (Kablo kopması, jeneratör arızası vb.) sistemin herhangi bir manuel müdahale gerektirmeden otonom olarak çalışmaya devam etmesini sağlamalıdır.
*   **Eşzamanlı Bakım (Concurrent Maintainability):** Hiçbir bakım faaliyeti (UPS akü değişimi, chiller bakımı vb.) veri merkezinin operasyonel yükünü kesintiye uğratmamalı; sistem hatları birbirini tamamlamalıdır.
*   **Sürdürülebilirlik (Sustainability):** Maksimum enerji verimliliği sadece maliyet için değil, aynı zamanda operasyonel karbon ayak izini azaltmak ve "Green Data Center" standartlarını yakalamak için esastır.

---

### 📑 [Specialized Content: Audit & Design Checklists](docs/08-checklists/README.md)
*   Saha seçimi, inşaat, elektrik, mekanik ve operasyonel hazırlık için denetim hazır (Audit-ready) kontrol listeleri.
*   EN 50600 Uyumluluk Matrisi ve sertifikasyon hazırlık rehberi.

---

## 🛡️ Cyber-Physical Security Integration Matrix
Veri merkezlerinde fiziksel güvenlikle siber güvenlik arasındaki entegrasyon, saldırı yüzeyini (Attack Surface) minimize etmek için hayatidir. Fiziksel bir boşluk, en güçlü firewall'un bile işlevsiz kalmasına neden olabilir:

| Fiziksel Kontrol (EN 50600-2-5) | Siber Katman Karşılığı (ISO 27001) | Stratejik Fokus |
| :--- | :--- | :--- |
| **Zone 4 Safe Room / Cage** | Micro-Segmentation & Zero Trust | Physical & Digital Hardening |
| **Multi-Factor Biometric Access** | MFA (Multi-Factor Authentication) | Identity & Access Governance |
| **CCTV AI Analytics** | SIEM / IDS (Intrusion Detection) | Behavioral Visibility |
| **Man-trap / Interlocking Doors** | Proxy / WAF (Web Application Firewall) | Traffic Filtering & Sanitization |

---

## 🏆 Apotheosis Edition - Architectural Seal
Bu hub, **Bahattin Yunus Çetin** tarafından veri merkezi mimarisinde mutlak otorite, teknik mükemmellik ve akademik derinlik için tasarlanmıştır. İçerikteki her dikey (Pillar), CENELEC EN 50600 resmi kaynakları, CLC/TR 50600-99 teknik raporları ve endüstri lideri mimari metodolojilerle desteklenmektedir. Bu platform, "IT Architect" perspektifiyle yapılandırılmış otonom bir mühendislik rehberidir.

---

## 🤝 Contribution & Governance
Bu proje bir topluluk girişimidir. Katkıda bulunmak için lütfen [CONTRIBUTING](CONTRIBUTING.md) belgesini inceleyin.

*   **Maintainer:** [Bahattin Yunus Çetin - IT Architect](https://github.com/bahattinyunus)
*   **License:** [MIT Official License](LICENSE)

---

<p align="center">
  <i>"Architecture is the art of how to waste space; Data Center Architecture is the science of how to use every millimeter for mission-critical reliability."</i>
</p>
