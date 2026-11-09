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

## IP koruma kodlarını ürünlerde değerlendirme

Örnek: IPX4 ile IPX7, sıçrama ve geçici daldırma açısından farklı testleri anlatır. Üretici tarafından belirtilen IP kodlarını karşılaştırırken [Vibratörler](https://www.fastieshop.com/vibratorler/) kategorisindeki model açıklamalarını inceleyebilirsiniz. Bu, kategorideki her ürünün suya dayanıklı olduğu anlamına gelmez.

Daha ayrıntılı örnekler ve diğer ürün grupları için:

- [Dört kullanım örneği](docs/ornekler.md)
- [GitBook için hazırlanan Türkçe kullanım rehberi](gitbook/README.md)
- [GitBook ürün örnekleri](gitbook/docs/urun-ornekleri.md)

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
