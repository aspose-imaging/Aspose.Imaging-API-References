---
title: "EmfCreateBrushIndirect"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_CREATEBRUSHINDIRECT-posten definierar en logisk pensel för grafikoperationer."
type: docs
weight: 35
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

Den EMR\_CREATEBRUSHINDIRECT-posten definierar en logisk pensel för grafikoperationer.

Det logiska penselobjektet som definieras av denna post kan väljas in i uppspelningsenhetens kontext av en EMR\_SELECTOBJECT-post (avsnitt 2.3.8.5), som specificerar den logiska penseln att använda i efterföljande grafikoperationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Initierar en ny instans av klassen `EmfCreateBrushIndirect`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska penselobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska penselobjektet i EMF Object Table (avsnitt 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | Hämtar eller anger ett LogBrushEx-objekt (avsnitt 2.2.12) som specificerar stil, färg och mönster för den logiska penseln. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Hämtar eller anger ett LogBrushEx-objekt (avsnitt 2.2.12) som specificerar stil, färg och mönster för den logiska penseln. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Initierar en ny instans av klassen `EmfCreateBrushIndirect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Initierar en ny instans av klassen `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska penselobjektet i EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska penselobjektet i EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan återanvändas eller modifieras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Hämtar eller anger ett LogBrushEx-objekt (avsnitt 2.2.12) som specificerar stil, färg och mönster för den logiska penseln. BrushStyle‑fältet i detta objekt MÅSTE vara BS\_SOLID, BS\_HATCHED eller BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Hämtar eller anger ett LogBrushEx-objekt (avsnitt 2.2.12) som specificerar stil, färg och mönster för den logiska penseln. BrushStyle‑fältet i detta objekt MÅSTE vara BS\_SOLID, BS\_HATCHED eller BS\_NULL.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

