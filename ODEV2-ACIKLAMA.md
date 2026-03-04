# Ödev 2: Bootstrap ile Instagram Clone

Bootstrap ve CSS ile Instagram benzeri bir arayüz clone'u.

## Yapılanlar

- **Navbar:** `fixed-top`, yükseklik 54px, arka plan beyaz. İçerikle birleşmemesi için `body`'e `padding-top: 54px`.
- **Logo:** `.logo` içine soldan 192px margin.
- **Arama:** `d-flex` ile ortalı, soldan 5 birim margin (`ms-5` / 5rem). `::placeholder` arka planına `assets/search-icon.svg` eklendi, `background-repeat: no-repeat`.
- **İkonlar:** FontAwesome (CDN) kullanıldı.
- **Sağ menü:** Soldan 5 birim, üstten 2 birim margin. `d-none d-sm-flex` ile sm altında gizleniyor.
- **İçerik alanı:** `offset-md-4`, üstten 2 birim margin (`mt-2`). Col: `col-12`, diğer ölçekler `col-md-6`.
- **middlearea:** `max-height: 200px !important`, `overflow-y: auto`.
- **Hikayeler:** İsimler resimlerin altında (flex column + align center).
- **Gönderi kartları:** Üç nokta sağda (`justify-content-between`). Beğenme/yorum/paylaşma alanında border yok. Bookmark sağda (spacer + `ms-auto`). Card header ve footer beyaz. "Yorum paylaş" metni sağa (`text-end`).
- **Sağ panel:** `stickysidebar` için `position: sticky`, `rightpanel` beyaz, kenarlık yok. "Tümünü gör" ve "Takip et" sağa hizalı.
- **Sayfa arka planı:** `#fafafa` (Instagram benzeri).

## Çalıştırma

`index.html` dosyasını tarayıcıda açın (Bootstrap ve FontAwesome CDN için internet gerekir).

## Dosya yapısı

- `index.html` — Sayfa yapısı (Bootstrap grid, navbar, hikayeler, kartlar, sağ panel)
- `style.css` — Ödevde istenen tüm stiller
- `assets/search-icon.svg` — Arama simgesi
- `ODEV2-ACIKLAMA.md` — Bu dosya
