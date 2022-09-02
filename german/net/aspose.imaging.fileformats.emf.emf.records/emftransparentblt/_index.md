---
title: EmfTransparentBlt
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_TRANSPARENTBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quellbitmap zu einem -Zielrechteck wobei eine angegebene Farbe als transparent behandelt wird wobei die Ausgabe gestreckt oder komprimiert wird um sie an die Abmessungen des Ziels anzupassen falls erforderlich
type: docs
weight: 4640
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

Der EMR_TRANSPARENTBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quellbitmap zu einem -Zielrechteck, wobei eine angegebene Farbe als transparent behandelt wird, wobei die Ausgabe gestreckt oder komprimiert wird, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfTransparentBlt`](../emftransparentblt) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck des -Ziels in Geräteeinheiten definiert. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Zielrechtecks angibt. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Quellrechtecks angibt. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Zielrechtecks angibt. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Quellrechtecks angibt. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap) { get; set; } | Ruft einen Puffer ab oder legt ihn fest, der die Quellbitmap enthält, die nicht zusammenhängend mit dem festen Teil des EMR_TRANSPARENTBLT-Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color) { get; set; } | Ruft ein WMF-ColorRef-Objekt ab oder legt es fest, das die Hintergrundfarbe der Quellbitmap angibt. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color) { get; set; } | Holt oder setzt ein WMF-ColorRef-Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die als transparent zu behandelnde Farbe in der Quell-Bitmap angibt. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc) { get; set; } | Ruft ein XForm-Objekt (Abschnitt 2.2.28) ab oder legt es fest, das eine Weltraum-zu-Seitenraum-Transformation angibt, die auf die Quellbitmap anzuwenden ist. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
