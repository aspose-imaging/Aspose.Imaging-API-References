---
title: "EmfPlusRecord"
second_title: "Aspose.Imaging för Java API-referens"
description: "Emf‑basposttypen."
type: docs
weight: 46
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Emf+-basposttyp.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Initierar en ny instans av klassen `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusRecord`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Hämtar ett 16‑bitars osignerat heltal som identifierar posttypen. |
| [getFlags()](#getFlags--) | Hämtar ett 16‑bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [setFlags(short value)](#setFlags-short-) | Anger ett 16‑bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [getSize()](#getSize--) | Hämtar ett 32‑bitars osignerat heltal som specificerar det 32‑bitars‑justerade antalet byte i hela posten, inklusive 12‑byte posthuvudet och post‑specifik data. |
| [setSize(int value)](#setSize-int-) | Anger ett 32‑bitars osignerat heltal som specificerar det 32‑bitars‑justerade antalet byte i hela posten, inklusive 12‑byte posthuvudet och post‑specifik data. |
| [getDataSize()](#getDataSize--) | Hämtar ett 32‑bitars osignerat heltal som MÅSTE definiera det 32‑bitars\\u2013justerade antalet byte data i det efterföljande RecordData‑fältet. |
| [setDataSize(int value)](#setDataSize-int-) | Anger ett 32‑bitars osignerat heltal som MÅSTE definiera det 32‑bitars\\u2013justerade antalet byte data i det efterföljande RecordData‑fältet. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Initierar en ny instans av klassen `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusRecord`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getType() {#getType--}
```
public short getType()
```


Hämtar ett 16‑bitars osignerat heltal som identifierar posttypen.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Hämtar ett 16‑bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur.

**Returns:**
short - Flaggorna.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Anger ett 16‑bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short | Flaggorna. |

### getSize() {#getSize--}
```
public int getSize()
```


Hämtar ett 32‑bitars osignerat heltal som specificerar det 32‑bitars‑justerade antalet byte i hela posten, inklusive 12‑byte posthuvudet och post‑specifik data.

**Returns:**
int - Storleken.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Anger ett 32‑bitars osignerat heltal som specificerar det 32‑bitars‑justerade antalet byte i hela posten, inklusive 12‑byte posthuvudet och post‑specifik data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Storleken. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Hämtar ett 32-bit osignerat heltal som MÅSTE definiera det 32-bit\u2013justerade antalet byte data i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑byte posthuvudet.

**Returns:**
int - Datastorleken.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Ställer in ett 32-bit osignerat heltal som MÅSTE definiera det 32-bit\u2013justerade antalet byte data i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑byte posthuvudet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Datastorleken. |

