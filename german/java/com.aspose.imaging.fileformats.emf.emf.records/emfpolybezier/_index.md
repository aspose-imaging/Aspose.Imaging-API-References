---
title: "EmfPolyBezier"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYBEZIER‑Datensatz spezifiziert einen oder mehrere Bézier‑Kurven."
type: docs
weight: 85
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

Der EMR\\_POLYBEZIER-Datensatz spezifiziert eine oder mehrere Bézier-Kurven.

Kubische Bézier‑Kurven werden mithilfe der Endpunkte und Steuerpunkte definiert, die im Feld aPoints angegeben sind. Die erste Kurve wird vom ersten Punkt zum vierten Punkt gezeichnet, wobei der zweite und dritte Punkt als Steuerpunkte dienen. Jede nachfolgende Kurve in der Sequenz benötigt genau drei weitere Punkte: Der Endpunkt der vorherigen Kurve wird als Ausgangspunkt verwendet, die nächsten beiden Punkte in der Sequenz sind Steuerpunkte und der dritte ist der Endpunkt. Die kubischen Bézier‑Kurven SOLLTEN mit dem aktuellen Stift gezeichnet werden
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyBezier` Klasse. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Initialisiert eine neue Instanz der `EmfPolyBezier` Klasse. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPolyBezier` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Initialisiert eine neue Instanz der `EmfPolyBezier` Klasse.

