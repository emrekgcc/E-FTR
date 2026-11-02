# Teknik kararlar

## İstemci

Önceki E-FTR belgelerinde seçilen Flutter ve Dart korunacaktır. Mobil uygulama ile web istemcisi aynı iş kurallarını paylaşacaktır. Provider ile oturum, seçili klinik ve özellik durumları yönetilecektir. Ekranlar Firebase çağrılarını doğrudan içermek yerine veri sınıfları kullanacaktır.

## Kimlik ve üyelik

Firebase Authentication planlanmıştır. Eski açıklamalardaki cihazda saklanan kullanıcı adı veya davet kodu tek başına kimlik doğrulama olarak kullanılmayacaktır. Davetle katılım, klinik üyeliği ve yetkili rol atama güvenilir sunucu işlemlerinde doğrulanacaktır. Hasta istemciden kendi rolünü uzman olarak değiştiremeyecektir.

## Veri ve dosya

Canlı kayıtlar için Realtime Database, medya için Cloud Storage kullanılacaktır. Klinik ve hasta kimlikleri veri erişimi sırasında kontrol edilecektir. Dosyalar Base64 olarak ana veritabanına yazılmayacaktır. Yetkili dosya erişimi için kalıcı ve herkese açık sağlık dosyası bağlantıları kullanılmayacaktır. Kesin sunucu sözleşmesi entegrasyon aşamasında belgelenecektir.

## Mevcut belgeler

`docs` içindeki Word belgesi bu deponun güncel arayüz planıdır. Önceki çalışma klasörlerindeki proje başlangıç ve gereksinim belgelerinde artık kullanılmayan kişi atıfları ve teknik kararlar bulunduğundan bunlar güncel belge olarak bu depoya kopyalanmamıştır. Bu belgelerin yeni sürümleri hazırlanırken geliştirici olarak yalnızca Emre Küçükgöçer yazılacaktır.

## Doğrulanacak konular

Firebase proje yapılandırması, veri saklama süresi, izin akışları, dosya sınırları ve hedef cihaz sürümleri uygulama geliştirilirken kesinleştirilecektir. Gerçek kullanıcı verisiyle kullanım, geliştirme örneklerinden ayrı ele alınacaktır.
