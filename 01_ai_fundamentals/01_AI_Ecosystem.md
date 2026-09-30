1- Artificial Intelligence (AI)
Karmaşık veya gelişmiş görevleri çözebilen, insan dışı bir program veya modeldir. Örneğin bir metni bir dilden başka bir dile çeviren bir sistem veya radyoloji görüntülerinden hastalıkları tespit eden bir model yapay zekadır. Dört ana dalda incelenir.
Tahminleyici Modeller (Predictive ML): Veriden öğrenerek sınıf, sayı veya olasılık tahmini yapan geleneksel modellerdir.
Derin Öğrenme ve Yapay Sinir Ağları: Biyolojik nöronlardan esinlenen, gizli katmanlar ve aktivasyon fonksiyonlarıyla karmaşık verileri işleyen mimarilerdir.
Üretken Yapay Zeka ve LLM'ler: Öğrendiği örüntülerle özgün metin, kod, görsel ve içerik üreten güncel modellerdir.
Sorumlu Yapay Zeka (Fairness & Ethics): Sistemlerin adil, şeffaf, güvenilir ve etik standartlara uygun çalışmasını denetleyen ilkeler bütünüdür.

2- Machine Learning (Makine Öğrenimi):
Geleneksel yazılımdaki gibi kuralların elle yazılması yerine sisteme verilen veri ve doğru yanıtların istatistiksel algoritmalarla incelenerek modelin otomatik olarak öğrenilmesidir.
Çalışma Döngüsü: Model tahmin üretir. Gerçek değerle farkından Kayıp (Loss) hesaplanır. Gradyan İnişi (Gradient Descent) ve Öğrenme Oranı (Learning Rate) ile model ağırlıkları güncellenerek hata en aza indirilir.
Temel Türleri:
1.	Regresyon: Sürekli sayısal değer tahmini (örn. Ev fiyatı).
2.	Lojistik Regresyon: Bir olayın gerçekleşme olasılığı (0-1 arası).
3.	Sınıflandırma: Veriyi kategorilere ayırma (örn. Spam / Normal e-posta).

3- Deep Learning (Derin Öğrenme) 
Çok sayıda gizli katmandan oluşan Yapay Sinir Ağlarını (ANN) kullanan makine öğrenmesi alt dalıdır. Klasik modellerin aksine, ham verideki (görsel, ses, metin) özellikleri insan müdahalesine gerek duymadan katmanlar boyunca kendi kendine öğrenir. Mimari; veriyi alan girdi, ağırlık ve aktivasyon fonksiyonlarıyla örüntüleri çözen gizli ve tahmini üreten çıktı katmanlarından oluşur. Öğrenme süreci, girdinin tahmine dönüştüğü ileri yayılım (forward) ve hesaplanan hataya göre ağırlıkların optimize edildiği geriye yayılım (backpropagation) adımlarıyla gerçekleşir.

4- Data Science (Veri Bilimi)
Ham veriyi temizleyip modellerin işleyebileceği matematiksel formata sokma sürecidir (Çöp girerse, çöp çıkar). Farklı büyüklükteki sayıları ölçeklendirerek (scaling) dengeler, sözel verileri kodlayarak (encoding) sayılara çevirir ve değişkenleri birleştirerek yeni özellikler (feature crossing) türetir. Modelin ezberlemesini (overfitting) önlemek için veriyi Eğitim (%70-80), Doğrulama (%10-15) ve Test (%10-15) kümelerine ayırır; uç değerleri temizleyip veri dengesini sağlayarak modelin taraflı (bias) kararlar vermesini engeller.

5- Generative AI (Üretken Yapay Zeka)
Mevcut verilerden öğrendiği örüntülerle daha önce var olmayan özgün metin, görsel, ses ve kod gibi yeni içerikler üreten teknolojidir. Geleneksel yapay zekanın sınıflandırma ve tahmin odaklı yapısından farklı olarak doğrudan yaratım sürecine odaklanır; rutin işleri otomatikleştirip insan-bilgisayar etkileşimini doğal dile taşır. Bu alanın temel taşlarından olan Doğal Dil İşleme (NLP) insan dilini anlama ve analiz etmeyi, Doğal Dil Üretimi (NLG) metin üretmeyi sağlarken; devasa verilerle eğitilen Büyük Dil Modelleri (LLM) bu iki yeteneği birleştirerek özetleme, çeviri ve içerik üretimini üst seviyeye çıkarır. Yeni başlayanlar hazır araçları doğrudan tüketici olarak kullanabilirken, uzmanlar bu modelleri veri bilimi ve mimari optimizasyonlarla özel ihtiyaçlara göre yeniden yapılandırabilir.

6- Natural Language Processing – NLP (Doğal Dil İşleme) 
Bilgisayarların insan dilini anlamasını, analiz etmesini ve üretmesini sağlayan yapay zeka dalıdır. Metinleri anlam ilişkilerini koruyarak matematiksel vektörlere dönüştürmeyi amaçlar.
İşlem Adımları:
Jetonlaştırma (Tokenization): Metni modelin işleyebileceği en küçük yapı birimlerine bölme adımıdır.
Gömme Vektörleri (Embeddings): Seyrek ve maliyetli One-Hot kodlama yerine, kelimeleri düşük boyutlu yoğun vektörlere çevirir. Anlamca benzer sözcükleri çok boyutlu uzayda birbirine yakın konumlandırır; bağlamsal modellerle kelimenin cümledeki görevine göre farklı anlamlar kazanmasını sağlar.
N-gram ve Olasılık: Ardışık kelime dizilerini inceleyerek bir sonraki kelimeyi olasılıksal olarak tahmin eder.
Transformer ve Dikkat (Self-Attention): Sıralı işleme yerine metindeki tüm kelimelerin birbiriyle ilişkisini eşzamanlı hesaplayarak uzun metinlerde bağlam kaybını önler.
Kullanım Alanları: Metin sınıflandırma, bilgi getirme, otomatik çeviri ile metin üretimi.

7- Computer Vision 
Bilgisayarlara dijital görsel ve videoları anlamlandırma yeteneği kazandıran yapay zeka alanıdır. Bilgisayar için her görsel sayılardan oluşan bir piksel matrisidir (siyah-beyaz için 0–255 arası tek katman, renkliler için 3 katmanlı RGB).

•	Matematiksel Temsil ve Boyut: Görseller düzleştirilerek modele sayısal özellikler olarak aktarılır. Bellek tasarrufu sağlamak ve ezberlemeyi önlemek için ham pikseller, benzer görselleri yakın noktalara toplayan Görüntü Gömme Vektörlerine (Image Embeddings) dönüştürülür.
•	Sınıflandırma Mantığı: Görsel tek bir sınıfa aitse çıktı katmanında olasılıkları 1'e tamamlayan Softmax, görselde aynı anda birden fazla nesne etiketlenebiliyorsa bağımsız olasılıklar üreten Sigmoid fonksiyonu kullanılır. Temel amaç, pikseller arasındaki sayısal örüntülerden nesneleri tespit etmek ve sınıflandırmaktır.

8- Large Language Models – LLM (Büyük Dil Modelleri)
Milyarlarca kelimelik devasa metinlerle eğitilmiş, insan gibi metin anlayabilen ve yazabilen gelişmiş yapay zeka modelleridir (GPT, Gemini gibi).
Cümleleri doğrudan kelime olarak değil, küçük parçalara (token) ayırıp sayılara dönüştürerek okur. Temel mantığı çok basittir. Kendisine verilen cümleye bakar ve istatistiksel olarak "bundan sonra gelmesi en muhtemel kelime hangisi?" tahminini yaparak yanıtı kelime kelime oluşturur.
Transformer ve Dikkat (Self-Attention): Cümledeki tüm kelimelerin birbiriyle bağlantısını aynı anda inceler. Bu sayede uzun paragraflarda bile konudan kopmaz, zamirlerin hangi kelimeyi işaret ettiğini unutmaz.
Eğitimi 2 Adımdır:
1.	Genel Eğitim: İnternetteki devasa yazıları okuyarak dilin yapısını ve dünya hakkındaki genel bilgileri öğrenir.
2.	İnce Ayar (Uzmanlaşma): Soru yanıtlama, özet çıkarma veya güvenli konuşma gibi belirli kuralları öğrenmesi için özel olarak eğitilir.
Büyük dil modellerinin en kritik zayıflığı halüsinasyon üretmeleridir. Bu modeller birer doğruluk veya arama motoru gibi değil, istatistiksel birer kelime tahmincisi mantığıyla çalışırlar. Bu sebeple bazen gerçekte hiç var olmayan bilgileri son derece akıcı, ikna edici ve kendinden emin bir dille uydurabilirler. Bu durum, özellikle araştırma ve karar alma gibi kritik alanlarda modellerin ürettiği verilerin mutlaka insan denetiminden geçirilmesini ve doğrulanmasını zorunlu kılar.






