---
title: EmfPlusFillClosedCurve
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusFillClosedCurve-Datensatz gibt an das Innere eines geschlossenen Kardinal-Splines zu füllen
type: docs
weight: 6060
url: /de/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

Der EmfPlusFillClosedCurve-Datensatz gibt an, das Innere eines geschlossenen Kardinal-Splines zu füllen

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Ruft die Pinselkennung ab oder legt sie fest. Eine 32-Bit-Ganzzahl ohne Vorzeichen, die den EmfPlusBrush angibt, dessen Inhalt durch das S-Bit im Flags-Feld bestimmt wird. Dieser Pinsel wird verwendet, um das Innere des geschlossenen Kardinal-Splines zu füllen. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)ist komprimiert. Dieses Bit gibt an, ob das PointData-Feld komprimierte Daten angibt. Falls gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16-Bit- -Ganzzahlkoordinaten an. Wenn es leer ist, gibt PointData absolute Positionen im -Koordinatenraum mit 32-Bit-Gleitkommakoordinaten an. ---------------------- Eine "gewundene" Füllung Die Operation füllt Bereiche gemäß der "gerade-ungerade Parität"-Regel. Gemäß dieser Regel kann ein Testpunkt innerhalb oder außerhalb einer geschlossenen Kurve wie folgt bestimmt werden: Ziehen Sie eine Linie vom Testpunkt zu einem Punkt, der von der Kurve entfernt ist. Wenn diese Linie die Kurve ungerade oft kreuzt, liegt der Testpunkt innerhalb der Kurve; andernfalls liegt der Testpunkt außerhalb der Kurve. --------------------- Eine "alternative" Fülloperation füllt Bereiche gemäß der "Nicht-Null"-Regel . Gemäß dieser Regel kann ein Testpunkt innerhalb oder außerhalb einer geschlossenen Kurve wie folgt bestimmt werden: Ziehen Sie eine Linie von einem Testpunkt zu einem Punkt, der von der Kurve entfernt ist. Zählen Sie, wie oft die Kurve die Testlinie von links nach rechts kreuzt, und zählen Sie, wie oft die Kurve die -Testlinie von rechts nach links kreuzt. Wenn diese beiden Zahlen gleich sind, liegt der Testpunkt außerhalb der Kurve; Andernfalls liegt der Testpunkt innerhalb der Kurve. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Ruft einen Wert ab oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist. Falls gesetzt, gibt BrushId eine Farbe als EmfPlusARGB-Objekt an (Abschnitt 2.2.2.1). Wenn leer, enthält BrushId den Index eines EmfPlusBrush-Objekts (Abschnitt 2.2.1.1 ) in der EMF+-Objekttabelle. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Ruft den Punkt ab oder legt ihn fest. data Ein Array von Count-Punkten, die die Endpunkte der Linien angeben, die den Spline definieren. In einem geschlossenen Kardinal-Spline wird die Kurve durch den letzten Punkt im Array PointData fortgesetzt und mit dem ersten Punkt im Array verbunden |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) ist relativ. Dieses Bit gibt an, ob das PointData-Feld relative oder absolute Positionen angibt. Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zu der durch das vorherige Element im Array angegebenen Position ist. Im Fall des ersten Elements in PointData wird eine frühere Position bei den Koordinaten (0,0) angenommen. Wenn leer, gibt PointData absolute Positionen gemäß dem C-Flag an. Hinweis Wenn dieses Flag gesetzt ist, ist das C-Flag (oben) undefiniert und MUSS ignoriert werden. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Ruft die Spannung ab oder legt sie fest Ein 32-Bit-Gleitkommawert, der angibt, wie eng sich der Spline biegt, wenn er durch die Punkte verläuft. Ein Wert von 0,0 gibt an, dass der Spline eine Folge gerader Linien ist. Mit zunehmendem Wert wird die Kurve runder. Weitere Informationen finden Sie unter [SPLINE77] und [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)ist gewunden. Dieses Bit zeigt an, wie die Fülloperation durchzuführen ist. Wenn gesetzt, ist die Füllung eine "gewundene" Füllung. Wenn klar, ist die Füllung eine "alternative" Füllung. |

### Siehe auch

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
