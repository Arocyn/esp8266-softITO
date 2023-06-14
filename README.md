# esp8266-softITO
Arduino IDE'yi açıp Preferinces>Settings>Addiitional board manager URLs kısmına giriyoruz
bu kısımdan yandaki simgeye tıklayıp iki linki oraya yapıştırıyoruz. 

http://arduino.esp8266.com/stable/package_esp8266com_index.json

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Ardından Board Manager kısmına gidip ESP32 ve ESP8266 yazıp çıkan şeyleri indiriyoruz. 
Bu işlem uzun sürecektir. 

Ardından Arduino idemizi kapatıp tekrar açıyoruz Port kısmından uygun portu seçip
NodeMCU 1.0 ESP-12E olan cihazı seçiyoruz. 


Setup kısmında pinlerin ayarları haberleşme vs gibi şeyleri ekleriz.
Loop kısmına main kodumuzu yazarız ve bu kod orada sonsuz döngüde çalışır. 

Serial monitorden seçeceğimiz baud değeri
115200 baud a kadar destekliyor cihazımız

ödev
serialden girdiğimiz rakam kadar 1s yanacak 1s sönecek işlem başlıyo yazacak bitince tekrar sayı giriniz diyecek
