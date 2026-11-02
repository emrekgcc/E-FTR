# E-FTR proje kapsamı

## Amaç

Hasta ile sağlık profesyoneli arasındaki mesajları, dosyaları ve takip bilgilerini aynı uygulamada tutmak. Hasta farklı uzmanlarla çalışırken her kliniğin verisinin ayrı kalmasını sağlamak. Sağlık profesyoneli; hekim, fizyoterapist, diyetisyen veya psikolog olabilir. İlk akışlar egzersiz ve ağrı takibi üzerinden geliştirilecektir.

## Kullanıcılar

- Hasta: Katıldığı klinikleri görür, kendi görüşmelerine mesaj ve dosya gönderir, atanan görevi tamamlar ve ağrı kaydı girer.
- Sağlık profesyoneli: Yetkili olduğu kliniğin hastalarını ve gruplarını yönetir, görev atar, mesaj gönderir ve gelişim kayıtlarını izler.
- Teknik yönetici: Teknik yapılandırma ve yetki işlemlerini yürütür. Bu rol kendiliğinden bütün sağlık kayıtlarına okuma izni vermez.

## Temel akışlar

1. Kullanıcı kimliğini doğrular ve kendi paneline ulaşır.
2. Hasta geçerli davet koduyla kliniğe katılır. Her klinik üyeliği ayrı kaydedilir.
3. Hasta ve yetkili uzman kendi görüşmelerinde mesaj veya dosya paylaşır.
4. Uzman hastaya veya tedavi grubuna açıklamalı görev atar.
5. Hasta görevi tamamlar ve ilgili görev için 1-10 arasında tam sayı ağrı puanı girer.
6. Uzman tarihli kayıtları izler. Okunmamış mesajları ve yeni etkinlikleri hasta listesinde görür.
7. Eski kayıtların aktarımı, şema incelendikten sonra yedek ve tekrar çalıştırma güvenliğiyle ele alınır.

## Geliştirme sırası

1. Uygulama iskeleti, tema, gezinme ve örnek verilerle hasta/uzman ekranları.
2. Oturum, klinik üyeliği ve sunucu erişim kuralları.
3. Mesajlaşma, görev atama, tamamlama ve ağrı kaydı.
4. Dosya paylaşımı, gruplar ve gelişim grafiği.
5. Eski veri aktarımı, bağlantı hataları, güvenlik ve cihaz testleri.

Bir özellik hem arayüz akışı hem veri erişimi doğrulandığında tamamlandı olarak işaretlenecektir. Örnek veriyle hazırlanan arayüz, canlı Firebase entegrasyonu olarak gösterilmeyecektir.

## Kapsam dışında

Uygulama tanı koymaz, tedavi planı üretmez ve sağlık profesyonelinin kararını değiştirmez. Yapay zekâ destekli tıbbi öneri bu başlangıç kapsamına dahil değildir.
