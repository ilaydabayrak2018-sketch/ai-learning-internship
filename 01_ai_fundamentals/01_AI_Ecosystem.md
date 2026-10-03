ÖĞRENİLECEK KONULAR

1- Artificial Intelligence (AI)
Karmaşık görevleri çözebilen, insan dışı program veya modellerdir (çeviri sistemleri, tıbbi tanı modelleri vb.).
Dört temel odakta şekillenir: Veriden tahmin üreten geleneksel modeller (Tahminleyici Modeller-ML), karmaşık örüntüleri çözen derin sinir ağları (Derin Öğrenme- Deep Learning), yeni ve özgün içerik üreten üretken modeller (GenAI/LLM) ve sistemlerin adil, şeffaf, güvenilir ve etikliğini sağlayan sorumlu yapay zeka ilkeleri.

2- Machine Learning (Makine Öğrenimi):
Geleneksel kural tabanlı yazılımların aksine, veriden ve doğru yanıtlardan istatistiksel yöntemlerle otomatik öğrenme sürecidir.
Çalışma Döngüsü: Modelin ürettiği tahmin ile gerçek değer arasındaki fark Kayıp Fonksiyonu (Loss Function) ile ölçülür. Bu hata payı, Gradyan İnişi (Gradient Descent) algoritması ve belirlenen Öğrenme Oranı (Learning Rate) doğrultusunda model ağırlıklarının geriye doğru güncellenmesiyle hata en aza indirilir. 
Temelde regresyon (sayısal değer tahmini) ve sınıflandırma (veriyi kategorilere ayırma / olasılık hesaplama) gibi problem alanlarına odaklanır

3- Deep Learning (Derin Öğrenme) 
Çok katmanlı Yapay Sinir Ağlarını (ANN) kullanan makine öğrenmesi alt dalıdır. Klasik modellerin aksine ham verideki (görsel, ses, metin) özellikleri insan müdahalesine gerek kalmadan girdi, gizli ve çıktı katmanları boyunca kendi kendine öğrenir. Öğrenme süreci; girdinin tahmine dönüştüğü ileri yayılım (forward) ve hesaplanan hata doğrultusunda ağırlıkların optimize edildiği geriye yayılım (backpropagation) adımlarıyla gerçekleşir.

4- Data Science (Veri Bilimi)
Ham veriyi temizleyip modellerin işleyebileceği matematiksel formata sokma sürecidir (Çöp girerse, çöp çıkar). Farklı büyüklükteki sayıları ölçeklendirerek (scaling) dengeler, sözel verileri kodlayarak (encoding) sayılara çevirir ve değişkenleri birleştirerek yeni özellikler (feature crossing) türetir. Modelin ezberlemesini (overfitting) önlemek için veriyi Eğitim (%70-80), Doğrulama (%10-15) ve Test (%10-15) kümelerine ayırır ve uç değerleri temizleyip veri dengesini sağlayarak modelin taraflı (bias) kararlar vermesini engeller.

5- Generative AI (Üretken Yapay Zeka)
Mevcut verilerden öğrendiği örüntülerle özgün metin, görsel, ses ve kod gibi yeni içerikler üreten teknolojidir. Geleneksel yapay zekanın tahmin ve sınıflandırma odaklı yapısından farklı olarak doğrudan yaratım sürecine odaklanır. Bünyesindeki Doğal Dil İşleme (NLP) ve Doğal Dil Üretimi (NLG) yeteneklerini birleştiren Büyük Dil Modelleri (LLM) sayesinde özetleme, çeviri ve içerik üretimini üst seviyeye taşır.

6- Natural Language Processing – NLP (Doğal Dil İşleme) 
Bilgisayarların insan dilini anlamasını, analiz etmesini ve üretmesini sağlayan yapay zeka dalıdır. Metinleri anlam ilişkilerini koruyarak matematiksel vektörlere dönüştürmeyi amaçlar. Metin sınıflandırma, bilgi getirme, otomatik çeviri ile metin üretimi gibi alanlarda kullanılır. Süreç, metinlerin parçalanması (Tokenization) ve anlam yüklü matematiksel vektörlere dönüştürülmesiyle (Embeddings) başlar. Günümüzde Transformer ve Dikkat (Self-Attention) mimarisi sayesinde tüm kelimeler arası ilişki eşzamanlı incelenerek uzun metinlerde bağlam kaybını önler.

7- Computer Vision 
Bilgisayarlara görsel ve videoları anlamlandırma yeteneği kazandıran alandır. Görseller, bilgisayar için piksellerden (RGB) oluşan sayısal matrislerdir (siyah-beyazda tek katman, renklide 3 kanallı RGB).
Ham pikseller, boyutu düşürmek ve örüntüleri yakalamak amacıyla matematiksel gömme vektörlerine (embeddings) çevrilir. Model çıktısında; tek sınıflı tahminler için olasılıkları 1'e tamamlayan Softmax, çoklu etiketlemeler için bağımsız olasılıklar üreten Sigmoid fonksiyonu kullanılarak pikseller arasındaki sayısal örüntülerden nesneler tespit edilir ve sınıflandırılır.

8- Large Language Models – LLM (Büyük Dil Modelleri)
Devasa metin verileriyle eğitilerek insan benzeri içerik anlama ve üretme yeteneği kazanan gelişmiş modellerdir (GPT, Gemini vb.). Metinleri parçalara (token) ayırıp sayısal verilere dönüştürür ve istatistiksel olarak sıradaki en muhtemel kelimeyi tahmin ederek yanıt üretir.
Transformer ve Self-Attention mimarisi sayesinde tüm kelimeler arası anlamsal ilişkiyi eşzamanlı hesaplayarak uzun metinlerde bağlamı korur. Süreç, genel dil yapısının kavrandığı ön eğitim ve belirli görevlere odaklanan ince ayar aşamalarından oluşur. Birer doğruluk motoru değil olasılık temelli sistemler olduklarından, gerçeğe aykırı bilgileri ikna edici dille üretme (halüsinasyon) riski taşırlar ve bu kritik zayıflık çıktıların insan denetiminden geçirilmesini zorunlu kılar.

-----------------------------------------------------------------------------------------------------------------
KONTROL SORUSU
Machine Learning (ML) ile Generative AI (GenAI) Aynı Şey Midir?
Machine Learning ve Generative AI aynı şey değildir. Aralarında bir üst küme alt küme ilişkisi vardır. Machine Learning (ML) verilerden örüntüler öğrenerek tahmin, karar verme veya sınıflandırma süreçlerini yönetir. Generative AI (GenAI) ise Machine Learning (ML)  mantığını kullanarak öğrendiği örüntülerden yola çıkarak tamamen yeni ve özgün içerikler üretir. 
Örneğin Yazılan bir kod bloğunu inceleyip içinde güvenlik açığı veya hata olup olmadığını tespit etmek Machine Learning görevidir. Verilen bir tanıma veya ihtiyaca göre o kod bloğunu sıfırdan yazmak ya da optimize etmek Generative AI görevidir. 


Deep Learning (DL) Bu Yapının Neresindedir?
Machine Learning (ML) çatısı altında yer alan Deep Learning, bu yapının tam merkezindedir. Karar ağaçları gibi basit istatistiksel yöntemlerin aksine çok katmanlı yapay sinir ağları sayesinde pikseller, ses dalgaları ve metinler gibi ham verilerdeki karmaşık örüntüleri insan müdahalesine gerek kalmadan kendi kendine çözer. Generative AI ise doğrudan bu mimari üzerine inşa edilmiştir ve görsel üreten modeller ve LLM'ler güçlerini derin sinir ağlarından alır. Kısacası ML genel çerçeveyi, Deep Learning bu verileri işleyen çekirdek motoru, Generative AI ise bu motorun ürettiği özgün çıktıları temsil eder.
Örneğin; Machine Learning bir fotoğraftaki canlının kedi mi köpek mi olduğunu sınıflandırır. Deep Learning, kedinin kulak, bıyık ve tüy yapısı gibi piksel düzeyindeki karmaşık örüntülerini kendi kendine çözer. Generative AI ise öğrenilen bu kedi temsilini kullanarak dünyada hiç var olmamış özgün bir içerik üretir. Örneğin "uzayda uçan şapkalı bir kedi" resmi çizer. 

-----------------------------------------------------------------------------------------------------------------
KAVRAM HARİTASI
<img width="1024" height="768" alt="kavram_haritasi png" src="https://github.com/user-attachments/assets/7af497fd-b271-435b-8e0a-249cfba1cc8b" />

KAVRAM HARİTASI AÇIKLAMASI 
Artificial Intelligence (AI): İnsan aklını ve problem çözme yeteneğini taklit ederek karmaşık görevleri başarmak için tasarlanan tüm sistemlerin en üst disiplinidir.
Machine Learning (ML): Kuralları tek tek elle kodlamak yerine, sisteme veri verip o verideki matematiksel örüntüleri kendi kendine keşfetmesini sağlayan AI alt dalıdır.
Deep Learning (DL): İnsan beynindeki nöron ağlarından esinlenen, çok sayıda gizli katmana sahip yapay sinir ağlarıyla ham veriden (ses, piksel, metin) doğrudan öğrenen ML yöntemidir.
Natural Language Processing (NLP): Bilgisayarların insan dilini anlayabilmesi, anlamını kaybetmeden sayılara dökebilmesi ve metin üretebilmesi için çalışan alandır.
Computer Vision: Bilgisayarların fotoğrafları ve videoları sayılardan oluşan piksel tabloları olarak okuyup içindeki nesneleri tanımasını ve sınıflandırmasını sağlayan teknolojidir.
Generative AI (GenAI): Verileri yalnızca sınıflandırmak veya filtrelemek yerine, öğrendiği kalıpları kullanarak sıfırdan tamamen yeni metin, görsel, ses ya da kod üreten güncel yapay zeka alanıdır.
