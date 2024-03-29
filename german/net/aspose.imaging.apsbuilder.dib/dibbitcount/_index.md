---
title: DibBitCount
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die BitCount-Enumeration gibt die Anzahl der Bits an die jedes Pixel definieren und die maximale Anzahl von Farben in einer geräteunabhängigen Bitmap DIB.
type: docs
weight: 30
url: /de/net/aspose.imaging.apsbuilder.dib/dibbitcount/
---
## DibBitCount enumeration

Die BitCount-Enumeration gibt die Anzahl der Bits an, die jedes Pixel definieren, und die maximale Anzahl von Farben in einer geräteunabhängigen Bitmap (DIB).

```csharp
public enum DibBitCount : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Bitcount0 | `0` | Die Anzahl der Bits pro Pixel ist nicht definiert. Das Bild SOLLTE entweder im JPEG- oder im PNG-Format vorliegen. Keines dieser Formate enthält eine Farbtabelle, daher gibt dieser Wert an, dass keine Farbtabelle vorhanden ist. Siehe [JFIF] und [RFC2083] für weitere Informationen zu JPEG- und PNG-Komprimierungsformaten. |
| Bitcount1 | `1` | Das Bild wird mit zwei Farben angegeben. Jedes Pixel in der Bitmap wird durch ein einzelnes Bit dargestellt. Wenn das Bit gelöscht ist, wird das Pixel mit der Farbe des ersten Eintrags in der Farbtabelle angezeigt; wenn das Bit gesetzt ist, hat das Pixel die Farbe des zweiten Eintrags in der Tabelle. |
| Bitcount2 | `4` | Das Bild wird mit maximal 16 Farben spezifiziert. Jedes Pixel in der Bitmap wird durch einen 4-Bit-Index in der -Farbtabelle dargestellt, und jedes Byte enthält 2 Pixel. |
| Bitcount3 | `8` | Das Bild wird mit maximal 256 Farben angegeben. Jedes Pixel in der Bitmap wird durch einen 8-Bit-Index in der -Farbtabelle dargestellt, und jedes Byte enthält 1 Pixel. |
| Bitcount4 | `16` | Das Bild wird mit maximal 2^16 Farben angegeben. Jedes Pixel in der Bitmap wird durch einen 16-Bit-Wert dargestellt |
| Bitcount5 | `24` | Die Bitmap hat maximal 2^24 Farben und das Colors-Feld von DIB ist NULL. Jedes 3-Byte-Triplet im Bitmap-Array repräsentiert die relativen Intensitäten von Blau, Grün bzw. Rot für ein Pixel. Die Colors-Farbtabelle wird zum Optimieren von Farben verwendet, die auf palettenbasierten Geräten verwendet werden, und MUSS die Anzahl der Einträge enthalten, die durch das ColorUsed-Feld des BitmapInfoHeader-Objekts angegeben wird. |
| Bitcount6 | `32` | Die Bitmap hat maximal 2^24 Farben |

### Siehe auch

* namensraum [Aspose.Imaging.ApsBuilder.Dib](../../aspose.imaging.apsbuilder.dib)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
