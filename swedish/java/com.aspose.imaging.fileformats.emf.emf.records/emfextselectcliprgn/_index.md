---
title: "EmfExtSelectClipRgn"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_EXTSELECTCLIPRGN-posten kombinerar den angivna regionen med den aktuella klippregionen med hjälp av det angivna läget."
type: docs
weight: 55
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

EMR\_EXTSELECTCLIPRGN-posten kombinerar den angivna regionen med den aktuella klippregionen med hjälp av det angivna läget. Observera att fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.2.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Initierar en ny instans av klassen `EmfExtSelectClipRgn`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken på regiondata i byte. |
| [getRegionMode()](#getRegionMode--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur regionen ska användas. |
| [setRegionMode(int value)](#setRegionMode-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur regionen ska användas. |
| [getRgnData()](#getRgnData--) | Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt i logiska enheter. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt i logiska enheter. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Initierar en ny instans av klassen `EmfExtSelectClipRgn`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Initierar en ny instans av klassen `EmfExtSelectClipRgn`.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken på regiondata i byte.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken på regiondata i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur regionen ska användas. Värdet MÅSTE finnas i uppräkningen RegionMode (avsnitt 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur regionen ska användas. Värdet MÅSTE finnas i uppräkningen RegionMode (avsnitt 2.1.29).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt i logiska enheter. Om RegionMode är RGN\_COPY kan denna data utelämnas och klippregionen BÖR sättas till standardklippregionen (NULL).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Hämtar eller anger en bytearray med längden RgnDataSize som specificerar ett RegionData‑objekt i logiska enheter. Om RegionMode är RGN\_COPY kan denna data utelämnas och klippregionen BÖR sättas till standardklippregionen (NULL).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

