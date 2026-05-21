---
title: "EmfRecord"
second_title: "Aspose.Imaging för Java API-referens"
description: "Basklass för EMF-poster Alla EMF-poster MÅSTE ha en längd som är en multipel av 4 byte."
type: docs
weight: 106
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Basklass för EMF‑poster. Alla EMF‑poster MÅSTE ha en längd som är en multipel av 4 byte. Detta visas i de generiska strukturerna för de föregående EMF‑posttyperna genom att inkludera AlignmentPadding‑fält där det är lämpligt i slutet av dessa strukturer. Innehållet i AlignmentPadding‑fält måste alltid ignoreras. För korthet visas dessa fält inte i varje enskild EMF‑postdefinition.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Initierar en ny instans av klassen `EmfRecord`. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfRecord`. |
| [EmfRecord(int type)](#EmfRecord-int-) | Initierar en ny instans av klassen `EmfRecord`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Hämtar typen. |
| [setType(int value)](#setType-int-) | Ställer in typen. |
| [getSize()](#getSize--) | Hämtar storleken på posten |
| [setSize(int value)](#setSize-int-) | Anger storleken på posten |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Initierar en ny instans av klassen `EmfRecord`.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Initierar en ny instans av klassen `EmfRecord`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Initierar en ny instans av klassen `EmfRecord`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Posttypen. |

### getType() {#getType--}
```
public int getType()
```


Hämtar typen.

**Returns:**
int – typen.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ställer in typen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Typen. |

### getSize() {#getSize--}
```
public int getSize()
```


Hämtar storleken på posten

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Anger storleken på posten

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

