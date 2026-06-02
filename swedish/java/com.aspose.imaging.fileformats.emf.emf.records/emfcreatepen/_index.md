---
title: "EmfCreatePen"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_CREATEPEN‑posten definierar en logisk penna för grafikoperationer."
type: docs
weight: 41
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

Den EMR\_CREATEPEN-posten definierar en logisk penna för grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreatePen`. |
| [EmfCreatePen()](#EmfCreatePen--) | Initierar en ny instans av klassen `EmfCreatePen`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPen()](#getIhPen--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det logiska pennaobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det logiska pennaobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). |
| [getLogPen()](#getLogPen--) | Hämtar eller anger ett LogPen‑objekt (avsnitt 2.2.19) som specificerar stil, bredd och färg för den logiska pennan. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Hämtar eller anger ett LogPen‑objekt (avsnitt 2.2.19) som specificerar stil, bredd och färg för den logiska pennan. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreatePen`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Initierar en ny instans av klassen `EmfCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det logiska pennaobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att objektet kan återanvändas eller modifieras.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för det logiska pennaobjektet i EMF‑objektabellen (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att objektet kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Hämtar eller anger ett LogPen‑objekt (avsnitt 2.2.19) som specificerar stil, bredd och färg för den logiska pennan.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Hämtar eller anger ett LogPen‑objekt (avsnitt 2.2.19) som specificerar stil, bredd och färg för den logiska pennan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

