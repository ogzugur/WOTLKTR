# Değişiklik Günlüğü

Bu projedeki önemli değişiklikler burada listelenir.
Biçim [Keep a Changelog](https://keepachangelog.com/tr/) esinlidir; sürümleme [SemVer](https://semver.org/lang/tr/) uyumludur.

## [Yayımlanmadı]

### Düzeltildi
- Görev çevirilerinde (`QuestData_TR.lua`) 585 görevde 695 yüksek önemli düzeltme: anlamı bozan veya
  ters çeviren cümleler, yanlış/başka görevden kopyalanmış metinler, çevrilmiş kişi/yer/fraksiyon
  adları, bozuk `$N` / `$g` yer tutucuları ve boş bırakılmış 15 alan. Tüm öneriler (orta ve düşük
  önemli olanlar dahil) `.github/raporlar/Gorev_Duzeltme_Raporu.xlsx` dosyasında incelemeye açıktır.

## [1.0.1] — 2026-07-03

### Düzeltildi
- Takip listesinden (Objectives) bir görev başlığına tıklayınca açılan görevin İngilizce kalması.
  Günlük çevirisi artık seçim değişikliklerinde de tetiklenir (takip listesi ve harita yolu dahil)
  ve oyunun her metin yenilemesinin ardından kendini onarır.

## [1.0.0] — 2026-06-28

İlk kararlı genel sürüm.

### Eklendi
- **Görevler** — başlık, açıklama, hedef ve ödül çevirisi (görev günlüğü + verme/teslim pencereleri). Takip listesinde (Objectives) görev başlıkları da çevrilir.
- **NPC Konuşmaları (Gossip)** — diyalog menüleri ve metinleri.
- **Konuşma Baloncukları** — NPC baş üstü / say / yell konuşmaları.
- **Sinematik Altyazılar** — film ve cinematic altyazıları.
- **Kitaplar** — oyun içi kitap, mektup ve tomarlar (EN ↔ TR geçişli).
- **İpuçları (Tutorials)** — oyun öğretici pencereleri.
- **Yetenekler** — talent, büyü ve glyph tooltip açıklamaları (1170 büyü şablonu dahil). Talent eşleştirme şablon (templatize)
  tabanlı: her rank/değer yakalanır. Sayılar oyundan canlı alınıp yerine konur; teçhizat/spell power
  ile değişen değerler doğru gösterilir. Glyph hem çantada (eşya) hem Yetenek ekranında (yuva) çevrilir.
- Çeviri penceresi uzun metinlerde otomatik büyür.
- Tanılama: giriş yükleme özeti, `/wtr` durum/debug, `pcall` çökme koruması.
- Türkçe karakter destekli fontlar.
- Ayarlar: `Esc → Interface → AddOns → WotLK TR` (Görevler / Baloncuklar / Kitaplar / Yetenekler).

### Notlar
- Çevirisi olmayan içerik orijinal (İngilizce) biçimde görünür; kapsam sürümlerle genişlemeye devam eder.
- Sınıf, ırk ve özel adlar (büyü adları, yer/kişi adları) İngilizce gösterilir.

[1.0.0]: https://github.com/ekremcanaltunyurt/WOTLKTR/releases/tag/v1.0.0
[1.0.1]: https://github.com/ekremcanaltunyurt/WOTLKTR/releases/tag/v1.0.1
