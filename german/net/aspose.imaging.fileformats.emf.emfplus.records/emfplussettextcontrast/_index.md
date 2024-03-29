---
title: EmfPlusSetTextContrast
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusSetTextContrast-Datensatz gibt den Textkontrast gemäß dem Gamma-Korrekturwert an.
type: docs
weight: 6380
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
## EmfPlusSetTextContrast class

Der EmfPlusSetTextContrast-Datensatz gibt den Textkontrast gemäß dem Gamma-Korrekturwert an.

```csharp
public sealed class EmfPlusSetTextContrast : EmfPlusPropertyRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusSetTextContrast](emfplussettextcontrast)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusSetTextContrast`](../emfplussettextcontrast) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/textcontrast) { get; set; } | Ruft den Gammakorrekturwert X 1000 ab oder legt ihn fest, der auf nachfolgende Textwiedergabeoperationen angewendet wird. Der zulässige Bereich liegt zwischen 1000 und 2200, und repräsentiert Text-Gammawerte von 1,0 bis 2,2. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
