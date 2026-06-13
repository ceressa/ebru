# 墨流し · Suminagashi

Tarayıcıda gerçek zamanlı akışkan simülasyonuyla suminagashi (Japon "yüzen mürekkep" sanatı).
Tek dosya (`index.html`), sıfır bağımlılık, saf WebGL2.

## Canlı

https://ceressa.github.io/ebru/

## Nasıl çalışır

- Navier-Stokes tabanlı GPU akışkan simülasyonu: advection, vorticity (girdap), basınç çözümü
- Mürekkep, kağıt üzerine Beer-Lambert soğurma modeliyle çizilir; renkler doğal biçimde üst üste biner
- Dokun: eşmerkezli mürekkep halkası bırak (önceki halkaları dışarı iter)
- Sürükle: suyu karıştır, deseni akıt
- 6 sakin renk, açılıp kapanabilen ortam sesi, PNG indir, temizle

## Eski sürüm

Türk ebrusu (Canvas 2D) sürümü korunuyor: [ebru-classic.html](ebru-classic.html)
Canlı: https://ceressa.github.io/ebru/ebru-classic.html
