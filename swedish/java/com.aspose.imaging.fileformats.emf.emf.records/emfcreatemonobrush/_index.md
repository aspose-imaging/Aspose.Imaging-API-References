---
title: "EmfCreateMonoBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_CREATEMONOBRUSH-posten definierar en monokrom mönsterborste för grafikoperationer."
type: docs
weight: 39
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

EMR\_CREATEMONOBRUSH-posten definierar en monokrom mönsterborste för grafikoperationer. Mönstret specificeras av en monokrom DIB.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreateMonoBrush`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för monokroma mönsterpenselobjektet i EMF-objektabellen (avsnitt 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för monokroma mönsterpenselobjektet i EMF-objektabellen (avsnitt 3.1.1.1). |
| [getUsage()](#getUsage--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i DIB‑huvudet ska tolkas. |
| [setUsage(int value)](#setUsage-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i DIB‑huvudet ska tolkas. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Hämtar eller anger en buffert som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreateMonoBrush`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för monokroma mönsterpenselobjektet i EMF-objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för monokroma mönsterpenselobjektet i EMF-objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

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

