* **Domain süresi dolup yenileme yapılamadığından veya yenileme zamanı geçtikten sonra yapılan yenilemelerden kaynaklı olabilir.**

Domain süresinin bitip bitmediğini kayıtlarından kontrol edin. Yenilemesi gelen domainleri mümkün olduğunca son günden önce yenilemekte fayda vardır. Yenileme süresi geçtikten sonra yapılan yenilemelerde ise ns kayıtları düştüğü için tekrar düzeltmek gerekir. Bu arada domain uzatıldığı zaman ns kayıtları anlık çalışamayabilir bir süre sonra kendine gelecektir.

* **Mail hesabı açılırken belli bir kota konulmuşsa kotanız dolmuş olabilir.  **

Böyle bir problemle karşılaşmamanız için bizim önerimiz kesinlikle mail hesaplarını imap değil pop3 olarak kullanın. Kota sorununu genellikle imap mail kullananlar yaşamaktadır. Kotanız dolduğu an mail kaybı yaşamaya başlarsınız veya tarafınıza gelen mail alımı sistem tarafından durdurulur. Mümkün olduğunca çok eski mailleri kutunuzda bekletmeyin.

* **Mail şifreniz çalınmış olabilir ve bu yüzden sistem tarafından bloklandığınız için mail alamayabilirsiniz.**

Bilgisayar, telefon veya tabletlerinizde muhakkak virüs tarama programı olmalı ve sıklıkla kontrol etmenizde fayda vardır. Genellikle çalınan hesaplardan spam mailler atılır ve bunu sistem tespit ederek hesabı bloklar. Bloklama kullandığınız makinadaki ip'ye yapılır. Hesabı tekrar kullanabilmeniz için sistemden ip bloğu kaldırıp sonrasında cpanelden giriş yaparak "email" başlığı altındaki "email accounts" şifreyi değiştirin. Mümkün olduğunca karışık şifre kullanın ve kesinlikle bilgisayara kayıtlı olarak kullanmanızı önermeyiz. Her seferinde şifre yazarak mail hesabınıza giriş yaparsanız sizin açınızdan daha güvenli olabilir. Bu arada bloklanıp bloklanmadığınızı öğrenmek için " [http://ips.witamin.net/\#/](http://ips.witamin.net/#/) " giriş yaparak ip'yi görebilir ve "search" butonuyla sorun olup olmadığına bakabilirsiniz.

* **Şifreniz çalınıp mail hesabınızdan spam mailler attığınız için ip kara listeye düşmüş olabilirsiniz.**

Blacklist \(Kara liste\) veya E-Mail Blacklist , istenmeyen e-posta gönderen adreslerin IP adresi bilgisinin kara listeye alınarak bu IP adresleri üzerinden gönderilen maillerin Spam olarak iletilmesini sağlayan sistemdir. Her kara liste sisteminin kendine göre bazı kriterleri vardır. Sistem bu kritere uygun olan mailleri kara listesine alarak kullanıcıları bu gereksiz postalardan korumayı hedefler.

##### Blacklist'den Nasıl Çıkılır?

Blacklist sorununun yaşanmasının en yaygın nedenlerinden biri sizinle aynı sunucuyu paylaşan diğer kullanıcıların yapmış olduğu spam çalışmalarıdır. Bu durumda Blacklist'den çıkış yapmanız için aşağıdaki yöntemleri önerebiliriz;

* Sunucunuz üzerindeki mail yazılımının hata kodlarını kontrol edin. Portların sorunsuz çalıştığından emin olun.
* Sunucunuzun IP adresini değiştirin.
* Popüler Blacklist web siteleriyle iletişime geçin.
* Sunucu veya barındırma hizmetinizdeki olası virüsleri kontrol edin.



