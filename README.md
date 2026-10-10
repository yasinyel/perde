# Perde · Elektro Gitar Atölyesi

Elektro gitar klavyesini dinleyerek ve dokunarak öğrenmek için ücretsiz, kurulum gerektirmeyen bir web uygulaması.

- **Klavye haritası:** doğal notalar, bütün notalar, bir notanın her yeri; dokununca ses ve oktav bilgisi
- **13 derslik yol:** teller ve akorttan doğal notalara, pozisyonlara, pentatoniğe, power chord ve bare akorlara
- **Nota avı:** notayı adlandır / perdeyi bul / hepsini bul, 60 sn sprint, zayıf noktaları gösteren ısı haritası
- **Pozisyonlar:** I–XII. pozisyon (her perdeye bir parmak, esneme notaları), pentatonik kutular, 3 nota/tel kalıpları, 8 dizi, 12 ton
- **Akorlar:** açık akorlar, E ve A formu bare, power chord, herhangi bir akor adı için şekil bulucu, geçiş antrenmanı
- **Şarkılar:** notaları klavyede yanan tab çalar, akorlu şarkılar (transpoze, otomatik kaydırma, ritim kalıbı), ünlü şarkı rehberleri, şarkı editörü ve düz metin tab dönüştürücü
- **Araçlar:** mikrofonla akort, metronom, tap tempo, hız antrenörü

Tüm veriler (ilerleme, rekorlar, eklenen şarkılar) kullanıcının tarayıcısında saklanır. Ayarlar penceresinden yedeklenip başka cihaza taşınabilir.

## Çalıştırma

Derleme adımı yok; düz HTML, CSS ve ES modülleri.

```sh
python3 -m http.server 8080
# http://localhost:8080
```

GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.

## Telif

Hazır tab ve akorlu parçalar kamu malı / geleneksel eserler ya da Perde için yazılmış alıştırmalardır. Ünlü şarkılar için yalnızca ton, akor adları, teknik ve hazırlık önerileri verilir; tab ve sözler için lisanslı kaynaklara bağlantı vardır.
