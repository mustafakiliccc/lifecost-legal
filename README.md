# lifecost-legal

LifeCost mobil uygulaması için yasal dokümanları barındıran statik site.
GitHub Pages ile yayınlanır.

## Yapı

```
privacy-policy/
  tr/
    index.html   → her zaman en güncel sürüm
    v1.0.html    → arşivlenmiş sürüm (asla silinmez)
  en/
    index.html
    v1.0.html
```

## Versiyon kuralı

1. `index.html` her zaman güncel metni gösterir.
2. Yeni bir sürüm yayınlanırken:
   - Mevcut `index.html` içeriği `vX.Y.html` olarak kopyalanır (arşivlenir).
   - `index.html` yeni metinle güncellenir.
   - Yeni versiyon numarası `index.html` içindeki "Versiyon" alanına yazılır.
3. Arşiv dosyaları **asla silinmez veya değiştirilmez** — KVKK kapsamında
   kullanıcının hangi metne onay verdiğini ispat etmek için gereklidir.
4. Uygulama tarafındaki `privacy_consent.version` alanı, kullanıcının onay
   verdiği `vX.Y` numarasıyla eşleşmelidir.

## Yayın

GitHub Pages: Settings → Pages → Source: `main` branch, `/ (root)`.

URL: `https://mustafakiliccc.github.io/lifecost-legal/`
