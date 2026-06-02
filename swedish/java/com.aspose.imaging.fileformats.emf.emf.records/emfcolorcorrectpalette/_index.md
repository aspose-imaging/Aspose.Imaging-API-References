---
title: "EmfColorCorrectPalette"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_COLORCORRECTPALETTE‑posten specificerar hur man korrigerar posterna i ett logiskt palettobjekt med hjälp av WCS 1.0‑värden."
type: docs
weight: 23
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

EMR\_COLORCORRECTPALETTE-posten specificerar hur man korrigerar posterna i ett logiskt palettobjekt med hjälp av WCS 1.0‑värden.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfColorCorrectPalette`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | Hämtar ett 32-bitars osignerat heltal som specificerar index för ett logiskt palettobjekt (avsnitt 2.2.17) i EMF‑objektstabellen (avsnitt 3.1.1.1). |
| [setIhPalette(int value)](#setIhPalette-int-) | Anger ett 32-bitars osignerat heltal som specificerar index för ett logiskt palettobjekt (avsnitt 2.2.17) i EMF‑objektstabellen (avsnitt 3.1.1.1). |
| [getNFirstEntry()](#getNFirstEntry--) | Hämtar ett 32-bitars osignerat heltal som specificerar index för den första posten som ska korrigeras. |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | Anger ett 32-bitars osignerat heltal som specificerar index för den första posten som ska korrigeras. |
| [getNPalEntries()](#getNPalEntries--) | Hämtar ett 32-bitars osignerat heltal som specificerar antalet palettposter som ska korrigeras. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Anger ett 32-bitars osignerat heltal som specificerar antalet palettposter som ska korrigeras. |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


Initierar en ny instans av klassen `EmfColorCorrectPalette`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


Hämtar ett 32-bitars osignerat heltal som specificerar index för ett logiskt palettobjekt (avsnitt 2.2.17) i EMF‑objektstabellen (avsnitt 3.1.1.1).

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


Anger ett 32-bitars osignerat heltal som specificerar index för ett logiskt palettobjekt (avsnitt 2.2.17) i EMF‑objektstabellen (avsnitt 3.1.1.1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


Hämtar ett 32-bitars osignerat heltal som specificerar index för den första posten som ska korrigeras.

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


Anger ett 32-bitars osignerat heltal som specificerar index för den första posten som ska korrigeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Hämtar ett 32-bitars osignerat heltal som specificerar antalet palettposter som ska korrigeras.

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Anger ett 32-bitars osignerat heltal som specificerar antalet palettposter som ska korrigeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

