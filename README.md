# 📄 Ödev 3 – Rehber Web Sitesi (Buser Coffee)

Bu proje, HTML kullanarak oluşturulmuş bir **rehber web sitesi ödevidir**. Tema olarak butik bir kahve dükkanı olan **Buser Coffee** seçilmiştir.

---

## 🔧 Proje Dosyaları

| Dosya Adı        | Açıklama |
|------------------|----------|
| `index.html`     | Ana sayfa – tanıtım metni, kahve türleri ve görseller içerir. |
| `hakkinda.html`  | Hakkımızda – marka hikayesi, değerler ve kuruluş bilgileri. |
| `servisler.html` | Menü – sunulan kahve ve tatlı çeşitlerinin listesi. |
| `iletisim.html`  | İletişim – form, iletişim bilgileri ve mesaj alanı. |

---

## 🧱 Yapılandırma

- Tüm dosyalar HTML5 standardına uygun şekilde oluşturulmuştur.
- `<meta charset="UTF-8">` etiketi ile karakter kodlaması belirtilmiştir.
- Sayfalarda mobil uyumluluk için `<meta name="viewport">` tanımı yapılmıştır.
- Tüm sayfalarda bir **navigasyon menüsü (navbar)** yer almaktadır.

---

## 🔗 Navigasyon Menüsü

Her sayfanın üst kısmında yer alan bağlantılar:

- Anasayfa
- Hakkında
- Servisler
- İletişim

Tüm bağlantılar `<a>` etiketi ile oluşturulmuştur.

---

## 📌 Sayfa Detayları

### `index.html`
- `<h1>` başlığı: “Buser Coffee”
- Tanıtıcı paragraflar (`<p>`)
- Kahve türlerini tanıtan görseller ve açıklamalar:
  - Filtre Kahve
  - Espresso
  - French Press
  - Türk Kahvesi
- Listeleme yapılmamıştır, her içerik kendi `<div>` bloğunda açıklanmıştır.

### `hakkinda.html`
- Giriş metni (`<p>`) ile kahve dükkanının hikayesi anlatılmıştır.
- Öne çıkan özellikler `<ul>` listesi ile sunulmuştur.
- “Tarladan Fincana” gibi üç başlık altında alt açıklamalar ve görsel eklenmiştir.

### `servisler.html`
- Başlık: “Coffee Menu”
- Menüdeki ürünler `<ul>` etiketi ile listelenmiştir.
- Her bir ürün için kısa açıklamalar eklenmiştir.

### `iletisim.html`
- Başlık `<h2>` ile verilmiştir.
- Ad, Soyad, E-posta, Konu ve Mesaj içeren bir `<form>` bulunmaktadır.
- Form içinde `label`, `input` ve `textarea` öğeleri kullanılmıştır.
- Tüm form sadece HTML ile yapılmıştır (JavaScript kullanılmadı).

---

## 🎨 Stil

Tasarım tamamen **satır içi CSS (`style=""`)** kullanılarak yapılmıştır.  
Kahve temasına uygun olarak:
- Arka plan rengi: krem ve bej tonları (`#fffaf3`, `#d2b48c`)
- Yazı rengi: koyu kahve (`#4b2e2e`)
- Kenarlıklar, gölgeler ve kutular: yumuşak ve sade stiller
- Resimlerde `border-radius` ile köşeler yumuşatılmıştır

---

## ✅ Uygunluk

Bu proje, aşağıdaki ödev gerekliliklerini karşılamaktadır:

✔ Ana sayfa + en az 3 alt sayfa  
✔ Her sayfa HTML5 yapısında  
✔ Navigasyon menüsü  
✔ En az 1 görsel ve alternatif metni  
✔ En az 1 liste (ul / ol)  
✔ Hakkında, servis ve iletişim içerikleri  
✔ Sadece HTML ile hazırlanmış form

---

## 📝 Oluşturan

**Ad:** Sercan Yalçınkaya  
**Proje:** Buser Coffee – HTML Rehber Web Sitesi  
**Tarih:** Temmuz 2025
