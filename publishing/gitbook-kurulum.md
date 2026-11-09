# GitBook yayını için kurulum

Bu depoda GitBook içeriği `gitbook/` altında, yapılandırma `.gitbook.yaml` içindedir.

1. [GitBook](https://app.gitbook.com/) hesabına girin.
2. Fastie Ölçek'in mevcut GitBook alanına dokunmadan **yeni bir doküman alanı (space)** oluşturun. Ad: **IP Koruma Kodu Okuyucu**.
3. **Set up Git Sync / GitHub** bölümünü açın.
4. Depo olarak `fastieshop/fastie-ipx-reader`, dal olarak `main` seçin. GitBook'un ilgili depoya erişimi yoksa GitHub uygulamasına **yalnız bu depo** için erişim verin.
5. İlk senkronizasyon yönünü **GitHub → GitBook** seçin. **GitBook → GitHub seçmeyin**: repo içeriğinin üstüne boş bir alan yazılmasını önlemek için.
6. İçe aktarılan navigasyonu (Başlangıç, IP kodu, Örnekler, SSS, Gizlilik) önizleyin.
7. **Publish / Publish to web** üzerinden yayımlayın. GitBook site adresini kontrol edin.
8. [Ürünlerde IP kodu: dört örnek] sayfasındaki dört kategori URL'sinin doğru açıldığını kontrol edin.

Mevcut Fastie Ölçek GitBook'u bağımsız kalmalıdır. GitBook bağlantısı kurulduktan sonra GitHub'daki Markdown dosyaları yeni GitBook alanına senkronize edilir.

Resmî rehber: https://gitbook.com/docs/guides/editing-and-publishing-documentation/import-or-migrate-your-content-to-gitbook-with-git-sync
