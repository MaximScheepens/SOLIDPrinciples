Single Responsibilty Principle

-Bir sınıfın değişmesi için sadece bir nedeni olmalıdır. Yani bir sınıfın yanlızca bir işi olmalıdır.
-Örneğin, işe yeni başlamış personelin özlük bilgilerinin sisteme kaydedilmesi, bu işlemin loglarının tutulması ve ilgili kişi sisteme kayıt olduğunda müdürüne bilgilendirme e-postası gönderecek basit bir uygulamamız olduğunu düşünelim. Bu işlemleri tek bir sınıf içerisinde yerine getirebiliriz. Bu işlemi bu şekilde yaparsak bu prensibe ters düşmüş oluruz. Bu prensibe uymak için tüm bu işlemleri ayrı sınıflarda ele alamamız gerekmektedir. Her sınıfın sadece bir sorumluluğu olmalıdır. Örneğin, loglama işlemi için bir sınıfın, çalışanı veri tabanına kaydetmek için bir sınıf ve bilgilendirme e-postası için bir sınıf kullanılımalıdır.
