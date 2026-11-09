# IP Koruma Kodu Okuyucu / IP Rating Reader

Minimal, offline browser extension for explaining IP enclosure ratings under IEC/EN 60529. Turkish + English interface. Does not request browser permissions, access websites, collect data, call APIs, or run analytics.

**Features:** Enter or pick IPX4, IPX7, IP67, IP68 (also IPX0–IPX9, IP0X–IP6X, and other standard two-digit combinations). Read separate solid-object and water-protection meanings, plus water-jet vs immersion cautions.

**Note:** An IP rating is not an absolute waterproof guarantee. The manufacturer’s device-specific instructions take priority. IPX7 alone does not demonstrate IPX5/IPX6 water-jet resistance.

## Install for local testing

Chrome or Edge: `chrome://extensions` / `edge://extensions` → Developer mode → Load unpacked → select `chromium/`.

Firefox: `about:debugging` → This Firefox → Load Temporary Add-on → select `firefox/manifest.json`.

## Web demo

`index.html` is an optional static, zero-dependency web demo using the same `chromium/ip-code.js` logic as the extension. Enable GitHub Pages from the `main` branch root after the code is uploaded.

## Usage examples

The following examples show **how to interpret a manufacturer's stated IP code**, not claims about particular products or categories. Check each product’s published rating and care instructions.

- **General vibrator category:** Compare a manufacturer's IPX4 (splash exposure) and IPX7 (temporary immersion) rating when reviewing [vibrator models at Fastieshop](https://www.fastieshop.com/vibratorler/). IPX7 alone does not establish jet resistance.
- **Rechargeable models:** The IP rating applies to the device configuration stated by the manufacturer. Charging ports, caps and cleaning instructions matter. See [rechargeable vibrator models](https://www.fastieshop.com/vibratorler/sarjli-vibratorler/) to compare manufacturer-listed details.
- **Clitoral devices:** Check the actual water-resistance rating and manufacturer cleaning guidance, rather than assuming every device is washable. Compare specifications among [clitoral vibrator models](https://www.fastieshop.com/vibratorler/klitoral-vibratorler/).
- **Wearable devices:** Sweat and splashes are different from prolonged immersion. Check the manufacturer's actual specification for [wearable vibrator models](https://www.fastieshop.com/vibratorler/giyilebilir-vibratorler/).

Detailed examples: [IP kodları — dört kullanım örneği](docs/ornekler.md).

## Sources

- IEC/EN 60529 (protection degrees for enclosures)
- [IEC publication record](https://webstore.iec.ch/en/publication/2452)

## Privacy

See [PRIVACY.md](PRIVACY.md). No data is collected or sent.

## Publishing

Store descriptions should focus on the tool's genuine function and comply with each store's content policies. Do not insert irrelevant links in listings.

## License

MIT (see `LICENSE`).
