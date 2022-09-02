---
title: EmfStretchDiBits
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EMR_STRETCHDIBITS-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck optional in Kombination mit einem Pinselmuster entsprechend einer spezifizierten Raster- -Operation wobei die Ausgabe gestreckt oder komprimiert wird um sie an die Abmessungen des Ziels anzupassen falls notwendig.
type: docs
weight: 4600
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

Der EMR_STRETCHDIBITS-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, optional in Kombination mit einem Pinselmuster, entsprechend einer spezifizierten Raster- -Operation, wobei die Ausgabe gestreckt oder komprimiert wird, um sie an die Abmessungen des Ziels anzupassen, falls notwendig.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfStretchDiBits`](../emfstretchdibits) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die einen -Code für eine Rasteroperation angibt. Diese Codes definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks und optional einem Pinselmuster kombiniert werden sollen, um die endgültige Farbe zu erhalten. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck des -Ziels in Geräteeinheiten definiert. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Breite des Zielrechtecks angibt. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Breite des Quellrechtecks in Pixel angibt. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische Höhe des Zielrechtecks angibt. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Höhe des Quellrechtecks in Pixel angibt. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap) { get; set; } | Ruft einen Puffer ab oder legt ihn fest, der die Quellbitmap enthält, die nicht zusammenhängend mit dem festen Teil des EMR_STRETCHDIBITS-Datensatzes sein muss. Dementsprechend sind Felder in diesem Puffer, die mit „UndefinedSpace“ gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der -Farbtabelle im Quell-Bitmap-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische x-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die x-Koordinate in Pixel der oberen linken -Ecke des Quellrechtecks angibt. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die logische y-Koordinate der oberen linken Ecke des Zielrechtecks angibt. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die y-Koordinate in Pixeln der oberen linken -Ecke des Quellrechtecks angibt. |

### Bemerkungen

Dieser Datensatz unterstützt Quellbilder im JPEG- und PNG-Format. Das Compression-Feld im Quell- -Bitmap-Header gibt das Bildformat an. Wenn sich die Vorzeichen der Höhen- und Breitenfelder von Quelle und Ziel unterscheiden, gibt dieser Datensatz eine Spiegelbildkopie der Quell-Bitmap zum Ziel an. Das heißt, wenn cxSrc und cxDest unterschiedliche Vorzeichen haben, wird ein Spiegelbild der Quellbitmap entlang der x-Achse angegeben. Wenn cySrc und cyDest unterschiedliche Vorzeichen haben, wird ein Spiegelbild der Quellbitmap entlang der y-Achse angegeben.

### Siehe auch

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
