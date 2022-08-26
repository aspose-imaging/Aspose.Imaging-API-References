---
title: EmfPlgBlt
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_PLGBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Parallelogramm unter Anwendung einer Farbmasken-Bitmap.
type: docs
weight: 3950
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

Der EMR_PLGBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Parallelogramm unter Anwendung einer Farbmasken-Bitmap.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlgBlt](emfplgblt)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfPlgBlt`](../emfplgblt) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest) { get; set; } | Erhält oder setzt ein Array von drei WMF PointL-Objekten ([MS-WMF] Abschnitt 2.2.2.15), das drei Ecken eines Parallelogramm-Zielbereichs für die Blockübertragung angibt. Die obere linke Ecke des Quellrechtecks wird dem zugeordnet ersten Punkt in diesem Array, die obere rechte Ecke zum zweiten Punkt und die untere linke Ecke zum dritten Punkt. Die untere rechte Ecke des Quellrechtecks wird dem impliziten vierten Punkt im -Parallelogramm zugeordnet, das aus den ersten drei Punkten (A, B und C) berechnet wird, indem es als -Vektoren behandelt wird. D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color) { get; set; } | Ruft ein WMF-ColorRef-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.8), das die -Hintergrundfarbe der Quell-Bitmap angibt. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das -Begrenzungsrechteck in Geräteeinheiten für die Ausgabe an das Ziel definiert. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Quellrechtecks angibt. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Quellrechtecks angibt. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap) { get; set; } | Ruft oder setzt einen Puffer, der die Masken-Bitmap enthält, die nicht mit dem festen Teil des EMR_PLGBLT-Datensatzes oder miteinander zusammenhängen müssen. Dementsprechend sind Felder in diesem Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap) { get; set; } | Ruft einen Puffer ab oder legt ihn fest, der die Quellbitmap enthält, die nicht mit dem festen Teil des EMR_PLGBLT-Datensatzes oder miteinander zusammenhängen müssen. Dementsprechend sind Felder in diesem Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Bitmap-Header der Maske zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration enthalten sein. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors enumeration enthalten sein |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc) { get; set; } | Ruft ein XForm-Objekt (Abschnitt 2.2.28) ab oder legt es fest, das eine Weltraum-zu-Seitenraum-Transformation angibt, die auf die Quellbitmap anzuwenden ist. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke der Maskenbitmap angibt. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke der Maskenbitmap angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
