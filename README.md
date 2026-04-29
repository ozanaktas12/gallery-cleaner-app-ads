# Vercel app-ads.txt setup

Bu klasor artik tek basina Vercel'e deploy edilebilir.

## Icerik

- `app-ads.txt` (koku dizin)
- `index.html` (basit aciklama sayfasi)
- `vercel.json`
- `public/app-ads.txt` (yedek, Next.js/public yapisi icin)

## Nasil yayinlanir

1. Vercel'de yeni proje olustur.
2. Root olarak bu klasoru sec: `vercel-app-ads-setup`
3. Deploy et.
4. Kontrol et:
   - `https://senin-domainin.com/app-ads.txt`

## App Store / AdMob

1. App Store Connect'te uygulamanin "Developer Website" alanina ayni domaini yaz.
2. AdMob'da app-ads.txt dogrulamasini tekrar calistir.

## app-ads.txt satiri

```txt
google.com, pub-4929426710820891, DIRECT, f08c47fec0942fa0
```

