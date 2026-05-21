---
title: "CmxImageFill"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Información de relleno de imagen"
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---
**Inheritance:**
java.lang.Object
```
public class CmxImageFill
```

Información de relleno de imagen
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmxImageFill()](#CmxImageFill--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getImages()](#getImages--) | Obtiene las imágenes. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Establece las imágenes. |
| [getProcedure()](#getProcedure--) | Obtiene el procedimiento. |
| [setProcedure(CmxProcedure value)](#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-) | Establece el procedimiento. |
| [getTileOffsetX()](#getTileOffsetX--) | Obtiene el desplazamiento de mosaico X. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Establece el desplazamiento de mosaico X. |
| [getTileOffsetY()](#getTileOffsetY--) | Obtiene el desplazamiento de mosaico Y. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Establece el desplazamiento de mosaico Y. |
| [getRcpOffset()](#getRcpOffset--) | Obtiene el desplazamiento relativo entre filas o columnas de mosaico (depende de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [setRcpOffset(float value)](#setRcpOffset-float-) | Establece el desplazamiento relativo entre filas o columnas de mosaico (depende de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [getOffsetType()](#getOffsetType--) | Obtiene el tipo de desplazamiento entre mosaicos adyacentes. |
| [setOffsetType(int value)](#setOffsetType-int-) | Establece el tipo de desplazamiento entre mosaicos adyacentes. |
| [getPatternWidth()](#getPatternWidth--) | Obtiene el ancho del patrón. |
| [setPatternWidth(float value)](#setPatternWidth-float-) | Establece el ancho del patrón. |
| [getPatternHeight()](#getPatternHeight--) | Obtiene la altura del patrón. |
| [setPatternHeight(float value)](#setPatternHeight-float-) | Establece la altura del patrón. |
| [isRelative()](#isRelative--) | Obtiene un valor que indica si los valores de tamaño de los patrones son relativos. |
| [setRelative(boolean value)](#setRelative-boolean-) | Establece un valor que indica si los valores de tamaño de los patrones son relativos. |
| [getRotate180()](#getRotate180--) | Obtiene un valor que indica si este [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) está al revés. |
| [setRotate180(boolean value)](#setRotate180-boolean-) | Establece un valor que indica si este [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) está al revés. |
| [toString()](#toString--) | Devuelve una cadena que representa esta instancia. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### CmxImageFill() {#CmxImageFill--}
```
public CmxImageFill()
```


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

### getProcedure() {#getProcedure--}
```
public final CmxProcedure getProcedure()
```


Obtiene el procedimiento.

**Returns:**
[CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) - the procedure.
### setProcedure(CmxProcedure value) {#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-}
```
public final void setProcedure(CmxProcedure value)
```


Establece el procedimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) | el procedimiento. |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Obtiene el desplazamiento de mosaico X.

**Returns:**
float - el desplazamiento de la loseta X.
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Establece el desplazamiento de mosaico X.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el desplazamiento de la loseta X. |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Obtiene el desplazamiento de mosaico Y.

**Returns:**
float - el desplazamiento de la loseta Y.
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Establece el desplazamiento de mosaico Y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el desplazamiento de la loseta Y. |

### getRcpOffset() {#getRcpOffset--}
```
public final float getRcpOffset()
```


Obtiene el desplazamiento relativo entre filas o columnas de losetas (depende de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). La dimensión es una fracción de la altura o anchura.

**Returns:**
float - el desplazamiento relativo entre filas o columnas de losetas (depende de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))).
### setRcpOffset(float value) {#setRcpOffset-float-}
```
public final void setRcpOffset(float value)
```


Establece el desplazamiento relativo entre filas o columnas de losetas (depende de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). La dimensión es una fracción de la altura o anchura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el desplazamiento relativo entre filas o columnas de losetas (depende de `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |

### getOffsetType() {#getOffsetType--}
```
public final int getOffsetType()
```


Obtiene el tipo de desplazamiento entre mosaicos adyacentes.

**Returns:**
int - el tipo de desplazamiento entre losetas adyacentes.
### setOffsetType(int value) {#setOffsetType-int-}
```
public final void setOffsetType(int value)
```


Establece el tipo de desplazamiento entre mosaicos adyacentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tipo de desplazamiento entre losetas adyacentes. |

### getPatternWidth() {#getPatternWidth--}
```
public final float getPatternWidth()
```


Obtiene el ancho del patrón. Utiliza la unidad de medida de distancia de documento común en caso de que `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sea `false`, de lo contrario tiene la dimensión de la fracción del ancho de píxel de la imagen.

**Returns:**
float - el ancho del patrón.
### setPatternWidth(float value) {#setPatternWidth-float-}
```
public final void setPatternWidth(float value)
```


Establece el ancho del patrón. Utiliza la unidad de medida de distancia de documento común en caso de que `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sea `false`, de lo contrario tiene la dimensión de la fracción del ancho de píxel de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el ancho del patrón. |

### getPatternHeight() {#getPatternHeight--}
```
public final float getPatternHeight()
```


Obtiene la altura del patrón. Utiliza la unidad de medida de distancia de documento común en caso de que `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sea `false`, de lo contrario tiene la dimensión de la fracción de la altura de píxel de la imagen.

**Returns:**
float - la altura del patrón.
### setPatternHeight(float value) {#setPatternHeight-float-}
```
public final void setPatternHeight(float value)
```


Establece la altura del patrón. Utiliza la unidad de medida de distancia de documento común en caso de que `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sea `false`, de lo contrario tiene la dimensión de la fracción de la altura de píxel de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | la altura del patrón. |

### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Obtiene un valor que indica si los valores de tamaño de los patrones son relativos.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public final void setRelative(boolean value)
```


Establece un valor que indica si los valores de tamaño de los patrones son relativos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRotate180() {#getRotate180--}
```
public final boolean getRotate180()
```


Obtiene un valor que indica si este [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) está al revés.

Valor: `true` si la imagen está al revés; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si este [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) está al revés.
### setRotate180(boolean value) {#setRotate180-boolean-}
```
public final void setRotate180(boolean value)
```


Establece un valor que indica si este [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) está al revés.

Valor: `true` si la imagen está al revés; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | un valor que indica si este [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) está al revés. |

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa esta instancia.

**Returns:**
java.lang.String - Una cadena que representa esta instancia.
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
