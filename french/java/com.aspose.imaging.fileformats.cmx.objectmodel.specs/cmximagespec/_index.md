---
title: "CmxImageSpec"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente les informations spécifiées pour les images raster."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

Représente les informations spécifiées pour les images raster.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | Obtient la boîte englobante. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | Définit la boîte englobante. |
| [getCropBox()](#getCropBox--) | Obtient la boîte de recadrage. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | Définit la boîte de recadrage. |
| [getMatrix()](#getMatrix--) | Obtient la matrice de transformation. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Définit la matrice de transformation. |
| [getImageType()](#getImageType--) | Obtient le type de l'image. |
| [setImageType(int value)](#setImageType-int-) | Définit le type de l'image. |
| [getImages()](#getImages--) | Obtient les images. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Définit les images. |
| [isCmx3Image()](#isCmx3Image--) | Obtient une valeur indiquant si cette instance est une image CMX3. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | Définit une valeur indiquant si cette instance est une image CMX3. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


Obtient la boîte englobante.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


Définit la boîte englobante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | la boîte englobante. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


Obtient la boîte de recadrage.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


Définit la boîte de recadrage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | la boîte de rognage. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Obtient la matrice de transformation.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Définit la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | la matrice de transformation. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


Obtient le type de l'image.

**Returns:**
int - le type de l'image.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Définit le type de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le type de l'image. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Obtient les images.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - les images.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Définit les images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | les images. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


Obtient une valeur indiquant si cette instance est une image CMX3.

Valeur : `true` si cette instance est une image CMX3 ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si cette instance est une image CMX3.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


Définit une valeur indiquant si cette instance est une image CMX3.

Valeur : `true` si cette instance est une image CMX3 ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si cette instance est une image CMX3. |

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne qui représente cette instance.
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


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
