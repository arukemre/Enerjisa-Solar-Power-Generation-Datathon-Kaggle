# arukemre-Enerjisa-Solar-Power-Generation-Datathon-Kaggle


# Dataset Description

Veri setinde 01.01.2019 – 30.11.2021 arasında Başkent bölgesinde yer alan lisanssız güneş santrallerinin saatlik bazda toplam üretim miktarları verilmiştir. Bu bölge içerisinde Ankara, Çankırı, Kırıkkale, Bartın, Karabük, Kastamonu, Zonguldak illerinde yer alan toplam 848 santral bulunmaktadır. Toplam üretime ek olarak; üretim ağırlığı Ankara ilinde olduğu için Ankara ilinin sıcaklık değişkenleri 01.01.2019 – 31.12.2021 tarih aralığında paylaşılmıştır. Sıcaklık değişkenleri 01.01.2019 - 30.11.2021 arası için gerçekleşen, 01.12.2021 - 31.12.2021 arasında tahmin verilerini içermektedir.

#### Bu santrallerin il bazında toplam sayıları ve kurulu güçleri aşağıdaki gibidir:

![image](https://user-images.githubusercontent.com/64266044/212724580-ac47aa57-cf14-4330-a6b6-ceaa68591f6d.png)



Tahmin edilmesi istenen tarih aralığı 01.12.2021 – 31.12.2021 olarak belirlenmiştir.

    |─ `generation` tablosunda:

        |─ `DateTime`: üretimin yapıldığı saat aralığını tarih-saat formatında belirtir.
        |─ `Generation`: İlgili saat aralığında yapılan toplam üretimi MWh biriminde belirtir.

    |─ `temperature` tablosunda:
      |─ `DateTime`: Sıcaklık değişkenlerinin gözlemlendiği saat aralığını belirtir.
      |─ `AirTemperature`: Saat aralığındaki hava sıcaklığını Celsius biriminde belirtir.
      |─ `ComfortTemperature`: Saat aralığındaki hissedilen hava sıcaklığını Celsius biriminde belirtir.
      |─ `RelativeHumidity`: Saat aralığındaki nem oranını belirtir.
      |─ `WindSpeed`: Saat aralığındaki rüzgar hızını km/s biriminde belirtir.
      |─ `WindDirection`: Saat aralığındaki rüzgar yönünü belirtir.
      |─ `WWCode`: Saat aralığındaki hava durumu kodunu belirtir.
      |─ `EffectiveCloudCover`: Saat aralığındaki bulutluluk oranını sekizlik ölçü birimi cinsinden belirtir.
