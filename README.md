# İnşaat — Örnek Web Tasarımları

İnşaat firmalarına gösterilmek üzere hazırlanmış örnek web sitesi tasarımları.
Görüşmelerde "böyle bir şey yapıyoruz" diye göstermek için kullanılır.

## Şablonlar

| Klasör | Tarz | İçerik |
| --- | --- | --- |
| `01-kurumsal` | Koyu antrasit + altın vurgu, serif başlık, uzun tek sayfa | Deneme tasarımı — marka yok |
| `02-modern` | Beyaz + mavi vurgu, tam ekran fotoğraf, ortalanmış sade dil | Deneme tasarımı — marka yok |
| `03-vitrin` | Açık zemin + çelik gri vurgu, kayan proje vitrini, fotoğraf ağırlıklı | Deneme tasarımı — marka yok |
| `cevirgen` | 01 ile aynı kurgu, bir firmaya uyarlanmış hâli | Firmaya özel renk ve proje adları |

`index.html` dördünü listeleyen seçim sayfasıdır; görüşmede önce bunu açıp aralarında gezinebilirsiniz.

## Fotoğraflar

Tüm şablonlar kökteki ortak `gorseller/` klasörünü kullanır (`../gorseller/...`).
Fotoğraflar Unsplash'ten alınmıştır; Unsplash lisansı ticari kullanıma ve değiştirmeye izin verir,
atıf zorunlu değildir. Firmanın kendi fotoğrafları geldiğinde bu dosyaların üzerine yazmak yeterli:
dosya adları aynı kalırsa CSS'e dokunmaya gerek kalmaz.

| Dosya | Kullanıldığı yer |
| --- | --- |
| `hero-1..3.jpg` | Kahraman alanlar ve 03'ün kayan vitrini |
| `proje-1..6.jpg` | Proje kartları |

## Açma

Derleme gerekmez. Kökteki `index.html` dosyasını çift tıklamak yeterli.
İnternet bağlantısı gerekmez: yazı tipi, görsel ya da betik dışarıdan çekilmez.

## Notlar

- **01, 02 ve 03 deneme tasarımıdır**; hiçbir firmanın adı, projesi ya da rakamı geçmez.
  Firma adı yerine "Firma Adı", proje adı yerine "Proje Adı 01…05" yazar.
- `cevirgen` klasörü belirli bir firmaya uyarlanmış sürümdür; renkler firmanın logosundan,
  proje adları kendi tanıtımlarından alınmıştır. **Yayına alınmaz, yalnızca sunum içindir.**
- Telefon, e-posta ve adres alanları her dosyada yer tutucudur (`0000 000 00 00`, `ornek@ornek.com`).


## Yeni şablon eklemek

Yeni bir klasör açıp içine `index.html` ve `style.css` koymak yeterli; sonra kökteki
`index.html` içindeki kart ızgarasına bir bağlantı eklenir.
