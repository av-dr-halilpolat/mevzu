# MEVZU

Sık kullanılan Türk mevzuatını tek pencerede toplayan, kendini güncelleyen
bir masaüstü programı.

**48 mevzuat · 8.691 madde** — metinlerin tamamı resmî
[Mevzuat Bilgi Sistemi](https://www.mevzuat.gov.tr/)'nden alınmıştır.

---

## Tarayıcıdan kullanmak — indirmeden

Telefon, tablet ya da başka bir bilgisayardan, hiçbir şey indirmeden:

**https://av-dr-halilpolat.github.io/mevzu/**

Telefonda tarayıcının menüsünden **"Ana Ekrana Ekle"** derseniz
uygulama gibi durur. İlk açılışta metinler bir kez iner (13 MB),
sonrasında hızlı açılır.

---

## İndirme

1. Şu bağlantıya tıklayın — her zaman en güncel sürümü indirir:
   **[MEVZU.exe indir](https://github.com/av-dr-halilpolat/mevzu/releases/latest/download/MEVZU.exe)**
2. İnen dosyaya çift tıklayın. Kurulum yok, Python ya da başka bir
   program gerekmez.

İndirdiğiniz dosyanın bozulmadığını doğrulamak isterseniz — Windows'ta
komut istemine şunu yazın, çıkan uzun numara aşağıdakiyle aynı olmalı:

```
certutil -hashfile MEVZU.exe SHA256
```

`MEVZU.exe` (sürüm 1.5) · SHA256:
`71b120fc8b208d6eb0055dcc41f13bc4f71fa002523ac1bb2d88396770bd634e`

### Windows uyarı verirse

İndirilen programlar dijital imzası yoksa Windows bir uyarı gösterir:

> **Windows bilgisayarınızı korudu** — Bilinmeyen yayımcı

**Daha fazla bilgi → Yine de çalıştır** deyin. Bu uyarı programın zararlı
olduğu anlamına gelmez; imzasız olduğu anlamına gelir.

---

## Ne yapar

- **Ağaç:** bütün mevzuat, kitap–kısım–bölüm–madde düzeniyle solda.
- **Arama:** bir kavramı bütün mevzuatta birden arar, sonuçları ait olduğu
  mevzuatın altında toplar. Yazarken kavram önerisi çıkar.
- **Tam metin ve sekmeler:** açtığınız her madde bir sekme olur.
- **Madde altındaki düğmeler:** gerekçe, değişiklik geçmişi, eski kanundaki
  karşılığı, maddenin mevzuat.gov'daki sayfası.
- **Değişiklik tabloları, cetveller, tarifeler** kaynaktaki görünümüyle.
- **Not defteri:** konu konu sayfalar; kısayol düğmeleri.
- **Ctrl+F:** açık metnin ve arayüzün içinde arama.

Bu uygulamayı yapmaktaki amacım, işlerimde sürekli kullandığım mevzuatı derli toplu bir şekilde ve hızlıca açabilmektir. 

Daha önce sürekli şekilde tarayıcıdan mevzuat.gov.tr ye girmek zorunda kalıyordum ve açılan sayfada arama yapmak zorundaydım. Bu uygulama ile internete ve tarayıcıya ihtiyaç olmadan basit, sade, hızlı, pratik ve ilgili madde veya konuya hızlı arama ile hızlıca erişim sağlamış oldum. 

Eskiden help (chm) dosyaları vardı, onlar çok kullanışlıydı. Yeni teknolojiyi kullanarak modern bir şey üretmek istedim. Ortaya bu ürün çıktı. 

Çok pratik ve kullanışlı oldu diye düşünüyorum. 

Herkese faydalı olmasını dilerim. 

Av. Dr. Halil POLAT



## Güncelleme

Mevzuat değiştiğinde program açılışta haber verir; **indir** deyince
yalnızca güncel metin dosyası iner (yaklaşık 13 MB), programın kendisi
değişmez.

Metinler geliştirici tarafından güncellenir ve **yayımlanmadan önce
denetlenir**: yeni metin kelime kelime kaynakla karşılaştırılır, tek kelime
eksik ya da fazlaysa yayımlanmaz. Böylece kimsenin ekranına yanlış
işlenmiş bir metin düşmez.

İnternet yoksa program yine çalışır; sadece güncelleme kontrolü yapılmaz.

## Verileriniz

Kavramlarınız ve notlarınız **kendi bilgisayarınızda** kalır
(`%LOCALAPPDATA%\MEVZU`). Hiçbir yere gönderilmez; program sunucuyu
yalnızca kendi bilgisayarınızda (127.0.0.1) açar, ağa kapalıdır.

Ağacın en altındaki **yedek al** bağlantısı kavramlarınızı ve notlarınızı
tek bir dosyaya kaydeder; yeni bir bilgisayarda **yedeği yükle** ile geri
alırsınız.

## Kaldırma

`MEVZU.exe` dosyasını silin. Verilerinizi de silmek isterseniz
`%LOCALAPPDATA%\MEVZU` klasörünü silin.

---

## Lisans

© Av. Dr. Halil Polat. Tüm hakları saklıdır. Ayrıntı için
[LICENSE](LICENSE) dosyasına bakınız.

Mevzuat metinleri kamuya açık kaynaktan alınmıştır; programın kendisi,
arayüzü ve metinlerin işlenme biçimi eser sahibine aittir.
