# Claude Code ile Calisma Rehberi

Bu rehber, staj gorevlerini Claude ile birlikte yaparken sana yol gosterir.

## Claude Kimdir?

Claude, Anthropic'in yapay zeka asistani. Claude Code ise terminalde calisan versiyonu — dosya okur, yazar, komut calistirir, kod yazar. Senin is arkadasin gibi dusunebilirsin.

## Temel Kurallar

### 1. Claude'a ne istedigini NET soyle

Kotu: "bana bir sayfa yap"

Iyi: "Next.js App Router kullanarak `app/page.tsx` dosyasinda bir 'Hakkimda' sayfasi olustur. Icinde ismim (Ahmet Yilmaz), meslek etiketim (Stajyer Gelistirici) ve 3 tane sosyal link olsun. Tailwind ile stillendir."

**Kural:** Ne istedigini, hangi dosyada, hangi teknoloji ile → hepsini soyle.

### 2. Ciktiyi mutlaka KONTROL et

Claude hata yapabilir. Kod yazdiginda:
- Calistir, gor
- Browser'da ac, test et
- Beklenen sey olmadiysa "soyle olmadi, X bekliyordum" de

**Kural:** "Calisti mi?" sorusunu KENDIN cevapla, Claude'a sorma.

### 3. Anlamadigin yeri SOR

Claude bir kod yazdi ve `useState` gordun, ne oldugunu bilmiyorsun → **sor**.

"useState ne ise yariyor? 2 cumleyle acikla" → Claude sana mini ders verir.

**Kural:** Kopyala-yapistir stajyer olma. Anladigin kodu teslim et.

### 4. Kucuk adimlarla ilerle

Kotu: "Tum sayfayi yap"

Iyi:
- "Once bos bir sayfa olustur"
- "Simdi baslik ekle"
- "Simdi foto alani ekle"
- "Simdi sosyal linkler ekle"

**Kural:** Her adimi gorerek ilerle. Buyuk bir seferde 100 satir kod = anlayamadigin kara kutu.

### 5. Hata cikarsa PANIK YAPMA

Terminalde kirmizi yazi? Normal.

- Hatanin TAMAMINI kopyala
- Claude'a yapistir, "bu hatayi aldim, ne yapayim?" de
- Claude cozecektir, sen de ogreneceksin

## Ornek Prompt Kaliplari

### Proje baslangicinda
```
Next.js 15 + TypeScript + Tailwind ile yeni bir proje kur.
Klasor adi: hakkimda-sayfasi
Ilk dosya: app/page.tsx
```

### Degisiklik isterken
```
app/page.tsx'te baslik rengini gri yerine mavi yap.
Tailwind class kullan.
```

### Bilgi istedginde
```
Bana Tailwind'deki flex ve grid arasindaki farki 3 cumle ile acikla.
```

### Hata aldiginda
```
Su hatayi aldim:

[hata metni]

Ne yapmam gerek?
```

### Deploy asamasinda
```
Bu projeyi Vercel'e nasil deploy ederim? Adim adim anlat.
```

## YAPMAMAN GEREKENLER

- Claude'un yazdigi kodu anlamadan commit etme
- "Bilmiyorum, Claude yapsin" deme — sen yonet, Claude yardimci
- Hata gordugunde panikle kapama, Claude'a sor
- Gereksiz buyuk promptlar yazma (ornek: "profesyonel, modern, premium, sik, harika bir sayfa yap") → anlam tasimaz, sonuc kotu

## YAPMAN GEREKENLER

- Her commit mesajini sen yaz (Claude onersin, sen onayla)
- Her satirin ne ise yaradigini bil
- Takildiginda once Claude'a, sonra mentoruna sor
- Gorev bittiginde kendi cumlelerinle ne ogrendigini yaz (GOREV.md sonunda)

---

**Motto:** Claude senin icin calismaz, seninle calisir.
