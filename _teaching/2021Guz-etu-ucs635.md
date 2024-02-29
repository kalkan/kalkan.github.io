---
title: "Eskişehir Teknik Üniversitesi - Uydu Görüntü İşleme UCS635 (Arşiv) - 2021"
collection: teaching
type: "Ph.D. course"
permalink: /teaching/2021Guz-etu-ucs635
venue: "Eskişehir Teknik Üniversitesi"
date: 04-10-2021
location: "Ekişehir, Türkiye"
---

Eskişehir Teknik Üniversitesi, Yer ve Uzay Bilimleri Enstitüsü, Uzaktan Algılama ve Coğrafi Bilgi Sistemleri Doktora Programı UCS635 Uydu Görüntü İşleme dersi ile ilgili bilgilerin paylaşılacağı sayfadır.

> Derslerimiz **Salı günleri Saat 19:00'** da size iletilecek Voov Meeting linki üzerinden yürütülecektir.

* Ders ile ilgili bilgilerin özetlendiği [ders bilgi formunu](http://kalkan.github.io/files/ucs635-2019/UCS635_2019_UyduGoruntuIsleme_KaanKalkan.pdf) incelemeyi unutmayınız.

* Derse kayıt olduktan sonra [öğrenci bilgi formunu](https://goo.gl/forms/nQR3TQm4LoK9DMDJ3) doldurmayı unutmayınız.

> Bilgisayarınıza aşağıdaki açık kaynaklı programları kurmanızı öneririm;
* [Monteverdi Orfeo Toolbox](https://www.orfeo-toolbox.org/download/)
* [SNAP](https://step.esa.int/main/download/snap-download/)
* [QGIS](https://qgis.org/en/site/forusers/download.html)

> Aşağıdaki web sayfalarına üye olmanızı öneririm;
* [USGS Earth Explorer](https://earthexplorer.usgs.gov/)
* [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/home)
* [www.gezgin.gov.tr](www.gezgin.gov.tr)

# Ödevler
------
> **1. ödev** ile ilgili bilgileri [linkte](http://kalkan.github.io/files/ucs635-2021/odev1-2021.pdf) bulabilirsiniz. 
* Ödevin son teslim tarihi: 5 Kasım 2021 Saat 23:00 
* Ödevin yılsonu notuna katkısı %30'dir.
* Ödevde kullanılacak OTB yazılımı linkten indirilebilir. [Monteverdi Orfeo Toolbox](https://www.orfeo-toolbox.org/download/)
* Ödevler Mergen sistemi üzerinden toplanacaktır. https://mergen.anadolu.edu.tr/courses/58323

> **2. ödev** ile ilgili bilgileri [linkte](http://kalkan.github.io/files/ucs635-2021/odev2-2021.pdf) bulabilirsiniz. 
* Ödevin son teslim tarihi: 5 Aralık 2021 Saat 23:00 
* Ödevin yılsonu notuna katkısı %20'dir.
* Ödevde kullanılacak SNAP yazılımı linkten indirilebilir. [SNAP](https://step.esa.int/main/download/snap-download/)
* Ödevler Mergen sistemi üzerinden toplanacaktır. https://mergen.anadolu.edu.tr/courses/58323

Dönem Projesi
------
> **Proje ödevi** ile ilgili bilgileri [linkte](http://kalkan.github.io/files/ucs635-2021/donemprojesi.pdf) bulabilirsiniz. 
* [Yayın şablonu](http://kalkan.github.io/files/ucs635-2019/UZAL_CBS_2018_bildiri_formati.docx)
* Ödevin son teslim tarihi 27 Ocak 2022 Saat 23:00 
* Ödevin yılsonu notuna katkısı %50'dur.

# Ders İçeriği
------
## Uzaktan Algılama’ya Giriş
* Uydular ve Yer Gözlem
* Tarihçe
  * https://www.unoosa.org/oosa/en/timeline/index.html
  * https://www.tua.gov.tr/en/our-space-history
* Türkiye ve Uzay
* Uzaktan Algılama'daki 7 İşlem
  * https://www.ncfc.gov.in/publications/p1.pdf
* Platformlar
* Yörüngeler
  * http://www.dspmuranchi.ac.in/pdf/Blog/REMOTE%20SENSING%20SATELLITES%20AND%20ITS%20ORBITS.pdf
  * https://www.youtube.com/watch?v=8KL2s2Ib4Q4
  * https://www.n2yo.com/satellite/?s=39030
* Sensörler
  * https://www.youtube.com/watch?v=c-JURgkLAW4
  * https://up42.com/blog/tech/a-definitive-guide-to-buying-and-using-satellite-imagery
* Enerji Kaynakları, Atmosfer ve Yüzey ile Etkileşim

## Uydu Görüntü İşleme’de Temel Kavramlar
* Piksel, Bant
  * https://www.youtube.com/watch?v=15aqFQQVBWU
* Çok bantlı görüntüler
* Görüntü oluşrturma prensipleri
* Histogram
* Mekansal, Radyometrik, Spektral, Zamansal Çözünürlü Kavramları
* Yer Örnekleme Aralığı
* Ölçek vs Piksel Boyutu
* Çözünürlük ve Öznitelik Çıkarımı

## Ön-İşleme (Pre-processing)
* Ön-İşleme Nedir?
* Görüntü Ön-İşleme Seviyeleri
* Radyometrik Düzeltme
* MTF, GIQE, SNR
* Atmosferik Düzeltme
* Radyans, Reflektans, Parlaklık Sıcaklığı
* BRDF
* MODTRAN, 6S
* Tuz Gölü
* Geometrik Düzeltme
* Rektifikasyon
* Orto-rektifikasyon
* Stereo

## Ön-İşleme -2  (Pre-processing)
* Coğrafi Referanslama
* Rektifikasyon
* Ortorektifikasyon
* Pankeskinleştirme
* Renk iyileştirme
* Keskinlik arttırma
* Stereo görüntüler
* Mozaik görüntüler
* Bant çakıştırma

## Geometrik Düzeltme
* Neden Geometrik Düzeltme?
* Geometrik Distorsiyonlar
* Rektifikasyon
* Ortorektifikasyon
* Yeniden Örnekleme
* Geo-coding, geo-referencing, rectification

## Uydu Görüntü Yorumlama Teknikleri (Image Interpretation)
* Tarihçe
* Renk-Ton
* Şekil
* Boyut
* Gölge
* Yükseklik-Derinlik
* Texture-yüzey
* Pattern-doku
* Komşuluk / site-situation-association
* Örnek görüntüler ve tahmin oyunu

## Uydu Görüntü Sınıflandırma
* Sınıflandırma yöntemleri
* Sınıflandırma şemaları
* Segmentasyon
* Semantik segmentasyon
* İleri seviye görüntü işleme, Derin Öğrenme
* Doğruluk analizi

## Sayısal Yükseklik Modelleri
* DEM, DSM, DTM
* LIDAR
* SRTM
* Stereo / tristereo
* inSAR
* Point cloud generation
* Klasik haritacılık yöntemleri
* Eğim, Bakı, Eşyükselti eğrileri, Gölgeli kabartma, Görünürlük, Kazı-dolgu


