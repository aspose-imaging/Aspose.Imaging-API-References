---
title: EmfPlusFillPolygon
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusFillPolygon-Datensatz gibt das Füllen des Inneren eines Polygons an.
type: docs
weight: 6100
url: /de/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

Der EmfPlusFillPolygon-Datensatz gibt das Füllen des Inneren eines Polygons an.

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusFillPolygon`](../emfplusfillpolygon) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid) { get; set; } | Ruft die Pinselkennung ab oder legt sie fest. Eine 32-Bit-Ganzzahl ohne Vorzeichen, die den Pinsel definiert, dessen Inhalt durch das S-Bit im Flags-Feld bestimmt wird. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist. Falls gesetzt, spezifiziert BrushId eine Farbe als ein EmfPlusARGB-Objekt (Abschnitt 2.2.2.1). Wenn klar, enthält BrushId den Index eines EmfPlusBrush-Objekts (Abschnitt 2.2.1.1) in der EMF+-Objekttabelle. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz komprimiert ist. Falls gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16-Bit- -Ganzzahlkoordinaten an. Wenn leer, gibt PointData absolute Positionen im Koordinatenraum mit 32-Bit-Gleitkommakoordinaten an. |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Instanz relativ ist. Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zu der Position ist, die durch das vorherige Element im Array angegeben wurde. Im Fall des ersten Elements in PointData wird eine vorherige -Position bei den Koordinaten (0,0) angenommen. Wenn leer, gibt PointData absolute Positionen gemäß dem C-Flag an. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata) { get; set; } | Ruft den Punkt ab oder legt ihn fest. data Ein Array von Zählpunkten, die die Scheitelpunkte des Polygons definieren. Die ersten beiden Punkte im Array geben die erste Seite des Polygons an. Jeder zusätzliche Punkt gibt eine neue Seite an, deren Eckpunkte den Punkt und den vorherigen Punkt einschließen. Wenn der letzte Punkt und der erste Punkt nicht zusammenfallen, geben sie die letzte Seite des Polygons an. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->