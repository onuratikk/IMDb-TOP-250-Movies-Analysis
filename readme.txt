
 IMDb Film Verileri Analizi ve Görselleştirme Projesi


# Proje Açıklaması

Bu proje, IMDb film verilerini kullanarak film endüstrisiyle ilgili çeşitli analizler ve görselleştirmeler yapmayı amaçlamaktadır. Proje, film türleri, izlenme sayıları, puanlar ve filmle ilgili diğer değişkenlerin birbirleriyle olan ilişkilerini incelemektedir. Kullanılan araçlar Python ve Excel gibi güçlü veri analizi ve görselleştirme araçlarıdır. Elde edilen bulgular, film endüstrisine dair önemli bilgiler sunmayı hedeflemektedir.

# Proje Hedefi

Bu projenin amacı, IMDb film verilerini analiz ederek filmlerin başarılarını ve izlenme sayılarını etkileyen faktörleri incelemektir. Proje sonunda aşağıdaki sorulara yanıt aranmaktadır:

1. Hangi film türleri daha fazla oy almıştır?
2. Film türü ve puan dağılımı arasında ne gibi bir ilişki bulunmaktadır?
3. Yıllara göre film çekilme sayısındaki değişimler nelerdir?
4. Hangi ülkeler ne kadar IMDb Top 250 listesine film sokabilmiştir?
5. Hangi film türü Top 250 listesine ne kadar girebilmiştir?
6. Hangi yönetmenler ne kadar yorum almıştır? 


# Veri Kaynağı ve Veri Toplama

Veri, IMDb'nin geniş film veritabanından alınmıştır. Veri toplama süreci şu adımlardan oluşmuştur:

- Web Scraping: IMDb verilerini daha detaylı bir şekilde çekebilmek için web scraping teknikleri kullanılmıştır. Python’un `BeautifulSoup` ve `requests` gibi kütüphaneleri kullanılarak IMDb sayfalarından film verileri toplanmıştır.

- Veri Dönüşümü: Toplanan veriler, analiz için uygun hale getirilmiştir. Eksik veriler doldurulmuş, kategorik veriler anlamlı gruplara ayrılmış ve tarih formatları düzgün hale getirilmiştir.

Veriler, aşağıdaki parametreleri içermektedir:
- Film Türü: Aksiyon, komedi, dram, bilim kurgu gibi türler
- Bütçe ve Hasılat: Filmin yapım bütçesi ve dünya çapındaki hasılatı
- Oy Sayısı: Filmin toplam oylanma sayısı
- Puanlar: IMDb puanı ve kullanıcı yorumları
- Yönetmen ve Yazar Bilgileri: Filmle ilgili yönetmen ve yazar bilgileri
- Yıl: Filmin çekildiği yıl

# Veri Temizleme ve Düzenleme

Toplanan ham veriler, analiz öncesi birkaç aşamalı temizleme işleminden geçirilmiştir. Bu aşamalar şunları içerir:
  
- Kategorik Verilerin Düzeltilmesi: Film türleri gibi kategorik veriler, belirli bir düzene sokulmuştur. Örneğin, bazı filmler “Drama, Aksiyon” gibi birden fazla türde etiketlenmişken, bunlar yalnızca bir türe indirilmiştir.

- Veri Formatlarının Düzeltilmesi: Tarihler doğru formatta düzenlenmiş, bütçe ve hasılat verileri düzgün biçimlere getirilmiştir.

- Outlier'ların Tespiti ve Düzeltilmesi: Verilerdeki uç değerler (outlier) tespit edilmiştir. Örneğin, çok düşük bütçeli veya olağanüstü yüksek bütçeli filmler özel olarak incelenmiş ve normal olmayan değerler çıkarılmıştır.

# Analiz Aşamaları

1. Oylanma Sayısı ve Film Türü İlişkisi

Filmlerin türlerine göre oylanma sayılarındaki farklar incelenmiştir. Bu analizde, Bar Chart (Çubuk Grafik) kullanılarak her film türünün izlenme sayıları görselleştirilmiştir. Çubuk grafik, hangi türlerin daha popüler olduğunu ve daha fazla izlendiğini açıkça gösterir.

2. Yıllara Göre Film Çekilme Sayısı

Yıllara göre film üretimindeki artış veya azalış incelenmiştir. Bu analizde, Line Chart (Çizgi Grafik) kullanılarak, yıllara göre film çekilme sayısındaki değişiklikler gözlemlenmiştir.

3. Ülkelere Göre Film Çekilme Sayısı

Ülkeler bazında film çekilme sayısını görmek için World Map (Dünya Haritası) kullanılmıştır. Bu harita, film üretiminin coğrafi dağılımını gösterir.

6. Filmin Türüne Göre Puan Dağılımı

Filmlerin türlerine göre puan dağılımları Box Plot (Kutu Grafiği) ile görselleştirilmiştir. Bu grafik, her türdeki filmlerin puanlarının dağılımını gösterir.

7. Yönetmen ve Senarist İlişkisi ile İzlenme Sayısı

Yönetmen ve senarist bilgisi ile izlenme sayısı arasındaki ilişkiyi Heat Map (Isı Haritası) kullanarak görselleştirmiştir. Isı haritası, belirli yönetmenlerin ve senaristlerin filmlerinin daha yüksek izlenme sayılarına sahip olduğunu gösterir.

# Kullanılan Araçlar ve Teknolojiler

- Python: Verilerin işlenmesi, görselleştirilmesi ve ön izlemesi adımlarında Python kullanılmıştır.
- Excel: Veri düzenleme ve kategorik hale getirmek için Excel kullanılmıştır.
- Word: Proje raporunun hazırlanmasında Microsoft Word kullanılmıştır.

# Sonuçlar ve Tartışma

Elde edilen sonuçlar, film türleri, izlenme sayıları ve puanlar arasındaki ilişkilerin oldukça belirgin olduğunu ortaya koymuştur. Bu bulgular, film yapımcılarına ve endüstri profesyonellerine film üretim ve yatırım kararları konusunda yardımcı olabilir. Özellikle aksiyon, bilim kurgu ve komedi türleri daha yüksek izlenme sayıları ve daha yüksek bütçelerle ilişkilidir.

# Gelecek Çalışmalar ve Öneriler

Gelecek çalışmalar, daha fazla verinin toplanması ve daha derinlemesine analizler yapılmasını içerebilir. Ayrıca, makine öğrenmesi teknikleri kullanılarak, filmlerin başarılarını tahmin eden modeller geliştirilebilir. Verinin daha geniş bir havuzdan toplanması, modelin doğruluğunu artırabilir.

# Kaynaklar
- IMDb (TOP 250 Sayfası)
- Web Scraping Araçları (BeautifulSoup, requests)
- Python ve Excel Dökümantasyonları
