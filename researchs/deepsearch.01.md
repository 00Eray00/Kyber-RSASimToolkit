# Proje ve Hedefler ve Özellikler

## KyberCrypto Toolkit

Bu Python tabanlı post-kuantum kriptografi aracı, **CRYSTALS-Kyber** algoritmasını temel alarak kuantum-dirençli anahtar değişimi ve şifreleme süreçlerini otomatikleştiren, kapsamlı, modüler ve kullanıcı dostu bir çözümdür.

- Kyber-512, Kyber-768, Kyber-1024 referans implementasyonları
- RSA ve ECC gibi klasik algoritmalarla karşılaştırmalı analiz
- Anahtar üretimi, kapsülleme, kapsül açma, hata oranı analizi
- TLS/SSL entegrasyonu, hibrit şifreleme, MAC adresi ile kimlik doğrulama
- Grafana tarzı görselleştirme ile performans analizi
- Gerçek zamanlı izleme ve loglama

Esnek, güvenli ve açık kaynak yapısıyla, bu araç post-kuantum analizleri basitleştirir ve kuantum bilgisayar tehditlerine karşı çözümler sunar.

---

## Hedefler

- **Post-Kuantum Güvenlik Bilinci**  
  Lattice tabanlı algoritmaların önemini vurgulamak ve kullanıcıları eğitmek.

- **Performans Karşılaştırması**  
  Kyber ve klasik algoritmaların hız, bellek ve güvenlik açısından kıyaslanması.

- **Protokol Entegrasyonu**  
  TLS, VPN gibi protokollerde Kyber kullanımı ve hibrit modellerin denenmesi.

- **Kullanıcı Dostu Deneyim**  
  Grafiksel arayüz ve modüler yapı ile kolay kullanım.

- **Araştırma ve Eğitim Desteği**  
  Açık kaynak ve dokümantasyon ile akademik çalışmalara destek.

---

## Özellikler

### Kyber Algoritma Implementasyonu

- Kyber-512, Kyber-768, Kyber-1024 seviyeleri
- Lattice tabanlı kriptografi ile kuantum direnç
- NIST standartlarıyla uyumlu yapı

### Karşılaştırmalı Performans Analizi

- RSA ve ECC ile karşılaştırmalı benchmark araçları
- Anahtar üretimi, şifreleme/deşifreleme hızı, bellek kullanımı
- Grafana tarzı kullanıcı dostu görselleştirme

### Gerçek Zamanlı Performans İzleme

- Gerçek zamanlı algoritma takip sistemi
- Hata oranları, başarısız kapsül açma logları
- Anormallik tespiti ve uyarı sistemleri

### TLS/SSL Protokol Entegrasyonu

- Kyber ile TLS/SSL desteği
- Hibrit şifreleme modeli (Kyber + RSA)
- Gerçek dünya senaryolarında test

### MAC Adresi Tabanlı Kimlik Doğrulama

- MAC adresi ile ek kimlik doğrulama
- OUI analizi ile cihaz türü ve üretici tanımlama
- Yerel ağlarda güvenli anahtar paylaşımı

### Kuantum-Dirençli Hibrit Şifreleme

- Klasik algoritmalarla hibrit yapı
- RSA ile anahtar değişimi, Kyber ile veri şifreleme

### Görselleştirme ve Raporlama

- Grafana tarzı paneller
- PDF/CSV formatında detaylı raporlar
- Güvenlik seviyesi derecelendirmesi

### Kuantum Saldırı Simülasyonu

- Grover, Shor gibi kuantum saldırılara karşı direnç testi
- LWE tabanlı saldırı analizleri

### Modüler ve Açık Kaynak Yapı

- Python tabanlı modüler kod
- MIT lisansı, açık kaynak geliştirme
- API ve kapsamlı dokümantasyon

### Eğitimsel Araçlar

- Interaktif Kyber algoritma rehberleri
- Lattice kriptografisi ve kuantum tehdit eğitim materyalleri
- Üniversite ve bireysel kullanıcılara özel dokümanlar

---

## Teknik Detaylar

- **Bağımlılıklar**: Python 3.8+, numpy, pycryptodome, matplotlib  
- **Performans Optimizasyonu**: Vektörleştirme ve paralel işlem desteği  
- **Güvenlik Uyarısı**: Üretim ortamına uygun değildir; sabit zamanlı işlemler eksik olabilir.

---

## Kullanım Senaryoları

- **Güvenlik Araştırması**: Kuantum-dirençli algoritma testleri
- **Akademik Çalışmalar**: Eğitim ve araştırmalarda kullanım
- **Protokol Geliştirme**: TLS, VPN gibi sistemlerde Kyber entegrasyonu
- **Kurumsal Güvenlik Planlaması**: Kuantum sonrası güvenlik dönüşümüne hazırlık
