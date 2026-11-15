# Vektörel Barkod & Etiket Stüdyosu (Standalone Edition)

Code 128, EAN-13, UPC-A, Code 39, Data Matrix ve PDF417 formatlarında tam Türkçe karakter destekli vektörel SVG barkod üretici.

- **Canlı Demo (GitHub Pages):** https://melihkarasu.github.io/barkod-studyosu/
- **Ana Proje (Monorepo):** [melihkarasu/VibeCodedApps](https://github.com/melihkarasu/VibeCodedApps)

## Mimari & Gizlilik Özellikleri
- **Sıfır Backend (Zero-Backend):** Tamamen tarayıcı üzerinde çalışır; kullanıcı verileri VibeRuntime üzerinden yalnızca localStorage içinde saklanır.
- **KVKK & GDPR Uyumu:** Google Fonts CDN veya 3. taraf takip betiği içermez; tüm fontlar (vendor/fonts/*.woff2) yerel olarak paketlenmiştir.

## Lokal Çalıştırma
```bash
npx serve .
```
