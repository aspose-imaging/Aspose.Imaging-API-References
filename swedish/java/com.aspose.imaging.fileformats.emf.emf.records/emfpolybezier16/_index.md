---
title: "EmfPolyBezier16"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_POLYBEZIER16-posten specificerar en eller flera Bezier-kurvor."
type: docs
weight: 86
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezier16 extends EmfPolyShape
```

EMR\_POLYBEZIER16-posten specificerar en eller flera Bezier-kurvor. Kurvorna ritas med den aktuella pennan.

Kubiska Bezier-kurvor definieras med hjälp av ändpunkterna och kontrollpunkterna som anges i aPoints‑fältet. Den första kurvan ritas från den första punkten till den fjärde punkten, med den andra och tredje punkten som kontrollpunkter. Varje efterföljande kurva i sekvensen kräver exakt tre ytterligare punkter: slutpunkten för den föregående kurvan används som startpunkt, de två nästa punkterna i sekvensen är kontrollpunkter, och den tredje är slutpunkten. De kubiska Bezier‑kurvorna SKALL ritas med den aktuella pennan
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPolyBezier16(EmfRecord source)](#EmfPolyBezier16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPolyBezier16`. |
| [EmfPolyBezier16()](#EmfPolyBezier16--) | Initierar en ny instans av klassen `EmfPolyBezier16`. |
### EmfPolyBezier16(EmfRecord source) {#EmfPolyBezier16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezier16(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPolyBezier16`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfPolyBezier16() {#EmfPolyBezier16--}
```
public EmfPolyBezier16()
```


Initierar en ny instans av klassen `EmfPolyBezier16`.

