# Derin-Diver
##Degz Robotics Suibo uyumlu İnsansız Su Altı Aracı kontrol yazılımı

Derin Diver, Degz Robotics Suibo Kontrol kartı üzerinde çalışmak üzere tasarlanmış olan bir İnsansız Su Altı Aracı kontrol yazılımıdır. 

## Özellikler

- 6 ve 8 motorlu araçlar için kullanıma uygun. (Farklı motor konfigürasyonlarına destek yakın zamanda gelecektir.)
- Açı ölçer, ivme ölçer ve pusula sensörleri ile 9 Eksen stabilizasyon.
- [Degz Robotics D300 Derinlik Sensörü ile](https://degzrobotics.com/product/derinlik-ve-sicaklik-sensoru/) derinlik ve su sıcaklığı ölçümü.
- Anlık voltaj ve akım ölçümü.
- State Machine sistemi ile Manual, Stabilize, Depth Hold, Loiter(eklenecek) dalış modları.
- Kolayca ayarlanabilir PID kontrolü.
- Tüm ayarlara kolayca erişebileceğiniz Parameter Sistemi
- Log sistemi
- Modern ve kolay kullanılabilen Dive Control Arayüzü ile uyumlu
- Kolayca otonom komutları yollayabileceğiniz Dive Commander otopilot kütüphanesi ile uyumlu
- Degz Rolicam ile çalışmaya hazır.

### Kartınızı verimli kullanabilmek için CH340 driverini kurmanız gerekmektedir.

## Derin Diver Kurulumu

1. En son yayınlanmış sürüme gidip UF2 dosyasını indirin [Releases](https://github.com/degzrobotics/Derin-Diver/releases/tag/latest).
2. Degz Robotics Suibo kartını bootloader moduna alın. BOOT tuşuna basılı tutarak USB ile bilgisayara bağlayabilirsiniz veya kart halihazırda bağlıysa, BOOT ve RESET tuşlarına aynı anda basıp ilk başta reset tuşundan elinizi kaldırıp ardından boot tuşundan elinizi kaldırarak da bootloader moduna girebilirsiniz.
3. İndirdiğiniz UF2 dosyasını bilgisayarınızın tanıyacağı RPI-RP2 adlı sürücüye kopyalayın. Kopyalama işlemi bittikten sonra sürücü kaybolacaktır ve Derin Diver yazılımını başarıyla yüklemiş olacaksınız.
4. Kurulumun başarıyla tamamlandığından emin olmak için kartınızı USB ile bilgisayara bağladıktan sonra Arduino vb Serial Port okuyabilen bir programla kartın bağlı olduğu COM portunu açtığınızda yazılımın açılış mesajlarını görebilirsiniz. Hiçbir mesaj görmüyorsanız RESET tuşuna basıp kartı yeniden başlatabilirsiniz.

## Problemleri Nasıl Bildirebilirim?

1. [Issues](https://github.com/degzrobotics/Derin-Diver/issues) sekmesine git.
2. New Issue butonuna tıkla
3. Issue veya Request seçeneğinden birisini seç
4. Formu doldur ve Submit'e tıkla
