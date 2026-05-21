---
title: "EmfRestoreDc"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_RESTOREDC‑posten återställer uppspelningsenhetens kontext till det angivna tillståndet."
type: docs
weight: 109
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

EMR\_RESTOREDC‑posten återställer uppspelningsenhetens kontext till det angivna tillståndet. Kontexten återställs genom att poppa tillståndsinformation från en stack som skapades av tidigare EMR\_SAVEDC‑poster (avsnitt 2.3.11).

Stacken kan innehålla tillståndsinformation för flera instanser av uppspelningsenhetens kontext. När ett tillstånd återställs måste alla tillståndsinstanser som sparades senare MÅSTE kasseras.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfRestoreDc`. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Initierar en ny instans av klassen `EmfRestoreDc`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar det sparade tillståndet att återställa relativt det aktuella tillståndet. |
| [setSavedDc(int value)](#setSavedDc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar det sparade tillståndet att återställa relativt det aktuella tillståndet. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Initierar en ny instans av klassen `EmfRestoreDc`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Initierar en ny instans av klassen `EmfRestoreDc`.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar det sparade tillståndet att återställa relativt det aktuella tillståndet. Detta värde MÅSTE vara negativt; \\u20131 representerar det tillstånd som senast sparades på stacken, \\u20132 det föregående, osv.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar det sparade tillståndet att återställa relativt det aktuella tillståndet. Detta värde MÅSTE vara negativt; \\u20131 representerar det tillstånd som senast sparades på stacken, \\u20132 det föregående, osv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

