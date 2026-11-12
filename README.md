# BERBER-RANDEVU-SISTEMI

MOBİL PROGRAMLAMA DERSİ PROJE RAPORU

Proje Adı: Berber Randevu Sistemi
Ders: Mobil Programlama
Bölüm: Bilgisayar Mühendisliği
Proje Ekibi: Diyar Arıkan – Hasan Kılıç

1. PROJENİN AMACI

Bu projenin amacı, berber işletmelerinde randevu alma ve yönetme işlemlerini dijital ortama taşıyan bir mobil uygulama geliştirmektir.

Müşteriler kendi telefonlarından berberin sunduğu hizmetleri inceleyebilecek, uygun tarih ve saatleri görüntüleyebilecek ve internet üzerinden randevu oluşturabilecektir. Berber işletmesi ise kendisine gelen randevuları yönetici ekranından takip edebilecektir.

Projede ayrıca yapay zekâ desteğiyle saç ve sakal modeli önerileri sunulması hedeflenmektedir.

2. PROJENİN KAPSAMI

Uygulamada müşteri ve yönetici olmak üzere iki farklı kullanıcı türü bulunacaktır.

Temel özellikler:

- Kullanıcı kayıt ve giriş sistemi.
- Berber hizmetlerini ve fiyatlarını görüntüleme.
- Tarih ve saat seçerek randevu oluşturma.
- Randevuları görüntüleme ve iptal etme.
- Yönetici tarafından randevuları onaylama ve yönetme.
- Aynı saate birden fazla randevu alınmasını engelleme.
- Yapay zekâ ile saç ve sakal modeli önerileri alma.

3. KULLANILACAK TEKNOLOJİLER

- Flutter: Mobil uygulamanın geliştirilmesi ve kullanıcı arayüzlerinin oluşturulması.
- Dart: Uygulamanın programlama dili.
- Firebase Authentication: Kullanıcı kayıt ve giriş işlemleri.
- Firebase Firestore: Kullanıcı, hizmet ve randevu bilgilerinin merkezi olarak saklanması.
- SQLite: Mobil cihazlarda yerel veri saklama ve önbellekleme işlemleri.
- Navigator: Uygulama ekranları arasındaki geçişlerin sağlanması.
- Yapay Zekâ API: Saç ve sakal modeli önerilerinin oluşturulması.

4. ARAYÜZ TASARIMI VE EKRANLAR ARASI GEÇİŞ

Uygulamanın arayüzleri Flutter kullanılarak hazırlanacaktır. Widget yapısından yararlanılarak sade ve kullanıcı dostu ekranlar oluşturulacaktır.

Hazırlanması planlanan ekranlar:

4.1. Giriş ve Kayıt Ekranı: Kullanıcıların sisteme giriş ve kayıt işlemlerini gerçekleştirmesi.

4.2. Ana Sayfa: Hizmetlerin, randevu alma seçeneğinin ve yapay zekâ önerilerinin gösterilmesi.

4.3. Hizmet Seçim Ekranı: Saç kesimi, sakal tıraşı ve diğer hizmetlerin listelenmesi.

4.4. Randevu Ekranı: Takvim üzerinden uygun tarih ve saat seçilmesi.

4.5. Randevularım Ekranı: Kullanıcıların mevcut randevularını görüntülemesi ve iptal etmesi.

4.6. Yönetici Ekranı: Berberin gelen randevuları görüntülemesi, onaylaması ve yönetmesi.

4.7. Yapay Zekâ Ekranı: Kullanıcılara saç ve sakal modeli önerilerinin sunulması.

Flutter Navigator yapısı kullanılarak ekranlar arasında geçiş sağlanacaktır.

5. BACKEND VE VERİTABANI TASARIMI

Uygulamanın veri yönetiminde Firebase ve SQLite teknolojileri kullanılacaktır.

Firebase Authentication kullanıcı giriş ve kayıt işlemlerini gerçekleştirecektir. Firebase Firestore ise merkezi veritabanı olarak kullanılacak ve farklı cihazlardan oluşturulan randevuların ortak bir sistemde görüntülenmesini sağlayacaktır.

SQLite, mobil cihazlarda yerel veri saklama ve önbellekleme amacıyla kullanılacaktır.

Veritabanında kullanıcı bilgileri, hizmetler, fiyatlar, randevu tarihleri, saatleri ve randevu durumları tutulacaktır.

Aynı tarih ve saat için birden fazla randevu oluşturulmasını engelleyen kontrol mekanizması geliştirilecektir.

6. YAPAY ZEKÂ KULLANIMI

Projede yapay zekâ teknolojisinden yararlanılarak müşterilere saç ve sakal modeli önerileri sunulacaktır.

Kullanıcının saç tipi, yüz şekli ve kişisel tercihleri değerlendirilerek uygun model önerileri oluşturulacaktır.

Bu özellik için uygun bir yapay zekâ servisiyle bağlantı kurulması planlanmaktadır.

7. GÖREV DAĞILIMI

Diyar Arıkan

- Proje raporlarının hazırlanması.
- Flutter ile mobil arayüzlerin tasarlanması.
- Widget kullanılarak ekranların oluşturulması.
- Giriş, kayıt ve ana sayfa ekranlarının geliştirilmesi.
- Navigator ile ekranlar arası geçişlerin sağlanması.
- Yapay zekâ öneri ekranının tasarlanması.

Hasan Kılıç

- Firebase bağlantısının oluşturulması.
- Firebase Authentication işlemlerinin geliştirilmesi.
- Firestore veritabanı işlemlerinin gerçekleştirilmesi.
- SQLite yerel veri yönetiminin geliştirilmesi.
- Randevu oluşturma, listeleme ve iptal işlemlerinin kodlanması.
- Uygun saat kontrol mekanizmasının oluşturulması.
- Yönetici ekranlarının geliştirilmesi.
- Yapay zekâ servisinin uygulamaya entegre edilmesi.

Ortak Görevler

- Uygulamanın test edilmesi.
- Hataların giderilmesi.
- Eksik özelliklerin tamamlanması.
- Proje raporlarının kontrol edilmesi.
- Proje pazarı sunumunun hazırlanması ve gerçekleştirilmesi.

8. PROJE PAZARI VE SUNUM

Proje tamamlandığında mobil uygulama proje pazarı etkinliğinde tanıtılacaktır.

Sunum sırasında Flutter ile geliştirilen arayüzler, randevu oluşturma işlemleri, Firebase ve SQLite kullanımı ve yapay zekâ destekli öneri sistemi gösterilecektir.

Diyar Arıkan ve Hasan Kılıç tarafından projenin geliştirilme süreci ve teknik özellikleri açıklanacaktır.

9. BEKLENEN SONUÇ

Proje tamamlandığında müşterilerin kendi telefonlarından randevu alabileceği, randevularını takip edebileceği ve saç-sakal modeli önerileri alabileceği işlevsel bir mobil uygulama ortaya çıkarılması hedeflenmektedir.

Berber işletmesi ise kendisine gelen randevuları yönetici ekranından takip edebilecektir.

Proje kapsamında Flutter, Dart, Firebase, SQLite, Navigator ve yapay zekâ entegrasyonu konularında uygulamalı deneyim kazanılması amaçlanmaktadır.

PROJE EKİBİ

Diyar Arıkan

Hasan Kılıç
