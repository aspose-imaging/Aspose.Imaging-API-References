---
title: "WmfFillRegion"
second_title: "Aspose.Imaging för Java API-referens"
description: "META_FILLREGION‑posten fyller en region med en specificerad pensel."
type: docs
weight: 37
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

META\_FILLREGION-posten fyller en region med en angiven pensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Initierar en ny instans av klassen `WmfFillRegion`. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Initierar en ny instans av klassen `WmfFillRegion`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Hämtar eller anger indexet för regionen. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Hämtar eller anger indexet för regionen. |
| [getBrushIndex()](#getBrushIndex--) | Hämtar eller anger index för penseln. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Hämtar eller anger index för penseln. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Initierar en ny instans av klassen `WmfFillRegion`.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Initierar en ny instans av klassen `WmfFillRegion`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Regionen. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Penseln. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Hämtar eller anger indexet för regionen.

Värde: Index i WMF-objektstabellen för att hämta regionen som ska fyllas.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Hämtar eller anger indexet för regionen.

Värde: Index i WMF-objektstabellen för att hämta regionen som ska fyllas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Hämtar eller anger index för penseln.

Värde: Index i WMF-objektstabellen för att hämta penseln som ska användas för att fylla regionen.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Hämtar eller anger index för penseln.

Värde: Index i WMF-objektstabellen för att hämta penseln som ska användas för att fylla regionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

