---
title: "DibBitCount Sıralaması"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

BitCount Sayımı, her pikseli tanımlayan bit sayısını ve<br/>                cihaz bağımsız bitmap (DIB) içindeki maksimum renk sayısını belirtir.

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| BITCOUNT0 | Piksel başına bit sayısı tanımsızdır.<br/>                Görüntü JPEG veya PNG formatında OLMALIdır.<br/>                Bu formatların hiçbiri bir renk tablosu içermez, bu yüzden bu değer<br/>                bir renk tablosunun mevcut olmadığını belirtir. JPEG ve PNG sıkıştırma formatlarıyla ilgili daha fazla bilgi için [JFIF] ve [RFC2083]<br/>                bağlantılarına bakın. |
| BITCOUNT1 | Görüntü iki renk ile tanımlanmıştır. Bitmap'teki her piksel<br/>                tek bir bit ile temsil edilir. Bit temizse, piksel<br/>                renk tablosundaki ilk girişin rengiyle gösterilir;<br/>                bit ayarlıysa, piksel tablodaki ikinci girişin rengine sahiptir. |
| BITCOUNT2 | Görüntü en fazla 16 renk ile tanımlanmıştır.<br/>                Bitmap'teki her piksel, renk tablosuna 4-bitlik bir indeksle temsil edilir<br/>                ve her bayt 2 piksel içerir. |
| BITCOUNT3 | Görüntü en fazla 256 renk ile tanımlanmıştır.<br/>                Bitmap'teki her piksel, renk tablosuna 8-bitlik bir indeksle temsil edilir<br/>                ve her bayt 1 piksel içerir. |
| BITCOUNT4 | Görüntü en fazla 2^16 renk ile tanımlanmıştır.<br/>                Bitmap'teki her piksel 16-bitlik bir değerle temsil edilir. |
| BITCOUNT5 | Bitmap en fazla 2^24 renk içerir ve DIB'nin Colors alanı NULL'dır.<br/>                Bitmap dizisindeki her 3 baytlık üçlü, bir piksel için sırasıyla mavi, yeşil ve kırmızı relatif yoğunlukları temsil eder. Colors renk tablosu<br/>                palet tabanlı cihazlarda kullanılan renkleri optimize etmek için kullanılır ve BitmapInfoHeader Nesnesinin ColorUsed alanı tarafından belirtilen giriş sayısını içermELİDİR. |
| BITCOUNT6 | Bitmap en fazla 2^24 renk içerir. |
