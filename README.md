
## MediaVault Nedir?

MediaVault, KeePass gibi şifre yöneticisi veritabanlarını yönetmek için geliştirilmiş bir Python uygulamasıdır. Bu araç, şifrelerinizi güvenli bir şekilde saklamak, düzenlemek ve çeşitli işlemleri kolaylaştırmak için tasarlanmıştır. Terminal tabanlı bir uygulamadır, bu nedenle komut satırında çalışır.

## Temel Özellikler

### Veritabanı Yönetimi
- **Giriş Listeleme**: Veritabanınızdaki tüm şifreli girişleri detaylı bir şekilde listeleyin.
- **Yeni Giriş Ekleme**: Yeni şifre girişi ekleyin ve başlık, kullanıcı adı, şifre, URL gibi bilgileri veritabanınıza kaydedin.
- **Giriş Düzenleme**: Mevcut bir girişin bilgilerini güncelleyin.
- **Giriş Silme**: İhtiyacınız olmayan girişleri veritabanından silin.

### Şifre İşlemleri
- **Şifre Oluşturma**: Güvenli ve rastgele şifreler oluşturun; uzunluk ve karakter çeşitlerini belirleyin.
- **Şifre Gösterme**: Bir girişin şifresini görün ve kopyalayın.

### Veri Dışa Aktarma ve İçe Aktarma
- **Veri İçe Aktarma**: Başka bir KeePass veritabanından girişleri mevcut veritabanınıza aktarın.
- **Veri Dışa Aktarma**: Veritabanınızdaki girişleri CSV veya JSON formatında dışa aktarın.

### Veritabanı ve Şifre Yönetimi
- **Yeni Veritabanı Oluşturma**: Yeni bir KeePass veritabanı oluşturun ve bunu bir şifre ile koruyun.
- **Veritabanı Şifresini Değiştirme**: Var olan bir veritabanının şifresini değiştirin.

### Şifre Kırma
- **Şifre Kırma**: Belirli bir dosya için çeşitli şifreleri deneyerek doğru şifreyi bulmaya çalışın.

### Ayarlar Yönetimi
- **Ayarlar Menüsü**: Veritabanı dosya yolu, CSV ve JSON dosya yollarını yönetebilir ve bu yolları güncelleyebilirsiniz.

## Nasıl Çalışır?

MediaVault, kullanıcıya ana menüde çeşitli seçenekler sunar ve kullanıcı bir işlem seçtiğinde uygun fonksiyonu çalıştırır. Her işlem, alt menüler içerir ve hata yönetimi sayesinde kullanıcıyı bilgilendirir.

## Kullanılan Kütüphaneler
- **os**: Dosya ve sistem işlemleri.
- **getpass**: Şifrelerin gizli bir şekilde girilmesi.
- **platform ve sys**: Sistem bilgilerini almak.
- **json**: JSON formatında veri okuma ve yazma.
- **random ve string**: Rastgele şifreler oluşturma.
- **itertools**: Şifre kombinasyonları oluşturma.
- **pandas**: Verileri tablo şeklinde gösterme.
- **concurrent.futures ve multiprocessing**: Şifre kırma işlemlerini hızlandırma.
- **pykeepass**: KeePass veritabanlarını okuma ve yazma.

## Kullanım Örneği

- **Giriş Listeleme**: "Girişleri Listele" seçeneğiyle mevcut KeePass veritabanındaki tüm girişleri tablo şeklinde görüntüleyin.
- **Yeni Giriş Ekleme**: "Yeni Giriş Ekle" seçeneğiyle başlık, kullanıcı adı, şifre gibi bilgileri girin ve veritabanınıza ekleyin.
- **Şifre Kırma**: Şifre kırma modunda belirli bir dosya için şifreleri deneyerek doğru şifreyi bulmaya çalışın.
