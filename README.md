Arduino Tabanlı Araç Park Sistemi Projesi Raporu

Grup üyeleri

1)Semanur Aslan
2) Ebru Karabürk 
3) Döne Sakız
4) Eda Küyük


Proje Amacı

Bu proje arduino uno, ultrasonik mesafe sensörü, LCD ekran ve LED'ler kullanarak basit bir araç park sistemi geliştirmeyi amaçlamaktadır. Sistem bir aracın park alanına ne kadar yaklaştığını ölçer ve kullanıcıya mesafeyi görsel olarak LCD ekranda gösterir. Aynı zamanda belirli mesafelere ulaşıldığında farklı renklerde LED'ler ile kullanıcıyı uyarır.


Kullanılan Malzemeler

Arduino Uno
HC-SR04 Ultrasonik Mesafe Sensörü
16x2 LCD Ekran
Kırmızı ve Yeşil LED
220 ohm direnç (LED'ler için)
Jumper kablolar
Breadboard


Devre Şeması


Devre aşağıdaki bileşenlerin doğru pinlere bağlanmasıyla oluşturulmuştur:


Ultrasonik Mesafe Sensörü:
VCC pin -> 5V
GND pin -> GND
Trig pin -> D7
Echo pin -> D6

LCD Ekran:
RS -> D12
EN -> D11
D4 -> D5
D5 -> D4
D6 -> D3
D7 -> D2

LED'ler:
Kırmızı LED Anot -> D8 (220 ohm direnç ile)
Yeşil LED Anot -> D10 (220 ohm direnç ile)
Her iki LED'in Katot'u -> GND


Sonuç Olarak 

Bu proje basit ve etkili bir araç park sistemi geliştirmek için Arduino Uno, ultrasonik sensör, LCD ekran ve Ledler kullanmıştır. Sistem kullanıcının park sırasında aracın mesafesini doğru bir şekilde ölçmesini sağlar. Proje temelde basit bileşenlerle çalışmakla birlikte genişletilebilir ve geliştirilebilir bir yapısı vardır.
