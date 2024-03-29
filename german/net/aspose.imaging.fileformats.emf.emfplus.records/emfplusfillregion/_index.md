---
title: EmfPlusFillRegion
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusFillRegion-Datensatz gibt an das Innere einer Grafikregion zu füllen
type: docs
weight: 6120
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
## EmfPlusFillRegion class

Der EmfPlusFillRegion-Datensatz gibt an, das Innere einer Grafikregion zu füllen

```csharp
public sealed class EmfPlusFillRegion : EmfPlusDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusFillRegion](emfplusfillregion)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusFillRegion`](../emfplusfillregion) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/brushid) { get; set; } | Ruft die Pinselkennung ab oder legt sie fest. Eine 32-Bit-Ganzzahl ohne Vorzeichen, die den Pinsel definiert, dessen Inhalt durch das S-Bit im Flags-Feld bestimmt wird. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/iscolor) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist. Falls gesetzt, spezifiziert BrushId eine Farbe als ein EmfPlusARGB-Objekt (Abschnitt 2.2.2.1). Wenn klar, enthält BrushId den Index eines EmfPlusBrush-Objekts (Abschnitt 2.2.1.1) in der EMF+-Objekttabelle. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/objectid) { get; set; } | Ruft die Objektkennung ab oder setzt sie. Der Index des zu füllenden EmfPlusRegion-Objekts (Abschnitt 2.2.1.8) in der EMF+-Objekttabelle. Der Wert MUSS null bis einschließlich 63 sein. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
