---
title: EmfBitBlt
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_BITBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck optional in Kombination mit einem Pinselmuster entsprechend einer spezifizierten Rasteroperation.
type: docs
weight: 3250
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
## EmfBitBlt class

Der EMR_BITBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, optional in Kombination mit einem Pinselmuster, entsprechend einer spezifizierten Rasteroperation.

```csharp
public sealed class EmfBitBlt : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfBitBlt](emfbitblt)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfBitBlt`](../emfbitblt) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bitbltrasteroperation) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den -Code der Rasteroperation angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinselmuster kombiniert werden sollen, um die endgültige Farbe zu erhalten. |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bksrcargb32color) { get; set; } | Ruft ein WMF ColorRef-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe der Quell-Bitmap angibt. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck des -Ziels in Geräteeinheiten definiert. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cxdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite der Quell- und -Zielrechtecke angibt. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe der Quell- und -Zielrechtecke angibt. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/sourcebitmap) { get; set; } | Ruft einen Puffer ab oder legt ihn fest, der die Quellbitmap enthält, die nicht zusammenhängend mit dem festen Teil des EMR_BITBLT-Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer , die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xformsrc) { get; set; } | Ruft ein XForm-Objekt (Abschnitt 2.2.28) ab oder legt es fest, das eine Weltraum-zu-Seitenraum-Transformation angibt, die auf die Quellbitmap anzuwenden ist. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
