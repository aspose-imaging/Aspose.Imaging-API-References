---
title: "EmfExtCreatePen"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_EXTCREATEPEN-posten definierar en utökad logisk penna för grafikoperationer."
type: docs
weight: 52
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

EMR\_EXTCREATEPEN-posten definierar en utökad logisk penna för grafikoperationer. En valfri DIB kan specificeras för att användas som linjestil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfExtCreatePen`. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Initierar en ny instans av klassen `EmfExtCreatePen`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPen()](#getIhPen--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det utökade logiska pennobjektet i EMF‑objektstabellen (avsnitt 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det utökade logiska pennobjektet i EMF‑objektstabellen (avsnitt 3.1.1.1). |
| [getElp()](#getElp--) | Hämtar eller anger ett LogPenEx‑objekt (avsnitt 2.2.20) som specificerar en utökad logisk penna med attribut inklusive en valfri radstil‑array. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Hämtar eller anger ett LogPenEx‑objekt (avsnitt 2.2.20) som specificerar en utökad logisk penna med attribut inklusive en valfri radstil‑array. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Hämtar eller anger en valfri buffer som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en valfri buffer som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Initierar en ny instans av klassen `EmfExtCreatePen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Initierar en ny instans av klassen `EmfExtCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det utökade logiska pennobjektet i EMF‑objektstabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att objektet kan återanvändas eller modifieras.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det utökade logiska pennobjektet i EMF‑objektstabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att objektet kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Hämtar eller anger ett LogPenEx‑objekt (avsnitt 2.2.20) som specificerar en utökad logisk penna med attribut inklusive en valfri radstil‑array.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Hämtar eller anger ett LogPenEx‑objekt (avsnitt 2.2.20) som specificerar en utökad logisk penna med attribut inklusive en valfri radstil‑array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Hämtar eller anger en valfri buffer som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). Den behöver inte vara sammanhängande med den fasta delen av EMR\_EXTCREATEPEN‑posten.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en valfri buffer som innehåller en packad DIB i form av ett WMF DeviceIndependentBitmap‑objekt ([MS-WMF] avsnitt 2.2.2.9). Den behöver inte vara sammanhängande med den fasta delen av EMR\_EXTCREATEPEN‑posten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

