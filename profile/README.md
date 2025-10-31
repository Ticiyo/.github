# 🛍️ Ticiyo

**Ticiyo**, .NET Core teknolojisiyle geliştirilmiş, modern ve ölçeklenebilir bir **B2C Saas platformudur**.  
Proje, monolith mimari yapısını koruyarak sade, yönetilebilir ve genişletilebilir bir çözüm sunar.

---

## 🚀 Özellikler

- 🧩 **Modüler yapı** — Katmanlı mimari, domain bazlı ayrımlar
- 🛒 **Ürün yönetimi** — Listeleme, filtreleme, detay, stok yönetimi
- 💳 **Ödeme altyapısı** — Çoklu ödeme sağlayıcısı desteği
- 🏪 **Pazaryeri entegrasyonu** — Dış API’ler ile ürün senkronizasyonu
- 🔍 **Akıllı arama ve filtreleme**
- ⚡ **Performans odaklı yapı** — Lazy loading, caching, async işlemler
- 🌐 **SSO (Single Sign-On)** altyapısı (OpenIddict ile)

---

## 🧱 Teknolojiler

- **Backend:** ASP.NET Core 9, ABP Framework
- **Frontend:** ASP.NET Core 9 Razor Pages
- **Database:** PostgreSQL
- **Authentication:** OpenIddict (SSO)
- **Infrastructure:** EF Core, AutoMapper, MediatR

---

## 🧭 Mimari

Ticiyo, monolith mimari altında modüler bir şekilde kurgulanmıştır.  
Her modül (örneğin *Product*, *Order*, *Payment*) kendi domain mantığını içerir, böylece yönetilebilirlik ve test edilebilirlik artırılmış olur.

---

## 📦 Kurulum

```bash
git clone https://github.com/kullaniciadi/ticiyo.git
cd ticiyo
dotnet restore
dotnet run
