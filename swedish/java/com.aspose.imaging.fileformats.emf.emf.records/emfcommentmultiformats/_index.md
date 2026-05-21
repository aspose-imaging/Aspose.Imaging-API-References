---
title: "EmfCommentMultiFormats"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COMMENT_MULTIFORMATS‑posten specificerar en bild i flera grafikformat."
type: docs
weight: 30
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

Den EMR\_COMMENT\_MULTIFORMATS-posten anger en bild i flera grafikformat.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCommentMultiFormats`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Hämtar eller anger ett WMF RectL‑objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utmatningsrektangeln i logiska koordinater. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL‑objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utmatningsrektangeln i logiska koordinater. |
| [getAFormats()](#getAFormats--) | Hämtar eller anger en array med längden CountFormats av grafikformat, specificerade av EmrFormat‑objekt (avsnitt 2.2.4), i preferensordning. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Hämtar eller anger en array med längden CountFormats av grafikformat, specificerade av EmrFormat‑objekt (avsnitt 2.2.4), i preferensordning. |
| [getFormatData()](#getFormatData--) | Hämtar eller anger en variabel‑längds array av byte med bilddata för alla grafikformat som finns i denna post. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Hämtar eller anger en variabel‑längds array av byte med bilddata för alla grafikformat som finns i denna post. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCommentMultiFormats`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Hämtar eller anger ett WMF RectL‑objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utmatningsrektangeln i logiska koordinater.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Hämtar eller anger ett WMF RectL‑objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar utmatningsrektangeln i logiska koordinater.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Hämtar eller anger en array med längden CountFormats av grafikformat, specificerade av EmrFormat‑objekt (avsnitt 2.2.4), i preferensordning.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Hämtar eller anger en array med längden CountFormats av grafikformat, specificerade av EmrFormat‑objekt (avsnitt 2.2.4), i preferensordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Hämtar eller anger en variabel‑längds array av byte med bilddata för alla grafikformat som finns i denna post. Storleken på data för varje bild tillhandahålls av DataSize‑fältet i motsvarande EmrFormat‑objekt. Därmed är den totala storleken på detta fält summan av DataSize‑värdena i alla EmrFormat‑objekt. Grafikformatet för data för varje bild specificeras av Signature‑fältet i motsvarande EmrFormat‑objekt.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Hämtar eller anger en variabel‑längds array av byte med bilddata för alla grafikformat som finns i denna post. Storleken på data för varje bild tillhandahålls av DataSize‑fältet i motsvarande EmrFormat‑objekt. Därmed är den totala storleken på detta fält summan av DataSize‑värdena i alla EmrFormat‑objekt. Grafikformatet för data för varje bild specificeras av Signature‑fältet i motsvarande EmrFormat‑objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[][] |  |

