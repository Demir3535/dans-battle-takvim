# Battle Takvimi Türkiye

Türkiye'deki hip-hop / street dance yarışmalarını tek listede gösteren tek dosyalık site.

## Çalıştırma
`index.html` dosyasına çift tıkla, tarayıcıda açılır. Kurulum yok.

## Etkinlik ekleme / güncelleme
`index.html` içindeki `<script>` bölümünde iki liste var:

- `EVENTS`: tarihi belli etkinlikler. Alanlar:
  `id` (benzersiz), `n` ad, `s` başlangıç (YYYY-AA-GG), `e` bitiş (isteğe bağlı),
  `c` şehir, `v` mekan, `k` kategoriler, `t` türler (`battle`, `crew`, `fed`, `intl`),
  `u` kaynak linki, `src` kaynak adı, `ig` Instagram kullanıcı adı, `sure:false` tarih kesin değilse.
- `WATCH`: tarihi henüz açıklanmamış organizasyonlar (`n` ad, `p` not, `w` beklenen dönem).

Geçmiş / yaklaşan ayrımı bugünün tarihine göre otomatik yapılır.

## Notlar
- Sayfadaki "Yarışma ekle" formu ve yıldızlar yalnızca o tarayıcının localStorage'ında saklanır.
- Son veri taraması: 13 Kasım 2026.
