---
title: "EmfPolyBezierTo16"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_POLYBEZIERTO16-posten specificerar en eller flera Bézier-kurvor baserade på den aktuella positionen."
type: docs
weight: 88
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolybezierto16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyBezierTo16 extends EmfPolyShape
```

EMR\_POLYBEZIERTO16‑posten specificerar en eller flera Bézierkurvor baserade på den aktuella positionen.

Kubiska Bezier-kurvor definieras med hjälp av ändpunkterna och kontrollpunkterna som anges i aPoints‑fältet. Den första kurvan ritas från den första punkten till den fjärde punkten, med den andra och tredje punkten som kontrollpunkter. Varje efterföljande kurva i sekvensen kräver exakt tre ytterligare punkter: slutpunkten för den föregående kurvan används som startpunkt, de två nästa punkterna i sekvensen är kontrollpunkter, och den tredje är slutpunkten. De kubiska Bezier‑kurvorna SKALL ritas med den aktuella pennan
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPolyBezierTo16(EmfRecord record)](#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPolyBezierTo16`. |
| [EmfPolyBezierTo16()](#EmfPolyBezierTo16--) | Initierar en ny instans av klassen `EmfPolyBezierTo16`. |
### EmfPolyBezierTo16(EmfRecord record) {#EmfPolyBezierTo16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyBezierTo16(EmfRecord record)
```


Initierar en ny instans av klassen `EmfPolyBezierTo16`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfPolyBezierTo16() {#EmfPolyBezierTo16--}
```
public EmfPolyBezierTo16()
```


Initierar en ny instans av klassen `EmfPolyBezierTo16`.

