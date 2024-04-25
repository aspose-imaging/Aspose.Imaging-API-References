---
title: EmfAlphaBlend
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_ALPHABLEND-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck einschließlich Alpha-Transparenzdaten entsprechend einer spezifizierten Mischoperation.
type: docs
weight: 3200
url: /de/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

Der EMR_ALPHABLEND-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, einschließlich Alpha-Transparenzdaten, entsprechend einer spezifizierten Mischoperation.

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfAlphaBlend](emfalphablend)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfAlphaBlend`](../emfalphablend) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color) { get; set; } | Ruft ein WMF ColorRef-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.8, das die Hintergrundfarbe der Quell-Bitmap angibt. |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction) { get; set; } | Ruft eine Struktur ab oder legt sie fest, die die Mischoperationen für Quell- und -Ziel-Bitmaps angibt |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck des -Ziels in Geräteeinheiten definiert. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Zielrechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Quellrechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Zielrechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Quellrechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap) { get; set; } | Ruft einen Puffer ab oder legt ihn fest, der die Quellbitmap enthält, die nicht zusammenhängend mit dem festen Teil des EMR_ALPHABLEND-Datensatzes sein muss. Dementsprechend sind Felder in diesem -Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr) { get; set; } | Ruft ein XForm-Objekt (Abschnitt 2.2.28) ab oder legt es fest, das eine Weltraum-zu-Seitenraum-Transformation angibt, die auf die Quellbitmap anzuwenden ist. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
