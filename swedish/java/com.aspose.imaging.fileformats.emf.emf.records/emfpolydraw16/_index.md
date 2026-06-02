---
title: "EmfPolyDraw16"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_POLYDRAW16‑posten specificerar en uppsättning linjesegment och Bézier‑kurvor."
type: docs
weight: 90
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

EMR\_POLYDRAW16‑posten specificerar en uppsättning linjesegment och Bézierkurvor.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPolyDraw16`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Hämtar eller anger en array med längden Count av byte som specificerar punkttyperna. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Ställer in en Count-längd array av byte som specificerar punkttyperna. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPolyDraw16`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Hämtar eller anger en Count-längd array av byte som specificerar punkttyperna. Detta värde MÅSTE finnas i Point (avsnitt 2.1.26) enumerationen.

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Ställer in en Count-längd array av byte som specificerar punkttyperna. Detta värde MÅSTE finnas i Point (avsnitt 2.1.26) enumerationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] | en Count-längd array av byte som specificerar punkttyperna. |

