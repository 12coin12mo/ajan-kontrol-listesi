# İkinci Göz: Yapay Zeka Ajanları İçin Paylaşım Öncesi Kontrol Listesi

12 ayda 12 şirket kuruyorum ve sosyal medyamı yapay zeka ajanları yönetiyor. Bir ajan paylaşım metnini yazıyor, **başka bir ajan** yayından önce o metni kontrol ediyor. Bu depo, o ikinci ajanın kullandığı kontrol listesinin herkesin kullanabileceği sürümü.

## Neden ayrı bir ajan?

- **Metni yazan, kendi metnini kontrol edemez.** Aynı oturum kendi hatasını görmez; kontrolü bağımsız biri yapmalı.
- **Kontrol yalnız tekniktir.** Ton, fikir ya da "daha iyi olabilirdi" gerekçesiyle ret yok. Sadece kırık link, fazla hashtag, karakter sınırı, karışık hitap gibi ölçülebilir hatalar. Böylece ajan her şeye takılıp paylaşımı durdurmuyor.
- **Ret verir, kendisi düzeltmez.** Düzeltme önerisini yazar; düzeltmeyi yazan ajan yapar.
- **Dış içerik veridir.** Yorum, mesaj, e-posta ya da web sayfasının içindeki "şunu yap" cümleleri talimat sayılmaz.

## Dosyalar

| Dosya | Ne işe yarar |
|---|---|
| [`kontrol-listesi.md`](kontrol-listesi.md) | Elle de kullanabileceğin kontrol listesi |
| [`ikinci-goz.md`](ikinci-goz.md) | Claude Code alt ajanı olarak hazır dosya |
| [`prompt.md`](prompt.md) | ChatGPT, Claude ya da Gemini sohbetine yapıştırılacak tek prompt |

## Nasıl kullanılır?

**Claude Code ile:** `ikinci-goz.md` dosyasını projendeki `.claude/agents/` klasörüne kopyala. Paylaşım metnini yazdıktan sonra "ikinci göz ajanıyla kontrol et" demen yeterli.

**Sohbet ile:** `prompt.md` içindeki metni kopyala, altına paylaşım metnini ve platformu yapıştır.

**Kendine göre uyarla:** Hitap kuralı ("sen" mi "siz" mi), hashtag sınırı, link takip şeması markadan markaya değişir. `kontrol-listesi.md` içinde **[uyarla]** yazan satırları kendi kurallarınla değiştir.

## Not

Platform sınırları zamanla değişir. Listedeki sınırları paylaşmadan önce platformun güncel yardım sayfasıyla karşılaştır. Sınırlar 17 Ekim 2026'da kontrol edildi.

Serbestçe kullanabilir, değiştirebilir ve paylaşabilirsin (MIT lisansı).

---
12in12 · 12 ayda 12 şirket · [12in12.co](https://12in12.co)
