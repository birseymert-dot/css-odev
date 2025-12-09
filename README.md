# HTML & CSS Layout Ödevi 240408801 kutay mert birsey

Bu projede tek bir HTML dosyası kullanılarak iki farklı CSS tasarımı uygulanmıştır. Amaç, aynı HTML yapısının farklı CSS dosyalarıyla nasıl tamamen farklı görünümler alabileceğini göstermektir.

---

## 📁 Dosya Yapısı

Projede toplam 3 ana dosya bulunmaktadır:

- `index.html` → Sayfanın HTML yapısını içerir  
- `styleA.css` → Dikey yerleşim (Style A) tasarımı  
- `styleB.css` → Yatay yerleşim + sabit konum (Style B) tasarımı  

Tasarım değiştirmek için `index.html` içindeki CSS bağlantısı değiştirilmektedir.

---

## 🎨 Style A Özellikleri

- 6 adet kutu dikey olarak hizalanmıştır.
- Kutular ekranın ortasında yer almaktadır.
- Her kutu 100x100 boyutlarındadır.
- Açık gri arka plan rengi kullanılmıştır.
- Üst kenarlarda 1px çizgi vardır.
- Son kutu (F) koyu renkte ve kalın siyah çerçevelidir.
- Flexbox kullanılarak ortalama yapılmıştır.

Kullanılan örnek Flexbox yapısı:

```css
display: flex;
flex-direction: column;
justify-content: space-evenly;
align-items: center;
