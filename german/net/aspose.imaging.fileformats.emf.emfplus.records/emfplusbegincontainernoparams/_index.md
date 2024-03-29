---
title: EmfPlusBeginContainerNoParams
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusBeginContainerNoParams-Datensatz öffnet einen neuen Grafikzustandscontainer.
type: docs
weight: 5850
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
## EmfPlusBeginContainerNoParams class

Der EmfPlusBeginContainerNoParams-Datensatz öffnet einen neuen Grafikzustandscontainer.

```csharp
public sealed class EmfPlusBeginContainerNoParams : EmfPlusStateRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusBeginContainerNoParams](emfplusbegincontainernoparams)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusBeginContainerNoParams`](../emfplusbegincontainernoparams) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/stackindex) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die einen Index angibt, der dem -Grafikzustandscontainer zugeordnet werden soll. Der Index MUSS von einem nachfolgenden EmfPlusEndContainer-Datensatz (Abschnitt 2.3.7.3) referenziert werden, um den Grafikzustandscontainer zu schließen. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
