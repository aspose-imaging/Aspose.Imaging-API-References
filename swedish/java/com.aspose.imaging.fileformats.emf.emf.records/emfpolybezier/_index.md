---
title: "EmfPolyBezier"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_POLYBEZIER‑posten specificerar en eller flera Bezier-kurvor."
type: docs
weight: 85
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier extends EmfPolyShape
```

EMR\_POLYBEZIER‑posten specificerar en eller flera Bézierkurvor.

Kubiska Bezier-kurvor definieras med hjälp av ändpunkterna och kontrollpunkterna som anges i aPoints‑fältet. Den första kurvan ritas från den första punkten till den fjärde punkten, med den andra och tredje punkten som kontrollpunkter. Varje efterföljande kurva i sekvensen kräver exakt tre ytterligare punkter: slutpunkten för den föregående kurvan används som startpunkt, de två nästa punkterna i sekvensen är kontrollpunkter, och den tredje är slutpunkten. De kubiska Bezier‑kurvorna SKALL ritas med den aktuella pennan
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPolyBezier(EmfRecord source)](#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPolyBezier`. |
| [EmfPolyBezier()](#EmfPolyBezier--) | Initierar en ny instans av klassen `EmfPolyBezier`. |
### EmfPolyBezier(EmfRecord source) {#EmfPolyBezier-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPolyBezier`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfPolyBezier() {#EmfPolyBezier--}
```
public EmfPolyBezier()
```


Initierar en ny instans av klassen `EmfPolyBezier`.

