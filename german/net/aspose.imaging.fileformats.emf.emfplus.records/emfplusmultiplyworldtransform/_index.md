---
title: EmfPlusMultiplyWorldTransform
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusMultiplyWorldTransform-Datensatz multipliziert die aktuelle Weltraumtransformation mit einer angegebenen Transformationsmatrix.
type: docs
weight: 6150
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
## EmfPlusMultiplyWorldTransform class

Der EmfPlusMultiplyWorldTransform-Datensatz multipliziert die aktuelle Weltraumtransformation mit einer angegebenen Transformationsmatrix.

```csharp
public sealed class EmfPlusMultiplyWorldTransform : EmfPlusTerminalServerRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusMultiplyWorldTransform](emfplusmultiplyworldtransform)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusMultiplyWorldTransform`](../emfplusmultiplyworldtransform) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/matrixdata) { get; set; } | Erhält oder setzt ein EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47), das die Multiplikationsmatrix definiert. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/postmultipliedmatrix) { get; } | Ruft einen Wert ab, der angibt, ob [postmultiplizierte Matrix]. Falls gesetzt, soll die Transformationsmatrix postmultipliziert werden. Wenn klar, sollte es vormultipliziert werden. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
