# Auramy 📸✨

Auramy, iPhone ve iPad için sade bir galeri, depolama temizleyici ve Google Drive yedekleme uygulamasıdır.

---

## 🌐 Canlı Web Bağlantıları (GitHub Pages)

Bu bağlantılar App Store Connect, Google OAuth Consent Screen ve uygulama içi yönlendirmelerde kullanılır:

| Hizmet | Canlı URL | Açıklama |
| :--- | :--- | :--- |
| 🏠 **Ana Sayfa / Landing** | [https://auramyy.github.io/](https://auramyy.github.io/) | Uygulama tanıtım ve vitrin sitesi |
| 🛡️ **Gizlilik Politikası** | [https://auramyy.github.io/privacy.html](https://auramyy.github.io/privacy.html) | App Store & Google OAuth zorunlu gizlilik sayfası |
| 💬 **Destek Sayfası** | [https://auramyy.github.io/support.html](https://auramyy.github.io/support.html) | SSS ve destek iletişim sayfası |
| 🖼️ **App İkon Görseli** | [https://auramyy.github.io/assets/icon.png](https://auramyy.github.io/assets/icon.png) | OpenGraph (og:image) ve meta görseli |

---

## 🍎 App Store Connect Bilgileri

App Store'a gönderim yaparken veya sürüm güncellerken ilgili alanlara girilecek hazır değerler:

- **Gizlilik Politikası URL'i (Privacy Policy URL):**  
  `https://auramyy.github.io/privacy.html`
- **Destek URL'i (Support URL):**  
  `https://auramyy.github.io/support.html`
- **Pazarlama URL'i (Marketing URL):**  
  `https://auramyy.github.io/`
- **Standart Apple EULA (Son Kullanıcı Lisans Sözleşmesi):**  
  `https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`
- **Destek E-posta Adresi:**  
  `yagjz@icloud.com`
- **Geliştirici Instagram:**  
  `@dev.yagiz` ([https://instagram.com/dev.yagiz](https://instagram.com/dev.yagiz))

---

## 📂 GitHub Depoları

- **Uygulama Kaynak Kodu (iOS Projesi):**  
  [https://github.com/myagjz/Auramy](https://github.com/myagjz/Auramy)
- **Web Sitesi Yayını (GitHub Pages Deposu):**  
  [https://github.com/Auramyy/Auramyy.github.io](https://github.com/Auramyy/Auramyy.github.io)

---

## 🛠️ Kod İçerisinde Bu Linklerin Geçtiği Dosyalar

Linkleri ileride değiştirmek veya kontrol etmek isterseniz şu dosyalara bakabilirsiniz:

1. **`Auramy/AboutView.swift`**
   - `privacyPolicyURL`: `https://auramyy.github.io/privacy.html`
   - `supportURL`: `https://auramyy.github.io/support.html`
   - `contactEmail`: `yagjz@icloud.com`
   - `instagramURL`: `https://instagram.com/dev.yagiz`

2. **`Auramy/AuramyPro.swift`**
   - `privacyURL`: `https://auramyy.github.io/privacy.html`
   - `termsURL`: `https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`

3. **`Auramy.storekit`**
   - `policyURL`: `https://auramyy.github.io/privacy.html`

4. **`docs/app-store-submission.md`**
   - App Store Connect gönderim notları ve gizlilik kontrol listesi.

---

## 🚀 Web Sitesinde Değişiklik Yapıldığında Canlıya Alma

`docs/` klasöründe bir değişiklik yaptığınızda `Auramyy.github.io` sitesini güncellemek için Terminal'de şu komutları çalıştırmanız yeterlidir:

```bash
# 1. Değişen dosyaları site deposuna kopyalayın
cp -R ~/Desktop/Auramy/docs/* ~/Desktop/Auramyy.github.io/

# 2. Site deposuna geçip commit & push yapın
cd ~/Desktop/Auramyy.github.io
git add .
git commit -m "Web sitesi guncellendi"
git push origin main
```
