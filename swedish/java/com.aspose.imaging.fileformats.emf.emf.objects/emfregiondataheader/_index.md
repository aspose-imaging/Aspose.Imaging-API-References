---
title: "EmfRegionDataHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "RegionDataHeader-objektet beskriver egenskaperna för ett RegionData-objekt."
type: docs
weight: 34
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

RegionDataHeader-objektet beskriver egenskaperna för ett RegionData-objekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar ett 32-bitars osignerat heltal som specificerar storleken på detta objekt i byte. |
| [setSize(int value)](#setSize-int-) | Anger ett 32-bitars osignerat heltal som specificerar storleken på detta objekt i byte. |
| [getType()](#getType--) | Hämtar ett 32-bitars osignerat heltal som specificerar regiontypen. |
| [setType(int value)](#setType-int-) | Anger ett 32-bitars osignerat heltal som specificerar regiontypen. |
| [getCountRects()](#getCountRects--) | Hämtar ett 32-bitars osignerat heltal som specificerar antalet rektanglar i denna region. |
| [setCountRects(int value)](#setCountRects-int-) | Ställer in ett 32-bitars osignerat heltal som specificerar antalet rektanglar i detta område. |
| [getRgnSize()](#getRgnSize--) | Hämtar ett 32-bitars osignerat heltal som specificerar storleken på bufferten för rektanglar i byte. |
| [setRgnSize(int value)](#setRgnSize-int-) | Ställer in ett 32-bitars osignerat heltal som specificerar storleken på bufferten för rektanglar i byte. |
| [getBounds()](#getBounds--) | Hämtar ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar gränserna för området. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ställer in ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar regionens gränser. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Hämtar ett 32-bitars osignerat heltal som specificerar storleken på detta objekt i byte. Detta MÅSTE vara 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Ställer in ett 32-bitars osignerat heltal som specificerar storleken på detta objekt i byte. Detta MÅSTE vara 0x00000020.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getType() {#getType--}
```
public int getType()
```


Hämtar ett 32-bitars osignerat heltal som specificerar regiontypen. Detta BÖR vara RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ställer in ett 32-bitars osignerat heltal som specificerar regiontypen. Detta BÖR vara RDH\_RECTANGLES (0x00000001).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Hämtar ett 32-bitars osignerat heltal som specificerar antalet rektanglar i denna region.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Ställer in ett 32-bitars osignerat heltal som specificerar antalet rektanglar i detta område.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Hämtar ett 32-bitars osignerat heltal som specificerar storleken på bufferten för rektanglar i byte.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Ställer in ett 32-bitars osignerat heltal som specificerar storleken på bufferten för rektanglar i byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar gränserna för området.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ställer in ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19), som specificerar regionens gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

