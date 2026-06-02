---
title: "EmfSetPaletteEntries"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETPALETTEENTRIES‑posten definierar RGB-färgvärden i ett intervall av poster för ett befintligt LogPalette-objekt enligt avsnitt 2.2.17."
type: docs
weight: 134
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSetPaletteEntries extends EmfObjectManipulationRecordType
```

EMR\\_SETPALETTEENTRIES-posten definierar RGB-färgvärden i ett intervall av poster för ett befintligt LogPalette-objekt (avsnitt 2.2.17).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetPaletteEntries(EmfRecord source)](#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetPaletteEntries`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPal()](#getIhPal--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar palettens EMF Object Table-index. |
| [setIhPal(int value)](#setIhPal-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar palettens EMF Object Table-index. |
| [getStart()](#getStart--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för den första posten som ska anges. |
| [setStart(int value)](#setStart-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för den första posten som ska anges. |
| [getNumberofEntries()](#getNumberofEntries--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster. |
| [setNumberofEntries(int value)](#setNumberofEntries-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster. |
| [getArgb32PalEntries()](#getArgb32PalEntries--) | Hämtar eller anger en array av LogPaletteEntry‑objekt (avsnitt 2.2.18), med längden NumberOfEntries, som specificerar palettposternas data. |
| [setArgb32PalEntries(int[] value)](#setArgb32PalEntries-int---) | Hämtar eller anger en array av LogPaletteEntry‑objekt (avsnitt 2.2.18), med längden NumberOfEntries, som specificerar palettposternas data. |
### EmfSetPaletteEntries(EmfRecord source) {#EmfSetPaletteEntries-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPaletteEntries(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetPaletteEntries`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar palettens EMF Object Table-index.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar palettens EMF Object Table-index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStart() {#getStart--}
```
public int getStart()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för den första posten som ska anges.

**Returns:**
int
### setStart(int value) {#setStart-int-}
```
public void setStart(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för den första posten som ska anges.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNumberofEntries() {#getNumberofEntries--}
```
public int getNumberofEntries()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster.

**Returns:**
int
### setNumberofEntries(int value) {#setNumberofEntries-int-}
```
public void setNumberofEntries(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet poster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getArgb32PalEntries() {#getArgb32PalEntries--}
```
public int[] getArgb32PalEntries()
```


Hämtar eller anger en array av LogPaletteEntry‑objekt (avsnitt 2.2.18), med längden NumberOfEntries, som specificerar palettposternas data. Values‑medlemmarna innehåller inga värden.

**Returns:**
int[]
### setArgb32PalEntries(int[] value) {#setArgb32PalEntries-int---}
```
public void setArgb32PalEntries(int[] value)
```


Hämtar eller anger en array av LogPaletteEntry‑objekt (avsnitt 2.2.18), med längden NumberOfEntries, som specificerar palettposternas data. Values‑medlemmarna innehåller inga värden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

