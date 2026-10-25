# Hafta 2: Yazılım Gereksinimleri

Aşağıdaki gereksinimler, katalogdaki teknik bilgilerden çıkarılmış yorumlardır. Üretici yazılımla ilgili ayrıntı vermediği için bunlar çıkarımdır.

## Fonksiyonel gereksinimler

| No | Katalog bilgisi | Yazılım gereksinimi |
|---|---|---|
| FR-01 | Testere arabası 170 m/dk, itici/tutucu 135 m/dk | Yüksek hızda gerçek zamanlı konum kontrolü, hız ve ivme profili |
| FR-02 | Tek plakada 100 m/dk, istifte 50 m/dk kesim hızı | Malzeme ve istif yüksekliğine göre kesim parametrelerinin otomatik seçimi |
| FR-03 | FLEXCUT 1/D: 2. kesim ekseni, bağımsız 2 tutuş-itiş ekseni | Çoklu eksen senkronizasyonu, görev planlama, çakışma önleme |
| FR-04 | Ana testere yükselme 130/145/165 mm, motor 11-37 kW | Testere yüksekliği ve motor akımı izleme, aşırı yük koruması |
| FR-05 | Plastik malzeme kesme kabiliyeti | Malzeme türüne göre ayrı parametre profilleri |
| FR-06 | Otomatik istif stok sistemi entegrasyonu | Harici sistemle haberleşme ve iş akışı koordinasyonu |
| FR-07 | Merkezi otomatik yağlama | Periyodik bakım zamanlaması ve uyarılar |
| FR-08 | Modüler donanım, opsiyonlu üretim | Yazılımın seçilen donanıma uyum sağlaması (konfigürasyon yönetimi) |

## Fonksiyonel olmayan gereksinimler (tahmini)

- **NFR-01:** Gerçek zamanlı çalışma (hareket kontrolünde gecikme olmamalı)
- **NFR-02:** Güvenlik (acil stop, hata durumunda güvenli duruş)
- **NFR-03:** Güvenilirlik (sürekli üretimde kararlı çalışma)
- **NFR-04:** Kullanılabilirlik (operatör arayüzünün anlaşılır olması)

## Not

HI-TRONIC özelliği katalogda açıklanmadığı için gereksinim olarak yazılmamıştır.
