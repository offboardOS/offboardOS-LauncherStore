# OffboardOS

OffboardOS, Ubuntu tabanlı işletim sistemlerini çalıştıran geliştirme kartları için özel olarak tasarlanmış bir işletim sistemidir. Bu sistem, robotik uygulamalar için çeşitli kontrolcüler ve sürücüler gibi launcher'ları yönetmek amacıyla Docker tabanlı LauncherStore kullanır.

## İçindekiler

- [OffboardOS](#offboardos)
  - [İçindekiler](#i̇çindekiler)
  - [Özellikler](#özellikler)
  - [Kurulum](#kurulum)
    - [Gereksinimler](#gereksinimler)
    - [Adımlar](#adımlar)
  - [Kullanım](#kullanım)
  - [LauncherStore](#launcherstore)
    - [Örnek Launcher'lar](#örnek-launcherlar)
  - [Katkıda Bulunma](#katkıda-bulunma)
  - [Lisans](#lisans)

## Özellikler

- Ubuntu tabanlı güvenilir işletim sistemi
- Docker ile kolay entegrasyon ve izolasyon
- LauncherStore ile genişletilebilir ve modüler yapı
- Robotik uygulamalar için optimize edilmiş kontrolcüler ve sürücüler
- Grafana ile gelişmiş izleme ve analiz
- HAProxy ile yük dengeleme
- Kullanıcı dostu ve kolay kurulum

## Kurulum

### Gereksinimler

- Geliştirme kartları (UP2 (amd64), Jetson Boards, Raspberry Pi, BeagleBone, vb.)
- SD Kart (en az 8GB önerilir)
- İnternet bağlantısı

### Adımlar

1. OffboardOS imaj dosyasını indirin.
2. İmaj dosyasını SD karta yazdırın.
3. SD kartı geliştirme kartınıza takın ve kartınızı başlatın.
4. İlk başlatma sırasında kurulum sihirbazını takip edin.

## Kullanım

OffboardOS yüklendikten sonra, sistem otomatik olarak başlatılacaktır. Sistemi ilk kurduğunuzda, temel yapılandırma ve ağ ayarlarını yapmanız gerekecektir. Ardından, Docker tabanlı LauncherStore'dan gerekli launcher'ları indirip kurabilirsiniz.

## LauncherStore

LauncherStore, çeşitli türlerde kontrolcüler ve sürücüler gibi robotik uygulamalar için gereken yazılımları barındıran Docker tabanlı bir platformdur. Bu platform, kullanıcıların kolayca launcher arayıp yüklemesini sağlar.

### Örnek Launcher'lar

- **MotorController**: Motor sürücülerini kontrol etmek için kullanılır.
- **SensorReader**: Sensör verilerini toplar ve işler.
- **CameraStream**: Kamera görüntülerini işler ve aktarır.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını okuyun ve yönergeleri takip edin. Her türlü katkı, hata bildirimi ve öneri memnuniyetle karşılanır.

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.
