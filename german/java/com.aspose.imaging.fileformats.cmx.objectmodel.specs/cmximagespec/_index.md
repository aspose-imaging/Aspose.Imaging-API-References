---
title: "CmxImageSpec"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt Informationen dar, die für Rasterbilder angegeben wurden."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

Stellt Informationen dar, die für Rasterbilder angegeben wurden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | Liefert die Begrenzungsbox. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | Setzt die Begrenzungsbox. |
| [getCropBox()](#getCropBox--) | Liefert die Zuschneidebox. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | Setzt die Zuschneidebox. |
| [getMatrix()](#getMatrix--) | Liefert die Transformationsmatrix. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Setzt die Transformationsmatrix. |
| [getImageType()](#getImageType--) | Liefert den Typ des Bildes. |
| [setImageType(int value)](#setImageType-int-) | Setzt den Typ des Bildes. |
| [getImages()](#getImages--) | Liest die Bilder. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Setzt die Bilder. |
| [isCmx3Image()](#isCmx3Image--) | Liefert einen Wert, der angibt, ob diese Instanz ein CMX3-Bild ist. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | Setzt einen Wert, der angibt, ob diese Instanz ein CMX3-Bild ist. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


Liefert die Begrenzungsbox.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


Setzt die Begrenzungsbox.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | die Begrenzungsbox. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


Liefert die Zuschneidebox.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


Setzt die Zuschneidebox.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | der Beschnittrahmen. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Liefert die Transformationsmatrix.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Setzt die Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | die Transformationsmatrix. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


Liefert den Typ des Bildes.

**Returns:**
int - der Typ des Bildes.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Setzt den Typ des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Typ des Bildes. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Liest die Bilder.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - die Bilder.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Setzt die Bilder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | die Bilder. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


Liefert einen Wert, der angibt, ob diese Instanz ein CMX3-Bild ist.

Wert: `true`, wenn diese Instanz ein CMX3‑Bild ist; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Instanz ein CMX3‑Bild ist.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


Setzt einen Wert, der angibt, ob diese Instanz ein CMX3-Bild ist.

Wert: `true`, wenn diese Instanz ein CMX3‑Bild ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob diese Instanz ein CMX3‑Bild ist. |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
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


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
