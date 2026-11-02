# E-FTR

E-FTR, hastalar ile sağlık profesyonellerinin mesajlarını, paylaşılan dosyaları, egzersizleri ve takip kayıtlarını aynı uygulamada yönetmesi için geliştirilen bir projedir. Bir hasta birden fazla uzmanla çalışabilir; her kliniğin görüşmeleri ve kayıtları ayrı tutulur.

Projeyi geliştiren: **Emre Küçükgöçer**  
Sivas Cumhuriyet Üniversitesi Bilgisayar Mühendisliği  
Öğrenci numarası: 2023123044

## Mevcut durum

Bu depo proje belgeleri ve geliştirme kurallarıyla başlatılmıştır. Henüz çalıştırılabilir uygulama kodu bulunmamaktadır. Arayüz ve istemci tarafı geliştirme belgesi hazırlanmıştır. Uygulamanın geliştirilmesine sonraki çalışma turunda başlanacaktır.

## Planlanan özellikler

- Hasta ve sağlık profesyoneli için ayrı ekranlar.
- Davet koduyla kliniğe katılım ve çoklu klinik üyeliği.
- Gerçek zamanlı mesajlaşma, görsel, PDF ve video paylaşımı.
- Hastaya veya gruba egzersiz ve görev atama.
- Görev tamamlama ve 1-10 arası ağrı kaydı.
- Hastanın ağrı ve görev geçmişini izleme.
- Tedavi grupları, duyurular ve okunmamış mesaj takibi.
- Eski tek doktorlu veriler için kontrollü veri aktarımı.

E-FTR tanı koymaz veya tedavi önermez. Tedaviye ilişkin kararları sağlık profesyoneli verir.

## Teknoloji planı

Flutter ve Dart ile mobil ve web istemcisi; Provider ile durum yönetimi; Firebase Authentication ile kimlik doğrulama; Realtime Database ile canlı veri akışı; Cloud Storage ile dosya saklama planlanmıştır. Klinik üyeliği ve ayrıcalıklı işlemler güvenilir sunucuda doğrulanacaktır.

Davet kodu, kimlik doğrulamanın yerine geçmez. Arayüzde bir düğmeyi gizlemek erişim kontrolü olarak kabul edilmez. Klinik ve hasta ayrımı sunucu kurallarıyla da uygulanır. Bu kararların gerekçeleri [teknik kararlar](docs/TEKNIK_KARARLAR.md) belgesindedir.

## Belgeler

- [Kullanıcı Arayüzü ve İstemci Tarafı Geliştirme Dokümanı](docs/E_FTR_Kullanici_Arayuzu_ve_Istemci_Tarafi_Dokumani.docx)
- [Proje kapsamı ve geliştirme sırası](docs/PROJE_KAPSAMI.md)
- [Teknik kararlar](docs/TEKNIK_KARARLAR.md)
- [Çalışma kaydı](docs/CALISMA_KAYDI.md)

## Geliştirme ve sürüm takibi

Her geliştirme turunda ilgili kontroller ve mevcut testler çalıştırılır. Anlamlı değişiklikler açıklayıcı bir commit ile kaydedilir ve GitHub bağlantısı kurulduktan sonra `origin` deposuna gönderilir. Gönderim sonucu ayrıca doğrulanır. Test veya gönderim başarısızsa çalışma kaydında açıkça belirtilir.

Gerçek hasta verileri, parolalar, servis hesabı anahtarları ve yerel ortam dosyaları bu depoya eklenmez. Kurulum ve çalıştırma komutları, uygulama iskeleti oluşturulduğunda bu dosyaya eklenecektir.
