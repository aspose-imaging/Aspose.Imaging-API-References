---
title: "DibBitCount-Aufzählung"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

Die BitCount‑Aufzählung gibt die Anzahl der Bits an, die jedes Pixel definieren, und<br/>                die maximale Anzahl von Farben in einer geräteunabhängigen Bitmap (DIB).

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| BITCOUNT0 | Die Anzahl der Bits pro Pixel ist undefiniert.<br/>                Das Bild SOLLTE entweder im JPEG- oder PNG-Format vorliegen.<br/>                Keines dieser Formate enthält eine Farbpalette, sodass dieser Wert<br/>                angibt, dass keine Farbpalette vorhanden ist. Siehe [JFIF] und [RFC2083]<br/>                für weitere Informationen zu JPEG- und PNG-Komprimierungsformaten. |
| BITCOUNT1 | Das Bild ist mit zwei Farben angegeben. Jeder Pixel im Bitmap wird<br/>                durch ein einzelnes Bit dargestellt. Ist das Bit gelöscht, wird der Pixel<br/>                mit der Farbe des ersten Eintrags in der Farbpalette angezeigt;<br/>                ist das Bit gesetzt, hat der Pixel die Farbe des zweiten Eintrags in der Palette. |
| BITCOUNT2 | Das Bild ist mit maximal 16 Farben angegeben.<br/>                Jeder Pixel im Bitmap wird durch einen 4‑Bit‑Index in die<br/>                Farbpalette dargestellt, und jedes Byte enthält 2 Pixel. |
| BITCOUNT3 | Das Bild ist mit maximal 256 Farben angegeben.<br/>                Jeder Pixel im Bitmap wird durch einen 8‑Bit‑Index in die<br/>                Farbpalette dargestellt, und jedes Byte enthält 1 Pixel. |
| BITCOUNT4 | Das Bild ist mit maximal 2^16 Farben angegeben.<br/>                Jeder Pixel im Bitmap wird durch einen 16‑Bit‑Wert dargestellt. |
| BITCOUNT5 | Das Bitmap hat maximal 2^24 Farben, und das Colors‑Feld von DIB ist NULL.<br/>                Jeder 3‑Byte‑Tripel im Bitmap‑Array stellt die relativen Intensitäten<br/>                von Blau, Grün und Rot für einen Pixel dar. Die Colors‑Farbpalette<br/>                wird zur Optimierung der auf palettenbasierten Geräten verwendeten Farben genutzt und MUSS die Anzahl der Einträge enthalten, die im Feld ColorUsed des BitmapInfoHeader‑Objekts angegeben ist. |
| BITCOUNT6 | Das Bitmap hat maximal 2^24 Farben |
