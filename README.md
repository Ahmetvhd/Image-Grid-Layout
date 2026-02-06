# Image Grid Layout 🖼️

Bu proje, CSS Grid kullanarak oluşturulmuş, asimetrik ve modern bir resim galeri düzenidir. Standart eşit kutular yerine, belirli hücrelerin dikeyde genişlediği (`span`) daha dinamik bir yapı hedeflenmiştir.

## 🚀 Özellikler

* **Asimetrik Tasarım:** Kenar sütunlardaki resimler tam boy kaplarken, orta sütun iki parçalı (üst-alt) yapıdadır.
* **Responsive Yaklaşım:** Resimler `object-fit: cover` özelliği ile en-boy oranını bozmadan alanı doldurur.
* **Temiz Kod:** Sadece HTML ve CSS kullanılarak, harici bir kütüphane gerektirmeden oluşturulmuştur.

## 🛠️ Teknik Detaylar

Projede temel olarak şu CSS Grid özellikleri kullanılmıştır:

* **`display: grid;`**: Esnek ve kontrollü bir yerleşim planı için.
* **`grid-template-columns: repeat(3, 1fr);`**: Alanı 3 eşit genişlikte sütuna böler.
* **`grid-row: span 2;`**: Belirli resimlerin (1. ve 3. resimler) iki satırlık yüksekliği kaplamasını sağlar.
* **`object-fit: cover;`**: Resimlerin konteyner dışına taşmadan ve bozulmadan hücreyi tam doldurması için.

## 📸 Görünüm

Düzen şu mantıkla çalışmaktadır:
- **Sütun 1:** Tek resim (Boydan boya)
- **Sütun 2:** İki resim (Üst üste)
- **Sütun 3:** Tek resim (Boydan boya)

## 💻 Kurulum ve Kullanım

Projeyi yerel bilgisayarınızda çalıştırmak için:

1. Depoyu klonlayın:
   ```bash
   git clone [https://github.com/ahmetvhd/Image-Grid-Layout.git](https://github.com/ahmetvhd/Image-Grid-Layout.git)