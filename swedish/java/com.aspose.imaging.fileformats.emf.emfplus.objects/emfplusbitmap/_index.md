---
title: "EmfPlusBitmap"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusBitmap-objektet specificerar en bitmap som innehåller en grafikbild."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusBitmap extends EmfPlusBaseImageData
```

EmfPlusBitmap-objektet specificerar en bitmap som innehåller en grafikbild.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusBitmap()](#EmfPlusBitmap--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitmapData()](#getBitmapData--) | Hämtar eller anger bitmapdata BitmapData (variabel): Variabel‑längd data som definierar bitmapdataobjektet som specificeras i fältet Type. |
| [setBitmapData(EmfPlusBaseBitmapData value)](#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-) | Hämtar eller anger bitmapdata BitmapData (variabel): Variabel‑längd data som definierar bitmapdataobjektet som specificeras i fältet Type. |
| [getHeight()](#getHeight--) | Hämtar eller anger bitmaphöjd Height (4 byte): Ett 32-bitars signerat heltal som specificerar höjden i pixlar för det område som bitmapen upptar. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger bitmaphöjd Height (4 byte): Ett 32-bitars signerat heltal som specificerar höjden i pixlar för det område som bitmapen upptar. |
| [getPixelFormat()](#getPixelFormat--) | Hämtar eller anger pixelformat PixelFormat (4 byte): Ett 32-bitars osignerat heltal som specificerar formatet på pixlarna som utgör bitmap‑bilden. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Hämtar eller anger pixelformat PixelFormat (4 byte): Ett 32-bitars osignerat heltal som specificerar formatet på pixlarna som utgör bitmap‑bilden. |
| [getStride()](#getStride--) | Hämtar eller anger radsteg för bilden Stride (4 byte): Ett 32-bitars signerat heltal som specificerar byte‑avståndet mellan början av en rad och nästa. |
| [setStride(int value)](#setStride-int-) | Hämtar eller anger radsteg för bilden Stride (4 byte): Ett 32-bitars signerat heltal som specificerar byte‑avståndet mellan början av en rad och nästa. |
| [getType()](#getType--) | Hämtar eller anger bildtyp Type (4 byte): Ett 32-bitars osignerat heltal som specificerar datatypen i BitmapData‑fältet. |
| [setType(int value)](#setType-int-) | Hämtar eller anger bildtyp Type (4 byte): Ett 32-bitars osignerat heltal som specificerar datatypen i BitmapData‑fältet. |
| [getWidth()](#getWidth--) | Hämtar eller anger bildbredd Width (4 byte): Ett 32-bitars signerat heltal som specificerar bredden i pixlar för det område som bitmapen upptar. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger bildbredd Width (4 byte): Ett 32-bitars signerat heltal som specificerar bredden i pixlar för det område som bitmapen upptar. |
### EmfPlusBitmap() {#EmfPlusBitmap--}
```
public EmfPlusBitmap()
```


### getBitmapData() {#getBitmapData--}
```
public EmfPlusBaseBitmapData getBitmapData()
```


Hämtar eller anger bitmapdata BitmapData (variabel): Variabel‑längd data som definierar bitmapdataobjektet som specificeras i fältet Type. Innehållet och formatet på data kan vara olika för varje bitmap‑typ.

Värde: Bitmapdata.

**Returns:**
[EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
### setBitmapData(EmfPlusBaseBitmapData value) {#setBitmapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData-}
```
public void setBitmapData(EmfPlusBaseBitmapData value)
```


Hämtar eller anger bitmapdata BitmapData (variabel): Variabel‑längd data som definierar bitmapdataobjektet som specificeras i fältet Type. Innehållet och formatet på data kan vara olika för varje bitmap‑typ.

Värde: Bitmapdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger bitmaphöjd Height (4 byte): Ett 32-bitars signerat heltal som specificerar höjden i pixlar för det område som bitmapen upptar. Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Höjden.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger bitmaphöjd Height (4 byte): Ett 32-bitars signerat heltal som specificerar höjden i pixlar för det område som bitmapen upptar. Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Hämtar eller anger pixelformat PixelFormat (4 byte): Ett 32-bitars osignerat heltal som specificerar formatet på pixlarna som utgör bitmap‑bilden. De stödjade pixelformaten specificeras i `EmfPlusPixelFormat`‑enumerationen (avsnitt 2.1.1.25). Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Pixelformatet.

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public void setPixelFormat(int value)
```


Hämtar eller anger pixelformat PixelFormat (4 byte): Ett 32-bitars osignerat heltal som specificerar formatet på pixlarna som utgör bitmap‑bilden. De stödjade pixelformaten specificeras i `EmfPlusPixelFormat`‑enumerationen (avsnitt 2.1.1.25). Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Pixelformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getStride() {#getStride--}
```
public int getStride()
```


Hämtar eller anger radsteg för bilden Stride (4 byte): Ett 32-bitars signerat heltal som specificerar byte‑avståndet mellan början av en rad och nästa. Detta värde är antalet byte per pixel, vilket specificeras i PixelFormat‑fältet, multiplicerat med bredden i pixlar, vilket specificeras i Width‑fältet. Värdet i detta fält MÅSTE vara en multipel av fyra. Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Radsteget.

**Returns:**
int
### setStride(int value) {#setStride-int-}
```
public void setStride(int value)
```


Hämtar eller anger radsteg för bilden Stride (4 byte): Ett 32-bitars signerat heltal som specificerar byte‑avståndet mellan början av en rad och nästa. Detta värde är antalet byte per pixel, vilket specificeras i PixelFormat‑fältet, multiplicerat med bredden i pixlar, vilket specificeras i Width‑fältet. Värdet i detta fält MÅSTE vara en multipel av fyra. Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Radsteget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getType() {#getType--}
```
public int getType()
```


Hämtar eller anger bildtyp Type (4 byte): Ett 32-bitars osignerat heltal som specificerar datatypen i BitmapData‑fältet. Detta värde MÅSTE definieras i `EmfPlusBitmapDataType`‑enumerationen (avsnitt 2.1.1.2).

Värde: Typen.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Hämtar eller anger bildtyp Type (4 byte): Ett 32-bitars osignerat heltal som specificerar datatypen i BitmapData‑fältet. Detta värde MÅSTE definieras i `EmfPlusBitmapDataType`‑enumerationen (avsnitt 2.1.1.2).

Värde: Typen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger bildbredd Width (4 byte): Ett 32-bitars signerat heltal som specificerar bredden i pixlar för det område som bitmapen upptar. Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Bredden.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger bildbredd Width (4 byte): Ett 32-bitars signerat heltal som specificerar bredden i pixlar för det område som bitmapen upptar. Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras.

Värde: Bredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

