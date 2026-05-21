---
title: "EmfPolyDraw"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_POLYDRAW‑posten specificerar en uppsättning linjesegment och Bézier‑kurvor."
type: docs
weight: 89
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

EMR\_POLYDRAW‑posten specificerar en uppsättning linjesegment och Bézierkurvor.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPolyDraw`. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Initierar en ny instans av klassen [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Hämtar en array med längden Count av byte‑värden som specificerar hur varje punkt i aPoints‑arrayen som hämtas eller sätts används. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Anger en array med längden Count av byte‑värden som specificerar hur varje punkt i aPoints‑arrayen som hämtas eller sätts används. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPolyDraw`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Initierar en ny instans av klassen [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw).

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Hämtar en array med längden Count av byte‑värden som specificerar hur varje punkt i aPoints‑arrayen som hämtas eller sätts används. Detta värde MÅSTE finnas i Point‑enumerationen (avsnitt 2.1.26).

**Returns:**
byte[] – en array med längden Count av byte‑värden som specificerar hur varje punkt i aPoints‑arrayen som hämtas eller sätts används.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Anger en array med längden Count av byte‑värden som specificerar hur varje punkt i aPoints‑arrayen som hämtas eller sätts används. Detta värde MÅSTE finnas i Point‑enumerationen (avsnitt 2.1.26).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] | en array med längden Count av byte‑värden som specificerar hur varje punkt i aPoints‑arrayen som hämtas eller sätts används. |

