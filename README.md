<p align="center"><img src="icon.png" width="112" alt=""></p>

<h1 align="center">SU Room Reservation</h1>

<p align="center">Sabancı Üniversitesi'ndeki oda rezervasyonlarını ve boş saatleri tek ekranda gösterir.</p>

---

SUIS'teki Room Search sayfasında binaları tek tek açmak yerine, tüm binaların rezervasyonları
**bina › oda › saat** düzeninde tek listede görünür.

- **Rezervasyonlar / Boş saatler:** Dolu saatleri ya da 08:00–17:00 arasındaki boş zamanları gösterir.
- **Detay:** Saate dokununca ders kodu, adı, CRN ve öğretim üyesi açılır; oklarla aynı odanın diğer rezervasyonlarına geçilir.
- **Filtreler:** Sadece amfiler, sadece seçtiğin odalar, arama (oda, bina, saat).
- Karanlık ve aydınlık tema; seçimlerin hatırlanır.

> Sabancı Üniversitesi'nin resmi uygulaması değildir. Veriler SUIS'in herkese açık oda arama sayfasından okunur.

## İndir

| | |
|---|---|
| **Android uygulaması** | [Son sürüm sayfası](../../releases/latest) → `SU-Room-Reservation-….apk` |
| **Edge / Chrome eklentisi** | [su-oda-ozeti-eklenti.zip](../../releases/latest/download/su-oda-ozeti-eklenti.zip) |
| **Yer imi (kurulumsuz)** | [su-oda-ozeti-kurulum.html](../../releases/latest/download/su-oda-ozeti-kurulum.html) |

## Android

1. Telefonda [son sürüm sayfasını](../../releases/latest) aç, `.apk` dosyasını indir ve aç.
2. İzin isterse tarayıcına **bilinmeyen uygulamaları yükleme** izni ver.
3. Play Protect "tanınmayan geliştirici" uyarısı gösterebilir → **Yine de yükle**.

Ana ekranda **SU Rooms** adıyla görünür. Yeni sürüm çıktığında uygulama açılışta haber verir;
**İndir ve kur** düğmesine dokunman yeterli.

## Edge / Chrome eklentisi (bilgisayar)

Simgesine tıklayınca özet doğrudan yeni sekmede açılır.

1. [Eklenti zip'ini](../../releases/latest/download/su-oda-ozeti-eklenti.zip) indir ve **kalıcı bir klasöre** çıkar
   (ör. `Belgeler\su-oda-ozeti`). Eklenti oradan çalışır; klasörü silme ya da taşıma.
2. Adres çubuğuna `edge://extensions` (Chrome'da `chrome://extensions`) yaz.
3. **Geliştirici modu** anahtarını aç → **Paketlenmemiş öğe yükle** (*Load unpacked*) → klasörü seç.
4. Yapboz simgesinden **SU Oda Özeti**'ni araç çubuğuna sabitle.

**Güncelleme:** yeni zip'i aynı klasöre çıkarıp üzerine yaz, eklentiler sayfasında yenile (↻) düğmesine bas.

## Yer imi (kurulum gerektirmez)

1. [Kurulum sayfasını](../../releases/latest/download/su-oda-ozeti-kurulum.html) indir ve tarayıcıda aç.
2. Sayfadaki **SU Oda Özeti** düğmesini yer imleri çubuğuna sürükle (çubuk görünmüyorsa `Ctrl+Shift+B`).
3. SUIS Room Search sayfasındayken yer imine tıkla.

## Kullanım ipuçları

- **Gün değiştirme:** Bilgisayarda `←` `→` tuşları, telefonda alttaki oklar.
- **Detay penceresi:** Bilgisayarda `←` `→` ile, telefonda sağa-sola kaydırarak aynı odanın önceki/sonraki
  rezervasyonuna geçilir. `Esc`, aşağı çekme ya da geri tuşu kapatır.
- **Oda seçme:** Odanın solundaki kutucuğu işaretle, sonra **Sadece seçililer** ile yalnızca onları gör.
- **Boş saatler:** 08:00–17:00 arası, 30 dakikadan kısa aralar gösterilmez.
