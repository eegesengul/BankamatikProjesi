<h1 align="center">Bankamatik Uygulaması</h1>
<h3 align="left">C dilinde proje geliştirmek amacıyla yaptığımız Bankamatik Uygulaması.</h3>

## Projede Yer Alan Kişiler:
- **Mert Özmen**
- **Saban Ege Sengul**
- **Fatih Yilmaz**

## Amaç:
Hem yönetici hem de müşteri tarafından kullanılabilen, kullanıcıların para yatırma, çekme ve gönderme işlemlerini gerçekleştirebileceği ve bu verileri txt dosyaları aracılığıyla kaydedip güncelleyebilen bir bankamatik uygulaması yapmak.

## Projede Neler Var?:
- **Veri Depolama:** Kullanıcı bilgileri ve hesap detayları txt dosyalarında saklanır ve bu verilere programın yeniden başlatılmasından bağımsız olarak erişilebilir.
- **Kullanıcı İşlemleri:** Kullanıcılar için para yatırma, çekme ve gönderme işlemleri yapılabilir.
- **Yönetici İşlemleri:** Hesap açma, kapama ve mevcut hesapların yönetimi gibi işlemler yapılabilir.
- **Giriş ve Kayıt:** Program başında giriş yapma ile kullanıcı türü için farklı menü gösterimi ve yeni kullanıcı kaydı oluşturma.

---

## Program Akışı:
1. **Ana Menü:**
   - Kayıt Ol
   - Giriş Yap
   - Kayıt Sil
   - Çıkış Yap

2. **Kullanıcı İşlemleri:**
   - Para Yatırma
   - Para Çekme
   - Para Gönderme
   - Hesap Bilgileri Görüntüleme
   - Çıkış

3. **Yönetici İşlemleri:**
   - Hesap Açma
   - Hesap Kapatma
   - Mevcut Hesapları Yönetme

---

## Kullanım Talimatları:
1. Programı başlattığınızda ana menüde çeşitli seçenekler göreceksiniz.
2. Yeni bir kullanıcı kaydı oluşturmak için "Kayıt Ol" seçeneğini seçin ve istenen bilgileri girin.
3. Mevcut bir kullanıcıysanız, "Giriş Yap" seçeneğiyle giriş yapın.
4. Giriş yaptıktan sonra, ana menüde sunulan işlemlerden birini seçebilirsiniz.
5. İşlemleri tamamladıktan sonra çıkış yaparak oturumu sonlandırabilirsiniz.

---

## Dosya Yapısı:
- `kayitlar.txt`: Kullanıcı bilgileri ve hesap detaylarının saklandığı dosya.
- `bankamatik.c`: Programın ana C kod dosyası.

---

<p align="center">
  <strong>Projemizi GitHub'da inceleyebilir ve katkıda bulunabilirsiniz:</strong>
  <br>
  <a href="https://github.com/eegesengul/MEFBankamatikProjesi" target="_blank">MEF Bankamatik Uygulaması GitHub</a>
</p>
