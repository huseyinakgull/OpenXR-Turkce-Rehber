## Geliştirme Ortamı Hazırlığı (Unity ile OpenXR)

OpenXR ile Unity’de sanal gerçeklik (VR) veya artırılmış gerçeklik (AR) projeleri geliştirmek istiyorsanız, aşağıdaki adımları takip ederek geliştirme ortamınızı hazırlayabilirsiniz. Her adımı basitçe anlattık ve görsellerle destekledik.

### Adım 1: Unity’yi Kurma
- **Nedir?**: Unity, oyun ve VR uygulamaları yapmak için kullanılan bir programdır.
- **Yapmanız Gereken**:
  1. [Unity Hub’ı indirin](https://unity.com/download) ve kurun.
  2. Unity Hub açıldığında, “Installs” (Kurulumlar) sekmesinden bir Unity sürümü ekleyin. OpenXR için 2020.3 veya üstü bir sürüm önerilir.
- **Fotoğraf**: Unity Hub’ın “Installs” sekmesini gösteren bir ekran görüntüsü. Yeni sürüm ekleme butonu (+ işareti) işaretlenmiş olsun.
  - *Eğer yoksa*: “Unity Hub açıkken ‘Installs’ sekmesinde ‘Add’ butonuna basıldığı bir görüntü” tarifine göre hazırlayabilirsin.

### Adım 2: Yeni Bir Proje Oluşturma
- Unity Hub’da “Projects” (Projeler) sekmesine gidin ve “New” (Yeni) butonuna basın.
- Proje türü olarak “VR” seçin, bir isim verin (örneğin “OpenXRTest”) ve “Create” (Oluştur) deyin.
<img width="1015" alt="projeAcma" src="https://github.com/user-attachments/assets/38c80186-83b9-43ed-8c37-cf50f4d75943" />


### Adım 3: OpenXR Desteğini Ekleme
- Unity projeniz açıldığında üst menüden “Window” > “Package Manager” yolunu izleyin.
- Package Manager açıldığında, sol üstteki “Packages” açılır menüsünden “Unity Registry”yi seçin.
- Arama çubuğuna “OpenXR” yazın, “XR” paketini bulun ve “Install” (Kur) butonuna basın.
<img width="1015" alt="Ekran Resmi 2025-02-27 15 43 18" src="https://github.com/user-attachments/assets/e1add5c8-a1e6-4184-a9e4-ea0774db2fef" />

### Adım 4: OpenXR Ayarlarını Yapma
- Üst menüden “Edit” > “Project Settings” (Proje Ayarları) seçeneğine gidin.
- Sol menüden “XR Plug-in Management”ı tıklayın.
- “OpenXR” seçeneğini etkinleştirin (kutucuğu işaretleyin).
<img width="938" alt="Ekran Resmi 2025-02-27 15 44 13" src="https://github.com/user-attachments/assets/5eafac63-58d6-47a5-a990-a526672791aa" />

### Adım 5: İlk Sahneyi Test Etme
- Unity’de “Hierarchy” (Hiyerarşi) penceresinde sağ tıklayın, “XR” > “XR Origin (VR)” ekleyin. Bu, VR cihazınızın hareketlerini takip edecek temel bir nesnedir.
- “File” > “Build Settings”e gidin, “Platform” olarak “PC, Mac & Linux Standalone”u seçin ve “Build and Run” ile test edin.
- Eğer bir VR cihazınız bağlıysa, projeniz cihazda çalışacaktır!
<img width="1424" alt="Ekran Resmi 2025-02-27 15 45 26" src="https://github.com/user-attachments/assets/9e556a3e-94ad-4fdf-878e-afc8d409cd5a" />

### İpuçları
- **VR Cihazı Yoksa**: Unity’nin “Game” penceresinde test edebilirsiniz, ama tam deneyim için bir VR gözlüğü önerilir.
- **Hata Alırsanız**: OpenXR runtime’ınızın (örneğin SteamVR) açık olduğundan emin olun.

Bu adımlarla Unity’de OpenXR geliştirme ortamınız hazır! Artık VR projelerinize başlayabilirsiniz.
