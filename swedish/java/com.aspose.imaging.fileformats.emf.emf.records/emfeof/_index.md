---
title: "EmfEof"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_EOF‑posten indikerar slutet på metafilen och specificerar en palett."
type: docs
weight: 48
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

Den EMR\_EOF-posten indikerar slutet på metafilen och anger en palett.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfEof`. |
| [EmfEof()](#EmfEof--) | Initierar en ny instans av klassen `EmfEof`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Hämtar en valfri buffer som innehåller palettdata, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_EOF‑posten. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Anger en valfri buffer som innehåller palettdata, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_EOF‑posten. |
| [getSizeLast()](#getSizeLast--) | Hämtar ett 32‑bitars osignerat heltal som MÅSTE vara samma som Size och MÅSTE vara det sista fältet i posten och därmed i metafilen. |
| [setSizeLast(int value)](#setSizeLast-int-) | Anger ett 32‑bitars osignerat heltal som MÅSTE vara samma som Size och MÅSTE vara det sista fältet i posten och därmed i metafilen. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Initierar en ny instans av klassen `EmfEof`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Initierar en ny instans av klassen `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Hämtar en valfri buffer som innehåller palettdata, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_EOF‑posten. Följaktligen är fält i denna buffer som är märkta \"UndefinedSpace\" valfria och MÅSTE ignoreras. Storleken på detta fält MÅSTE vara en multipel av 4 byte.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Anger en valfri buffer som innehåller palettdata, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_EOF‑posten. Följaktligen är fält i denna buffer som är märkta \"UndefinedSpace\" valfria och MÅSTE ignoreras. Storleken på detta fält MÅSTE vara en multipel av 4 byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Hämtar ett 32‑bitars osignerat heltal som MÅSTE vara samma som Size och MÅSTE vara det sista fältet i posten och därmed i metafilen. LogPaletteEntry‑objekt, om de finns, MÅSTE föregå detta fält.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Anger ett 32‑bitars osignerat heltal som MÅSTE vara samma som Size och MÅSTE vara det sista fältet i posten och därmed i metafilen. LogPaletteEntry‑objekt, om de finns, MÅSTE föregå detta fält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

