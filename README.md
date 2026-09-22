# Mihenk

> Kanita dayali, aciklanabilir kurum-yetenek eslestirme ve ekip optimizasyon platformu.

Mihenk, Zemin360 Hackathon kapsaminda gelistirilmesi planlanan acik kaynakli bir karar destek platformudur. Kurumlarin gercek ihtiyaclarini yapilandirir; genc yeteneklerin beyanlarini GitHub projeleri ve portfolyo ciktilari gibi kanitlarla destekler; uygun adaylari ve birbirini tamamlayan ekip kombinasyonlarini aciklanabilir bicimde onerir.

## Problem

Kurum-yetenek ve kurum-girisim eslesmelerinde dort temel sorun goruyoruz:

- Kurum ihtiyaclari genellikle uygulanabilir bir proje tanimina donusturulemiyor.
- Profil ve portfolyolardaki yetkinlikler guvenilir bicimde dogrulanamiyor.
- Eslesmeler cogunlukla anahtar kelime benzerligine dayaniyor.
- Ilk temas sonrasindaki pilot ve is birligi surecleri olculebilir sekilde izlenemiyor.

## Cozum

Mihenk uc asamali bir akis sunar:

1. **Ihtiyaci yapilandir:** Kurumun serbest metinle girdigi problem; hedef, veri, sure, kisit ve basari olcutleri iceren bir ihtiyac kartina donusturulur.
2. **Kanita dayali eslestir:** Teknik yetkinlikler, proje deneyimi, kanit guveni, uygunluk ve ekip ici tamamlayicilik birlikte degerlendirilir.
3. **Is birligini takip et:** Secilen ekiple baslatilan pilot surec kilometre taslari ve olculebilir basari metrikleriyle izlenir.

## Neden farkli?

Mihenk, adaylari yalnizca CV anahtar kelimelerine gore siralamak yerine eslestirmeyi cok kriterli bir optimizasyon problemi olarak ele alir.

- Her yetkinlik, kaynagi gorulebilen bir kanitla iliskilendirilir.
- Her onerinin hangi faktorlerden olustugu aciklanir.
- Yalnizca en uygun birey degil, becerileri birbirini tamamlayan ekip onerilir.
- Eksik veya zayif kanitlar bir guven skoru ile gorunur hale getirilir.
- Eslesme sonrasindaki pilot sureci ayni platformda takip edilir.

## Ornek eslestirme modeli

Ilk prototipte uyum skoru asagidaki faktorlerin agirlikli bilesimi olarak tasarlanacaktir:

```text
uyum_skoru =
    teknik_yetkinlik
  + proje_deneyimi
  + kanit_guveni
  + uygunluk
  + ekip_tamamlayiciligi
  - risk_cezalari
```

Agirliklar sabit bir "kara kutu" olmayacak; kullaniciya gosterilecek ve pilotlardan elde edilen geri bildirimlerle gelistirilecektir.

## MVP kapsami

- [ ] Kurum ihtiyac karti olusturma
- [ ] Yetenek profili ve proje kaniti ekleme
- [ ] GitHub proje verilerini profil ile iliskilendirme
- [ ] Cok kriterli uyum ve guven skoru hesaplama
- [ ] Skor bilesenlerini aciklama
- [ ] Kisitlara gore tamamlayici ekip onerme
- [ ] Pilot sureci icin kilometre tasi panosu
- [ ] Temel analitik ve geri bildirim ekrani

## Planlanan teknik mimari

| Katman | Teknoloji / yaklasim |
| --- | --- |
| Web arayuzu | Next.js, TypeScript |
| API ve eslestirme servisi | Python, FastAPI |
| Veri katmani | PostgreSQL |
| Eslestirme | Vektor benzerligi, cok kriterli skorlama, kisitli optimizasyon |
| Entegrasyon | GitHub API |
| Dagitim | Docker tabanli gelistirme ortami |

Teknik tercihler, hackathon on hazirlik ve mentor geri bildirimleri sonrasinda guncellenebilir.

## Ekip

- **N. Baris Celik** - Takim liderligi, full-stack gelistirme ve makine ogrenmesi
- **Mustafa Tabu** - Istatistiksel modelleme, veri analizi ve gorsellestirme
- **Buse Selin Tavlak** - Algoritmalar, backend gelistirme ve optimizasyon

## Yol haritasi

### 1. Kesif ve tasarim

- Kullanici akislari ve veri modelinin netlestirilmesi
- Eslestirme kriterleri ile basari metriklerinin tanimlanmasi

### 2. Calisan MVP

- Profil ve ihtiyac kartlari
- Aciklanabilir eslestirme skoru
- Ekip kombinasyonu onerisi

### 3. Pilot takibi

- Kilometre taslari
- Geri bildirim dongusu
- Eslestirme kalitesi analitigi

## Durum

Proje basvuru ve kapsam tasarimi asamasindadir. Kod, teknik kararlar ve demo ilerledikce bu depo uzerinden acik olarak paylasilacaktir.

## Lisans

Bu proje [MIT Lisansi](LICENSE) ile lisanslanmistir.
