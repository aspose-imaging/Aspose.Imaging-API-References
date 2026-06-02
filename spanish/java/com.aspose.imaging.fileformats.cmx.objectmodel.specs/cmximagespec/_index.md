---
title: "CmxImageSpec"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa la información especificada para imágenes raster."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

Representa la información especificada para imágenes raster.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | Obtiene la caja delimitadora. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | Establece la caja delimitadora. |
| [getCropBox()](#getCropBox--) | Obtiene la caja de recorte. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | Establece la caja de recorte. |
| [getMatrix()](#getMatrix--) | Obtiene la matriz de transformación. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Establece la matriz de transformación. |
| [getImageType()](#getImageType--) | Obtiene el tipo de la imagen. |
| [setImageType(int value)](#setImageType-int-) | Establece el tipo de la imagen. |
| [getImages()](#getImages--) | Obtiene las imágenes. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Establece las imágenes. |
| [isCmx3Image()](#isCmx3Image--) | Obtiene un valor que indica si esta instancia es una imagen CMX3. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | Establece un valor que indica si esta instancia es una imagen CMX3. |
| [toString()](#toString--) | Devuelve una cadena que representa esta instancia. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


Obtiene la caja delimitadora.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


Establece la caja delimitadora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | la caja delimitadora. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


Obtiene la caja de recorte.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


Establece la caja de recorte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | el cuadro de recorte. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Obtiene la matriz de transformación.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Establece la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | la matriz de transformación. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


Obtiene el tipo de la imagen.

**Returns:**
int - el tipo de la imagen.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Establece el tipo de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tipo de la imagen. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Obtiene las imágenes.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - las imágenes.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Establece las imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | las imágenes. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


Obtiene un valor que indica si esta instancia es una imagen CMX3.

Valor: `true` si esta instancia es una imagen CMX3; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta instancia es una imagen CMX3.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


Establece un valor que indica si esta instancia es una imagen CMX3.

Valor: `true` si esta instancia es una imagen CMX3; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si esta instancia es una imagen CMX3. |

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa esta instancia.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
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


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
