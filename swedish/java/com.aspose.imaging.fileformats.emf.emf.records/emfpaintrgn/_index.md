---
title: "EmfPaintRgn"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_PAINTRGN‑posten målar det angivna området genom att använda den pensel som för närvarande är vald i uppspelningsenhetens kontext."
type: docs
weight: 80
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

EMR\_PAINTRGN‑posten målar den angivna regionen genom att använda penseln som för närvarande är vald i uppspelningsenhetens kontext.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfPaintRgn`. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Initierar en ny instans av klassen `EmfPaintRgn`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar ett 128‑bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som anger den omgivande rektangeln. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Anger ett 128‑bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som anger den omgivande rektangeln. |
| [getRgnDataSize()](#getRgnDataSize--) | Hämtar ett 32‑bitars osignerat heltal som specificerar storleken på regiondata, i byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Anger ett 32‑bitars osignerat heltal som specificerar storleken på regiondata, i byte. |
| [getRgnData()](#getRgnData--) | Hämtar en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt (avsnitt 2.2.24) i logiska enheter. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Anger en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt (avsnitt 2.2.24) i logiska enheter. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Initierar en ny instans av klassen `EmfPaintRgn`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Initierar en ny instans av klassen `EmfPaintRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar ett 128‑bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som anger den omgivande rektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Anger ett 128‑bitars WMF RectL‑objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som anger den omgivande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Hämtar ett 32‑bitars osignerat heltal som specificerar storleken på regiondata, i byte.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Anger ett 32‑bitars osignerat heltal som specificerar storleken på regiondata, i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Hämtar en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt (avsnitt 2.2.24) i logiska enheter.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Anger en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt (avsnitt 2.2.24) i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

