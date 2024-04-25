---
title: EmfMaskBlt
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_MASKBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Rechteck optional in Kombination mit einem Pinselmuster und mit der Anwendung einer Farbmasken- -Bitmap gemäß spezifizierten Vordergrund- und Hintergrund-Rasteroperationen.
type: docs
weight: 3800
url: /de/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

Der EMR_MASKBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Rechteck, optional in Kombination mit einem Pinselmuster und mit der Anwendung einer Farbmasken- -Bitmap, gemäß spezifizierten Vordergrund- und Hintergrund-Rasteroperationen.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfMaskBlt](emfmaskblt)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfMaskBlt`](../emfmaskblt) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc) { get; set; } | Ruft ein WMF-ColorRef-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.8, das die -Hintergrundfarbe der Quell-Bitmap angibt. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck des -Ziels in Geräteeinheiten definiert. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Zielrechtecks angibt. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Zielrechtecks angibt. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap) { get; set; } | Holt oder setzt einen Puffer, der die Masken-Bitmaps enthält, die nicht mit dem festen Teil des EMR_MASKBLT-Datensatzes oder mit jedem anderen zusammenhängen müssen. Dementsprechend sind Felder in diesem Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4) { get; set; } | Ruft eine quaternäre Rasteroperation ab oder legt sie fest, die ternäre Rasteroperationen für die Vorder- und Hintergrundfarben einer Bitmap angibt. Diese Werte definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks kombiniert werden sollen. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap) { get; set; } | Holt oder setzt einen Puffer, der die Quell-Bitmaps enthält, die nicht mit dem festen Teil des EMR_MASKBLT-Datensatzes oder mit jedem anderen zusammenhängen müssen. Dementsprechend sind Felder in diesem Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Bitmap-Header der Maske zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration enthalten sein. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc) { get; set; } | Ruft ein XForm-Objekt (Abschnitt 2.2.28) ab oder legt es fest, das eine Weltraum-zu-Seitenraum-Transformation angibt, die auf die Quellbitmap anzuwenden ist. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke der Maskenbitmap angibt. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke der Maskenbitmap angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
