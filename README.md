Rating Product & Sorting Reviews in Amazon

E-ticaretteki en önemli problemlerden biri, ürünlere satış sonrası verilen puanların doğru şekilde hesaplanmasıdır. Bu problemin çözümü, e-ticaret sitesi için daha fazla müşteri memnuniyeti sağlamak, satıcılar için ürünün öne çıkmasını ve satın alanlar için sorunsuz bir alışveriş deneyimi demektir. Bir diğer problem ise ürünlere verilen yorumların doğru bir şekilde sıralanmasıdır. Yanıltıcı yorumların öne çıkması, ürünün satışını doğrudan etkileyeceğinden hem maddi kayba hem de müşteri kaybına neden olacaktır. Bu iki temel problemin çözümünde e-ticaret sitesi ve satıcılar satışlarını artırırken, müşteriler ise satın alma yolculuğunu sorunsuz olarak tamamlayacaktır.

Veri Seti

Amazon ürün verilerini içeren bu veri seti, elektronik kategorisindeki en fazla yorum alan ürünlerin kullanıcı puanları ve yorumlarını içermektedir. Veri seti çeşitli metadataları da kapsamaktadır.

Değişkenler

- reviewerID: Kullanıcı ID’si. Yorum yapan kişinin eşsiz kimliği.
- asin: Ürün ID’si. Her ürün için eşsiz tanımlayıcı.
- reviewerName: Kullanıcı Adı. Yorum yapan kişinin adı.
- helpful: Faydalı değerlendirme derecesi. Yorumun diğer kullanıcılar tarafından ne kadar faydalı bulunduğunu gösterir.
- reviewText: Değerlendirme. Kullanıcının ürünle ilgili yazdığı yorum metni.
- overall: Ürün rating’i. Kullanıcının ürün için verdiği puan.
- summary: Değerlendirme özeti. Yorumun kısa bir özeti.
- unixReviewTime: Değerlendirme zamanı (Unix zaman damgası). Yorumun yapıldığı tarih ve zamanı belirtir.
- reviewTime: Değerlendirme zamanı (Raw). Yorumun yapıldığı tarih ve zamanı belirtir, daha okunabilir formatta.
- day_diff: Değerlendirmeden itibaren geçen gün sayısı. Yorumun yapıldığı tarihten itibaren geçen gün sayısını gösterir.
- helpful_yes: Değerlendirmenin faydalı bulunma sayısı. Diğer kullanıcılar tarafından yorumun faydalı bulunduğu sayısı.
- total_vote: Değerlendirmeye verilen oy sayısı. Toplam oy sayısını belirtir.

Proje Amacı

Bu projede, Amazon ürünlerinin kullanıcı puanları ve yorumları üzerinden analizler yapılacaktır. Hedefler şunlardır:

1. Ürün Puanlarının Hesaplanması: Ürünlerin aldığı puanları doğru bir şekilde hesaplamak ve analiz etmek.
2. Yorumların Sıralanması: Ürün yorumlarını, yorumun faydalı bulunma sayısına ve toplam oy sayısına göre sıralamak.
3. Yorum Kalitesinin Değerlendirilmesi: Yanıltıcı yorumları tespit etmek ve doğru bir sıralama algoritması geliştirmek.

Analiz Adımları

1. Veri Setinin Yüklenmesi ve İncelenmesi
   - Veri setinin yüklenmesi.
   - Verilerin genel yapısının incelenmesi.
   - Eksik veya hatalı verilerin kontrol edilmesi.

2. Puan ve Yorum Analizleri
   - Ürün puanlarının hesaplanması.
   - Yorumların faydalı bulunma ve toplam oy sayısına göre sıralanması.

3. Yorumların Sıralanması
   - Faydalı yorumları ön planda tutan bir sıralama algoritması oluşturulması.
   - Yorumların zaman damgalarına göre sıralanması.

4. Kalite Kontrolü ve Raporlama
   - Yorumların doğruluğunun ve güvenilirliğinin değerlendirilmesi.
   - Analiz sonuçlarının özetlenmesi ve görselleştirilmesi.
   - Yorum sıralama ve puan hesaplama sistemine dair önerilerin sunulması.

Katkıda Bulunma

Bu proje üzerinde geliştirme yapmak istiyorsanız, lütfen projeyi fork'layın ve pull request gönderin. Her türlü katkı kabul edilir ve projeye katkıda bulunanlara teşekkür edilir.

Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Lisans hakkında daha fazla bilgi için LICENSE dosyasına bakabilirsiniz.
