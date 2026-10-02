# İnşaat — Örnek Web Tasarımları

İnşaat firmalarına gösterilmek üzere hazırlanmış örnek web sitesi tasarımları.
Görüşmelerde "böyle bir şey yapıyoruz" diye göstermek için kullanılır.

## Şablonlar

| Klasör | Tarz | İçerik |
| --- | --- | --- |
| `01-kurumsal` | Koyu antrasit + altın vurgu, serif başlık, uzun tek sayfa | Deneme tasarımı — marka yok |
| `02-modern` | Beyaz + mavi vurgu, tam ekran fotoğraf, ortalanmış sade dil | Deneme tasarımı — marka yok |
| `03-vitrin` | Açık zemin + çelik gri vurgu, kayan proje vitrini, fotoğraf ağırlıklı | Deneme tasarımı — marka yok |

`index.html` üçünü listeleyen seçim sayfasıdır; görüşmede önce bunu açıp aralarında gezinebilirsiniz.

## Tanıtım videosu

`tanitim/index.html`, 01-kurumsal tasarımını bir dizüstü ya da telefon çerçevesi içinde
kendi kendine kaydırır. Ekran kaydı alıp videoya çevirmek içindir.

1. Yerel sunucuyu çalıştırın: `npx serve -l 4180 .`
2. `http://localhost:4180/tanitim/` adresini açın.
3. Kadrajı (yatay 16:9 / dikey 9:16) ve hızı seçin.
4. **Sunum kipi** düğmesine basın — kontroller gizlenir, tam ekrana geçer.
5. `Win + Alt + R` ile kaydı başlatın, bir tur dönsün, aynı kısayolla durdurun.
   Video `VideolarCaptures` klasörüne MP4 olarak düşer.

Başka bir tasarımı göstermek için `tanitim/index.html` içindeki iframe kaynağını değiştirin
(örn. `src="../02-modern/"`). Yol klasör biçiminde verilmeli; `index.html` yazılırsa sunucu
yönlendirme yapıp stil dosyasının yolunu bozuyor.

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
- Telefon, e-posta ve adres alanları her dosyada yer tutucudur (`0000 000 00 00`, `ornek@ornek.com`).


## Yeni şablon eklemek

Yeni bir klasör açıp içine `index.html` ve `style.css` koymak yeterli; sonra kökteki
`index.html` içindeki kart ızgarasına bir bağlantı eklenir.
