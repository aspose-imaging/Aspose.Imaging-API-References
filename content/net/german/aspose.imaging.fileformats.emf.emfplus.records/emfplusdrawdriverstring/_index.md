---
title: EmfPlusDrawDriverString
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusDrawDriverString-Datensatz spezifiziert die Textausgabe mit Zeichenpositionen.
type: docs
weight: 5940
url: /de/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

Der EmfPlusDrawDriverString-Datensatz spezifiziert die Textausgabe mit Zeichenpositionen.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Ruft die Pinselkennung ab oder legt sie fest Eine 32-Bit-Ganzzahl ohne Vorzeichen, die entweder die Vordergrundfarbe des Texts oder eines Grafikpinsels angibt, abhängig vom Wert des S-Flags in Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Ruft die Optionen für die Treiberzeichenfolge ab oder legt sie fest. flags Eine 32-Bit-Ganzzahl ohne Vorzeichen, die den Abstand, die Ausrichtung und die Wiedergabequalität für die Zeichenfolge angibt. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Ruft die Anzahl der Glyphen ab oder legt sie fest Eine 32-Bit-Ganzzahl ohne Vorzeichen, die die Anzahl der Glyphen in der Zeichenfolge angibt |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Ruft die Glyphenpositionen ab oder setzt sie. array Ein Array von EmfPlusPointF-Objekten (Abschnitt 2.2.2.36), die die Ausgabeposition jedes Zeichens angeben Glyphen-Array. Glyphenpositionen werden aus der Position der ersten Glyphe berechnet, wenn das DriverStringOptionsRealizedAdvance -Flag in DriverStringOptions-Flags gesetzt ist. In diesem Fall gibt GlyphPos nur die Position der ersten Glyphe an. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Ruft die Glyphen ab oder legt sie fest. array Ein Array von 16-Bit-Werten, die die zu zeichnende Textzeichenfolge definieren. Wenn das DriverStringOptionsCmapLookup-Flag im Feld DriverStringOptionsFlags gesetzt ist, gibt jeder Wert in diesem -Array ein Unicode-Zeichen an. Andernfalls gibt jeder Wert einen Index zu a Zeichenglyphe im EmfPlusFont-Objekt an, das durch den ObjectId-Wert im Flags-Feld angegeben wird. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist. Dieses Bit gibt den Datentyp im BrushId-Feld an. Falls gesetzt, spezifiziert BrushId den Farbwert in einem EmfPlusARGB-Objekt (Abschnitt 2.2.2.1). Wenn klar, enthält BrushId den EMF+ Object Tabellenindex eines EmfPlusBrush-Objekts (Abschnitt 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Ermittelt oder setzt, ob die Matrix vorhanden ist. flag Eine 32-Bit-Ganzzahl ohne Vorzeichen, die angibt, ob eine Transformationsmatrix im TransformMatrix-Feld vorhanden ist 0 – keine Matrix vorhanden. 1 - Transformationsmatrix ist in TransformMatrix field |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Ruft die Objektkennung ab oder legt sie fest. Der EMF+-Objekttabellenindex einer[EmfPlusFont](EmfPlusFont) Objekt (section 2.2.1.3), um den Text zu rendern. Der Wert MUSS null bis einschließlich 63 sein. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Ruft die Transformationsmatrix ab oder legt sie fest. Ein optionales EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47), das die Transformation angibt, die auf jeden Wert im Textarray anzuwenden ist. Das Vorhandensein dieser Daten wird aus dem MatrixPresent-Feld ermittelt. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
