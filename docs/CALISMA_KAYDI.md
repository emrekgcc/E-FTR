# Çalışma kaydı

## Depo başlangıcı

- E-FTR için ayrı Git deposu yapısı hazırlandı.
- Güncel kullanıcı arayüzü ve istemci tarafı Word belgesi `docs` klasörüne alındı.
- Proje kapsamı, teknik kararlar ve her geliştirme turu sonunda commit/push yapılması kuralı yazıldı.
- Gizli anahtarlar, yerel ayarlar ve gerçek hasta verileri için `.gitignore` eklendi.
- Bu aşamada uygulama kodu veya çalışır Firebase bağlantısı bulunmuyor.

Doğrulama: Word belgesinin kaynakla birebir aynı olduğu SHA-256 özetiyle doğrulandı. Ortam dosyaları, gizli anahtar klasörü, hasta verisi ve derleme çıktılarının Git tarafından dışarıda bırakıldığı kontrol edildi. İlk yerel commit `56d17b3` ile oluşturuldu.

## GitHub bağlantısı

- `emrekgcc/E-FTR` özel GitHub deposu oluşturuldu.
- Yerel `origin`, `https://github.com/emrekgcc/E-FTR.git` adresine bağlandı.
- Ana dal `main` olarak kullanılıyor.
- Her geliştirme turunun sonunda kontrol, commit, push ve uzak commit doğrulaması uygulanacak.
- Bu adımda uygulama geliştirilmedi; proje belgeleri ve depo ayarları hazırlandı.

Sonraki geliştirme: Flutter iskeleti ve örnek verilerle hasta/uzman ekranları.

## Arayüz belgesinin anlatım dili

- Birinci tekil şahıs ifadeleri resmî ve edilgen anlatıma dönüştürüldü.
- Proje kapsamı, teknik kararlar, tablolar, başlıklar ve biçim ayarları korundu.
- Belgenin 11 sayfası görsel olarak kontrol edildi. İçindekilerdeki 24 bağlantı korundu.
- Bu turda uygulama kodunda geliştirme yapılmadı.
