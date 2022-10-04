---
title: EmfPlusPenDataFlags
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die PenData-Flags spezifizieren Eigenschaften von Grafikstiften einschließlich des Vorhandenseins optionaler Datenfelder. Diese Flags können kombiniert werden um mehrere Optionen anzugeben.
type: docs
weight: 5000
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
## EmfPlusPenDataFlags enumeration

Die PenData-Flags spezifizieren Eigenschaften von Grafikstiften, einschließlich des Vorhandenseins optionaler Datenfelder. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.

```csharp
[Flags]
public enum EmfPlusPenDataFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| PenDataTransform | `1` | Falls gesetzt, MUSS eine 2x3-Transformationsmatrix im OptionalData-Feld von an angegeben werden[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataStartCap | `2` | Falls gesetzt, MUSS der Stil einer Startlinienkappe im OptionalData-Feld von angegeben werden[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataEndCap | `4` | Gibt an, ob der Stil einer Endzeilenkappe im OptionalData-Feld von angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataJoin | `8` | Gibt an, ob ein Linienverbindungstyp im OptionalData-Feld einer angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataMiterLimit | `10` | Gibt an, ob eine Gehrungsgrenze im OptionalData-Feld eines angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataLineStyle | `20` | Gibt an, ob ein Linienstil im OptionalData-Feld eines angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataDashedLineCap | `40` | Gibt an, ob im OptionalData-Feld von an eine gestrichelte Obergrenze angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataDashedLineOffset | `80` | Gibt an, ob ein Offset der gestrichelten Linie im OptionalData-Feld einer angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataDashedLine | `100` | Gibt an, ob ein[`EmfPlusDashedLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) Objekt MUSS im OptionalData-Feld eines angegeben werden[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataNonCenter | `200` | Gibt an, ob eine Stiftausrichtung im OptionalData-Feld eines angegeben werden MUSS[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataCompoundLine | `400` | Gibt an, ob Länge und Inhalt von a[`EmfPlusCompoundLineData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)-Objekt sind im OptionalData-Feld eines vorhanden[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataCustomStartCap | `800` | Gibt an, ob ein[`EmfPlusCustomStartCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) Objekt MUSS im OptionalData-Feld eines angegeben werden[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |
| PenDataCustomEndCap | `1000` | Gibt an, ob ein[`EmfPlusCustomEndCapData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) Objekt MUSS im OptionalData-Feld eines angegeben werden[`EmfPlusPenData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) Objekt. |

### Bemerkungen

Grafikstifte werden angegeben durch[`EmfPlusPen`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) Objekte.

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->