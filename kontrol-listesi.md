# Paylaşım Öncesi Kontrol Listesi

Her madde ya geçer ya kalır. Kalan madde varsa paylaşım yapılmaz; düzeltme önerisi yazılır ve metin yazana geri gider.

**[uyarla]** yazan satırlar markaya göre değişir; kendi kuralını yaz.

## 1. Linkler
- [ ] Metindeki her link açılıyor mu (404 ya da yönlendirme hatası yok)?
- [ ] Her linkte takip parametresi var mı? Örnek şema: `utm_source=<platform>&utm_medium=social&utm_campaign=<kampanya>&utm_content=<içerik kimliği>` **[uyarla]**
- [ ] Instagram ve TikTok açıklamasında tıklanır link olmadığı için "link profilde" yazıyor mu?

## 2. Hashtag
- [ ] Instagram: en çok 5 hashtag (platform sınırı)
- [ ] Facebook: 0–3 hashtag **[uyarla, bizim kuralımız]**
- [ ] X: en çok 1 hashtag **[uyarla, bizim kuralımız]**

## 3. Uzunluk
- [ ] Instagram / Facebook açıklaması ≤ 2.200 karakter
- [ ] X gönderisi ≤ 280 karakter (ücretsiz hesap)
- [ ] YouTube başlığı ≤ 100 karakter
- [ ] YouTube açıklaması ≤ 5.000 bayt (Türkçe harfler 2 bayt sayılır, yani karakter sayısından fazla tutar)
- [ ] YouTube etiketlerinin toplamı ≤ 500 karakter
- [ ] YouTube başlığında ve açıklamasında `<` ve `>` yok (YouTube kabul etmiyor)

## 4. Hitap ve dil
- [ ] Hitap markanın kuralına uyuyor mu? Örnek: kişisel hesapta "sen", kurumsal hesapta "siz" **[uyarla]**
- [ ] Aynı metinde "sen" ile "siz" karışmıyor mu?
- [ ] Metin hedef dilde mi? Yerleşik terimler (demo, LED, QR) sorun değil.

## 5. Dosya
- [ ] Metin dosyası var ve boş değil.
- [ ] Karar dosyası (JSON kullanıyorsan) geçerli, açılabiliyor.

## 6. Yorum ve mesaj yanıtları (ek kontroller)
- [ ] Kişisel veri yok: telefon, adres, e-posta, başka müşterinin bilgisi.
- [ ] Hakaret ya da tartışmayı büyütecek dil yok.
- [ ] Onaylı listende olmayan vaat, fiyat ya da indirim yok.

## Kontrol dışı (bunlar için ret verilmez)
- Ton, üslup tercihi, "daha iyi yazılabilirdi"
- Onaylanmış videonun içeriği
- Marka sahibinin doğru dediği bilgi

## Çıktı biçimi
```json
{ "karar": "onay | ret", "gerekceler": ["..."], "duzeltme_onerisi": "..." }
```
