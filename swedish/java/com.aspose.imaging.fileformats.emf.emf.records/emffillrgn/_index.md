---
title: "EmfFillRgn"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_FILLRGN-posten fyller den angivna regionen genom att använda den angivna penseln."
type: docs
weight: 59
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

Den EMR_FILLRGN-posten fyller den angivna regionen genom att använda den angivna penseln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | Initierar en ny instans av klassen `EmfFillRgn`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [getRgnDataSize()](#getRgnDataSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [getIhBrush()](#getIhBrush--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index för att fylla regionen. |
| [setIhBrush(int value)](#setIhBrush-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index för att fylla regionen. |
| [getRgnData()](#getRgnData--) | Hämtar eller anger en RgnDataSize-längd array av byte som innehåller ett RegionData (avsnitt 2.2.24) objekt. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Hämtar eller anger en RgnDataSize-längd array av byte som innehåller ett RegionData (avsnitt 2.2.24) objekt. |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Initierar en ny instans av klassen `EmfFillRgn`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Initierar en ny instans av klassen `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index för att fylla regionen.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index för att fylla regionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Hämtar eller anger en RgnDataSize-längd array av byte som innehåller ett RegionData (avsnitt 2.2.24) objekt.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Hämtar eller anger en RgnDataSize-längd array av byte som innehåller ett RegionData (avsnitt 2.2.24) objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

