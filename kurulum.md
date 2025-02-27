## OpenXR SDK’nın İndirilmesi ve Kurulumu

OpenXR ile uygulama geliştirmeye başlamak için önce OpenXR SDK’yı (yazılım geliştirme kitini) bilgisayarınıza kurmanız gerekiyor. İşte bunu nasıl yapacağınız:

### Adım 1: OpenXR SDK’yı İndirme
- **Nereden İndirilir?**: OpenXR SDK, resmi Khronos Group deposundan alınır.
- **Yapmanız Gereken**: [Khronos OpenXR GitHub sayfasına](https://github.com/KhronosGroup/OpenXR-SDK) gidin.
- **Dosyayı Bulma**: Sayfada “Releases” (Sürümler) bölümüne tıklayın. En güncel sürümü (örneğin `openxr_loader_windows-x.x.x.zip`) seçip indirin.
  - *Not*: Windows kullanıyorsanız `.zip`, Linux için `.tar.gz` dosyasını seçin.

### Adım 2: Dosyaları Çıkarma
- İndirdiğiniz `.zip` dosyasını bilgisayarınızda bir klasöre çıkarın. Mesela, `C:\OpenXR` gibi bir klasör oluşturabilirsiniz.
- İçinde `include` (başlık dosyaları) ve `lib` (kütüphane dosyaları) gibi klasörler göreceksiniz. Bunlar kod yazarken kullanılacak.

### Adım 3: Geliştirme Ortamını Hazırlama
- **Gerekli Araçlar**:
  - Bir kod editörü (Visual Studio, VS Code gibi).
  - CMake (projeyi derlemek için, [cmake.org](https://cmake.org/download/) adresinden indirin).
  - C++ derleyicisi (Visual Studio ile geliyorsa ekstra kurulum gerekmez).
- SDK’yı kullanmak için bu araçların kurulu olduğundan emin olun.

### Adım 4: SDK’yı Test Etme
- İndirdiğiniz dosyalar arasında bir `hello_xr` örneği varsa, bunu deneyebilirsiniz:
  1. CMake ile bir proje oluşturun: `cmake -S . -B build`.
  2. Projeyi derleyin: `cmake --build build`.
  3. Çalıştırın ve OpenXR’ın aktif olduğunu kontrol edin.
- Eğer bir VR cihazınız varsa, bağlayıp örneği test edebilirsiniz.

### Adım 5: Oyun Motorlarıyla Kullanım (Tarafımca Önerilen.)
- **Unity**: Unity Hub’dan yeni bir proje açın, ardından OpenXR desteğini “Package Manager”dan ekleyin.
- **Unreal Engine**: Motoru kurduktan sonra proje ayarlarından OpenXR’ı etkinleştirin.
- Bu motorlar SDK’yı otomatik kullanır, sizin ekstra bir şey yapmanıza gerek kalmaz.

### İpuçları
- **Sorun mu çıktı?**: İnternetten “OpenXR runtime” indirip kurmanız gerekebilir (örneğin SteamVR).
- ** Belgeler**: Daha fazla bilgi için [resmi OpenXR sayfasını](https://www.khronos.org/openxr/) ziyaret edin.

Artık OpenXR SDK’yı kurdunuz ve projelerinize başlayabilirsiniz!
