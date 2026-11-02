# Çalışma kaydı

## Depo başlangıcı

- E-FTR için ayrı Git deposu yapısı hazırlandı.
- Güncel kullanıcı arayüzü ve istemci tarafı Word belgesi `docs` klasörüne alındı.
- Proje kapsamı, teknik kararlar ve her geliştirme turu sonunda commit/push yapılması kuralı yazıldı.
- Gizli anahtarlar, yerel ayarlar ve gerçek hasta verileri için `.gitignore` eklendi.
- Bu aşamada uygulama kodu veya çalışır Firebase bağlantısı bulunmuyor.

Doğrulama: Word belgesinin kaynakla birebir aynı olduğu SHA-256 özetiyle doğrulandı. Ortam dosyaları, gizli anahtar klasörü, hasta verisi ve derleme çıktılarının Git tarafından dışarıda bırakıldığı kontrol edildi. İlk yerel commit `56d17b3` ile oluşturuldu. GitHub hesabı bu sohbete henüz bağlanmadığı için uzak depo ve gönderim yapılmadı.

Sonraki geliştirme: Flutter iskeleti ve örnek verilerle hasta/uzman ekranları. GitHub bağlantısı ayrı olarak tamamlanacaktır.
