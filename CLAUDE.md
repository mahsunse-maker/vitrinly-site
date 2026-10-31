# vitrinly-site (proje özeti)

> Son güncelleme: 2026-10-31

https://vitrinly.app sitesinin yayın deposu (herkese açık). Cloudflare Pages `vitrinly-site` projesi `public/`
klasörünü yayınlar; **`main`'e push = otomatik yayın**. Derleme adımı yok, düz HTML.

- `public/index.html`: Vitrinly tanıtım (TR/EN), `public/privacy/`: Vitrinly gizlilik politikası
- `public/vadelio/`: Vadelio tanıtım sayfası (`/vadely/` → 301 yönlendirme, `_redirects`)
- `public/shots/`: ekran görüntüleri

Kopya: Vitrinly deposundaki `docs/site/public` (`~/Desktop/emlak uygulamasi`). İkisini aynı tut: önce orada
değiştir, sonra aynı dosyaları buraya kopyalayıp push et. Doğrulamayı vitrinly.app üzerinden yap
(Türkiye ağından *.pages.dev açılmıyor).

Proje listesi: `~/.claude/CLAUDE.md`.
