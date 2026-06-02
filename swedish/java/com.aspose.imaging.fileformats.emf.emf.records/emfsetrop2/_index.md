---
title: "EmfSetRop2"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETROP2-posten definierar ett binärt rasteroperationsläge."
type: docs
weight: 137
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

EMR\\_SETROP2-posten definierar ett binärt rasteroperationsläge.

Binära rasteroperationsblandningslägen definierar hur man kombinerar källa- och destinationsfärger när man ritar med den aktuella pennan. Blandningslägena är binära rasteroperationskoder som representerar alla möjliga boolska funktioner av två variabler, med de binära operationerna OCH, ELLER och XOR (exklusiv ELLER) samt den unära operationen INTE. Blandningsläget gäller endast rasterenheter; det är inte tillgängligt för vektorenheter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetRop2`. |
| [EmfSetRop2()](#EmfSetRop2--) | Initierar en ny instans av klassen `EmfSetRop2`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationsläget och MÅSTE finnas i WMF Binary Raster Op‑enumerationen ([MS-WMF] avsnitt 2.1.1.2). |
| [setRop2Mode(int value)](#setRop2Mode-int-) | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationsläget och MÅSTE finnas i WMF Binary Raster Op‑enumerationen ([MS-WMF] avsnitt 2.1.1.2). |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetRop2`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


Initierar en ny instans av klassen `EmfSetRop2`.

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationsläget och MÅSTE finnas i WMF Binary Raster Op‑enumerationen ([MS-WMF] avsnitt 2.1.1.2).

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar rasteroperationsläget och MÅSTE finnas i WMF Binary Raster Op‑enumerationen ([MS-WMF] avsnitt 2.1.1.2).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

