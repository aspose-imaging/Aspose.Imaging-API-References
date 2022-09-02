---
title: EmfPlusSetTsGraphics
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusSetTSGraphics-Datensatz gibt den Status eines Grafikgerätekontexts für einen Terminalserver an.
type: docs
weight: 6410
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

Der EmfPlusSetTSGraphics-Datensatz gibt den Status eines Grafikgerätekontexts für einen Terminalserver an.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusSetTsGraphics`](../emfplussettsgraphics) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode) { get; set; } | Ruft eine vorzeichenlose 8-Bit-Ganzzahl ab oder legt sie fest, die die Qualität der Linienwiedergabe angibt, einschließlich der Art des Linien-Anti-Aliasing. Es MUSS in der Aufzählung SmoothingMode definiert werden (Abschnitt 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors) { get; } | Ruft einen Wert ab, der angibt, ob [grundlegende VGA-Farben]. Wenn festgelegt, enthält die Palette nur die grundlegenden VGA-Farben. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Quellfarben mit Hintergrundfarben kombiniert werden. Es MUSS ein Wert in der Aufzählung CompositingMode sein (Abschnitt 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die den Grad der -Glättung angibt, die auf Linien, Kurven und die Kanten gefüllter Bereiche angewendet werden soll, damit sie mehr kontinuierlich oder scharf definiert erscheinen. Es MUSS ein Wert in der CompositingQuality-Enumeration sein (Abschnitt 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie die Skalierung, einschließlich Streckung und Verkleinerung, durchgeführt wird. Es MUSS ein Wert in der FilterType-Enumeration sein (Abschnitt 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette) { get; } | Ruft einen Wert ab, der angibt, ob [Palette haben]. Falls gesetzt, enthält dieser Datensatz ein EmfPlusPalette-Objekt (Abschnitt 2.2.2.28) im Feld Palette nach den Grafikzustandsdaten. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette) { get; set; } | Ruft ein optionales EmfPlusPalette-Objekt ab oder legt es fest. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Gesamtqualität des image - und Textwiedergabeprozesses angibt. Es MUSS ein Wert in der PixelOffsetMode-Enumeration sein (Abschnitt 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx) { get; set; } | Ruft eine vorzeichenbehaftete 16-Bit-Ganzzahl ab oder legt sie fest, bei der es sich um die horizontale Koordinate des -Ursprungs zum Rendern von Halbton- und Dithering-Matrizen handelt. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy) { get; set; } | Ruft eine vorzeichenbehaftete 16-Bit-Ganzzahl ab oder legt sie fest, bei der es sich um die vertikale Koordinate des Ursprungs zum Rendern von Halbton- und Dithering-Matrizen handelt. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Gammakorrekturwert angibt, der zum Rendern von geglättetem und ClearType-Text verwendet wird. Dieser Wert MUSS im Bereich von 0 bis einschließlich 12 liegen. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint) { get; set; } | Ruft eine 8-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Qualität der Wiedergabe von text angibt, einschließlich der Art des Text-Anti-Aliasing. Es MUSS in der Aufzählung TextRenderingHint (Abschnitt 2.1.1.32) definiert werden. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice) { get; set; } | Ruft ein 192-Bit-EmfPlusTransformMatrix-Objekt ab oder legt es fest (Abschnitt 2.2.2.47), das die Transformationen von World Space in Device Space angibt. |

### Siehe auch

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
