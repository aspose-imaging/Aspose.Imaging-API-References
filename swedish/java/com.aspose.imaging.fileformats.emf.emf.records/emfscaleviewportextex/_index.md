---
title: "EmfScaleViewportExtex"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SCALEVIEWPORTEXTEX‑posten omdefinierar vyporten för en enhetskontext genom att använda de förhållanden som bildas av de angivna multiplikatorerna och divisorena."
type: docs
weight: 113
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

EMR\_SCALEVIEWPORTEXTEX-posten specificerar om visningsområdet för en enhetskontext genom att använda de förhållanden som bildas av de angivna multiplikatorerna och divisionerna.

Omfånget kan inte ändras om enhetskontexten använder ett fast skalningskartläggningsläge. Endast MM\_ISOTROPIC och MM\_ANISOTROPIC är inte fasta skalor. Vyportens omfång modifieras enligt följande. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfScaleViewportExtex`. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | Initierar en ny instans av klassen [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXNum()](#getXNum--) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella multiplikanden. |
| [setXNum(int value)](#setXNum-int-) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella multiplikanden. |
| [getXDenom()](#getXDenom--) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella divisor. |
| [setXDenom(int value)](#setXDenom-int-) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella divisor. |
| [getYNum()](#getYNum--) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala multiplikanden. |
| [setYNum(int value)](#setYNum-int-) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala multiplikanden. |
| [getYDenom()](#getYDenom--) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala divisor. |
| [setYDenom(int value)](#setYDenom-int-) | Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala divisor. |
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


Initierar en ny instans av klassen `EmfScaleViewportExtex`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


Initierar en ny instans av klassen [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella multiplikanden. Kan inte vara noll.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella multiplikanden. Kan inte vara noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella divisor. Kan inte vara noll.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den horisontella divisor. Kan inte vara noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala multiplikanden. Kan inte vara noll.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala multiplikanden. Kan inte vara noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala divisor. Kan inte vara noll.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Hämtar eller anger ett 32-bitars heltal med tecken som specificerar den vertikala divisor. Kan inte vara noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

