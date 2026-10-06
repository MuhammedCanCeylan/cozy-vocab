# 📖 Cozy Vocab — Akıllı Ezber Masası

> **Canlı Uygulama:** [cozy-vocab'ı Aç](https://muhammedcanceylan.github.io/cozy-vocab/)
> *(Linkteki yer tutucuları kendi GitHub kullanıcı adınız ve repo adınız ile güncelleyin)*

Gerçekçi ahşap masa ve 20 satırlık çizgili defter konseptiyle tasarlanmış, **Quizlet** ve **Anki** aktarım uyumlu, doğal telaffuz motoruna (Web Speech API) ve gerçek zamanlı ses sentezleyicisine sahip minimalist bir kelime ezberleme uygulaması.

---

## ✨ Öne Çıkan Özellikler

- **Skeuomorfik Ahşap Masa Deneyimi:** 20 metal telli spiral cilt, dikey kırmızı kenar boşluğu, kılavuz çizgileri ve Caveat/Patrick Hand el yazısı fontları.
- **Kayar A4 Örtücü Kağıt (Blinder Sheet):** Ekranın sağına dokunulduğunda satır satır aşağı kayarak anlamı açar; sola dokunulduğunda yukarı kapanır.
- **Doğal Telaffuz Motoru (Web Speech API):** Kelime açıldığı anda yüksek kaliteli yerel seslerle (Samantha, Daniel, Siri, Google Natural) otomatik telaffuz eder.
- **Mobil & Dokunmatik Jestler:**
  - **Sağa / Sola Dokunma:** 1 satır aç / 1 satır kapat.
  - **Basılı Tutma (Long Press):** Sayfa değiştir (titreşim geri bildirimi ile).
- **Gelişmiş Quizlet & Anki Aktarımı:** Tab (`\t`), virgül, tire, iki nokta veya özel ayırıcılarla (`custom delimiter`) metinleri otomatik algılayıp 20'şerli sayfalara böler.
- **Rastgele Karıştırma (Shuffle) & A-Z Sıralama:** Yer ezberini önlemek için sayfayı tek tıkla karıştırın veya alfabetik hizalayın.
- **Masa Lambası (Sıcak Gece Modu):** Gece çalışmaları için deftere odaklanan sıcak konik aydınlatma.
- **iPhone / PWA Uyumu:** Safari'den *Ana Ekrana Ekle* yapıldığında tarayıcı çubukları olmadan tam ekran yerel uygulama gibi çalışır.
- **Kalıcı Tarayıcı Hafızası:** Tüm kelimeler, sayfalar ve ayarlar `localStorage` üzerinde saklanır; harici sunucu veya veritabanı gerektirmez.

---

## 🚀 Hızlı Başlangıç

Bu proje hiçbir derleme aracı (`npm`, `webpack` vb.) gerektirmez. Tek bir HTML dosyası üzerinden sıfır bağımlılıkla çalışır.

1. Projeyi klonlayın:
   ```bash
   git clone [https://github.com/](https://github.com/)<KULLANICI_ADINIZ>/<REPO_ADINIZ>.git
   ```
2. `index.html` dosyasını herhangi bir modern tarayıcıda çift tıklayarak açın.

---

## ⌨️ Masaüstü Kısayolları

| Tuş | İşlev |
| :--- | :--- |
| `Boşluk (Space)` / `Aşağı Ok (↓)` | 1 Kelime Aç & Dinle |
| `Yukarı Ok (↑)` | 1 Kelime Kapat |
| `Sağ Ok (→)` | Sonraki Sayfaya Geç |
| `Sol Ok (←)` | Önceki Sayfaya Geç |
| `S` | Sayfadaki Kelimeleri Rastgele Karıştır |
| `L` | Masa Lambasını Aç / Kapat |

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) kapsamında lisanslanmıştır.