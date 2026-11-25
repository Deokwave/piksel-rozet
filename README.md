# piksel-rozet

Profilimizdeki teknoloji panelindeki rozetlerin PHP hali. Bir yazı ve bir renk veriyorsun, piksel kenarlı bir SVG rozet dönüyor. Türkçe harfler de çalışıyor.

```
php rozet.php yazi=WEBGPU renk=c04fc8 > rozet.svg
```

`olcek` ile boyutu ayarlayabilirsin (1-8, varsayılan 3): `php rozet.php yazi=RUST renk=7c4ddb olcek=6`.

Bir sunucuya koyarsan `rozet.php?yazi=PHP&renk=3b6be0` adresi doğrudan rozeti döndürüyor.

## Panelde kullandığımız renkler

| Grup | Renk |
|---|---|
| Diller | `3b6be0` |
| Web ve arayüz | `d9653b` |
| Uygulama | `7c4ddb` |
| Sunucu ve altyapı | `0e9fb0` |
| Görüntü ve model | `c04fc8` |

Örneğin `php rozet.php yazi=FFMPEG renk=c04fc8` görüntü grubundaki rozetin aynısını verir.

© 2026 Deokwave. Tüm hakları saklıdır.
