---
title: "EmfSelectClipPath"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SELECTCLIPPATH‑posten specificerar den aktuella vägen som ett beskärningsområde för en uppspelningsenhetens kontext och kombinerar det nya området med eventuella befintliga beskärningsområden med den angivna metoden."
type: docs
weight: 115
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

EMR\_SELECTCLIPPATH-posten specificerar den aktuella banan som ett urklippsområde för en uppspelningsenhetskontext, och kombinerar det nya området med eventuella befintliga urklippsområden med den angivna metoden.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSelectClipPath`. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Initierar en ny instans av klassen `EmfSelectClipPath`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur vägen ska användas. |
| [setRegionMode(int value)](#setRegionMode-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur vägen ska användas. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSelectClipPath`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Initierar en ny instans av klassen `EmfSelectClipPath`.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur vägen ska användas. Värdet MÅSTE finnas i uppräkningen RegionMode (avsnitt 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur vägen ska användas. Värdet MÅSTE finnas i uppräkningen RegionMode (avsnitt 2.1.29).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

