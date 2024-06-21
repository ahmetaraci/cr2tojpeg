# CR2 to JPEG Dönüştürücü

## Genel Bakış

CR2 to JPEG Dönüştürücü, Canon CR2 RAW dosyalarını yüksek kaliteli JPEG dosyalarına dönüştüren bağımsız bir çalıştırılabilir uygulamadır. Bu araç, kullanıcı dostu ve verimli olacak şekilde tasarlanmış olup, kullanıcıların birden fazla CR2 dosyasını toplu olarak, belirli bir çıktı kalitesi ile işleyebilmesine olanak tanır.

## Özellikler

- CR2 dosyalarının toplu olarak JPEG'e dönüştürülmesi.
- Ayarlanabilir JPEG çıkış kalitesi.
- Basit çift tıklama ile çalıştırma.

## Kullanım

1. **Çalıştırılabilir Dosyayı İndirin:**
   `CR2_to_JPEG.exe` dosyasını [buradan](https://github.com/ahmetaraci/cr2tojpeg/releases) indirin.

2. **Uygulamayı Çalıştırın:**
   `CR2_to_JPEG.exe` dosyasına çift tıklayarak uygulamayı başlatın.

3. **Girdi ve Çıktı Dizinlerini Seçin:**
   CR2 dosyalarını içeren dizini ve dönüştürülmüş JPEG dosyalarının kaydedileceği dizini seçmek için ekrandaki talimatları izleyin.

4. **JPEG Kalitesini Ayarlayın:**
   Çıktı JPEG dosyalarının istenen kalitesini belirleyin (1-100), burada 100 en yüksek kaliteyi temsil eder.

## Örnek

1. `CR2_to_JPEG.exe` dosyasına çift tıklayın.
2. CR2 dosyalarınızı içeren klasörü seçin.
3. JPEG dosyalarını kaydetmek istediğiniz klasörü seçin.
4. JPEG dosyalarının kalite seviyesini girin (örneğin, 85).
5. "Dönüştür" düğmesine tıklayın ve işlemin tamamlanmasını bekleyin.

## Geliştirme

Bu uygulama, Python ve Pillow kütüphanesi kullanılarak geliştirilmiş ve ardından PyInstaller kullanılarak çalıştırılabilir bir dosyaya paketlenmiştir. Geliştirme süreci şu adımları içermektedir:

1. Pillow ile dönüştürme scripti yazıldı.
2. Tkinter ile arayüzü yazıldı.
3. Script, PyInstaller kullanılarak bağımsız bir çalıştırılabilir dosya haline getirildi.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.

## İletişim

Herhangi bir soru veya öneri için [muhammetahmet.araci@gmail.com] adresinden iletişime geçebilirsiniz.

[Beni Ziyaret Edin ve İletişime Geçin](https://ahmetaraci.github.io)
