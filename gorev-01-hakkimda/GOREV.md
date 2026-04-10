# Gorev 01 — Hakkimda Sayfasi

**Sure:** ~30 dakika
**Zorluk:** Baslangic
**Araclar:** Next.js, Tailwind CSS, Claude Code, Git, Vercel

## Amac

Kendini tanitan basit, sik bir web sayfasi yap ve canliya al. Bu gorev bitince linkini paylasacaksin — gercek bir proje gibi.

## Ne Yapacaksin?

Bu klasorun icine (`gorev-01-hakkimda/`) Next.js projesi kur ve asagidaki bolumleri iceren tek sayfalik bir site olustur:

### Zorunlu Bolumler

1. **Basligin** — Adin soyadin
2. **Etiketin** — "Stajyer Gelistirici" veya kendini nasil tanimliyorsan
3. **Kisa bio** — 2-3 cumle kendinden bahset
4. **3 Ozellik/Skill** — Kart seklinde (ornek: "HTML/CSS", "Ogrenmeye acik", "Takim oyuncusu")
5. **3 Sosyal Link** — LinkedIn, GitHub, Email (gercek linkler)

### Teknik Gereksinimler

- Next.js 15+ (App Router)
- Tailwind CSS ile stillendirme
- TypeScript
- Mobile responsive (telefonda da duzgun gorunmeli)
- `app/page.tsx` tek dosya yeterli, karmasiklastirma

### Tasarim Ipuclari

- Ferah bir layout (cok sikisik olmasin)
- 1 veya 2 ana renk kullan (ornek: beyaz + mavi, veya siyah + turuncu)
- Okunabilir font boyutu (basit tut)
- Hover efektleri eklersen bonus
- Kopyalama yapma: Dribbble'da 1-2 ornek bak, KENDI yorumunu kat

## Adim Adim Rehber

Eger takilirsan, Claude Code'a bu adimlari soyle:

1. `gorev-01-hakkimda/` klasoru icinde Next.js projesi kur
2. Tailwind kurulumunu kontrol et
3. `app/page.tsx` dosyasini duzenle
4. Yukaridaki 5 bolumu ekle
5. `npm run dev` ile test et, tarayicida ac
6. Begenmedigin yerleri Claude'a soyle, duzelt
7. Git commit at
8. GitHub'a push et
9. Vercel'e deploy et
10. Canli linki asagiya yapistir

## Done Kriteri (Bitti Sayilmasi Icin)

- [ ] Next.js projesi `gorev-01-hakkimda/` klasorunde calisiyor
- [ ] 5 zorunlu bolum sayfada gorunuyor
- [ ] Mobile responsive (Chrome DevTools ile test et)
- [ ] Git'e commit atildi
- [ ] GitHub'a push edildi
- [ ] Vercel'e deploy edildi, canli link calisiyor
- [ ] Canli link bu dosyanin sonuna eklendi
- [ ] "Ne Ogrendim" bolumu dolduruldu

## Kurallar

- **Claude ile birlikte yap** — ama sen yonet, Claude yapmasin
- **Anladigin kodu commit et** — kopyala-yapistir degil
- **30 dakikayi asarsa bitmeli** — mukemmel olmasi gerekmiyor, calisiyor olmasi yeterli
- **Takilirsan sor** — Claude'a, sonra mentoruna

## Canli Link

<!-- Deploy bittikten sonra buraya Vercel linkini yapistir -->

Ornek: `https://hakkimda-ahmet.vercel.app`

## Ne Ogrendim

<!-- Gorev bittikten sonra buraya 3-5 cumle yaz: -->
<!-- - Ne yeni bir sey ogrendim? -->
<!-- - Nerede takildim? -->
<!-- - Claude ile calismak nasildi? -->
<!-- - Bir sonraki sefere ne farkli yaparim? -->

---

**Ipucu:** Claude'a ilk promptun soyle olabilir:

> Merhaba Claude, `gorev-01-hakkimda/` klasoru icinde Next.js 15 + TypeScript + Tailwind ile yeni bir proje kurmak istiyorum. Bana komutu ver, sonra `app/page.tsx` dosyasinda "Hakkimda" sayfasi yapacagiz. Adim adim ilerleyelim.
