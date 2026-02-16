# n8n

## n8n Nedir?

n8n, açık kaynaklı bir iş akışı otomasyon aracıdır. Kullanıcıların farklı uygulamalar ve servisler arasında veri akışlarını görsel olarak tasarlamalarına ve otomatik hale getirmelerine olanak tanır.

## Temel Özellikler

- **Görsel İş Akışı Tasarımı**: Sürükle-bırak arayüzü ile iş akışları oluşturma
- **Geniş Entegrasyon Seçenekleri**: 350'den fazla hazır entegrasyon (CRM, e-posta, sosyal medya, veritabanları vb.)
- **Özelleştirilebilir**: Kendi özel entegrasyonlarınızı veya düğümlerinizi (nodes) oluşturma
- **Esnek Dağıtım**: Kendi sunucunuzda (self-hosted) veya n8n bulutunda kullanma
- **Güvenlik**: Veri gizliliği ve güvenlik odaklı tasarım
- **API Erişimi**: İş akışlarını programatik olarak tetikleme ve yönetme

## Kullanım Alanları

- **Müşteri İlişkileri Yönetimi (CRM)**: Yeni müşteri verilerini otomatik olarak CRM'e kaydetme
- **E-posta Otomasyonu**: Belirli koşullara göre otomatik e-posta gönderme
- **Sosyal Medya Yönetimi**: İçerik planlama ve yayınlama otomasyonu
- **Veri Entegrasyonu**: Farklı sistemler arasında veri senkronizasyonu
- **İş Süreçleri Otomasyonu**: Tekrarlayan görevleri otomatikleştirme

mongodb+srv://umu1aksoy_db_user:dhCugp5VXxC3w0Q8@cluster0.5i84hyc.mongodb.net/?appName=Cluster0

### Docker ile Kurulum

```bash
# Docker Compose ile kurulum
docker-compose up -d
```

### npm ile Kurulum

```bash
npm install -g n8n
n8n
```

## Kullanım

Kurulum tamamlandıktan sonra web arayüzünden (genellikle `http://localhost:5678`) erişebilirsiniz.

## Kaynaklar

- [n8n Resmi Web Sitesi](https://n8n.io)
- [n8n Dokümantasyonu](https://docs.n8n.io)
- [n8n GitHub](https://github.com/n8n-io/n8n)