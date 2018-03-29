**Gri Liste \(Greylisting\)**

Etkili bir spam önleme metodudur.

Gelen her mailde, gönderenin ip adresi, gönderen email adresi, alıcı email adresi kontrol edilir. Bu bilgiye ** triplet ** denir.  
Buna göre ilk defa gönderilen bütün mailler **Gri Liste **tarafından reject edilir ve tekrar gönderilmesi beklenir.

Reject işlemi geçici bir reddetmedir. **SMTP** **RFC2821 **standardına göre** ** reject edilen bir mail, gönderen MTA tarafından bir süre sonra tekrar gönderilir. İkinci gönderide **Gri Liste** maili kabul eder. Spam mailler ikinci kez gönderilmezler ve böylece ilk seferde reject edildikten sonra ayrılmış olurlar.

**Gri Liste ** kullanımı sebebiyle reject edilen mailin tekrar gönderilip hedefe ulaşması tabiki bir süre alacak ve normal şartlarda iletilen maillerden daha geç ulaşacaktır.

Ayrıca **RFC2821 **yerine önceki standart olan **RFC821 **kullanan MTA’larda bu durum yukarıda anlattığımız gibi çalışmayacaktır. Bu durumda 2. deneme olmayacak ve mail hedefe ulaşmayacaktır.

Maillerin **Gri Liste** kontrolüne takılmaması için maili gönderen domainin SPF kaydının doğru yapılandırılmış olması gerekir. SPF kaydı olmayan domainlerden gelen tüm mailler **Gri Liste** denetimine alınır.

