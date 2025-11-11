# LOOMA - AI Destekli Gardirob

<p align="center">
  <img src="https://media.giphy.com/media/Q5QswS6OUnH0uA6AI7/giphy.gif" alt="LOOMA animated hero" width="720">
</p>

> LOOMA, kiyafetlerini dijitallestirip yapay zeka ile aninda kombin onerileri sunan neon-isikli bir moda ussudur.

## One Cikanlar
- **Akilli Gardirob:** Favori parcalarini yukle, kategorize et ve dijital gardirobunda sakla.
- **AI Stilist:** Gunluk planina, hava durumuna veya ruh haline gore kisisellestirilmis kombin onerileri al.
- **Cyberpunk UI:** Pixelify Sans tabanli retro-futuristik arayuz, cam efektleri ve neon animasyonlarla desteklenir.
- **Etkilesimli Arka Plan:** Canvas tabanli partikuller ve parallax dokunuslariyla yasayan bir deneyim.
- **Esnek Bolumler:** Hero, ozellikler, urun akisI, beta daveti ve SSS bilesenleri Tailwind CSS ile modulerdir.

## Teknoloji Yigini

| Katman | Teknoloji | Aciklama |
| --- | --- | --- |
| UI/Styling | Tailwind CSS, Pixelify Sans | Temiz tasarim, cam efektleri, glitch basliklar |
| Animasyon | Custom Canvas, CSS keyframes | Partikul sistemi, fade-in, scanline overlay |
| Mantik | Vanilla JS | Beta formu, scroll yonetimi, responsif davranis |

## Proje Yapisi

```text
.
|- index.html   # Bitmis tek sayfa deneyim
|- README.md    # Bu belge
|- /assets      # (Opsiyonel) gorsel ve medya dosyalari icin onerilen klasor
```

## Yerelde Calistirma
1. Bu depoyu klonla veya zip olarak indir.
2. Herhangi bir statik sunucu ile ac:
   ```sh
   # Node tabanli hizli bir secenek
   npx serve .
   ```
3. Tarayicida `http://localhost:3000` adresine git ve neon dunyayi kesfet.

> Not: Proje tamamen statik oldugu icin herhangi bir derleme ya da bagimlilik kurulumu gerekmez.

## Yol Haritasi
- [ ] AI stilist icin gercek API entegrasyonu
- [ ] Gardirob ogeleri icin gorsel yukleme & surukle-birak destegi
- [ ] Coklu tema (gunduz / gece) secenegi
- [ ] PWA destegi ve offline onbellek

## Katki Rehberi
1. Yeni bir dal olustur (`git checkout -b feat/benim-ozelligim`).
2. Degisikliklerini yap ve test et.
3. Net bir aciklama ile pull request ac.

## Baglantilar
- **Canli Onizleme:** https://looma.github.io
- **Beta Listesi:** Sayfa icindeki formu doldurarak erken erisime katil.

---

LOOMA, dolabini retro-futuristik bir komuta merkezine donusturmek icin burada. Fikirlerin, geri bildirimlerin ve tasarimlarin icin issues/pr'larda bulusalim!
