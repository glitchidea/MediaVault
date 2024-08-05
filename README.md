# MediaVault
MediaVault Nedir?
MediaVault, KeePass gibi şifre yöneticisi veritabanlarını yönetmek ve çeşitli işlemler yapmak için geliştirilmiş bir Python uygulamasıdır. Bu araç, şifrelerinizi güvenli bir şekilde saklamak, düzenlemek ve çeşitli şifre işlemlerini kolaylaştırmak için tasarlanmıştır.

MediaVault'un Temel Özellikleri
Veritabanı Yönetimi:

Giriş Listeleme: Veritabanınızdaki tüm şifreli girişleri detaylı bir şekilde listeleyebilirsiniz. Her bir girişin başlık, kullanıcı adı, şifre, URL ve notlarını görebilirsiniz.
Yeni Giriş Ekleme: Yeni bir şifre girişi ekleyerek başlık, kullanıcı adı, şifre, URL ve notlar gibi bilgileri veritabanına kaydedebilirsiniz.
Giriş Düzenleme: Mevcut bir girişin bilgilerini güncelleyebilirsiniz.
Giriş Silme: İhtiyacınız olmayan girişleri veritabanından silebilirsiniz.
Şifre İşlemleri:

Şifre Oluşturma: Güvenli ve rastgele şifreler oluşturabilirsiniz. Şifrelerin uzunluğunu ve karakter çeşitlerini belirleyebilirsiniz.
Şifre Gösterme: Bir girişin şifresini görebilir, kopyalayabilirsiniz.
Veri Dışa Aktarma ve İçe Aktarma:

Veri İçe Aktarma: Başka bir KeePass veritabanından girişleri mevcut veritabanınıza aktarabilirsiniz.
Veri Dışa Aktarma: Veritabanınızdaki tüm girişleri CSV veya JSON formatında bir dosyaya dışa aktarabilirsiniz.
Veritabanı ve Şifre Yönetimi:

Yeni Veritabanı Oluşturma: Yeni bir KeePass veritabanı oluşturabilir ve bunu belirli bir şifre ile koruyabilirsiniz.
Veritabanı Şifresini Değiştirme: Var olan bir veritabanının şifresini değiştirebilirsiniz.
Şifre Kırma:

Şifre Kırma: Belirli bir dosya için çeşitli şifreleri deneyerek doğru şifreyi bulmaya çalışabilirsiniz. Şifreler ya bir dosyadan ya da kullanıcı tarafından sağlanmış olabilir.
Ayarlar Yönetimi:

Ayarlar Menüsü: Veritabanı dosya yolu, CSV ve JSON dosya yollarını yönetebilir ve bu yolları güncelleyebilirsiniz.
Nasıl Çalışır?
Ana Menü: Uygulama, kullanıcıya ana menüde çeşitli seçenekler sunar. Kullanıcı bir işlem seçer ve MediaVault bu işleme uygun fonksiyonu çalıştırır.

İşlem Menülerinin Yönetimi: Her işlem, kullanıcıya daha fazla seçenek sunan alt menüler içerir. Örneğin, giriş eklerken önce mevcut girişleri listeleyebilir ve ardından yeni bilgileri ekleyebilirsiniz.

Hata Yönetimi: MediaVault, kullanıcı hatalarını yakalar ve uygun hata mesajları ile kullanıcıyı bilgilendirir. Örneğin, yanlış şifre girilirse veya geçersiz bir dosya seçilirse kullanıcıya bilgi verir.

Kullanılan Kütüphaneler
os: Dosya ve sistem işlemleri için kullanılır, örneğin ekranı temizlemek.
getpass: Şifrelerin gizli bir şekilde girilmesini sağlar.
platform ve sys: Sistem bilgilerini almak için kullanılır.
json: JSON formatında veri okuma ve yazma işlemleri için kullanılır.
random ve string: Rastgele şifreler oluşturmak için kullanılır.
itertools: Şifre kombinasyonları oluşturmak için kullanılır.
pandas: Verileri tablo şeklinde göstermek için kullanılır.
concurrent.futures ve multiprocessing: Şifre kırma işlemlerini paralel olarak hızlandırmak için kullanılır.
pykeepass: KeePass veritabanlarını okuma ve yazma işlemleri için kullanılır.
Kullanım Örneği
Giriş Listeleme: Ana menüden "Girişleri Listele" seçeneğini seçtiğinizde, mevcut KeePass veritabanındaki tüm girişleri tablo şeklinde görüntülersiniz.
Yeni Giriş Ekleme: "Yeni Giriş Ekle" seçeneğine tıkladığınızda, başlık, kullanıcı adı, şifre gibi bilgileri girer ve veritabanına eklersiniz.
Şifre Kırma: Şifre kırma moduna geçtiğinizde, belirli bir dosya için şifreleri deneyerek doğru şifreyi bulmaya çalışabilirsiniz.
