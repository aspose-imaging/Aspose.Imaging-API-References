---
title: "EmfPlusBeginContainerNoParams"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusBeginContainerNoParams-posten öppnar en ny grafikstatusbehållare."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

EmfPlusBeginContainerNoParams-posten öppnar en ny grafikstatusbehållare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusBeginContainerNoParams`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. |
| [setStackIndex(int value)](#setStackIndex-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusBeginContainerNoParams`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. Indexet MÅSTE refereras av en efterföljande EmfPlusEndContainer‑post (avsnitt 2.3.7.3) för att stänga grafikstatusbehållaren.

Värde: Indexet för stacken.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar ett index att associera med grafikstatusbehållaren. Indexet MÅSTE refereras av en efterföljande EmfPlusEndContainer‑post (avsnitt 2.3.7.3) för att stänga grafikstatusbehållaren.

Värde: Indexet för stacken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

