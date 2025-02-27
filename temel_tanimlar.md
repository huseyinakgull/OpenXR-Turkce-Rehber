## Temel Tanımlar

Bu bölümde OpenXR’ın en önemli kavramlarını basit bir dille açıklayacağız. Teknik bilgiye ihtiyacınız yok, sadece merakınız yeterli!

- **OpenXR**: Sanal gerçeklik (VR) ve artırılmış gerçeklik (AR) uygulamalarını farklı cihazlarda kolayca çalıştırmak için geliştirilmiş bir araçtır. Mesela, aynı oyunu hem Oculus’ta hem Vive’da oynatmak için kullanılır.
- **Runtime**: OpenXR uygulamanızı çalıştıran bir yardımcı yazılımdır. Arabanızın motoru gibi düşünün; o olmadan araç hareket etmez. Örnek: SteamVR bir runtime’dır.
- **Session**: Uygulamanızın VR veya AR cihazıyla konuşmaya başladığı zamandır. Bir telefon görüşmesi gibi, bağlantı kurduğunuzda her şey bu oturumda olur.
- **Actions**: Kullanıcının yaptığı hareketleri (örneğin kontrolörü sallamak veya bir tuşa basmak) tanımlayan şeylerdir. Mesela, oyunda kılıcı sallamak bir “action”dır.
- **Space**: Sanal dünyada nerede olduğunuzu ve nereye baktığınızı belirleyen alandır. Odanızın içini bir harita gibi düşünün; “space” size yerinizi söyler.
- **Swapchain**: VR gözlüğünüzün ekranına görüntüleri gösteren bir sistemdir. Televizyona resim gönderen bir kablo gibi çalışır.
- **Extensions**: OpenXR’a eklenen özel yeteneklerdir. Mesela, gözlerinizi takip etme özelliği bir “extension” olabilir.
- **Instance**: OpenXR’ı kullanmaya başlamak için oluşturduğunuz ana merkezdir. Bir projeyi başlatmak için açtığınız dosya gibi düşünün.
- **Frame**: Sanal dünyadaki her bir görüntünün çizildiği andır. Göz kırpması kadar hızlı bir resim gibi, sürekli yenilenir.
- **Input Profiles**: Kontrolörlerinizin nasıl çalıştığını anlatan bir plandır. Mesela, “bu düğme şunu yapar” diye tarif eder.
- **View**: VR gözlüğünüzde gördüğünüz şeylerdir. Her göz için ayrı bir görüntü gibi, size sanal dünyayı gösterir.
- **Reference Space**: Sanal dünyada sabit bir nokta seçmektir. Odanızın ortasını başlangıç noktası yapmak gibi bir şey.
- **Layers**: Görüntülerin üst üste bindiği katmanlardır. Mesela, oyunun üstüne bir menü koymak için kullanılır.
- **Events**: OpenXR’ın size bir şey olduğunu haber verdiği anlardır. “Kontrolör bağlandı” ya da “gözlük çıkarıldı” gibi uyarılar.

Bu tanımlarla OpenXR’ın temel taşlarını öğrendiniz! Daha fazla merak ederseniz, diğer bölümlere göz atabilirsiniz.
