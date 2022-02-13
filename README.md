# Hepsiemlak-Java-Spring-Bootcamp-HW2


• Java dünyasındaki framework’ler ve çözdükleri problemler nedir? Kod Örneklendirini de 
içermelidir. 

• Spring frameworkünün kullandığı design patternlar neler?

• Creational Patterns neler? Önceki ödevde oluşturulan nesnelerinizi factory Design patterni ile 
oluşacak şekilde düzenleyin.

3 konu da makale olarak yazılmalı ve repo’larınızın içerisine pdf olarak veya .md formatında 
yazılmalıdır. Ayrıca medium hesabınız yoksa oluşturup, teslim tarihi sonrasında hesabınızdan 
paylaşmanız gereklidir. 


<hr><br>

<h1>Java</h1>
<p>&ensp;Java günümüzde Java Community Process tarafından geliştirilmektedir. <br>Bu geliştirme işlemleri herkesin katkı sağlayıp rahat bir şekilde katılabileceği bir ortamda yapılmaktadır. <br>Java’nın geleceği hakkındaki tüm kararlar oy çokluğu ile burada alınıp geleceğine dair gidişat bu topluluk tarafından çizilmektedir. <br>Java standartlarının halka açık olması bu yazılımı özgür yazılım haline getirmiştir.</p>

<p>&ensp;Java da diğer başarılı diller gibi OOP (object oriented programming), yani nesne tabanlı bir programlama dilidir. <br>Java ile programlar oluşturmak istiyorsanız nesne tabanlı programlamanın ne olduğu hakkında bilgi sahibi olmalısınız. <br>Çünkü Java nesne kavramı üzerine kurulmuş bir dildir.</p><br>

<h2> Spring </h2>
<p>&ensp;En çok kullanılan Java Framework’ü olarak Spring’i örnek verebiliriz. <br>Spring Framework’ü hem .net hem de Java için geliştirilmiş Java EE uygulamaları yapmamızı kolaylaştıran harika bir Framework’tür. <br>Bu framework model-view-controller katmanlarını kontrol ederek ihtiyacımız olan paket ve sınıfları ekleyebildiğimiz ve bu paketleri kullanabilmemizi sağlayan bir Framework’tür. <br>Spring ile çok karmaşık uygulamaların yanında oldukça basit uygulamalar yapmak da mümkündür.</p><br>

<h2> Vaadin </h2>
<p>&ensp;Vaadin, web yazılımları geliştirmek için hazırlanmış bir frameworktur. <br>Sunduğu alt yapı sayesinde, masaüstü uygulamaları geliştirircesine, güçlü, performanslı ve hızlı  web yazılımlarının ortaya çıkarılmasını sağlar. <br>Vaadin ile Javascript ve HTML ile ilgili detay birçok detaydan kurtulmayı sağlar.</p><br>

<h2> JSF (Java Server Faces) </h2>
<p>&ensp;Java ile web siteleri de yapmak mümkündür. Ancak Java Server Faces Framework’ü dinamik web sayfaları oluşturmamıza yaramaktadır. <br> JSP kodları HTML dilinin içine yazılır ve kendine özel etiket sistemi vardır. <br>Bu sayede HTML ile Java'yı harmanlayarak performanslı ve düzenli web siteler oluşturabilmeniz mümkündür.</p><br>
  
  
<h2> Maven </h2>
<p>&ensp;Bir proje geliştirirken proje içinde bir standart ve düzen oluşturmayı, geliştirme sürecini daha basitleştirmemizi sağlayan Java Framework’üdür.<br> Geliştirdiğimiz projenin bağımlılıklarını bu framework ile ortadan kaldırabildiğimiz gibi, daha kolay gelitşirebilmemiz gibi birçok kolaylık sağlamaktadır.</p><br>

<h2> Hibernate </h2>
<p>&ensp;Hibernate bir ORM kütüphanesidir. Veritabanı üzerinde yapılan işlemleri kolaylaştıran bu framework için Java sınıflarının veritabanı dönüşümünü yapıyor diyebiliriz. <br>Aynı zamanda veri çekme ve veri sorgulama işlerinde de oldukça yardımı dokunan bir Framework’tür.</p><br>

<hr><br><h1>Spring Boot İle Kullanılan Design Patternlar</h1><br>

<h2>Singleton Design Pattern</h2>
<p>&ensp;Singleton bir nesnenin sadece bir örneğinin olduğundan emin olmak ve bu nesneye ihtiyacınız olduğunda kodunuzda her yerde aynı örneğin çağırılmasını sağlamak için kullanılır. <br>Singleton deseni SOLID programlama prensiplerinin en başında gelen tekil sorumluluk prensibine aykırılığa neden olan iki sorunu tek seferde çözmektedir.</p><br>

<h2>Factory Method Design Pattern</h2>
<p>&ensp;Kelime anlamı “Fabrika Metodu” olan Factory Method, üst sınıfta nesneler oluşturmak için bir arabirim sağlayan, ancak alt sınıfların oluşturulacak bu nesne türünü değiştirmesine izin veren bir yaratımsal desen (creational pattern) türüdür.</p><br>

<h2>Proxy Design Pattern</h2>
<p>&ensp;Vekil kalıp (Proxy Pattern), nesne temelli yazılım mimarilerinde belirlenmiş temel tasarım kalıplarından biridir. <br>Var olan bir nesneye ulaşılmak istendiğinde vekil kalıp oluşturulur. <br>Nesneyle istemci arasına yeni bir katman koyarak nesnenin kontrollü bir şekilde paylaşılması sağlanır. <br>Böylece istemci, işlem yapan sınıfla doğrudan temasa geçmemiş olur.</p><br>

<h2>Template Method Design Pattern</h2>
<p>&ensp;Şablon metot kalıbı davranışsal tasarım kalıpları grubunda yer alır. <br>Şablon metot kalıbı bir işlem için gerekli adımları soyut olarak tanımlar ve bir şablon metot ile algoritmanın nasıl çalışacağını belirler. <br>Alt sınıflar algoritma için gerekli bir ya da birden fazla metodu kendi bünyelerinde gerçekleyerek kullanılan algoritmanın kendi istekleri doğrultusunda çalışmasını sağlarlar.</p><br>

<h1>Kaynakça</h1>
<ul>
    <li>Java: https://www.niobehosting.com/blog/java/</li><br>
    <li>Spring, JSF, Maven, Hibernate: https://www.niobehosting.com/blog/java/</li><br>
    <li>Vaadin: http://www.yazilimdilleri.net/YazilimMakale-2223-Vaadin-Web-Framework-ile-Form-Uygulamasi.aspx</li><br>
    <li>Singleton: https://www.evrenbal.com/singleton-tasarim-deseni-nedir/</li><br>
    <li>Factory: https://www.evrenbal.com/tasarim-kaliplari-design-patterns-factory-method-nedir/</li><br>
    <li>Proxy: https://bidb.itu.edu.tr/seyir-defteri/blog/2013/09/08/vekil-kal%C4%B1p-(proxy-pattern)</li><br>
    <li>Template: https://bidb.itu.edu.tr/seyir-defteri/blog/2013/09/08/%C5%9Fablon-metot-kal%C4%B1b%C4%B1-(template-method-pattern)</li>
   </ul>
