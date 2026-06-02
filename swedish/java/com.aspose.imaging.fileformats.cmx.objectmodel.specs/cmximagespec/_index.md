---
title: "CmxImageSpec"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar information specificerad för rasterbilder."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

Representerar information specificerad för rasterbilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | Hämtar den begränsningsrutan. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | Ställer in den begränsningsrutan. |
| [getCropBox()](#getCropBox--) | Hämtar beskärningsrutan. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | Ställer in beskärningsrutan. |
| [getMatrix()](#getMatrix--) | Hämtar transformationsmatrisen. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Ställer in transformationsmatrisen. |
| [getImageType()](#getImageType--) | Hämtar bildens typ. |
| [setImageType(int value)](#setImageType-int-) | Ställer in bildens typ. |
| [getImages()](#getImages--) | Hämtar bilderna. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Ställer in bilderna. |
| [isCmx3Image()](#isCmx3Image--) | Hämtar ett värde som indikerar om denna instans är en CMX3-bild. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | Ställer in ett värde som indikerar om denna instans är en CMX3-bild. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


Hämtar den begränsningsrutan.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


Ställer in den begränsningsrutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | den begränsningsrutan. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


Hämtar beskärningsrutan.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


Ställer in beskärningsrutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | beskärningsrutan. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Hämtar transformationsmatrisen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Ställer in transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | transformationsmatrisen. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


Hämtar bildens typ.

**Returns:**
int - bildens typ.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Ställer in bildens typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | bildens typ. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Hämtar bilderna.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - bilderna.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Ställer in bilderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | bilderna. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


Hämtar ett värde som indikerar om denna instans är en CMX3-bild.

Värde: `true` om detta objekt är en CMX3-bild; annars `false`.

**Returns:**
boolean - ett värde som indikerar om detta objekt är en CMX3-bild.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


Ställer in ett värde som indikerar om denna instans är en CMX3-bild.

Värde: `true` om detta objekt är en CMX3-bild; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om detta objekt är en CMX3-bild. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En sträng som representerar detta objekt.
### toArray() {#toArray--}
```
public CmxRasterImage[] toArray()
```




**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
