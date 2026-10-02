# İnşaat — Örnek Web Tasarımları

İnşaat firmalarına gösterilmek üzere hazırlanmış örnek web sitesi tasarımları.
Görüşmelerde "böyle bir şey yapıyoruz" diye göstermek için kullanılır.

## Şablonlar

| Klasör | Tarz | İçerik |
| --- | --- | --- |
| `01-kurumsal` | Koyu zemin, serif başlık, uzun tek sayfa | Deneme tasarımı — marka yok |
| `02-modern` | Açık zemin, tam ekran görsel, ortalanmış sade dil | Deneme tasarımı — marka yok |
| `03-vitrin` | Proje odaklı kayan vitrin, taş ve bronz tonları | Deneme tasarımı — marka yok |
| `cevirgen` | 01 ile aynı kurgu, bir firmaya uyarlanmış hâli | Firmaya özel renk ve proje adları |

`index.html` dördünü listeleyen seçim sayfasıdır; görüşmede önce bunu açıp aralarında gezinebilirsiniz.

## Açma

Her şablon bağımsızdır, derleme gerekmez. Kökteki `index.html` dosyasını çift tıklamak yeterli.
İnternet bağlantısı gerekmez: yazı tipi, görsel ya da betik dışarıdan çekilmez.

## Notlar

- **01, 02 ve 03 deneme tasarımıdır**; hiçbir firmanın adı, projesi ya da rakamı geçmez.
  Firma adı yerine "Firma Adı", proje adı yerine "Proje Adı 01…05" yazar.
- `cevirgen` klasörü belirli bir firmaya uyarlanmış sürümdür; renkler firmanın logosundan,
  proje adları kendi tanıtımlarından alınmıştır. **Yayına alınmaz, yalnızca sunum içindir.**
- Telefon, e-posta ve adres alanları her dosyada yer tutucudur (`0000 000 00 00`, `ornek@ornek.com`).
- Fotoğraf kullanılmaz; görsellerin geleceği yerler renkli alanlarla ve "Görsel alanı" yazısıyla
  belirtilmiştir. Firmanın kendi fotoğrafları geldiğinde bu alanlara konur.

## Yeni şablon eklemek

Yeni bir klasör açıp içine `index.html` ve `style.css` koymak yeterli; sonra kökteki
`index.html` içindeki kart ızgarasına bir bağlantı eklenir.
