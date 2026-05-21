---
title: "EmfPlusRestore"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusRestore‑posten återställer grafikstatusen som identifieras av ett angivet index från en stack av sparade grafikstatusar."
type: docs
weight: 49
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

EmfPlusRestore-posten återställer grafikstatusen, identifierad av ett specificerat index, från en stack av sparade grafikstatusar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusRestore`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar nivån som är associerad med en grafikstatus. |
| [setStackIndex(int value)](#setStackIndex-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar nivån som är associerad med en grafikstatus. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusRestore`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar nivån som är associerad med en grafikstatus. Nivåvärdet tilldelades grafikstatusen av en tidigare EmfPlusSave‑post (avsnitt 2.3.7.5).

Värde: Indexet för stacken.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar nivån som är associerad med en grafikstatus. Nivåvärdet tilldelades grafikstatusen av en tidigare EmfPlusSave‑post (avsnitt 2.3.7.5).

Värde: Indexet för stacken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

