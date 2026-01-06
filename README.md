# BLM0111_24360859079
İLAYDA GÜNDOĞDU
24360859079

# Fizik Deneyleri Simülasyonu (C Programlama)

Bu proje, C programlama dili kullanılarak Güneş Sistemi gezegenleri üzerinde gerçekleştirilen çeşitli fizik deneylerinin simülasyonunu yapmak amacıyla geliştirilmiştir. Program, kullanıcıdan alınan girdiler doğrultusunda seçilen deneyleri her gezegen için ayrı ayrı hesaplayarak sonuçları birimleriyle birlikte konsol ekranına yazdırmaktadır.

Proje, temel fizik formüllerinin programlama yoluyla uygulanmasını ve C dilinde dizi, pointer, fonksiyon ve kullanıcı girişi kontrolü gibi konuların pekiştirilmesini hedeflemektedir.

## Programın Özellikleri

- Gezegenlerin yerçekimi ivmeleri bir dizi içerisinde tutulmaktadır.
- Tüm deneyler ayrı fonksiyonlar halinde tasarlanmıştır.
- Diziler üzerinde yapılan tüm işlemler pointer mantığı ile gerçekleştirilmiştir.
- Kullanıcıdan alınan fiziksel büyüklüklerin negatif girilmesi durumunda, değerler ternary operatörü kullanılarak mutlak değere dönüştürülmektedir.
- Kullanıcı, bir deney tamamlandıktan sonra tekrar deney seçimi yapabilmektedir.
- Menü ekranında `-1` seçeneği girildiğinde program güvenli bir şekilde sonlandırılmaktadır.
- Sayısal olmayan veya geçersiz menü girişleri kontrol edilmekte ve kullanıcı uyarılmaktadır.
- Deney sonuçları birimleriyle birlikte sunulmaktadır.

## Uygulamada Bulunan Deneyler

Programda aşağıdaki fizik deneyleri yer almaktadır:

1. Serbest Düşme  
2. Yukarı Atış  
3. Ağırlık Hesabı  
4. Potansiyel Enerji  
5. Hidrostatik Basınç  
6. Arşimet Kuvveti  
7. Sarkaç Periyodu  
8. İp Gerilmesi  
9. Asansörde Etki Eden Kuvvet  

Her deney:
- Kullanıcıdan gerekli fiziksel büyüklükleri alır,
- Güneş Sistemi’ndeki tüm gezegenler için hesaplama yapar,
- Sonuçları gezegen bazında alt alta ekrana yazdırır.

## Gezegen Yerçekimi İvmeleri

Gezegenlerin yerçekimi ivmeleri aşağıdaki sırayla bir dizi içerisinde saklanmaktadır:

| İndis | Gezegen  | Yerçekimi (m/s²) |
|------|---------|------------------|
| 0    | Merkür  | 3.70             |
| 1    | Venüs   | 8.87             |
| 2    | Dünya   | 9.81             |
| 3    | Mars    | 3.71             |
| 4    | Jüpiter | 24.79            |
| 5    | Satürn  | 10.44            |
| 6    | Uranüs  | 8.69             |
| 7    | Neptün  | 11.15            |
| 8    | Plüton  | 0.62             |

## Programın Çalışma Akışı

1. Program başlatıldığında kullanıcıdan bilim insanının adı istenir.
2. Deney menüsü ekrana yazdırılır.
3. Kullanıcı bir deney seçer.
4. Seçilen deneye ait fiziksel büyüklükler kullanıcıdan alınır.
5. Deney sonuçları tüm gezegenler için hesaplanarak ekrana yazdırılır.
6. Kullanıcı yeni bir deney seçebilir.
7. Menü ekranında `-1` girildiğinde program sonlandırılır.

## Kullanılan Programlama Yapıları

- Fonksiyonlar
- Diziler
- Pointer kullanımı
- Ternary operatörü
- Döngüler (`do-while`)
- Koşul yapıları (`if-else`)
- Kullanıcı girişi doğrulama (`scanf` dönüş değeri kontrolü)

## Proje Amacı
Bu projenin amacı, C programlama dili kullanılarak fiziksel problemlerin algoritmik olarak çözülmesi ve kullanıcı etkileşimli bir konsol uygulamasının geliştirilmesidir.
