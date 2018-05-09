* Ters dns kaydı ile alakalı bir problem olduğunda bu tarz bir hata alırsınız;

**Your host \(your IP address\) is not registered to you through whois-databases and therefore it is part of your providers infrastructure. See **[**http://\*\*\*.net/cgi-bin/lacnic/whois?query=93.190.220.205**](http://lacnic.net/cgi-bin/lacnic/whois?query=93.190.220.205)

** Furthermore "**[**93-190-220-205.static.turkns.net**](http://93-190-220-205.static.turkns.net)**" matches a generic hostname pattern which is often in use in this IP range. You \(respectively your company\) are not identifiable via WhoIs; neither by means of the IP address nor on the basis of this hostname. As such please use the infrastructures mailserver \(e.g. via "smarthost"\), because we do not accept SMTP connections from IP addresses without WhoIs-delegation to the company using it and with anonymous hostnames, too. You need at least to let your provider change the PTR Record \(rDNS\) for your IP address. Please be aware that mailservers hostnames and reverse hostnames \(PTR\) SHOULD \(!\) be the same. The current situation is: The PTR-Record \(rDNS\) of your IP address 93.190.220.205 contains the reverse DNS hostname "**[**93-190-220-205.static.turkns.net**](http://93-190-220-205.static.turkns.net)**"; this looks like an end user system. Therefore we recommend you to contact the technical support to set the PTR record to a non-generic hostname \(in one of your own domains\). At **[**http://\*\*\*.net/ip/93.190.220.205\#\_dns**](http://bgp.he.net/ip/93.190.220.205#_dns)** you can verify if the change is already done. Nevertheless we will unblock your IP. Please notice that it may take up to 24 hours until the change shows acute effect. Please excuse any inconveniences, but we do not see other possibilities to react to the millions of junkmails we receive from anonymous systems with generic rDNS which are very often hijacked, virus infected or open relays flooding our servers.**



* **\(Reverse Domain Name System\)**

  Ters isim kaydı demektir. PTR kaydı diye de adlandırılır. RDNS tanımlamasını genelde ISP servisleri yapmaktadır yani bir host hizmeti aldığınızda sunucu yada vps kiraladığınızda makinanızdaki yada kontrol panelinizdeki DNS kısmından bu RDNS kaydını giremezsiniz.Bu kaydın girilebilmesi için hizmet alınan isp servisine kullandığınız ip adresi için istediğiniz ismi yazdırabilirsiniz. Örnek olarak : 192.168.2.1 ip adresi için = www.witamin.net yazdırabilirsiniz. RDNS kaydımız olmazsa ne olur, eğer rdns kaydımız olmaz ise bir çok mail servsi veren firmaların mail sunucularına mail gönderemeyebilirsiniz. Firmaların %90 nı RDNS kaydını kontrol ettirmektedir, %70 kısmıda SPF kaydını kontrol ettirmektedir.

* **Düz dns kaydı** alan adının ip adresine çevrilmesi için kullanılmaktadır. **Ters dns kaydı** ise ip adresinin alan adına çevrilmesi işlemini yerine getirmektedir. Bu işlem genellikle sunucu üzerinden maillerin gönderimi ile ilgili sorun yaşanılmaması için yapılmaktadır.

* Paylaşımlı hostinglerde belli ip'ler atanmaktadır. Diğer türlü her hosting için ayrı ip atanması gerekmektedir ki bu mümkün değildir. Bu yüzden her domainin kendisine ait ip'si olması gerekmektedir ki ters dns kaydı o domaine özel yapılabilsin. O sebeple bu tarz hata aldığınız zaman dilerseniz karşı firmadan bu korumayı kaldırmayı rica edebilir ve engeli bu şekilde atlayabilirsiniz. Bu tarz koruma kullanan firmalar kendi ip'si olmayan hiçbir firmadan mail alamazlar.

  




