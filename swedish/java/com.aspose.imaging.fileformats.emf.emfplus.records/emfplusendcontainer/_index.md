---
title: "EmfPlusEndContainer"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusEndContainer-posten stänger en grafikstatusbehållare som tidigare öppnades av en startbehållaroperation."
type: docs
weight: 30
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

EmfPlusEndContainer-posten stänger en grafikstatusbehållare som tidigare öppnades av en startbehållaroperation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusEndContainer`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för en grafikstatusbehållare. |
| [setStackIndex(int value)](#setStackIndex-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för en grafikstatusbehållare. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusEndContainer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för en grafikstatusbehållare. Indexet MUST matcha värdet som är associerat med en grafikstatusbehållare som öppnats av en tidigare EmfPlusBeginContainer (avsnitt 2.3.7.1) eller EmfPlusBeginContainerNoParams‑post (avsnitt 2.3.7.2).

Värde: Indexet för stacken.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar indexet för en grafikstatusbehållare. Indexet MUST matcha värdet som är associerat med en grafikstatusbehållare som öppnats av en tidigare EmfPlusBeginContainer (avsnitt 2.3.7.1) eller EmfPlusBeginContainerNoParams‑post (avsnitt 2.3.7.2).

Värde: Indexet för stacken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

