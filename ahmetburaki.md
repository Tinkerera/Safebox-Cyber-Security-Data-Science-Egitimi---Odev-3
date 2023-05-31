# Ahmet Burak İMAL 
## Creeper Malware

Creeper malware, bilgisayar dünyasında bilinen ilk zararlı yazılımlardan biridir. 1970'lerin ortalarında ortaya çıkan ve bir DEC PDP-10 bilgisayarı üzerinde çalışan bir programdır. Creeper, bir bilgisayar ağı üzerinde hareket edebilen ve işletim sistemine müdahale edebilen bir tür solucan olarak sınıflandırılmıştır.

Creeper, bilgisayarlara giren ve çalışan bir programdır. Kendi kendini kopyalayarak ağı tarama ve diğer bilgisayarlara bulaşma yeteneğine sahiptir. Bir bilgisayara bulaştığında, çalışan bir program olarak ekranda belirir ve "Ben Creeper, seni yakaladım. Yakalamam için beni yakalamalısın. Beni yakala!" mesajını görüntüler.

Creeper, eğer hedef sistemde bir TELNET hizmeti çalışıyorsa, diğer bilgisayarlara yayılmak için bu hizmeti kullanır. Bir hedef bilgisayara bulaştığında, kendini oraya kopyalar ve yayılmaya devam eder. Ancak, Creeper diğer bilgisayarlardan temizlenemezdi, bu yüzden temizlenmesi için bir program olan "Reaper" geliştirildi. Reaper, Creeper'ı algılayarak ve silerek sistemleri temizlemek için kullanılan bir programdır.

Creeper, günümüzdeki zararlı yazılımların karmaşıklığına veya yayılma hızına kıyasla oldukça basit bir yapıya sahipti. Ancak, bilgisayar güvenliği ve zararlı yazılımların ortaya çıkması konusunda bir dönüm noktasıdır. Creeper, bilgisayar güvenliği ve zararlı yazılımların önlenmesi için daha ileri teknolojilerin ve önlemlerin geliştirilmesine katkıda bulunmuştur.

## Analitik SQL Nedir? 

Analitik SQL, veritabanlarında yapılan analitik sorgulama ve veri analizi işlemlerini gerçekleştirmek için kullanılan bir SQL (Structured Query Language) türüdür. SQL, ilişkisel veritabanlarına erişmek ve verileri sorgulamak için kullanılan bir programlama dilidir.

Analitik SQL, genellikle büyük veri kümeleri üzerinde karmaşık analizler yapmak için kullanılır. Bu tür sorgular, veritabanında depolanan veriler üzerinde derinlemesine analizler yapmayı, eğilimleri ve desenleri belirlemeyi, özetlemeyi ve istatistiksel sonuçları elde etmeyi sağlar. Ayrıca, veritabanındaki verileri daha anlamlı hale getirmek için birleştirme, gruplama, filtreleme ve sıralama gibi işlemleri de içerir.

Analitik SQL, bazı özel işlevler ve operatörlerle genişletilmiştir. Örneğin, verileri toplama, ortalama, minimum, maksimum gibi işlevler kullanarak özetleyebilir veya zaman serilerini analiz etmek için hareketli ortalama veya regresyon işlevlerini kullanabilirsiniz. Ayrıca, pencere fonksiyonları kullanarak veri setleri üzerinde kayan pencereler oluşturabilir ve bu pencerelerdeki veriler üzerinde hesaplamalar yapabilirsiniz.

Analitik SQL'nin kullanımı, iş analitiği, veri keşfi, iş zekası ve veri bilimi gibi alanlarda yaygındır. Bu tür sorgular, işletmelerin verilerini analiz etmek, karar vermelerine yardımcı olmak ve stratejik bilgiler elde etmek için kullanılır. Analitik SQL, veritabanlarındaki büyük veri kümeleri üzerinde hızlı ve etkili analizler yapma yeteneği sağlar.

### Örnek Basit SQL Sorgusu:

```sql
    SELECT country, AVG(order_total) AS average_order_total, MAX(order_total) AS highest_order_total
    FROM customers
    GROUP BY country
    ORDER BY average_order_total DESC;
```
