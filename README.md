# RGBLED_LM35_RGBLED_TERMOMETRE_TASARIMI
Msp430g2553 ile LM35DZ sıcaklık sensörü ve RGB Led kullanılarak sıcaklığa göre renk veren termometre tasarımı.

MSP430G2553 Mikroişlemcisi kullanılmıştır. LM35DZ sıcaklık sensöründen alınan gerilim değeri gerekli ADC İşlemleri yapılarak sıcaklık verisine dönüştürülmüştür.
Belirlenen sıcaklık aralıklarına göre RGB Led üzerinden belirlenen sıcaklık değerine ait renk görülmektedir. 

Proje IAR Embedded Workbench programı ile gerçekleştirilmiştir. Şematik çizimi ve PCB Tasarımı Altium Designer Programı ile yapılmıştır.

Projede kullanılan malzemeler;

1 adet LM35DZ
1 adet RGB LED (ortak anot kullanılmıştır.)
2 adet 2li Header 
1 adet 10lu Entegre Soketi

Proje besleme gerilimleri;

Mikrodenetleyici 3.3v ile beslenmektedir.
LM35DZ 5V ile beslenmektedir

