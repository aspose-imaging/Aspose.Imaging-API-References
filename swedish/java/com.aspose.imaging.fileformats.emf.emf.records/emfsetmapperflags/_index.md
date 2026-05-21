---
title: "EmfSetMapperFlags"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETMAPPERFLAGS‑posten specificerar parametrar för processen att matcha logiska teckensnitt mot fysiska teckensnitt som utförs av teckensnittsmapparen."
type: docs
weight: 131
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

EMR\\_SETMAPPERFLAGS-posten specificerar parametrar för processen att matcha logiska typsnitt med fysiska typsnitt, som utförs av typsnittsmapparen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetMapperFlags`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFlags()](#getFlags--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar parametrar för teckensnittsmatchningsprocessen. |
| [setFlags(int value)](#setFlags-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar parametrar för teckensnittsmatchningsprocessen. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetMapperFlags`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar parametrar för teckensnittsmatchningsprocessen.

0x00000001 Teckensnittsmapparen SKA endast välja teckensnitt som matchar bildförhållandet för utmatningsenheten, enligt hur det för närvarande definieras i uppspelningsenhetens kontext.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar parametrar för teckensnittsmatchningsprocessen.

0x00000001 Teckensnittsmapparen SKA endast välja teckensnitt som matchar bildförhållandet för utmatningsenheten, enligt hur det för närvarande definieras i uppspelningsenhetens kontext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

