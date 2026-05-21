---
title: "EmfPolyBezier16"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYBEZIER16-Datensatz gibt einen oder mehrere Bézierkurven an."
type: docs
weight: 86
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier16 extends EmfPolyShape
```

Der EMR\_POLYBEZIER16-Datensatz gibt einen oder mehrere Bézierkurven an. Die Kurven werden mit dem aktuellen Stift gezeichnet.

Kubische Bézier‑Kurven werden mithilfe der Endpunkte und Steuerpunkte definiert, die im Feld aPoints angegeben sind. Die erste Kurve wird vom ersten Punkt zum vierten Punkt gezeichnet, wobei der zweite und dritte Punkt als Steuerpunkte dienen. Jede nachfolgende Kurve in der Sequenz benötigt genau drei weitere Punkte: Der Endpunkt der vorherigen Kurve wird als Ausgangspunkt verwendet, die nächsten beiden Punkte in der Sequenz sind Steuerpunkte und der dritte ist der Endpunkt. Die kubischen Bézier‑Kurven SOLLTEN mit dem aktuellen Stift gezeichnet werden
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyBezier16(EmfRecord source)](#EmfPolyBezier16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyBezier16`-Klasse. |
| [EmfPolyBezier16()](#EmfPolyBezier16--) | Initialisiert eine neue Instanz der `EmfPolyBezier16`-Klasse. |
### EmfPolyBezier16(EmfRecord source) {#EmfPolyBezier16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier16(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPolyBezier16`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPolyBezier16() {#EmfPolyBezier16--}
```
public EmfPolyBezier16()
```


Initialisiert eine neue Instanz der `EmfPolyBezier16`-Klasse.

