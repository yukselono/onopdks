<div align="center">
  <h1>🏢 PDKS Analiz Pro</h1>
  <p><strong>Modern Personel Devam Kontrol ve Analiz Sistemi</strong></p>

  <p>
    <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge" alt="Maintained">
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  </p>
</div>

---

## 📝 Hakkında
**PDKS Analiz Pro**, personel devam kontrol sistemlerinden alınan ham CSV verilerini anlamlı içgörülere dönüştüren modern bir analiz aracıdır. Özellikle Teknopark ve TEKMER yapılarındaki personel çalışma takibi ihtiyaçları gözetilerek geliştirilmiştir.

Yönetici inisiyatifi ile kayıt düzenleme, otomatik hedef saat ataması ve veri yedekleme gibi kritik özellikleri tek bir arayüzde toplar.

---

## 🚀 Öne Çıkan Özellikler

| Özellik | Açıklama |
| :--- | :--- |
| **📅 Akıllı Takvim** | Personel bazlı aylık çalışma ve ihlal (geç gelme, erken çıkma) görünümü. |
| **🏛️ Teknopark Desteği** | NS (Kayıt olmayan) günler için otomatik hedef saat ataması ve yasal uyumluluk takibi. |
| **🔍 Hafta Sonu Filtresi** | Sadece iş günlerine odaklanma seçeneği ile temiz veri analizi. |
| **💾 Veri Yedekleme** | Manuel not ve izinlerin JSON olarak dışa aktarımı ve geri yüklenmesi. |
| **🌙 Karanlık Mod** | Gece çalışmaları için göz yormayan, modern Dashboard tasarımı. |

---

## 🛠️ Kurulum

Projeyi yerel ortamınızda ayağa kaldırmak için aşağıdaki adımları izleyin:

### 1. Bağımlılıkları Yükleyin
```bash
npm install
```

### 2. Gerekli Kütüphaneleri Ekleyin
Projenin grafik ve ikon yapısı için gerekli paketler:
```bash
npm install lucide-react recharts
```

### 3. Tailwind CSS Kurulumu
Görsel stilin düzgün çalışması için yapılandırmayı tamamlayın:
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

---

## 💻 Çalıştırma

Yerel geliştirme sunucusunda projeyi başlatmak için:

```bash
npm run dev
```

Ardından tarayıcınızda `http://localhost:5173` adresine giderek uygulamayı görüntüleyebilirsiniz.

---

## 📦 Yayına Alma (GitHub Pages)

Uygulamayı **GitHub Pages** üzerinde sorunsuz çalıştırmak için şu adımları izleyin:

1.  **Vite Ayarı:** `vite.config.js` dosyasında `base` değerini repo adınıza göre güncelleyin:
    ```javascript
    export default defineConfig({
      base: '/repo-adi/', // Burayı kendi repo adınızla değiştirin
      // ...diğer ayarlar
    })
    ```
2.  **Derleme:** Projeyi üretim (production) modunda derleyin:
    ```bash
    npm run build
    ```
3.  **Yükleme:** Oluşan `dist` klasörünün içindeki dosyaları GitHub deponuzun ana dizinine veya `gh-pages` branch'ine yükleyin.

---

## 👨‍💻 Geliştirici

**Yiğit Yüksel**
*Veri analitiği ve kurumsal araçlar üzerine uzmanlaşmış geliştirici.*

---

## ⭐ Destek
Bu proje işinize yaradıysa bir yıldız (⭐) bırakmayı unutmayın!

> **Not:** Bu araç ham veriyi işleme odaklıdır; CSV formatının uygulama içindeki şablonla uyumlu olduğundan emin olun.
