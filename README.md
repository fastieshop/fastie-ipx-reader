# IP Koruma Kodu Okuyucu

IPX4, IPX7, IP67 ve IP68 gibi koruma kodlarının ne anlama geldiğini açıklayan, ücretsiz ve hafif bir tarayıcı eklentisi.

**Türkçe arayüz varsayılandır.** İsteyen kullanıcı İngilizceye geçebilir. Eklenti internet bağlantısı gerektirmez; tarayıcı izinleri istemez, kullanıcı verisi toplamaz, analiz servisi veya reklam kullanmaz.

## Ne işe yarar?

- IP kodunun ilk karakterini açıklayarak katı cisim ve toz korumasını gösterir.
- İkinci karakteri açıklayarak suya karşı korumayı gösterir.
- IPX4, IPX7, IP67 ve IP68 kodlarını tek tıklamayla inceletir.
- Su sıçraması, su jeti ve suya daldırma testlerinin aynı şey olmadığını belirtir.

**Önemli:** Bir IP kodu, ürünün her koşulda su geçirmez olduğu anlamına gelmez. IPX7 tek başına IPX5/IPX6 su jeti korumasını kanıtlamaz. Üreticinin ürün özelindeki kullanım ve temizlik talimatları önceliklidir.

## Kurulum ve deneme

**Chrome / Edge:** `chrome://extensions` veya `edge://extensions` adresini açın → Geliştirici modunu etkinleştirin → **Paketlenmemiş öğe yükle** → `chromium/` klasörünü seçin.

**Firefox:** `about:debugging` adresini açın → **Bu Firefox** → **Geçici eklenti yükle** → `firefox/manifest.json` dosyasını seçin.

## İnternet tarayıcısında demo

Kök dizindeki `index.html` aynı hesaplama mantığıyla çalışan, kurulum gerektirmeyen statik bir demodur. GitHub Pages açıldığında doğrudan kullanılabilir.

## IP koruma kodlarını ürünlerde değerlendirme örnekleri

Aşağıdaki örneklerde **herhangi bir ürünün belirli bir IP sınıfına sahip olduğu varsayılmıyor.** Her modelin gerçek IP sınıfını ve üretici talimatlarını kontrol edin.

### Vibratörler: IPX4 ve IPX7 arasındaki fark

IPX4, sıçrayan suya; IPX7 ise belirtilen test koşullarında geçici daldırmaya karşı korumayı tanımlar. Bu farklılıkları ürün teknik bilgilerinde incelerken [Vibratörler](https://www.fastieshop.com/vibratorler/) kategorisindeki modelleri karşılaştırabilirsiniz.

### Şarjlı Vibratörler: şarj girişleri ve koruyucu kapaklar

IP derecesi cihazın üretici tarafından tanımlanan koşulları için geçerlidir. Şarj girişi, kapak ve temizlik talimatlarını ürün bazında incelemek için [Şarjlı Vibratörler](https://www.fastieshop.com/vibratorler/sarjli-vibratorler/) kategorisinden yararlanabilirsiniz.

### Klitoral Vibratörler: temizlik ve sıçrama koruması

Bir cihazın IPX4 sınıfında olması, suya daldırılabileceği anlamına gelmez. [Klitoral Vibratörler](https://www.fastieshop.com/vibratorler/klitoral-vibratorler/) kategorisindeki ürünleri incelerken her modelin belirtilen koruma sınıfını ve bakım açıklamasını ayrı kontrol edin.

### Giyilebilir Vibratörler: ter, nem ve suya maruz kalma

Ter, su sıçraması ve suya daldırma farklı koşullardır. [Giyilebilir Vibratörler](https://www.fastieshop.com/vibratorler/giyilebilir-vibratorler/) kategorisinde ürünlerin üretici tarafından belirtilen özelliklerini karşılaştırabilirsiniz.

**Ayrıntılı rehber:** [IP koruma kodları ve dört kullanım örneği](docs/ornekler.md).

## Teknik bilgiler

- Standart referansı: **IEC 60529** — [Resmî yayın kaydı](https://webstore.iec.ch/en/publication/2452)
- Eklenti sürümü: **1.0.0**
- Çalışma şekli: Yerel, çevrimdışı; harici sunucu veya API yok
- Tarayıcılar: Chrome, Edge ve Firefox için ayrı dosyalar

## Gizlilik

Kişisel veri toplanmaz veya aktarılmaz. Ayrıntılar: [Gizlilik politikası](PRIVACY.md).

## Lisans

[MIT Lisansı](LICENSE).

## Yayıncı

Fastieshop. Eklenti, IP koruma sınıflarını anlamaya yardımcı olan bağımsız bir bilgilendirme aracıdır.
