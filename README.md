# ✨ Çeyiz & Ev Hazırlık Takip Uygulaması

GitHub Pages üzerinde derleme (build) gerektirmeden anında çalışan, **Ortak PIN / Şifre Korumalı** ve **Firebase Gerçek Zamanlı Bulut Senkronizasyonlu** çeyiz takip uygulaması.

## Özellikler
- **Ortak Şifre / PIN Girişi:** Varsayılan şifre `2026` (Uygulama içinden veya koddan değiştirilebilir).
- **Ürün Takibi:** Ürün Adı, Alınacak Yer (Mağaza önerileriyle), Kategori ve **Çeyizde Var / Alınacak** durumu.
- **Gerçek Zamanlı Bulut Eşitleme (Firebase):** Tek bir Firebase Realtime Database URL'si ile tüm telefon ve bilgisayarlarda anlık senkronize çalışır.
- **Akıllı Filtreleme & İstatistik:** Tamamlanma yüzdesi, mağazaya göre filtreleme, kategori sekmeleri ve anlık arama.

## 🚀 1 Dakikada Firebase Bulut Kurulumu
1. [Firebase Console](https://console.firebase.google.com/) adresine gidin ve **Create a project** ile ücretsiz bir proje oluşturun.
2. Sol menüden **Build > Realtime Database** bölümüne tıklayın ve **Create Database** deyin.
3. Güvenlik kuralları adımında **Start in test mode** seçeneğini seçip oluşturun.
4. Size verilen veritabanı adresini (Örn: `https://proje-adi-default-rtdb.europe-west1.firebasedatabase.app`) kopyalayın:
   - İsterseniz uygulama içindeki **Bulut & Ayarlar** butonuna tıklayıp yapıştırın.
   - İsterseniz tüm cihazlarda otomatik bağlanması için `index.html` içindeki `DEFAULT_FIREBASE_DB_URL` değişkenine yapıştırın.

## 🌐 GitHub Pages ile Yayına Alma
1. Bu klasörü yeni bir GitHub reposuna yükleyin:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Ceyiz takip uygulamasi"
   git branch -M main
   git remote add origin https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git
   git push -u origin main
   ```
2. GitHub reponuzda **Settings > Pages** sekmesine gidin.
3. **Branch** kısmından `main` seçip **Save** butonuna basın. 1 dakika içinde siteniz yayında!

