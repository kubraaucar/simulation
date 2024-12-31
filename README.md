# simulation
#####
## 1. Problem Çözümüne Genel Yaklaşım
Modelleme:
Hayvanları ve avcıyı birer nesne (class) olarak modelle.
Her nesnenin konumunu, hareket mesafesini ve cinsiyet gibi özelliklerini tut.

Hareket:
Hayvanlar ve avcı rastgele bir yöne belirli bir mesafe hareket eder.
Hareket, alanın sınırlarını aşmayacak şekilde kontrol edilir.

Etki Mesafesi ve Avlanma:
Her türün etki mesafesine göre başka hayvanlarla etkileşim kurmasını sağla (avlanma, çiftleşme).

Çiftleşme:
Aynı türden zıt cinsiyetler yakınlaştığında yeni bir hayvan eklenir.
Simülasyon Döngüsü:
Tüm bu işlemler 1000 birim hareket boyunca tekrar edilir.

Sonuç:
Simülasyon sonunda her hayvan türünün sayısını raporla.

## 2. Algoritma Yaklaşımı
Başlangıç:
Hayvanları ve avcıyı başlangıç pozisyonlarına yerleştir.
Her nesnenin özelliklerini tanımla (tür, cinsiyet, hareket mesafesi vb.).

Simülasyon Döngüsü (1000 Birim):
Her nesneyi rastgele bir yöne hareket ettir.

Etkileşimleri kontrol et:
Avlanma: Etki mesafesindeki avlanma kurallarını uygula.
Çiftleşme: Aynı türün farklı cinsiyetleri yakınsa yeni hayvan oluştur.
Her adımda hayvanların listesini güncelle.

Simülasyon sonunda her hayvan türünün sayısını hesapla ve yazdırır.


## Task:
Hayvanat Bahçesi Projesi 
500'e 500'lük bir alanda yaşayan 30 koyun (15 erkek,15 dişi), 10 inek (5 erkek,5 dişi), 
10 tavuk,10 kurt (5 dişi,5 erkek) 10 horoz, 8 aslan (4 erkek, 4 dişi) ve 1 avcı 
bulunmaktadır. 
Hayvanlardan;  
koyun 2 birim, 
kurt 3 birim, 
inek 2 birim, 
tavuk 1 birim, 
horoz 1 birim, 
aslan 4 birim, 
avcı 1 birim rasgele şekilde hareket etmektedir ancak alanın dışına çıkamamaktadır. 
kurt kendisine 4 birim yakınındaki koyun, tavuk, horoz'u avlayabiliyor.  
aslan kendisine 5 birim yakınlıktaki inek, koyun'u avlayabiliyor. 
avcı da kendisine 8 birim yakınlıktaki hayvanlardan herhangi birisini avlayabiliyor. 
aynı cins farklı cinsiyetteki hayvanlar birbirine 3 birim yakınlaştığı zaman random 
cinsiyetli ve aynı cins bir hayvan meydana gelmektedir. 
1000 birim hareket sonunda hayvanların sayısının bulunduğu bir console application 
yazılması beklenmektedir. 

