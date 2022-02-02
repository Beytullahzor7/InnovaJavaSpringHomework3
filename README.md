# InnovaJavaSpringHomework3

## ÖDEVLER

***

### Ödev 1 : ASCII code ile UNICODE nedir ? Farkları nelerdir ?	


**ASCII CODE**

<p> Ascii kodu , bizim bilgisayarda görsel olarak girdiğimiz karakter,harf ve rakamların bilgisayar 
dilindeki temsil edilme şeklidir diyebiliriz.Yani bilgisayarımızın o karakteri,harfi veya rakamı 
belleğinde saklama biçimidir,bilgisayar dilindeki kodlama sistemidir.
Açılımı ASCII (American Standard Code for Information Interchange) olan bu kodlama sistemi 
ilk olarak telgraf kodlarında ticari amaçlı kullanılmıştır 
ve daha sonraları değişim ve gelişime uğramıştır.
ASCII adı verilen sistem, birtakım sayıların birtakım karakterlerle eşleştirildiği basit bir tablodan ibarettir
ASCII tablosunda toplam 128 karakterin sayılarla eşleştirilmiş durumda olduğunu görüyoruz.
128 adet sayı 7 bite karşılık gelir (2⁷=128). Yani 7 bit ile gösterilebilecek son sayı 127‘dir. Dolayısıyla ASCII 7 bitlik bir sistemdir.</p>

**UNICODE**
<p>
  Unicode, dijital, ve geleneksel medyada her bir karakter ve sembolleri benzersiz bir rakam yardımıyla oluşturmak için geliştirilen bir metin standartıdır. Adı “Universal” ve   “Code” kelimelerinin bir araya getirilmesiyle oluşan Unicode, standartı 1980’li yıllarda geliştirilmiştir. Unicode’un geliştirilmesinin arında yatan temel neden ASCII, karakter kodlamasının daha gelişmiş ve stratejik bir sürümünün oluşturulabilmesidir.

ASCII karakterler sadece İngilizce üzerinde etkili olurken, Unicode tamamen evrenseldir. Unicode’un farklı sürümleri sayesinde İbranice ve Arapça gibi kompleks diller başta olmak üzere Çince gibi karmaşık diller kolayca dijital ortamlara aktarılabilmektedir. Yalnızca diller değil, Unicode kodlaması sayesinde karmaşık semboller ve karakterler kolayca meydana getirilebilirler.

Unicode standartı her karakter için benzersiz bir numara kullanılarak platformlar arası karmaşalara çözüm getirildi. Unicode kullanıldığı sürece hangi platformu kullandığınızı hangi cihaz, yazılım, veya dili kullandığınız fark etmiyordu. Yazılım üreticileri kısa süre içinde Unicode standartını kabul ettiler ve yazılımlarını bu standarta bağlı kalarak geliştirdiler ve düzenlediler. Bugün Unicode kodlaması artık her yerde kullanılıyor. Tüm işletim sistemleri, arama motorları, internet tarayıcıları, bilgisayarlar ve hatta akıllı telefonlar bile. İnternet, dahi Unicode karakter kodlaması üzerinden çalışıyor. URL’ler, HTML, XML, CSS, JSON, vb. diller yine Unicode ile internet dünyasına hayat veriyor.  
  
![farklar](https://user-images.githubusercontent.com/62347094/151522804-1e808a20-2f29-4838-abc8-6223b82db661.PNG)
  
</p>

### Ödev 2 : Jar ile War arasındaki farklar nelerdir ? 	
<p>
  
**JAR dosyası**, kendi kendine yeterli bir Java uygulaması oluşturmak için tüm bileşenleri içeren bir dosyadır. Ayrıca bir JAR dosyası, derlenmiş Java kaynak kodunu, bildirim dosyasını, XML tabanlı yapılandırma verilerini, JSON tabanlı veri dosyalarını, görüntüleri ve sesleri içerir. Tüm bu dosyaların tek, sıkıştırılmış bir dosyada toplanmasıdır. Tüm dosyaların sıkıştırılması, uygulamanın boyutunu azaltmaya yardımcı olur. Ayrıca, JAR dosyasını ağ üzerinden farklı platformlar arasında taşımayı kolaylaştırır.
  
**WAR dosyası**, bir web projesiyle ilgili dosyaları içerir. Herhangi bir sunucu uygulaması / JSP kabına dağıtılabilen sunucu uygulaması, JSP, XML, HTML, CSS ve JavaScript dosyaları içerir. JDK'nın jar aracı bir WAR dosyası oluşturmanıza yardımcı olur. Bu dosyalar projenin WEB-INF klasörü içindedir. Bir WAR dosyası tüm dosyaları tek bir ünitede birleştirir. Bu nedenle, bir dosyayı istemciden sunucuya aktarmak en az zaman alır.
  
JAR ve WAR Dosyaları arasındaki ana fark, içerikleridir. JAR dosyaları, bir Java uygulamasını yürütmek için Java sınıfı dosyaları, ilişkili meta verileri ve tek bir dosyada toplanmış kaynakları içeren dosyalardır. Oysa WAR dosyaları, Servlet, JSP, HTML, JavaScript ve web uygulamaları geliştirmek için gerekli diğer dosyaları içeren dosyalardır.  
</p>

### Ödev 3 : Absolute path nedir ?				

```
PATH NEDİR? 

Path(Yol) unique(eşsiz, özel) olarak bir işletim sisteminde bir dosya yada klasöre verilen özel bir lokasyondur. 
Path bir dosya yolunun alfa sayısal karakterlerin birleşiminden oluşur.
Kısaca diyebiliriz ki, bir dosya yada klasörün lokal yolu olarak diyebiliriz.

ABSOLUTE PATH NEDİR? 

Absolute path ise bir dosya yada klasörün root(kök) dizinden itibaren verilen path’e denir.
Root (/) dizininden itibaren alt klasörler üzerinde çalışmalarınızı gerçekleştirebilirsiniz.
Fakat Absolute Path işlemi, genellikle pek tavsiye edilmeyen bir path verme işlemidir. 
Sebebine gelirsek, Projemize locale olarak Path veriyoruz fakat projemizi farklı makinalar da 
çalıştırmak istediğimiz zaman verilen Absolute Path(Locale Path) projenin patlamasına sebebiyet vermektedir. 
Bu yüzden çoğunlukla Relative Path tercih edilmektedir.

```

