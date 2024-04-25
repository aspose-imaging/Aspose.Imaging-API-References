---
title: EmfPlusDrawClosedCurve
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusDrawClosedCurve-Datensatz gibt das Zeichnen eines geschlossenen kardinalen Splines an
type: docs
weight: 5920
url: /de/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

Der EmfPlusDrawClosedCurve-Datensatz gibt das Zeichnen eines geschlossenen kardinalen Splines an

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType – Eine 16-Bit-Ganzzahl ohne Vorzeichen, die diesen Datensatztyp als EmfPlusDrawClosedCurve aus der RecordType-Enumeration identifiziert (Abschnitt 2.1.1.1). Der Wert MUSS 0x4017. sein |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)komprimiert ist. Dieses Bit gibt an, ob das PointData-Feld komprimierte Daten angibt. Falls gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16-Bit-Ganzzahlkoordinaten an. Wenn leer, gibt PointData absolute Positionen im Koordinatenraum mit 32-Bit-Gleitkommakoordinaten an Hinweis Wenn das relative Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Ruft die Objektkennung ab oder setzt sie. Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+ -Objekttabelle zum Zeichnen der geschlossenen Kurve. Der Wert MUSS null bis einschließlich 63 sein. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Ruft den Punkt ab oder legt ihn fest. data Ein Array von Count-Punkten, die die Endpunkte der Linien angeben, die den Spline definieren. In einem geschlossenen Kardinal-Spline setzt sich die Kurve durch den letzten Punkt im PointData-Array fort und verbindet sich mit dem ersten Punkt im Array. Der Datentyp in diesem Array wird durch das Flags-Feld wie folgt angegeben: Datentyp Bedeutung EmfPlusPointR Objekt (Abschnitt 2.2.2.37) Wenn das P-Flag in den Flags gesetzt ist, spezifizieren die Punkte relative Positionen. EmfPlusPointF-Objekt (Abschnitt 2.2.2.36) Wenn die P- und C-Bits im Flags-Feld gesetzt sind, spezifizieren die Punkte absolute Positionen. EmfPlusPoint-Objekt (Abschnitt 2.2.2.35) Wenn das P-Bit gelöscht und das C-Bit im Flags-Feld gesetzt ist, geben die Punkte relative Positionen an. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)ist relativ. Dieses Bit gibt an, ob das PointData-Feld relative oder absolute Positionen angibt. Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zu der durch das vorherige Element im Array angegebenen Position ist. Im Fall des ersten -Elements in PointData wird eine frühere Position bei den Koordinaten (0,0) angenommen. Wenn es leer ist, gibt PointData absolute Positionen gemäß dem C-Flag an. Hinweis Wenn dieses Flag gesetzt ist, ist das Compressed-Flag (oben) undefiniert und MUSS ignoriert werden |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Ruft die Spannung ab oder legt sie fest. Eine 32-Bit-Gleitkommazahl, die angibt, wie stark sich der Spline biegt, wenn er durch die Punkte läuft. Ein Wert von 0 gibt an, dass der Spline eine Folge von geraden Linien ist. Mit steigendem Wert wird die Kurve runder. Weitere Informationen finden Sie unter [SPLINE77] und [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Siehe auch

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
