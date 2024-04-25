---
title: EmfStretchBlt
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_STRETCHBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck optional in Kombination mit einem Pinselmuster gemäß einer spezifizierten raster -Operation wobei die Ausgabe gestreckt oder komprimiert wird um sie an die Abmessungen des Ziels anzupassen falls erforderlich .
type: docs
weight: 4590
url: /de/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

Der EMR_STRETCHBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, optional in Kombination mit einem Pinselmuster, gemäß einer spezifizierten raster -Operation, wobei die Ausgabe gestreckt oder komprimiert wird, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich .

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfStretchBlt](emfstretchblt#constructor)() | Initialisiert eine neue Instanz von[`EmfStretchBlt`](../emfstretchblt) Klasse. |
| [EmfStretchBlt](emfstretchblt#constructor_1)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfStretchBlt`](../emfstretchblt) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc) { get; set; } | Ruft ein WMF-ColorRef-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.8, das die -Hintergrundfarbe der Quell-Bitmap angibt. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den -Code der Rasteroperation angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinselmuster kombiniert werden sollen, um die endgültige Farbe zu erhalten. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck des -Ziels in Geräteeinheiten definiert. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Zielrechtecks angibt. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Quellrechtecks angibt. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Zielrechtecks angibt. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Quellrechtecks angibt. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect) { get; set; } | Ruft das Zielrechteck ab oder legt es fest. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap) { get; set; } | Ruft einen Puffer ab oder legt ihn fest, der die Quellbitmap enthält, die nicht zusammenhängend mit dem festen Teil des EMR_STRETCHBLT-Datensatzes sein muss. Dementsprechend sind Felder in diesem -Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect) { get; set; } | Ruft das Quellrechteck ab oder legt es fest. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Zielrechtecks angibt. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc) { get; set; } | Holt oder setzt ein XForm-Objekt (Abschnitt 2.2.28), das eine Weltraum-zu-Seitenraum-Transformation angibt, die auf die Quell-Bitmap anzuwenden ist. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken -Ecke des Quellrechtecks angibt. |

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
