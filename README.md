📚 University Online Library API
Bu proje, bir üniversitenin çevrim içi kütüphane sistemi için tasarlanmış **RESTful API** mimarisini tanımlar. API, öğrencilerin kitaplara erişmesini, kitapları ödünç almasını ve iade etmesini sağlayan temel işlevselliği kapsar. Proje **OpenAPI 3.1.0** standardına uygun olarak hazırlanmıştır.

🎯 Amaç
Öğrencilerin ve kütüphane personelinin aşağıdaki işlemleri yapabilmesini sağlamak:
- Kitap ekleme, listeleme, silme ve güncelleme
- Öğrenci bilgilerini yönetme
- Kitap ödünç alma ve iade süreçlerini yürütme

🧬 Ana Bileşenler
- **Books (Kitaplar)**
- **Students (Öğrenciler)**
- **Loans (Ödünç Alma)**

📡 API Belgeleme
- OpenAPI Spec Dosyası: [`openapi.yaml`](./openapi.yaml)
- JSON Schema standardı: `https://json-schema.org/draft/2020-12/schema`

💻 Geliştirme Ortamı
- **OpenAPI Sürümü:** 3.1.0
- **JSON Schema Uyumu:** Draft 2020-12
- **Geliştirme Aracı:** Swagger Editor, Redocly CLI

✅ Test Süreci
Testler Swagger, Postman veya benzeri araçlarla manuel olarak yapılabilir. Otomatik testler kapsam dışıdır.

🧰 Kurulum ve Kullanım

`openapi.yaml` dosyasını Swagger Editor'da açın:
   [https://editor.swagger.io](https://editor.swagger.io)

📂 Dosya Yapısı
```bash
/
├── openapi.yaml       # OpenAPI tanımı
├── README.md          # Proje açıklaması
└── DELIVERY.md        # Teslim raporu
