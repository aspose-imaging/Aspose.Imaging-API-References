---
title: "EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_CREATEDIBPATTERNBRUSHPT‑posten definierar en mönsterpensel för grafikoperationer."
type: docs
weight: 38
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

EMR\_CREATEDIBPATTERNBRUSHPT‑posten definierar en mönsterpensel för grafikoperationer. Mönstret specificeras av en DIB.

Mönsterpenselobjektet som definieras av denna post kan väljas in i uppspelningsenhetens kontext av en EMR\_SELECTOBJECT‑post (avsnitt 2.3.8.5), som specificerar vilken mönsterpensel som ska användas i efterföljande grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreateDibPatternBrushPt`. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | Initierar en ny instans av klassen `EmfCreateDibPatternBrushPt`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för mönsterpenselobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för mönsterpenselobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). |
| [getUsage()](#getUsage--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i DIB‑huvudet ska tolkas. |
| [setUsage(int value)](#setUsage-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i DIB‑huvudet ska tolkas. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Hämtar eller anger en buffert som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreateDibPatternBrushPt`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


Initierar en ny instans av klassen `EmfCreateDibPatternBrushPt`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för mönsterpenselobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för mönsterpenselobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i DIB‑huvudet ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i DIB‑huvudet ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Hämtar eller anger en buffert som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). Det krävs inte att den är sammanhängande med den fasta delen av EMR\_CREATEDIBPATTERNBRUSHPT‑posten.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). Det krävs inte att den är sammanhängande med den fasta delen av EMR\_CREATEDIBPATTERNBRUSHPT‑posten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

