---
title: "EmfPlusSave"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusSave‑posten sparar grafikstatusen som identifieras av ett angivet index på en stack av sparade grafikstatusar."
type: docs
weight: 51
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

EmfPlusSave-posten sparar grafikstatusen, identifierad av ett specificerat index, på en stack av sparade grafikstatusar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSave`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar en nivå att associera med grafikstatusen. |
| [setStackIndex(int value)](#setStackIndex-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar en nivå att associera med grafikstatusen. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSave`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar en nivå att associera med grafikstatusen. Värdet för nivån kan användas av en efterföljande EmfPlusRestore‑post (avsnitt 2.3.7.4) operation för att återhämta grafikstatusen.

Värde: Indexet för stacken.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar en nivå att associera med grafikstatusen. Värdet för nivån kan användas av en efterföljande EmfPlusRestore‑post (avsnitt 2.3.7.4) operation för att återhämta grafikstatusen.

Värde: Indexet för stacken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

