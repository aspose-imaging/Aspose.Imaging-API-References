---
title: "EmfInvertRgn"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_INVERTRGN-posten inverterar färgerna i den angivna regionen."
type: docs
weight: 67
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

Den EMR_INVERTRGN-posten inverterar färgerna i den angivna regionen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfInvertRgn`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som specificerar den omgivande rektangeln. |
| [getRgnDataSize()](#getRgnDataSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [getRgnData()](#getRgnData--) | Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData-objekt i logiska enheter. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData-objekt i logiska enheter. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


Initierar en ny instans av klassen `EmfInvertRgn`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

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

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData-objekt i logiska enheter.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData-objekt i logiska enheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

