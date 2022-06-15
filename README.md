## Cevap 2

*   Karmaşıklığı azaltmak ve dili basitleştirmek için Java'da birden fazla kalıtım desteklenmez.
*   Java programlamada çoklu ve karma kalıtım yalnızca arayüzlerle (interface) desteklenir.
*   A, B ve C'nin üç sınıf olduğu bir senaryo düşünelim.
*   C sınıfı A ve B sınıflarını miras alır
*   A ve B sınıfları aynı yönteme sahipse ve size onu sınıf nesnesinden çağırırsanız, A ve B sınıfı yöntemini çağırmak için belirsizlik oluşur.
*   Derleme zamanı hataları çalışma zamanı hatalarından dacha iyi olduğu için Java, 2 sınıfı devraldığında derleme zamanı hatası oluşturur.
*   Yani aynı yönteme veya farklı bir yönteme sahip olsanız derleme zamanı hatası olacaktır.
*   Çoklu kalıtımı destekleyen C++, Perl, Python, Lisp gibi dillerin konuyla alakalı olaraktan çeşitli çözümleri ve best practice’leri var, zaten araştırdığım kadırıyla dilin bu özelliğinin böylesine kullanılmasını kimse tavsiye etmiyor.