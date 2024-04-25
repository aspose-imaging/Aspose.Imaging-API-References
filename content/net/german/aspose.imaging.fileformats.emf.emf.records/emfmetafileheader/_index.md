---
title: EmfMetafileHeader
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die EMR_HEADER-Datensatztypen definieren die Startpunkte von EMF-Metadateien und geben Eigenschaften des Geräts an auf dem das Bild in der Metadatei erstellt wurde. Die Informationen im Header-Datensatz machen es möglich dass EMF-Metadateien von einem bestimmten Ausgabegerät unabhängig sind. Der Wert des Felds Größe kann verwendet werden um zwischen den verschiedenen EMR_HEADER-Datensatztypen zu unterscheiden die weiter oben in diesem Abschnitt aufgeführt sind. Es gibt drei Möglichkeiten headers Der Basisheader der der EmfMetafileHeader-Datensatz ist. Der Teil mit fester Größe dieses Headers ist 88 Bytes groß und enthält ein Header-Objekt. Der erste Erweiterungsheader der der EmfMetafileHeaderExtension1-Datensatz ist. Die feste Größe Teil dieses Headers ist 100 Bytes groß und enthält ein Header-Objekt und ein HeaderExtension1-Objekt Abschnitt 2.2.10. Der zweite Erweiterungs-Header der der EmfMetafileHeaderExtension2-Datensatz ist. Der Teil mit fester Größe dieses Headers ist 108 Bytes und es enthält ein Header-Objekt ein HeaderExtension1-Objekt und ein HeaderExtension2-Objekt Abschnitt 2.2.11.
type: docs
weight: 3810
url: /de/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

Die EMR_HEADER-Datensatztypen definieren die Startpunkte von EMF-Metadateien und geben Eigenschaften des Geräts an, auf dem das Bild in der Metadatei erstellt wurde. Die Informationen im Header-Datensatz machen es möglich, dass EMF-Metadateien von einem bestimmten Ausgabegerät unabhängig sind. Der Wert des Felds Größe kann verwendet werden, um zwischen den verschiedenen EMR_HEADER-Datensatztypen zu unterscheiden, die weiter oben in diesem Abschnitt aufgeführt sind. Es gibt drei Möglichkeiten headers: Der Basisheader, der der EmfMetafileHeader-Datensatz ist. Der Teil mit fester Größe dieses Headers ist 88 Bytes groß und enthält ein Header-Objekt. Der erste Erweiterungsheader, der der EmfMetafileHeaderExtension1-Datensatz ist. Die feste Größe Teil dieses Headers ist 100 Bytes groß und enthält ein Header-Objekt und ein HeaderExtension1-Objekt (Abschnitt 2.2.10). Der zweite Erweiterungs-Header, der der EmfMetafileHeaderExtension2-Datensatz ist. Der Teil mit fester Größe dieses Headers ist 108 Bytes, und es enthält ein Header-Objekt, ein HeaderExtension1-Objekt und ein HeaderExtension2-Objekt (Abschnitt 2.2.11).

```csharp
public class EmfMetafileHeader : EmfRecord
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader#constructor)() | Initialisiert eine neue Instanz von[`EmfMetafileHeader`](../emfmetafileheader) Klasse. |
| [EmfMetafileHeader](emfmetafileheader#constructor_1)(EmfMetafileHeader) | Initialisiert eine neue Instanz von[`EmfMetafileHeader`](../emfmetafileheader) Klasse. |
| [EmfMetafileHeader](emfmetafileheader#constructor_2)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfMetafileHeader`](../emfmetafileheader) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription) { get; set; } | Ruft die EMF-Beschreibung ab oder legt sie fest. Eine optionale, nullterminierte Unicode-UTF16-LE-Zeichenfolge mit beliebiger Länge und beliebigem Inhalt. Seine Position im Datensatz und die Anzahl der Zeichen werden durch die Felder offDescription bzw. nDescription in EmfHeader angegeben. Wenn der Wert eines der Felder Null ist, ist keine Beschreibungszeichenfolge vorhanden. |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer) { get; set; } | Ruft die EMF-Beschreibung ab oder legt sie fest. buffer Ein optionales Array von Bytes, das die EMF-Beschreibungszeichenfolge enthält, die nicht zwingend mit dem festen Teil des EmfMetafileHeader-Datensatzes zusammenhängen muss. Dementsprechend ist das Feld in diesem Puffer mit der Bezeichnung „UndefinedSpace“ optional und MUSS ignoriert werden. |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader) { get; set; } | Holt oder setzt ein Header-Objekt (Abschnitt 2.2.9), das Informationen über den Inhalt und die Struktur der Metadatei enthält |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer) { get; set; } | Ruft ein optionales Array von Bytes ab oder legt es fest, das den Rest des EMF-Header-Datensatzes enthält. Die Größe dieses Feldes MUSS ein Vielfaches von 4 Bytes sein |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Siehe auch

* class [EmfRecord](../emfrecord)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
