---
title: "EmfSetBkMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETBKMODE‑posten specificerar bakgrundens blandningsläge för uppspelningsenhetens kontext."
type: docs
weight: 120
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

EMR\\_SETBKMODE‑posten specificerar bakgrundens blandningsläge för uppspelningsenhetens kontext. Bakgrundens blandningsläge används med text, skuggade penslar och pennstilar som inte är solida linjer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetBkMode`. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Initierar en ny instans av klassen `EmfSetBkMode`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bakgrundsläget och MÅSTE finnas i uppräkningen BackgroundMode (avsnitt 2.1.4). |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bakgrundsläget och MÅSTE finnas i uppräkningen BackgroundMode (avsnitt 2.1.4). |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetBkMode`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Initierar en ny instans av klassen `EmfSetBkMode`.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bakgrundsläget och MÅSTE finnas i uppräkningen BackgroundMode (avsnitt 2.1.4).

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bakgrundsläget och MÅSTE finnas i uppräkningen BackgroundMode (avsnitt 2.1.4).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

