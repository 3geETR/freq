## İçindekiler

-   [Giriş](https://github.com/Purgatoria/freq)
-   [Tanım](https://github.com/Purgatoria/freq)
-   [Amaç](https://github.com/Purgatoria/freq)
-   [Kapsam](https://github.com/Purgatoria/freq)
-   [Dayanak](https://github.com/Purgatoria/freq)
-   [Kullanım Şartları](https://github.com/Purgatoria/freq)

## Giriş

İlk kez 2018 yılında TA2SLC tarafından radyoamatörleri.com'un "Türkiye Amatör Telsiz Röle, APRS ve Echolink Frekans Listesi" baz alınarak hazırlanıp sunulan ve yıllardır Türkiye'de pek çok Amatör Telsizci tarafından kullanılmakta olan "Marmara Master" isimli telsiz programını yeni yönetmeliğe göre güncellemek ve herkes için daha ulaşılabilir bir şekilde sunmak üzere çıktığımız bu yolda artık bu repo çok daha kapsamlı bir hale gelmiş ve bu şekliyle iş birliğine açılmıştır.

## Tanım

İşbu repo, Amatör Telsizcilerin umumiyetle ihtiyaç duydukları bant planlarını, sık kullanılan frekans tahsislerini, güncel röle bilgilerini ve yaygın kullanılan telsizler için hazır konfigürasyon dosyalarını barındırmak üzere işletilmektedir.


##  Amaç

İşbu repo'nun temel amacı, Amatör Telsizcilerin; topluluk desteğiyle güncel tutulan merkezi bir konumdan ihtiyaç duydukları bütün bant planlarına, tahsisli frekanslara ve hazır ayar dosyalarına erişebilmeleridir.

Bahsedilen bilgilerin, güncel yönetmelikler takip edilerek frekans, bant genişliği, mod vb. düzenlemelerinin güncel ve mevzuata uygun bir şekilde yapılması birinci önceliktir.
Öte yandan yine yönetmelikler baz alınarak yapılan isimlendirmeler de Amatör Telsizciler arasında bir standart oluşturmak adına ziyadesiyle önemlidir.
Aynı bilgiler, ".img", ".dat", ".csv" gibi çeşitli formatlarda sunularak farklı programlarda kolayca kullanılabilmesi amaçlanmaktadır.

Ayrıca röle bilgilerinin güncellenmesinde baz alınan bilgilerin ilgili röleleri kuran Amatör Telsizcilik Dernekleri ve röle sorumluları ile mülakat yapılarak kayda geçirilmesi ve bu süreçte önce RF yayılım haritalarının çıkartılması, daha sonrasında yapılacak planlı çevrimler üzerinden ortaya çıkartılacak menzil testleri ile oluşturulacak kapsama haritalarının oluşturulması; bu şekilde rölelerin kapsama alanlarının daha sağlıklı belgelenmesi amaçlanmaktadır.

Bahse konu unsurlar üzerinden aşağıdakiler hedeflenmektedir:

- Bant kısıtlamaları sayesinde adli arama, GBT kontrolü, asayiş denetimi vb. çeşitli uygulamalara takılan Amatör Telsizcilerin kamu görevlileri ile sorun yaşamaması,
- IARU, BTK vb. kurumlar tarafından belirlenen yasal bant planlarına uygunluğu önceden kontrol edilmiş listeler sunmak suretiyle Amatör Telsizcilerin bilmeden yasaları çiğnememesi,
- Anlaşılır isimlendirme ve detaylı açıklamalar ile yanlış nokta frekanslarda yanlış modların kullanımının önüne geçilerek Amatör Telsizcilerin birbirlerinin iletişimine engel olmamaları,
- En güncel ve doğru röle bilgilerini bulundurmak ve kolayca telsizlere yüklenebilir formatta hazır bulundurmak,
- Standart isimlendirme düzeni üzerinden acil durum ve rutin haberleşme süreçlerinin optimizasyonu,
- Yanlış frekans başta olmak üzere; hatalı shift, offset, tone, bant genişliği vb. parametreler yüzünden iletişimin sekteye uğramaması için insan faktörünü zayıflatmak,
- Yeni Amatör Telsizcilerin cihazlarına yasaklı veya yanlış frekansları kaydetmemeleri ve bilgiye kolay ulaşmaları,
- Hazır ayar dosyaları sayesinde Amatör Telsizcilerin kolay ve hızlı entegrasyonu,
- 433.575MHz'e denk gelen UHF-286 (eski adıyla SMP-U23) kanalını her zaman için 127. hanede bitirerek simplex frekansların kanal numaralarının her zaman için aynı olması,
- Hazır kanal listelerini Chirp veya diğer programlar ile açılabilir ve düzenlenebilir ".img", ".dat", ".csv" gibi dosyalar şeklinde sunarak bu süreçlerde bütün Amatör Telsizcilere zaman kazandırmak,
- Katkı sunmaya açık bu repo üzerinden Amatör Telsizcilere işbirliği yapma pratiği kazandırmak ve işbu yeteneği geliştirmelerine olanak sağlamak,
- Farklı projelerde bahse konu bilgileri kullanmak isteyen Amatör Telsizciler için güncel ve entegrasyona açık bir veri bankası sunmak,


## Kapsam

İşbu repo; BTK, IARU, FCC vb. çeşitli kurumlar tarafından Dünya genelinde ve Türkiye özelinde tahsis edilmiş frekansları ve çeşitli bant planlarını fikir vermesi açısından bulundurmaktadır.
Bunun yanında Amatör Telsizciler tarafından bir takım koşullara bağlı kullanılabilen simplex ve nokta frekansları, Amatör Telsiz rölelerine ait ayar bilgilerini ve bunun dışında kalan diğer tahsis edilmiş frekansları; Amatör Telsizciler tarafından yaygın kullanılmakta olan Baofeng, TYT, Quansheng vb. çeşitli telsiz modelleri için oluşturulmuş güncel hazır ayar dosyalarını içermektedir.

## Dayanak

İşbu kütüphane içerisinde yer alan tüm frekans tahsisleri ve bant planları:

- [TA Röle Listesi](https://www.radyoamatorleri.com/depo/linkver/html/TA_ROLE.html)
- [IARU-R1 VHF Handbook](https://www.iaru-r1.org/wp-content/uploads/2024/11/VHF_Handbook_V10_02.pdf)

esas alınarak hazırlanmaktadır.


## Kullanım Şartları

-   **Sorumluluk Reddi:** İşbu repo'da paylaşılan frekanslar ve ayar dosyaları bilgi amaçlıdır. Cihazların programlanması ve kullanımı sırasında doğabilecek donanımsal hatalardan veya yasal ihlallerden son kullanıcı sorumludur.
    
-   **Lisans Zorunluluğu:** Paylaşılan frekanslarda iletim/gönderme (TX) yapmak için ilgili kanunlar gereği "Amatör Telsizcilik Belgesi"ne sahip olunması zorunludur. Belgesiz kişilerce kullanımı suçtur.
    
-   **Güncellik:** Röle ve frekans bilgileri, yönetmeliklere ve ilgili rölelerin üzerinde yapılan tasarruflara göre değişiklik gösterebilir. Kullanıcıların, dosyaları cihazlarına yüklemeden önce güncelliğini kontrol etmeleri gerekmektedir.
