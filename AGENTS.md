# E-FTR çalışma kuralları

## Proje ve kapsam

- Projenin geliştiricisi Emre Küçükgöçer'dir. Başka kişilere tasarım, kodlama veya geliştirme sorumluluğu atfetme.
- Hasta, sağlık profesyoneli ve klinik yapısını `docs/PROJE_KAPSAMI.md` üzerinden takip et.
- Kodları anlaşılır isimlerle, küçük sorumluluklara ayırarak yaz. Gereksiz soyutlamalar ve uzun açıklama yorumları ekleme.
- Mevcut özellikleri veya belge içeriğini kullanıcı istemeden çıkarma.
- Çalışmayan özellikleri veya çalıştırılmamış testleri tamamlanmış gibi gösterme.

## Her geliştirme turunun sonunda

Kullanıcı, bu projedeki geliştirmelerin her tur sonunda commit edilmesini ve GitHub'da güncellenmesini açıkça istemiştir.

1. `git status` ve değişiklik farkını incele. Kullanıcının ilgisiz değişikliklerini kendi commit'ine katma.
2. Değişiklik için uygun analiz ve testleri çalıştır; sonuçlarını kaydet.
3. Gerçek sağlık verileri, parolalar, servis hesabı anahtarları veya gizli ortam dosyalarının eklenmediğini denetle.
4. Tamamlanan işi ve kalan eksikleri `docs/CALISMA_KAYDI.md` içinde güncelle.
5. Yalnızca ilgili dosyaları stage et ve yapılan işi açıklayan bir commit oluştur. Anlamlı değişiklik yoksa boş commit oluşturma.
6. `origin` ayarlıysa ve erişim varsa mevcut çalışma dalını normal `git push` ile gönder. Force push yapma.
7. Yerel commit ve uzak dalın aynı commit'e işaret ettiğini doğrula. GitHub'a gönderilmemiş bir commit'i gönderilmiş gibi bildirme.
8. Erişim veya ağ sorunu varsa yerel commit'i koru; sorunu ve gereken kullanıcı işlemini belirt. Kimlik bilgilerini dosyalara veya günlük çıktılarına yazma.

## Güvenlik

- Davet kodu yalnızca üyelik içindir. Kullanıcı kimliği güvenilir kimlik doğrulamayla belirlenir.
- Klinik ve hasta yetkilerini sunucu katmanında da uygula ve farklı klinikten erişimi test et.
- Gerçek hasta kaydı yerine açıkça örnek olduğu belirtilen test verileri kullan.
- Sağlık içeriklerini hata günlüklerine yazma. Çıkışta veya klinik değişiminde ilgili durum ve dinleyicileri temizle.
- Yeni hesap, ücretli hizmet veya gerçek veri yayını gerektiren işleri ayrıca belirt.

## Sınırlar

Bu dosya kendi başına zamanlanmış iş oluşturmaz. Yalnızca kullanıcı tarafından başlatılan veya ayrıca yetkilendirilmiş geliştirme turlarının kapanışını düzenler.
