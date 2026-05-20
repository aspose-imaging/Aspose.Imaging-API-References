---
title: "EmfPolyBezierTo16"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYBEZIERTO16-Datensatz definiert einen oder mehrere Bézier‑Kurven basierend auf der aktuellen Position."
type: docs
weight: 88
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo16 extends EmfPolyShape
```

Der EMR\\_POLYBEZIERTO16-Datensatz spezifiziert eine oder mehrere Bézier-Kurven basierend auf der aktuellen Position.

Kubische Bézier‑Kurven werden mithilfe der Endpunkte und Steuerpunkte definiert, die im Feld aPoints angegeben sind. Die erste Kurve wird vom ersten Punkt zum vierten Punkt gezeichnet, wobei der zweite und dritte Punkt als Steuerpunkte dienen. Jede nachfolgende Kurve in der Sequenz benötigt genau drei weitere Punkte: Der Endpunkt der vorherigen Kurve wird als Ausgangspunkt verwendet, die nächsten beiden Punkte in der Sequenz sind Steuerpunkte und der dritte ist der Endpunkt. Die kubischen Bézier‑Kurven SOLLTEN mit dem aktuellen Stift gezeichnet werden
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyBezierTo16(EmfRecord record)](#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyBezierTo16`-Klasse. |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16--) | Initialisiert eine neue Instanz der `EmfPolyBezierTo16`-Klasse. |
### EmfPolyBezierTo16(EmfRecord record) {#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo16(EmfRecord record)
```


Initialisiert eine neue Instanz der `EmfPolyBezierTo16`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Der Datensatz. |

### EmfPolyBezierTo16() {#EmfPolyBezierTo16--}
```
public EmfPolyBezierTo16()
```


Initialisiert eine neue Instanz der `EmfPolyBezierTo16`-Klasse.

