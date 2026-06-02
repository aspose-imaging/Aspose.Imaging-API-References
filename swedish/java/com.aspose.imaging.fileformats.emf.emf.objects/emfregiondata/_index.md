---
title: "EmfRegionData"
second_title: "Aspose.Imaging för Java API-referens"
description: "RegionData-objektet specificerar data som definierar en region som består av icke-överlappande rektanglar."
type: docs
weight: 33
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionData extends EmfObject
```

RegionData-objektet specificerar data som definierar en region, som består av icke‑överlappande rektanglar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRegionData()](#EmfRegionData--) | Initierar en ny instans av klassen `EmfRegionData`. |
| [EmfRegionData(Rectangle rectangle)](#EmfRegionData-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen `EmfRegionData`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegionDataHeader()](#getRegionDataHeader--) | Hämtar ett 256-bitars RegionDataHeader-objekt som beskriver följande data. |
| [setRegionDataHeader(EmfRegionDataHeader value)](#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-) | Ställer in ett 256-bitars RegionDataHeader-objekt som beskriver följande data. |
| [getData()](#getData--) | Hämtar en matris av WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19); objekten slås samman för att skapa regionen |
| [setData(Rectangle[] value)](#setData-com.aspose.imaging.Rectangle---) | Ställer in en matris av WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19); objekten slås samman för att skapa regionen |
### EmfRegionData() {#EmfRegionData--}
```
public EmfRegionData()
```


Initierar en ny instans av klassen `EmfRegionData`.

### EmfRegionData(Rectangle rectangle) {#EmfRegionData-com.aspose.imaging.Rectangle-}
```
public EmfRegionData(Rectangle rectangle)
```


Initierar en ny instans av klassen `EmfRegionData`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

### getRegionDataHeader() {#getRegionDataHeader--}
```
public EmfRegionDataHeader getRegionDataHeader()
```


Hämtar ett 256-bitars RegionDataHeader-objekt som beskriver följande data.

**Returns:**
[EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader)
### setRegionDataHeader(EmfRegionDataHeader value) {#setRegionDataHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader-}
```
public void setRegionDataHeader(EmfRegionDataHeader value)
```


Ställer in ett 256-bitars RegionDataHeader-objekt som beskriver följande data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfRegionDataHeader](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader) |  |

### getData() {#getData--}
```
public Rectangle[] getData()
```


Hämtar en matris av WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19); objekten slås samman för att skapa regionen

**Returns:**
com.aspose.imaging.Rectangle[]
### setData(Rectangle[] value) {#setData-com.aspose.imaging.Rectangle---}
```
public void setData(Rectangle[] value)
```


Ställer in en matris av WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19); objekten slås samman för att skapa regionen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

