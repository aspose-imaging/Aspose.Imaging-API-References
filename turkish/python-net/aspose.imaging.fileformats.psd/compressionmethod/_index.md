---
title: "CompressionMethod Enumerasyonu"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar.

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| RAW | Sıkıştırma yok. Görüntü verileri RGBA düzlemsel sırada ham baytlar olarak depolanır.<br/>            Bu, önce tüm R verisinin, ardından tüm G verisinin, sonra tüm B ve son olarak tüm A verisinin yazıldığı anlamına gelir. |
| RLE | RLE sıkıştırmalı görüntü verileri, tüm tarama hatları (satırlar * kanallar) için bayt sayılarını içeren bir başlıkla başlar ve her<br/>            sayı iki baytlık bir değer olarak depolanır. RLE sıkıştırmalı veri ardından gelir ve her tarama hattı ayrı ayrı sıkıştırılır.<br/>            RLE sıkıştırması, Macintosh ROM rutin PackBits ve TIFF standardı tarafından kullanılan aynı sıkıştırma algoritmasıdır. |
| ZIP_WITHOUT_PREDICTION | Tahmin olmadan ZIP. |
| ZIP_WITH_PREDICTION | Tahminli ZIP. |
