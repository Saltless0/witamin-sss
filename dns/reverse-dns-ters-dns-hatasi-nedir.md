* **\(Reverse Domain Name System\)**

Ters isim kaydı demektir. PTR kaydı diye de adlandırılır. RDNS tanımlamasını genelde ISP servisleri yapmaktadır yani bir host hizmeti aldığınızda sunucu yada vps kiraladığınızda makinanızdaki yada kontrol panelinizdeki DNS kısmından bu RDNS kaydını giremezsiniz.Bu kaydın girilebilmesi için hizmet alınan isp servisine kullandığınız ip adresi için istediğiniz ismi yazdırabilirsiniz. Örnek olarak : 192.168.2.1 ip adresi için = www.witamin.net yazdırabilirsiniz. RDNS kaydımız olmazsa ne olur, eğer rdns kaydımız olmaz ise bir çok mail servisi veren firmaların mail sunucularına mail gönderemeyebilirsiniz.

* **Düz dns kaydı** alan adının ip adresine çevrilmesi için kullanılmaktadır. **Ters dns kaydı** ise ip adresinin alan adına çevrilmesi işlemini yerine getirmektedir. Bu işlem genellikle sunucu üzerinden maillerin gönderimi ile ilgili sorun yaşanılmaması için yapılmaktadır.

* Paylaşımlı hostinglerde belli ip'ler atanmaktadır. Diğer türlü her hosting için ayrı ip atanması gerekmektedir ki bu mümkün değildir. Bu yüzden her domainin kendisine ait ip'si olması gerekmektedir ki ters dns kaydı o domaine özel yapılabilsin. O sebeple bu tarz hata aldığınız zaman dilerseniz karşı firmadan bu korumayı kaldırmayı rica edebilir ve engeli bu şekilde atlayabilirsiniz. Bu tarz koruma kullanan firmalar kendi ip'si olmayan hiçbir firmadan mail alamazlar.



