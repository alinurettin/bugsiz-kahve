# Bugsız Kahve Bug Avı

İçine 15 hata saklanmış sahte bir kahve dükkânı. Yazılım testi pratiği için hazırlanmış küçük bir oyun.

**Oyna:** https://alinurettin.github.io/bugsiz-kahve/

## Nasıl oynanır

1. Dükkânı bir test uzmanı gibi gez: ürün ara, sırala, sepete ekle, kupon dene, sipariş ver.
2. Bir hata fark edince alttaki **Bug bildir** düğmesine bas ve hatanın göründüğü yere dokun.
3. Doğruysa av defterine yazılır. Değilse yanlış alarm sayılır.

Sonunda skorunu, süreni ve unvanını görürsün.

## Teknik

Tek dosyalık statik bir sayfa (`index.html`), bağımlılığı yok. Girilen hiçbir veri bir yere gönderilmez; ilerleme yalnızca tarayıcının `localStorage` alanında tutulur.

Bugsız Kahve gerçek bir dükkân değildir.
