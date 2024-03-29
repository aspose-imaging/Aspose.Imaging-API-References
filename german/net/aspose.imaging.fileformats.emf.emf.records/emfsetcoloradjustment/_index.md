---
title: EmfSetColorAdjustment
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Datensatz EMR_SETCOLORADJUSTMENT gibt Farbanpassungseigenschaften im Gerätekontext Wiedergabe an.
type: docs
weight: 4310
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
## EmfSetColorAdjustment class

Der Datensatz EMR_SETCOLORADJUSTMENT gibt Farbanpassungseigenschaften im Gerätekontext Wiedergabe an.

```csharp
public sealed class EmfSetColorAdjustment : EmfStateRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfSetColorAdjustment](emfsetcoloradjustment)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfSetColorAdjustment`](../emfsetcoloradjustment) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorAdjustment](../../aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/coloradjustment) { get; set; } | Ruft ein ColorAdjustment-Objekt ab oder legt es fest (Abschnitt 2.2.2), das color -Anpassungswerte angibt. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Bemerkungen

Farbanpassungswerte werden verwendet, um die Eingabefarbe der Quell-Bitmap für Grafiken Operationen anzupassen, die von EMR_STRETCHBLT- und EMR_STRETCHDIBITS-Datensätzen durchgeführt werden, wenn der STRETCH_HAALFTONE-Modus aus der StretchMode-Enumeration (Abschnitt 2.1.32) festgelegt wird. Das von diesem Datensatz angegebene ColorAdjustment-Objekt MUSS sein Wird in Grafikoperationen verwendet, die ein ColorAdjustment-Objekt erfordern, bis ein anderes ColorAdjustment-Objekt durch einen anderen EMR_SETCOLORADJUSTMENT-Datensatz angegeben wird oder bis das Objekt durch einen EMR_DELETEOBJECT -Datensatz entfernt wird.

### Siehe auch

* class [EmfStateRecordType](../emfstaterecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
