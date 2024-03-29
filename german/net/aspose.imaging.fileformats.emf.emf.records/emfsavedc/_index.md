---
title: EmfSaveDc
second_title: Aspose.Imaging für .NET-API-Referenz
description: Speichert den aktuellen Zustand des Kontexts des Wiedergabegeräts in einem -Stack von Zuständen die von vorhergehenden EMR_SAVEDC -Datensätzen gespeichert wurden falls vorhanden. Der Zustand besteht aus Grafikeigenschaften und Objekten einschließlich der aktuell ausgewählten Bitmap Pinsel Palette Schriftart Stift und Bereich. Ein EMR_RESTOREDC-Datensatz wird verwendet um den Zustand wiederherzustellen. Dieser EMF-Datensatz gibt keine Parameter an.
type: docs
weight: 4210
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
## EmfSaveDc class

Speichert den aktuellen Zustand des Kontexts des Wiedergabegeräts in einem -Stack von Zuständen, die von vorhergehenden EMR_SAVEDC -Datensätzen gespeichert wurden, falls vorhanden. Der Zustand besteht aus Grafikeigenschaften und Objekten, einschließlich der aktuell ausgewählten Bitmap, Pinsel, Palette, Schriftart, Stift und Bereich. Ein EMR_RESTOREDC-Datensatz wird verwendet, um den Zustand wiederherzustellen. Dieser EMF-Datensatz gibt keine Parameter an.

```csharp
public sealed class EmfSaveDc : EmfStateRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfSaveDc](emfsavedc#constructor)() | Initialisiert eine neue Instanz von[`EmfSaveDc`](../emfsavedc) Klasse. |
| [EmfSaveDc](emfsavedc#constructor_1)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfSaveDc`](../emfsavedc) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Bemerkungen

Der Stapel kann Zustandsinformationen für mehrere Instanzen des Kontexts des Wiedergabegeräts enthalten. Wenn ein Status wiederhergestellt wird, MÜSSEN alle kürzlich gespeicherten Statusinstanzen verworfen werden.

### Siehe auch

* class [EmfStateRecordType](../emfstaterecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
