--calculate_average--

Boş Liste Gelince 0 Döndürmek Doğru Mudur?

Boş bir liste geldiğinde 0 döndürmek doğru değildir. Çünkü boş bir kümenin ortalaması matematiksel olarak tanımsızdır (sıfıra bölme hatası verir) ve 0 döndürmek bir veri eksikliği ya da hata durumunu başarılıymış gibi göstererek sessiz bir hataya yol açar.

Ortalaması 0 Olan Bir Listeden Nasıl Ayırt Edilir?

[-1, 1] veya [0, 0] gibi bir listenin ortalaması gerçekten sıfırdır. Boş liste için de 0 döndürülmesi kullanıcının listenin boş mu olduğunu yoksa ortalamanın gerçekten sıfır mı çıktığını ayırt etmesini engellediğinden, bu belirsizliği önlemek için ya bir hata fırlatılmalı ya da None değeri döndürülmelidir.
Fonksiyon Tuple (1, 2, 3) Aldığında Ne Olur?
Fonksiyon yalnızca sum() ve len() fonksiyonlarını kullanıyorsa (1, 2, 3) gibi bir tuple ile de sorunsuz çalışarak 2.0 sonucunu üretir. Çünkü Python'da önemli olan verinin mutlaka liste olması değil, toplanabilir ve uzunluğu ölçülebilir bir dizi olmasıdır, bu nedenle fonksiyonu yalnızca listelerle sınırlandırmayıp demet gibi benzer veri tiplerine de açık bırakmak doğru bir yaklaşımdır.


Kod Örneği:
<img width="1044" height="684" alt="Ekran Görüntüsü (659)" src="https://github.com/user-attachments/assets/2e29941e-36ab-48e8-aa3c-3102dba2567a" />
