---
title: "EmfGraphicsMode Sıralaması"
type: docs
weight: 150
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

GraphicsMode sayımı, dikdörtgen koordinatları gibi şekil verilerinin nasıl yorumlanacağını belirtmek için kullanılır.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| GM_ADVANCED | TrueType metin çıktısı, oynatma cihaz bağlamındaki mevcut dünya‑cihaz dönüşümüne tamamen uymalıdır.<br/>            Yaylar, dünya uzayında saat yönünün tersine çizilmelidir; ancak, hem yay kontrol noktaları <br/>            hem de yayların kendileri, oynatma cihaz bağlamındaki mevcut dünya‑cihaz dönüşümüne tamamen saygı göstermelidir.<br/>            Dünya‑cihaz dönüşümü, EMR_MODIFYWORLDTRANSFORM veya <br/>            EMR_SETWORLDTRANSFORM kayıtları kullanılarak doğrudan değiştirilebilir veya pencere ve görüntüleme alanı genişlik ve konumları değiştirilerek dolaylı olarak, <br/>            EMR_SETWINDOWEXTEX (bölüm 2.3.11.30) ve EMR_SETVIEWPORTEXTEX (bölüm 2.3.11.28) kayıtları, <br/>            ve EMR_SETWINDOWORGEX (bölüm 2.3.11.31) ve EMR_SETVIEWPORTORGEX (bölüm 2.3.11.30) kayıtları sırasıyla kullanılarak değiştirilebilir.<br/>            GM_ADVANCED grafik modunda, dikdörtgenler çizilirken alt ve en sağ kenarlar KAPSANMALIDIR. |
| GM_COMPATIBLE | TrueType metni, oynatma cihaz bağlamındaki mevcut dünya‑cihaz dönüşümü nedeniyle grafiklerin geri kalan kısmı x‑ekseninde veya y‑ekseninde döndürülmüş olsa bile, soldan sağa ve sağ tarafı yukarı doğru yazılmalıdır. Metnin yalnızca yüksekliği ölçeklenmelidir. Yaylar, oynatma cihaz bağlamındaki mevcut yay yönü kullanılarak çizilmelidir, ancak mevcut dünya‑cihaz dönüşümüne saygı göstermemelidir; bu dönüşüm x‑ekseninde veya y‑ekseninde bir döndürme gerektirebilir.<br/>            Dünya‑cihaz dönüşümü yalnızca pencere ve görüntüleme alanı genişlik ve konumları değiştirilerek, EMR_SETWINDOWEXTEX (bölüm 2.3.11.30) ve EMR_SETVIEWPORTEXTEX (bölüm 2.3.11.28) kayıtları, ve EMR_SETWINDOWORGEX (bölüm 2.3.11.31) ve EMR_SETVIEWPORTORGEX (bölüm 2.3.11.30) kayıtları sırasıyla kullanılarak değiştirilmelidir. EMR_MODIFYWORLDTRANSFORM (bölüm 2.3.12.1) veya EMR_SETWORLDTRANSFORM (bölüm 2.3.12.2) kayıtlarıyla dönüşümün doğrudan değiştirilmesi DESTEKLENMEYEBİLİR.<br/>            GM_COMPATIBLE grafik modunda, dikdörtgenler çizilirken alt ve en sağ kenarlar KAPSANMAMALIDIR. |
