---
title: EmfPolyBezierTo
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Datensatz EMR_POLYBEZIERTO gibt eine oder mehrere Bezier-Kurven basierend auf der aktuellen Position an.
type: docs
weight: 3980
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/
---
## EmfPolyBezierTo class

Der Datensatz EMR_POLYBEZIERTO gibt eine oder mehrere Bezier-Kurven basierend auf der aktuellen Position an.

```csharp
public sealed class EmfPolyBezierTo : EmfDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPolyBezierTo](emfpolybezierto#constructor)() | Initialisiert eine neue Instanz von[`EmfPolyBezierTo`](../emfpolybezierto) Klasse. |
| [EmfPolyBezierTo](emfpolybezierto#constructor_1)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfPolyBezierTo`](../emfpolybezierto) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/apoints) { get; set; } | Ruft ein Count-Length-Array von WMF-PointL-Objekten ([MS-WMF] Abschnitt 2.2.2.15) ab oder legt es fest, das die Endpunkte und Kontrollpunkte der Bezier-Kurven in logischen Einheiten angibt. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolybezierto/bounds) { get; set; } | Ruft ein 128-Bit-WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das das Begrenzungsrechteck in Geräteeinheiten angibt. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |

### Bemerkungen

Kubische Bezier-Kurven werden mit den Endpunkten und Kontrollpunkten definiert, die im Feld aPoints angegeben sind. Die erste Kurve wird vom ersten zum vierten Punkt gezeichnet, wobei der zweite und der dritte -Punkt als Kontrollpunkte verwendet werden. Jede nachfolgende Kurve in der Sequenz benötigt genau drei weitere Punkte: wird der Endpunkt der vorherigen Kurve als Startpunkt verwendet, die nächsten beiden Punkte in der -Sequenz sind Kontrollpunkte und der dritte ist der Endpunkt. Die kubischen Bezier-Kurven SOLLTEN mit dem aktuellen Stift gezeichnet werden

### Siehe auch

* class [EmfDrawingRecordType](../emfdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->