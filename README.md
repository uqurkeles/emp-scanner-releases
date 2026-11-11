# EMP Scanner — Windows dağıtımı

Bu depo yalnız Windows kurucuları, değişiklik notları, SHA-256 dosyaları ve güncelleme
manifestlerini yayımlar. Uygulama kaynak kodunu veya araştırma dosyalarını içermez.

[Son kararlı Windows sürümünü indir](https://github.com/uqurkeles/emp-scanner-releases/releases/latest).
Windows 10/11 x64 ve .NET Framework 4.8+ gerekir. Setup gerekli WebView2 çevrimdışı
kurucusunu içerir; Python, pip, terminal veya harici tarayıcı gerekmez.

1. Kararlı sürümdeki `EMPScanner-<sürüm>-Windows-x64-Setup.exe` dosyasını çalıştırın.
2. Masaüstündeki **EMP Scanner** kısayolunu açın.
3. Sonraki sürümler uygulama içinde bildirilir. Elle kontrol için
   **Yardım → Güncellemeleri kontrol et** seçeneğini kullanın.
4. İndirme ve doğrulama sonrası yüklemeyi siz başlatırsınız. Kaydedilmemiş proje
   için kaydetme, çalışan hesaplama için durdurma onayı istenir.

Eski, yayın adresi boş 2.3.0 teslimini kullananlar etkin bağlantılı son Setup'ı bir
kez elle kurmalıdır. Proje, kalibrasyon ve ayarlar kurulum klasöründen ayrı saklanır.

`updates/stable.json` uygulamanın kararlı HTTPS manifestidir; GitHub Releases API
yanıtı değildir. `updates/acceptance.json` yalnız yayın öncesi kabul içindir.
Ön sürümler normal kararlı kanala test tamamlanmadan yönlendirilmez.

SHA-256 indirilen dosyanın bütünlüğünü denetler; yayıncı kimliği veya kod imzası
doğrulaması değildir. Bu ilk paketler Authenticode ile imzalanmamıştır.
EMP Scanner Windows installers, release notes and update manifests. No application source.
