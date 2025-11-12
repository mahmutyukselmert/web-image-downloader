# Web Image Downloader

[English](#english) | [Türkçe](#türkçe)

---

## English

### Description
Web Image Downloader is a powerful tool designed to extract and download images from web pages. Simply provide a URL, and the tool will automatically find and download all image paths from the webpage content.

### Features
- 🌐 Extract images from any web page
- 📥 Bulk download multiple images at once
- 🔍 Automatically detect image URLs in web content
- 💾 Save images to a local directory
- ⚡ Fast and efficient downloading
- 🎯 Support for various image formats (JPG, PNG, GIF, WebP, SVG, etc.)

### Installation
```bash
# Clone the repository
git clone https://github.com/mahmutyukselmert/web-image-downloader.git

# Navigate to the project directory
cd web-image-downloader

# Install dependencies (if any)
npm install
```

### Usage
```bash
# Basic usage example
node downloader.js <website-url>

# Example
node downloader.js https://example.com
```

### How It Works
1. Enter the URL of the webpage you want to download images from
2. The tool scans the webpage content and extracts all image URLs
3. Images are automatically downloaded to the output directory
4. Downloaded images are saved with their original names or auto-generated names

### Configuration
You can customize the download behavior by modifying the configuration:
- Output directory
- Image format filters
- Maximum concurrent downloads
- File naming patterns

### Example Output
```
Downloading images from: https://example.com
Found 15 images
[1/15] Downloaded: image1.jpg
[2/15] Downloaded: image2.png
...
[15/15] Downloaded: image15.jpg
✓ Successfully downloaded 15 images to ./downloads/
```

### Requirements
- Node.js (v12 or higher)
- npm or yarn package manager

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### License
This project is open source and available under the MIT License.

### Author
Mahmut Yüksel Mert

### Support
If you encounter any issues or have questions, please open an issue on GitHub.

---

## Türkçe

### Açıklama
Web Image Downloader, web sayfalarından görselleri çıkarmak ve indirmek için tasarlanmış güçlü bir araçtır. Sadece bir URL sağlayın ve araç, web sayfası içeriğindeki tüm görsel yollarını otomatik olarak bulup indirecektir.

### Özellikler
- 🌐 Herhangi bir web sayfasından görsel çıkarma
- 📥 Birden fazla görseli toplu olarak indirme
- 🔍 Web içeriğindeki görsel URL'lerini otomatik algılama
- 💾 Görselleri yerel dizine kaydetme
- ⚡ Hızlı ve verimli indirme
- 🎯 Çeşitli görsel formatları destekleme (JPG, PNG, GIF, WebP, SVG, vb.)

### Kurulum
```bash
# Depoyu klonlayın
git clone https://github.com/mahmutyukselmert/web-image-downloader.git

# Proje dizinine gidin
cd web-image-downloader

# Bağımlılıkları yükleyin (varsa)
npm install
```

### Kullanım
```bash
# Temel kullanım örneği
node downloader.js <website-url>

# Örnek
node downloader.js https://example.com
```

### Nasıl Çalışır
1. Görsel indirmek istediğiniz web sayfasının URL'sini girin
2. Araç, web sayfası içeriğini tarar ve tüm görsel URL'lerini çıkarır
3. Görseller otomatik olarak çıktı dizinine indirilir
4. İndirilen görseller, orijinal isimleriyle veya otomatik oluşturulan isimlerle kaydedilir

### Yapılandırma
İndirme davranışını aşağıdaki ayarları değiştirerek özelleştirebilirsiniz:
- Çıktı dizini
- Görsel format filtreleri
- Maksimum eşzamanlı indirme sayısı
- Dosya isimlendirme kalıpları

### Örnek Çıktı
```
Görseller indiriliyor: https://example.com
15 görsel bulundu
[1/15] İndirildi: image1.jpg
[2/15] İndirildi: image2.png
...
[15/15] İndirildi: image15.jpg
✓ 15 görsel başarıyla ./downloads/ dizinine indirildi
```

### Gereksinimler
- Node.js (v12 veya üzeri)
- npm veya yarn paket yöneticisi

### Katkıda Bulunma
Katkılarınızı bekliyoruz! Lütfen Pull Request göndermekten çekinmeyin.

1. Projeyi fork edin
2. Feature branch'i oluşturun (`git checkout -b feature/HarikaBirOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Harika bir özellik ekle'`)
4. Branch'inizi push edin (`git push origin feature/HarikaBirOzellik`)
5. Pull Request açın

### Lisans
Bu proje açık kaynaklıdır ve MIT Lisansı altında sunulmaktadır.

### Yazar
Mahmut Yüksel Mert

### Destek
Herhangi bir sorunla karşılaşırsanız veya sorularınız varsa, lütfen GitHub'da bir issue açın.