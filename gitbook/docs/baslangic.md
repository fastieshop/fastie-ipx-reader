---
description: IP Koruma Kodu Okuyucu eklentisini tarayıcıda açma, kod girme ve sonuçları yorumlama adımları.
---

# Başlangıç ve kullanım

## Eklentiyi test ederek kurma

Eklenti henüz mağazalarda yayımlanmadan önce kaynak kodlarından yüklenebilir.

**Chrome veya Edge**

1. [GitHub kaynak deposunu](https://github.com/fastieshop/fastie-ipx-reader) açın ve kodları indirin.
2. Chrome için `chrome://extensions`, Edge için `edge://extensions` adresini açın.
3. **Geliştirici modu** seçeneğini etkinleştirin.
4. **Paketlenmemiş öğe yükle** seçeneğinden `chromium` klasörünü seçin.
5. Araç çubuğundaki eklentiler menüsünden **IP Koruma Kodu Okuyucu** simgesine tıklayın.

**Firefox**

1. `about:debugging` adresini açın, **Bu Firefox** bölümüne geçin.
2. **Geçici eklenti yükle** seçeneğinde `firefox/manifest.json` dosyasını seçin.
3. Eklenti simgesine tıklayarak pencereyi açın.

Firefox'un geçici eklentileri tarayıcı yeniden başlatıldığında kaldırılabilir.

## IP kodunu açıklama

1. Giriş alanına `IPX4`, `IPX7`, `IP67` veya `IP68` gibi bir kod yazın.
2. **Açıkla** düğmesine basın veya Enter tuşunu kullanın.
3. **Toz ve katı cisimler** ile **Suya karşı koruma** açıklamalarını ayrı okuyun.
4. Gösterilen uyarıyı üreticinin ürün talimatlarıyla birlikte değerlendirin.

Örneğin `IP67` kodunda **6**, toz korumasını; **7**, geçici daldırma testini ifade eder. `IPX7` kodundaki **X**, toz koruması için bir sınıf belirtilmediği anlamındadır; korumanın hiç olmadığı anlamına gelmez.

## Dil

Pencerenin sağ üstündeki **EN / TR** düğmesinden dili değiştirebilirsiniz.

## Sonraki adım

[IP kodunun ayrıntılarını öğrenin](ip-kodu-nasil-okunur.md).
