# 🛍️ Ticiyo — Dijital Satışın Yeni Adresi


**Ticiyo**, küçük ve orta ölçekli işletmelerin online satış yapmasını kolaylaştırmak için geliştirilen, modern ve açık kaynaklı bir **B2C Saas platformudur.**.  
Tamamen **.NET Core** üzerinde inşa edilmiştir ve  kendi gücünü kullanarak modüler, güvenli ve genişletilebilir bir altyapı sunar.

---

## 🚀 Vizyonumuz

Ticiyo’nun hedefi, her ölçekten satıcının kendi markası altında profesyonel bir çevrimiçi mağaza kurmasını mümkün kılmaktır.  
Basit kurulum, güçlü yönetim paneli ve ölçeklenebilir altyapısı sayesinde işletmelerin **teknik detaylara takılmadan satışa odaklanmasını** sağlar.

---

## ✨ Öne Çıkan Özellikler

- 🧩 **Modüler mimari** — Güçlü katmanlı yapı  
- 🛒 **Ürün yönetimi** — Listeleme, varyant, stok ve fiyat kontrolü  
- 💳 **Ödeme altyapısı** — Çoklu ödeme sağlayıcı entegrasyonu  
- 🌐 **Pazaryeri entegrasyonu** — Trendyol, Hepsiburada, Çiçeksepeti vb. ile senkronizasyon  
- 🔍 **Gelişmiş filtreleme ve arama**  
- 👥 **SSO (Single Sign-On)** — OpenIddict ile kullanıcı yönetimi  
- ⚙️ **Yönetim paneli** — Sipariş, ürün, kullanıcı ve ayar yönetimi  
- 💬 **Gerçek zamanlı bildirimler** (SignalR)  

---

## 🧱 Teknolojiler

| Katman | Teknoloji |
|--------|------------|
| Backend | ASP.NET Core 9, EF Core |
| Frontend | ASP.NET Core 9 Razor Pages, Bootstrap |
| Authentication | OpenIddict (SSO) |
| Database | SQL Server / PostgreSQL |
| Tools | AutoMapper, MediatR, FluentValidation |

---

## 🧭 Mimari Yapı

Ticiyo, **monolith mimari** üzerine kuruludur ancak **modüler domain yaklaşımı** ile bölünmüştür.  
Her domain (örneğin *Product*, *Order*, *Payment*) kendi servislerini, repository’lerini ve uygulama servislerini içerir.  
Bu sayede proje hem **tek parça dağıtılabilir**, hem de gelecekte mikroservis geçişine uygun hale gelir.

---

## ⚡ Kurulum

```bash
git clone https://github.com/kullaniciadi/ticiyo.git
cd ticiyo
dotnet restore
dotnet run
