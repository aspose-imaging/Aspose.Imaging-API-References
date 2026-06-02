---
title: "EmfSelectPalette"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SELECTPALETTE‑posten specificerar en logisk palett för uppspelningsenhetens kontext."
type: docs
weight: 117
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfSelectPalette extends EmfObjectManipulationRecordType
```

EMR\_SELECTPALETTE-posten specificerar en logisk palett för uppspelningsenhetskontexten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSelectPalette(EmfRecord source)](#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSelectPalette`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIhPal()](#getIhPal--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett LogPalette‑objekt (avsnitt 2.2.17) i EMF‑objektstabellen eller värdet DEFAULT\_PALETTE, vilket är indexet för en standardobjektspalett från StockObject‑enumerationen (avsnitt 2.1.31). |
| [setIhPal(int value)](#setIhPal-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett LogPalette‑objekt (avsnitt 2.2.17) i EMF‑objektstabellen eller värdet DEFAULT\_PALETTE, vilket är indexet för en standardobjektspalett från StockObject‑enumerationen (avsnitt 2.1.31). |
### EmfSelectPalette(EmfRecord source) {#EmfSelectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectPalette(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSelectPalette`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett LogPalette‑objekt (avsnitt 2.2.17) i EMF‑objektstabellen eller värdet DEFAULT\_PALETTE, vilket är indexet för en standardobjektspalett från StockObject‑enumerationen (avsnitt 2.1.31).

Detta värde FÅR INTE vara noll eller indexet för något annat standardobjekt.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett LogPalette‑objekt (avsnitt 2.2.17) i EMF‑objektstabellen eller värdet DEFAULT\_PALETTE, vilket är indexet för en standardobjektspalett från StockObject‑enumerationen (avsnitt 2.1.31).

Detta värde FÅR INTE vara noll eller indexet för något annat standardobjekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

