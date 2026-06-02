---
title: "EmfFrameRgn"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_FRAMERGN-posten ritar en ram runt den angivna regionen med den angivna penseln."
type: docs
weight: 62
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

Den EMR_FRAMERGN-posten ritar en ram runt den angivna regionen med den angivna penseln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Initierar en ny instans av klassen [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [getRgnDataSize()](#getRgnDataSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [getIhBrush()](#getIhBrush--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index. |
| [setIhBrush(int value)](#setIhBrush-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index. |
| [getWidth()](#getWidth--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar bredden på den vertikala penseldraget, i logiska enheter. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar bredden på den vertikala penseldraget, i logiska enheter. |
| [getHeight()](#getHeight--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden på den horisontella penseldraget, i logiska enheter. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden på den horisontella penseldraget, i logiska enheter. |
| [getRgnData()](#getRgnData--) | Hämtar eller anger en RgnDataSize-längd bytearray som specificerar ett RegionData-objekt, i logiska enheter |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Hämtar eller anger en RgnDataSize-längd bytearray som specificerar ett RegionData-objekt, i logiska enheter |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Initierar en ny instans av klassen `EmfFrameRgn`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Initierar en ny instans av klassen [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

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


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselns EMF Object Table-index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar bredden på den vertikala penseldraget, i logiska enheter.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar bredden på den vertikala penseldraget, i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden på den horisontella penseldraget, i logiska enheter.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden på den horisontella penseldraget, i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Hämtar eller anger en RgnDataSize-längd bytearray som specificerar ett RegionData-objekt, i logiska enheter

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Hämtar eller anger en RgnDataSize-längd bytearray som specificerar ett RegionData-objekt, i logiska enheter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

