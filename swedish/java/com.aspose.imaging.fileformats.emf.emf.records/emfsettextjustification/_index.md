---
title: "EmfSetTextJustification"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETTEXTJUSTIFICATION‑posten specificerar mängden extra utrymme som ska läggas till vid avbrottstecken för textjustering."
type: docs
weight: 141
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

EMR\\_SETTEXTJUSTIFICATION-posten specificerar mängden extra utrymme att lägga till för avbrotts­tecken vid textjustering.

Istället för att använda en EMR\_SETTEXTJUSTIFICATION‑post bör en implementation ANVÄNDA en EMR\_EXTTEXTOUTW‑post (avsnitt 2.3.5.8) för att utföra denna funktion.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetTextJustification`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den totala mängden extra utrymme, i logiska enheter, att lägga till. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den totala mängden extra utrymme, i logiska enheter, att lägga till. |
| [getNBreakCount()](#getNBreakCount--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar antalet avbrotts­tecken. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar antalet avbrotts­tecken. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetTextJustification`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den totala mängden extra utrymme, i logiska enheter, att lägga till.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den totala mängden extra utrymme, i logiska enheter, att lägga till.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar antalet avbrotts­tecken.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar antalet avbrotts­tecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

