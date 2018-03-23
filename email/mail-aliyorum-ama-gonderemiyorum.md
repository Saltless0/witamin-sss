* **Domain süresi dolup yenileme yapılamadığından veya yenileme zamanı geçtikten sonra yapılan yenilemelerden kaynaklı olabilir.**

Domain süresinin bitip bitmediğini kayıtlarından kontrol edin. Yenilemesi gelen domainleri mümkün olduğunca son günden önce yenilemekte fayda vardır. Yenileme süresi geçtikten sonra yapılan yenilemelerde ise ns kayıtları düştüğü için tekrar düzeltmek gerekir. Bu arada domain uzatıldığı zaman ns kayıtları anlık çalışamayabilir bir süre sonra kendine gelecektir.

* **Mail gönderdiğiniz kişinin SPF kaydı olmadığı için gri listeye düşer ve attığınız mailler karşıya ulaşmayabilir. **

Bunu cpanelden email başlığının altında track delivery kısmından takip edebilirsiniz. Ulaşan ulaşmayan tüm maillerin sonucu yazmaktadır. Bu durumda sizin yapabileceğiniz pek birşey bulunmamakla birlikte bunu en fazla karşı tarafa bildirebilirsiniz. SPF kaydını oluşturduktan sonra karşı tarafın problemi çözülecektir ve mail trafiği açılacaktır.

\(Sender Policy Framework’ün baş harflerinden oluşan SPF kaydı, Microsoft tarafından oluşturulmuştur ve spam mailleri kontrol etmek amacıyla kullanılır. “Kimlik ibrazı” niteliğindedir. Daha terimsel anlatımıyla SPF; mail sunucularına hangi hostların bir domain adına mail göndermeye yetkili olduğunu belirtmek için kullanılır.\)

* **Mail gönderdiğiniz kişi SPF kaydını yapmadan sürekli mail attığı için kara listeye girmiş olabilir.**

Bu durumda yine cpanelden email başlığının altında track delivery kısmından takip edebilirsiniz. Mailin sonucunu orada spam atıyor diye yazar. Spam gönderimi yaptığı tespit edilen IP adreslerinin tutulduğu veri tabanlarına  blacklist denir. Blacklistler firmaların kendi veritabanlarında tutulabildiği gibi tüm dünyaca kabul gören kuruluşlar tarafından da tutulur.

Bunlardan en büyükleri;

Spamhaus / Spamcop / Sorbs /

**Eğer gönderilen mail IP si spam kuruluşları tarafından blackliste alınmış ise ;**

**a- **Gelen mail geri çevrilir ve göndericiye hata mesajı  gönderilir.

**b- **Herhangi bir işleme tabi olmadan Posta Kutusu’na düşer .  
**c- **Gelen mail işaretlenir, alıcı firma tarafından oluşturulan kurallara göre Posta Kutusu’na gönderilir.

**Blacklistte Olduğunuzu Nasıl Anlarsınız ?**

Kara liste sorgulama yani blacklist te olup olmadığınızı aşağıdaki linklerden kontol edebilirsiniz .

Spamhaus : [http://www.spamhaus.org/lookup/](http://www.spamhaus.org/lookup/)  
Spamcop   : [http://www.spamcop.net/bl.shtml](http://www.spamcop.net/bl.shtml)  
Sorbs         : [https://www.secure.sorbs.net/scgi-bin/login](https://www.secure.sorbs.net/scgi-bin/login)  


