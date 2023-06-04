<h2 align="Center">KPMG Data and Analytics Challenge 2023 Raporu</h2>

Bu repo, KPMG Data and Analytics Challenge 2023 yarışmasında yarı finalde elde ettiğim sonuçları içermektedir.

## İçindekiler
- [Yarı Final Hakkında](#yarı-final-hakkında)
    - [Kişisel Görüşlerim](#kişisel-düşünceler)
    - [Proje Yapısı](#proje-yapısı)
- [Final Hakkında](#final-hakkında)
    - [Hedefler](#hedef)
    - [Kısıtlar](#kısıtlar)
    - [Proje Yapısı](#proje-yapısı)

## Yarı Final Hakkında

Veri kümelerini inceledim ve zaman serilerini görselleştirdim. Ayrıca, görüntüleri `./KPMG Semi Final/Images/..` dizininde kaydettim.
Değişkenler arasındaki ilişkiyi de inceledim ve ilgili görüntüyü aynı dizine kaydettim.

Verilerin mevsimsel bir zaman serisi özelliği gösterdiğini gözlemledim, ancak başlangıçta regresyon analizi yapmayı tercih ettim. Bildiğiniz gibi, regresyon için öncesinde test edilmesi gereken çeşitli hipotezler bulunmaktadır.

Normal dağılım testi gerçekleştirdim:

<div align="center">

$H_0:$ Veri kümelerinin dağılımı ile normal dağılım arasında anlamlı bir fark yoktur.

</div>

Hipotez testinin sonucunda $H_0$ reddedildi ve veri kümelerinin normal bir dağılımı izlemediği belirlendi. Bu nedenle, normal dağılım varsayımı sağlanmadığından regresyon analizine devam edemedim.

Bundan sonra, ARIMA modellerini denedim, ancak uzun vadeli zaman serileri için uygun değillerdir. Ancak, sonuçlar memnuniyet verici değildi. 
Oto-ARIMA modellerini de denedim, ancak sonuçlar benzerdi.

### Kişisel Görüşler

Daha fazla zamanım olsaydı, "fbprophet" modelini denemek isterdim, çünkü geçmiş deneylerimde çok iyi başarı oranları elde etmiştim.

Ayrıca Vanilla ve Stacked LSTM derin sinir ağları denemeyi düşünüyordum, ancak ne yazık ki bunları uygulayamadım.

### Proje Yapısı

Projenin dizin yapısı aşağıdaki gibidir:

📦 Semi-Final Solution  
├───Datasets  
├───Images  
└───Notebooks  

Daha detaylı bilgi için ilgili dizinlere bakınız.

---

## Final Hakkında

<h4 align="center">DxA 2023 Case Study İleri Analitik Vaka Çalışması</h4>

Uluslararası faaliyet gösteren bir kahve dükkanları zincirinde International Franchise yöneticisi olarak markayı Türkiye pazarına sokmayı hedeflemektedir. İstanbul pilot bölge olarak seçilmiş ve mevcut bütçe ve kısıtlar göz önünde bulundurularak çeşitli lokasyonlarda kahve dükkanları açılması, müşteri segmentasyonu, müşteri sayısı, satış ve gelir tahminleri yapılması beklenmektedir. Lokasyon seçiminde hedeflenen müşteri grubu, sosyo-ekonomik ve sosyo kültürel statüler, ulaşım imkanları gibi unsurlar dikkate alınmıştır.

**a.** Bu proje için bir strateji sunumu hazırlanması beklenmektedir. Stratejiniz lokasyon seçimlerini veya seçim yaklaşımlarını, bu seçimleri değerlendirirken analize kattığınız etkenleri neden-sonuç ilişkileriyle birlikte sunmalıdır.

**b.** Tahminlediğiniz gelirin giderlerin %X'ini oluşturduğu varsayımıyla yatırımın geri dönüşü (ROI) hesaplanarak sunulmalıdır.

### Hedef 
- Lokasyon planlaması sonrası açılacak kahve dükkanlarının toplam satış gelirinin maksimize edilmesi

### Kısıtlar
- Proje yöneticisi olarak 3 Milyon TL bütçeniz bulunmaktadır.

### Proje Yapısı 

Projenin dizin yapısı aşağıdaki gibidir:

📦 Final-Solution  
├───Datasets  
│ ├───EXTERNAL  
│ ├───PROCESSED  
│ └───RAW  
├───Notebooks  
└───Sunum  

Detaylı bilgiler için ilgili dizinlere göz atabilirsiniz.

---

<p align="right"><i>Ramazan ERDURAN</i></p>
