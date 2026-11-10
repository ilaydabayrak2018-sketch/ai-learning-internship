### Supervised Learning (Denetimli Öğrenme):	

Modelin hem girdileri (features) hem de bu girdilere karşılık gelen doğru çıktıları (labels/targets) içeren etiketli verilerle eğitilmesidir. Model girdi ve çıktı arasındaki matematiksel ilişkiyi öğrenir. Gelecekte yeni bir soru geldiğinde doğru cevabı tahmin etmeyi amaçlar. Kendi içinde ikiye ayrılır:

I.	Regression (Regresyon): Sürekli sayısal bir büyüklüğü tahmin eder.

II.	Classification (Sınıflandırma): Kesikli bir kategoriyi veya olasılık değerini tahmin eder.

### Unsupervised Learning (Denetimsiz Öğrenme): 

Hedef çıktının (etiketin) bulunmadığı durumdur. Model, verinin kendi içindeki gizli örüntüleri, benzerlikleri veya dağılım yapılarını kendisi keşfeder. Veride herhangi bir cevap anahtarı (label/target) bulunmaz. Sadece girdiler vardır.
Kapsamı modelin amacı önceden belirlenmiş bir hedefi tutturmak değil, verinin kendi içindeki doğal geometriyi, benzerlikleri, yoğunlukları veya anormallikleri çıkarmaktır. En yaygın örneği Clustering (Kümeleme) algoritmasıdır.

### Feature (Özellik – X ): 
Modele tahmin yapabilmesi için sunulan girdi değişkenleridir. Ölçülebilir, somut ve sayısal veya kategorik veri sütunlarıdır (örneğin bir evin metrekaresi, oda sayısı, yaşı).
Basit bir doğrusal modelde formüldeki x1,x2…xn bileşenleridir. Örneğin bir spam filtresinde "e-postadaki belirli kelimeler", "göndericinin IP adresi" veya bir konut tahmininde "oda sayısı", "metrekare" birer feature'dır.

### Target / Label (Hedef Çıktı - y): 
Modelin tahmin etmesini istediğimiz gerçek sonuç değişkenidir (örneğin evin satış fiyatı ya da bir e-postanın "spam" olup olmadığı).
Formüldeki y değeridir. Örneğin e-postanın "spam" olup olmadığı (1/0) veya bir evin "satış fiyatı" etikettir.

### Training (Eğitim):
 Modelin girdi özellikleri (X) ile hedef çıktı (y) arasındaki ağırlıkları ve parametreleri hata fonksiyonunu minimize edecek şekilde optimize etme sürecidir.

### Training / Test Split (Eğitim ve Test Ayrımı): 
Mevcut veri kümesinin genellikle %80 eğitim, %20 test (veya %70 / %30) şeklinde bölünmesidir. Amaç, modelin yalnızca ezberleyip ezberlemediğini değil, bağımsız bir test kümesinde ne kadar doğru genelleme yaptığını doğrulamaktır.

### Prediction (Tahmin / Çıkarım): 
Eğitilmiş modelin daha önce hiç görmediği yeni girdi verilerini alarak bir çıktı üretmesi işlemidir.



### Problem Türleri:  Regression, Classification, Clustering

1- Regression (Regresyon):

Sayı doğrusu üzerinde sürekli (continuous) bir değer tahmin eder. Ne kadar?" veya "Kaç tane?" sorularına yanıt arar. Çıktı sonsuz sayıda olası sayısal değer alabilir.
Örnek: İstanbul'daki bir dairenin büyüklüğüne, konumuna ve yaşına bakarak piyasa değerini tahmin etmek.

2- Classification (Sınıflandırma):

Veriyi önceden tanımlanmış kesikli (discrete) sınıflardan birine atar. "Bu A mı yoksa B mi?" (Binary / İkili Sınıflandırma) veya "Bu A mı, B mi, C mi?" (Multi-class / Çok Sınıflı Sınıflandırma) sorularına yanıt verir. Çoğu sınıflandırma modeli doğrudan sınıf adını değil, o sınıfa ait olma olasılığını (0 ile 1 arasında bir değer) üretir.
Örnek: Bir hastanın tahlil sonuçlarına bakarak "Diyabet Pozitif" veya "Diyabet Negatif" tahmini yapmak.

3- Clustering (Kümeleme):

Etiketsiz verileri özellik benzerliklerine göre kümelere ayırır. Denetimsiz bir yöntemdir, model hangi kümenin ne anlama geldiğini bilmez, sadece bu veri noktaları birbirine yakın, şu noktalar ise uzak tespitini yapar.
Örnek: Bir müzik uygulamasının, kullanıcıların dinlediği şarkıların tempo, akustiklik ve enstrüman özelliklerine bakarak benzer dinleme alışkanlıklarına sahip dinleyici grupları yani kullanıcı segmentleri oluşturması.

------------------------------------------------------------------------------------------

1. Classification (Sınıflandırma) Örneği
   
E-posta gelen kutusuna gelen mesajın Spam / İstenmeyen olup olmadığının filtrelenmesi.

•	Input:

Gönderici e-posta adresinin alan adı uzantısı (güvenilir kurumsal alan adı mı yoksa şüpheli/ücretsiz bir servis mi).

E-posta gövdesinde geçen belirli anahtar kelimelerin sıklığı ("ücretsiz", "hemen tıkla", "çekiliş kazandınız", "şifre yenileme").

Mesaj gövdesindeki harici web bağlantısı (URL) sayısı ve bu bağlantıların IP/alan adı güvenlik puanı.

Mesajdaki büyük harf ve ünlem işareti kullanım oranı.

•	Output:

İkili (binary) etiket: Spam (1) veya Spam Değil (0).

•	Neden Bu Problem Türü: Modelden beklenen sonuç sayısal ve sürekli bir büyüklük değil, veriyi önceden belirlenmiş sonlu ve kesikli (discrete) sınıflardan birine yerleştirmektir. Eğitim verisinde her e-postanın gerçekte spam olup olmadığı (hedef etiket - label) önceden bilinir, bu nedenle etiketli veriye dayalı bir denetimli öğrenme (supervised learning) ve sınıflandırma (classification) problemidir.

3. Regression (Regresyon) Örneği
   
Ankara'da kiralık bir dairenin aylık kira bedelinin piyasa şartlarına göre tahmin edilmesi.

•	Input: 

Dairenin metrekaresi.

Bulunduğu ilçe ve semt.

Binanın yaşı ve bulunduğu kat.

Toplu taşıma duraklarına yürüme mesafesi.

Isınma türü ve oda sayısı.

•	Output:

Aylık kira tutarı.

•	Neden Bu Problem Türü: Tahmin edilmek istenen hedef değişken belirli sınıflar veya kategoriler değil, sayı doğrusu üzerinde sürekli, ölçülebilir ve teorik olarak sonsuz sayıda ara değer alabilen sayısal bir büyüklüktür. Girdi özellikleri ile parasal değer arasındaki sayısal ilişki öğrenildiği için denetimli bir regresyon (regression) problemidir.

5. Clustering (Kümeleme) Örneği

Bir dijital müzik platformunun , kullanıcıları dinleme alışkanlıklarına göre müzik profili segmentlerine ayırması.

•	Input:

Kullanıcının gün içinde müzik dinlediği saat aralıkları (sabah, öğle, gece).

Dinlenen parçaların ortalama akustiklik ve tempo değerleri.

Parçaları sonuna kadar dinleme veya şarkı atlama sıklığı.

Haftalık toplam dinleme süresi (dakika).

•	Output :

Doğal kullanıcı kümeleri (Örn: Küme 0: Gece dinleyicileri, Küme 1: Yüksek tempolu spor ve motivasyon müzikçileri, Küme 2: Gün boyu kesintisiz arka plan pop dinleyicileri).

•	Neden Bu Problem Türü: Veri kümesinde önceden tanımlanmış bir doğru cevap, yani önceden belirlenmiş bir kullanıcı sınıfı veya hedef etiket (y) yoktur. Model, kullanıcıları vektör uzayındaki dinleme özelliklerinin birbirine olan geometrik benzerliklerine göre tamamen denetimsiz (unsupervised learning) olarak doğal gruplara kümelemektedir.

---------------------------------------------------------------------------------------------------------------------------------------------------

### Kontrol Sorusu:

Classification ile Regression farkı nedir?

Her ikisi de etiketli verilerle çalışan denetimli öğrenme (supervised learning) yöntemleridir. Temel fark hedef değişkenin (target) veri tipidir. Regression, bir evin satış fiyatı (örn. 3.500.000 TL) veya yarınki hava sıcaklığı gibi sayı doğrusu üzerindeki sürekli (continuous) sayısal büyüklükleri tahmin eder. Classification ise gelen bir e-postanın Spam / Normal olması veya bir evin Lüks / Standart olarak ayrılması gibi veriyi önceden tanımlanmış kesikli (discrete) sınıflardan birine yerleştirir.

Clustering neden farklıdır?

Classification ve Regression'da hedef çıktı (label) baştan bellidir, model doğru cevaba bakarak hatasını optimize eder. Clustering ise veri setinde hiçbir hedef etiket veya doğru sınıf adının bulunmadığı denetimsiz bir öğrenmedir (unsupervised learning). Algoritma verileri sadece özelliklerin geometrik yakınlıklarına göre kendiliğinden gruplar. Örneğin müşterilerin harcama ve ziyaret sıklığına bakılarak hiçbir etiket verilmeden fırsat takipçileri ve düzenli alıcılar şeklinde doğal profillere ayrılması Clustering'e örnektir.


