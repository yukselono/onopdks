# **PDKS Analiz Pro**

Personel devam kontrol sisteminden alınan CSV verilerini analiz eden, çalışma saatlerini hesaplayan ve yönetici inisiyatifi ile kayıtları düzenlemeye olanak sağlayan modern bir analiz aracıdır.

## **🚀 Özellikler**

* **Akıllı Takvim:** Personel bazlı aylık çalışma ve ihlal (geç gelme, erken çıkma) görünümü.  
* **TEKMER / Teknopark Desteği:** NS (kayıt olmayan) günler için otomatik hedef saat ataması.  
* **Hafta Sonu Filtresi:** Sadece iş günlerine odaklanma seçeneği (istendiğinde açılabilir).  
* **Veri Yedekleme:** Manuel girilen not ve izinlerin JSON olarak dışa aktarımı ve geri yüklenmesi.  
* **Karanlık Mod:** Göz yormayan modern gece teması desteği.

## **🛠️ Kurulum**

1. **Bağımlılıkları Yükleyin:**  
   npm install

2. **Gerekli Kütüphaneleri Ekleyin:**  
   npm install lucide-react recharts

3. **Tailwind CSS Kurulumu:**  
   Projenin görsel olarak düzgün çalışması için Tailwind CSS paketlerinin yüklü olması gerekir:  
   npm install \-D tailwindcss postcss autoprefixer  
   npx tailwindcss init \-p

## **💻 Çalıştırma**

Yerel geliştirme sunucusunda projeyi başlatmak için:

npm run dev

## **📦 Yayına Alma (GitHub Pages)**

Uygulamayı GitHub Pages üzerinde sorunsuz çalıştırmak için şu adımları izleyin:

1. **Vite Ayarı:** vite.config.js dosyasında base değerini repo adınıza göre güncelleyin:  
   base: '/repo-adi/'

2. **Derleme:** Projeyi derleyin:  
   npm run build

3. **Yükleme:** Oluşan dist klasörünün **içindeki** dosyaları GitHub deponuzun ana dizinine yükleyin.

**Geliştirici:** Yiğit Yüksel