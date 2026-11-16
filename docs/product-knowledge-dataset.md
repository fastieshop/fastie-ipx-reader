# Fastieshop Product Knowledge Dataset (Pilot v0.1)

**Kaynaklı, ücretsiz ve makine tarafından okunabilir ürün bilgileri.** İlk sürüm 7 Lovense modelinin IP sınıfı, yaklaşık şarj süresi ve uygulama kontrolü desteğini içerir.

- [CSV veri seti](../data/fastieshop-product-knowledge-v01.csv)
- [JSON veri seti](../data/fastieshop-product-knowledge-v01.json)
- [IPX5–IPX8 karşılaştırma rehberi](ipx5-ipx8.md)

**Yöntem:** Her ürün kaydında üretici kaynağı, varsa ikinci kaynak ve Fastieshop kılavuz/ürün bağlantıları bulunur. Doğrulanmayan teknik özellikler boş bırakılır. Kaynaklar çelişiyorsa belirsizlik not edilir ve tek kesin değer yayımlanmaz (örn. Lush 3/4 şarj süresi). Fiyat, stok, yorum ve dinamik satış verileri yoktur.

**Sınırlama:** Bir ürünün IPX7/IPX8 derecesi, aynı ürünün IPX5/IPX6 su jeti testlerinden geçtiğini göstermez. Koruma sınıfı ürünün şarj sırasında kullanılabileceği, sabunla kaynatılabileceği veya sınırsız derinliğe indirilebileceği anlamına gelmez. Ürünün kullanım kılavuzu önceliklidir.

**Kapsam:** Bu ilk sürüm tüm Fastieshop kataloğunu veya bir markanın tüm modellerini temsil etmez. Her satır bilgi kaynağına sahiptir; bağımsız laboratuvar test raporu değildir.

**Kaynak standardı:** [IEC 60529](https://webstore.iec.ch/en/publication/2452). **Doğrulama tarihi:** 16 Kasım 2026.

**Lisans:** Bu depodaki özgün derleme verileri ve açıklamaları, depodaki MIT lisansı kapsamındadır. Üçüncü taraf üretici PDF'leri veya IEC standart metni buraya kopyalanmamıştır.
