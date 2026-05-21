---
title: "EmfSetIcmMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_SETICMMODE specificerar läget för Image Color Management (ICM) för grafikoperationer."
type: docs
weight: 125
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

EMR\\_SETICMMODE-posten specificerar läget för bildfärghantering (ICM) för grafikoperationer.

När ICM‑läget är aktiverat bör färger som specificeras i EMF‑poster färgmatchas, medan standardfärgprofilen i uppspelningsenhetens kontext bör användas när en bit‑block‑överföring utförs. Om standardfärgprofilen inte önskas bör ICM‑läget stängas av innan bit‑block‑överföringen utförs.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetIcmMode`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar om ICM ska aktiveras eller inaktiveras, från ICMMode‑enumerationen (avsnitt 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar om ICM ska aktiveras eller inaktiveras, från ICMMode‑enumerationen (avsnitt 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetIcmMode`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar om ICM ska aktiveras eller inaktiveras, från ICMMode‑enumerationen (avsnitt 2.1.18). Detta värde är en del av tillståndet för uppspelningsenhetens kontext.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar om ICM ska aktiveras eller inaktiveras, från ICMMode‑enumerationen (avsnitt 2.1.18). Detta värde är en del av tillståndet för uppspelningsenhetens kontext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

