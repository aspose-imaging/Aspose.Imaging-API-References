---
title: "ImageAttributes"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Un objeto com.aspose.imaging.ImageAttributes contiene información sobre cómo se manipulan los colores de bitmap y metafile durante el renderizado."
type: docs
weight: 57
url: /es/java/com.aspose.imaging/imageattributes/
---
**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Un objeto `com.aspose.imaging.ImageAttributes` contiene información sobre cómo se manipulan los colores de mapas de bits y metafiles durante el renderizado. Un objeto `com.aspose.imaging.ImageAttributes` mantiene varios ajustes de corrección de color, incluyendo matrices de ajuste de color, matrices de ajuste en escala de grises, valores de corrección gamma, tablas de mapa de colores y valores de umbral de color. Durante el renderizado, los colores pueden ser corregidos, oscurecidos, aclarados y eliminados. Para aplicar dichas manipulaciones, inicialice un objeto `com.aspose.imaging.ImageAttributes` y pase la ruta de ese objeto `com.aspose.imaging.ImageAttributes` (junto con la ruta de una [Image](../../com.aspose.imaging/image)) al método drawImage.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Inicializa una nueva instancia de la clase `com.aspose.imaging.ImageAttributes`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.imaging.ColorMatrix-) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Establece la matriz de ajuste de color para una categoría especificada. |
| [clearColorMatrix()](#clearColorMatrix--) | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Borra la matriz de ajuste de color para una categoría especificada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-) | Establece la matriz de ajuste de color y la matriz de ajuste en escala de grises para la categoría predeterminada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-) | Establece la matriz de ajuste de color y la matriz de ajuste en escala de grises para la categoría predeterminada. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-) | Establece la matriz de ajuste de color y la matriz de ajuste en escala de grises para una categoría especificada. |
| [setThreshold(float threshold)](#setThreshold-float-) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Establece el umbral (rango de transparencia) para una categoría especificada. |
| [clearThreshold()](#clearThreshold--) | Borra el valor del umbral para la categoría predeterminada. |
| [clearThreshold(int type)](#clearThreshold-int-) | Borra el valor del umbral para una categoría especificada. |
| [setGamma(float gamma)](#setGamma-float-) | Establece el valor gamma para la categoría predeterminada. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Establece el valor gamma para una categoría especificada. |
| [clearGamma()](#clearGamma--) | Desactiva la corrección gamma para la categoría predeterminada. |
| [clearGamma(int type)](#clearGamma-int-) | Desactiva la corrección gamma para una categoría especificada. |
| [setNoOp()](#setNoOp--) | Desactiva el ajuste de color para la categoría predeterminada. |
| [setNoOp(int type)](#setNoOp-int-) | Desactiva el ajuste de color para una categoría especificada. |
| [clearNoOp()](#clearNoOp--) | Borra la configuración NoOp para la categoría predeterminada. |
| [clearNoOp(int type)](#clearNoOp-int-) | Borra la configuración NoOp para una categoría especificada. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Establece la clave de color para la categoría predeterminada. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-) | Establece la clave de color (rango de transparencia) para una categoría especificada. |
| [clearColorKey()](#clearColorKey--) | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [clearColorKey(int type)](#clearColorKey-int-) | Borra la clave de color (rango de transparencia) para una categoría especificada. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada. |
| [clearOutputChannel()](#clearOutputChannel--) | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Establece el archivo de perfil de color del canal de salida para una categoría especificada. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Borra la configuración del perfil de color del canal de salida para una categoría especificada. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.imaging.ColorMap---) | Establece la tabla de remapeo de color para la categoría predeterminada. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.imaging.ColorMap---int-) | Establece la tabla de remapeo de color para una categoría especificada. |
| [clearRemapTable()](#clearRemapTable--) | Borra la tabla de remapeo de color para la categoría predeterminada. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Borra la tabla de remapeo de color para una categoría especificada. |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.imaging.ColorMap---) | Establece la tabla de remapeo de color para la categoría de pincel. |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Borra la tabla de remapeo de color del pincel de este objeto `com.aspose.imaging.ImageAttributes`. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Establece el modo de ajuste que se usa para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.imaging.Color-) | Establece el modo de ajuste y el color usados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.imaging.Color-boolean-) | Establece el modo de ajuste y el color usados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Inicializa una nueva instancia de la clase `com.aspose.imaging.ImageAttributes`.

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de color. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Establece la matriz de ajuste de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de color. |
| banderas | int | Un elemento de `Aspose.Imaging.ColorMatrixFlag` que especifica el tipo de imagen y color que será afectado por la matriz de ajuste de color. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Establece la matriz de ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de color. |
| modo | int | Un elemento de `Aspose.Imaging.ColorMatrixFlag` que especifica el tipo de imagen y color que será afectado por la matriz de ajuste de color. |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece la matriz de ajuste de color. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Borra la matriz de ajuste de color para la categoría predeterminada.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Borra la matriz de ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra la matriz de ajuste de color. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Establece la matriz de ajuste de color y la matriz de ajuste en escala de grises para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de escala de grises. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Establece la matriz de ajuste de color y la matriz de ajuste en escala de grises para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de escala de grises. |
| banderas | int | Un elemento de `Aspose.Imaging.ColorMatrixFlag` que especifica el tipo de imagen y color que será afectado por las matrices de ajuste de color y de escala de grises. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.imaging.ColorMatrix-com.aspose.imaging.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Establece la matriz de ajuste de color y la matriz de ajuste en escala de grises para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de color. |
| grayMatrix | [ColorMatrix](../../com.aspose.imaging/colormatrix) | La matriz de ajuste de escala de grises. |
| modo | int | Un elemento de `Aspose.Imaging.ColorMatrixFlag` que especifica el tipo de imagen y color que será afectado por las matrices de ajuste de color y de escala de grises. |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establecen las matrices de ajuste de color y de escala de grises. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Establece el umbral (rango de transparencia) para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Un número real que especifica el valor del umbral. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Establece el umbral (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | Un valor de umbral de 0.0 a 1.0 que se utiliza como punto de ruptura para ordenar colores que se asignarán a un valor máximo o mínimo. |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece el umbral de color. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Borra el valor del umbral para la categoría predeterminada.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Borra el valor del umbral para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra el umbral. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Establece el valor gamma para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | El valor de corrección gamma. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Establece el valor gamma para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | El valor de corrección gamma. |
| tipo | int | Un elemento de la enumeración `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece el valor gamma. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Desactiva la corrección gamma para la categoría predeterminada.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Desactiva la corrección gamma para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual la corrección gamma está deshabilitada. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Desactiva el ajuste de color para la categoría predeterminada.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Desactiva el ajuste de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual la corrección de color está desactivada. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Borra la configuración NoOp para la categoría predeterminada.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Borra la configuración NoOp para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra la configuración NoOp. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Establece la clave de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | El valor bajo de la clave de color. |
| colorHigh | [Color](../../com.aspose.imaging/color) | El valor alto de la clave de color. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.imaging.Color-com.aspose.imaging.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Establece la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.imaging/color) | El valor bajo de la clave de color. |
| colorHigh | [Color](../../com.aspose.imaging/color) | El valor alto de la clave de color. |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece la clave de color. |

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Borra la clave de color (rango de transparencia) para la categoría predeterminada.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Borra la clave de color (rango de transparencia) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra la clave de color. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| banderas | int | Un elemento de `Aspose.Imaging.ColorChannelFlag` que especifica el canal de salida. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| banderas | int | Un elemento de `Aspose.Imaging.ColorChannelFlag` que especifica el canal de salida. |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece el canal de salida. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra la configuración del canal de salida. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Establece el archivo de perfil de color del canal de salida para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | El nombre de ruta de un archivo de perfil de color. Si el archivo de perfil de color está en el directorio %SystemRoot%\\System32\\Spool\\Drivers\\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser la ruta completa. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Establece el archivo de perfil de color del canal de salida para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | El nombre de ruta de un archivo de perfil de color. Si el archivo de perfil de color está en el directorio %SystemRoot%\\System32\\Spool\\Drivers\\Color, este parámetro puede ser el nombre del archivo. De lo contrario, este parámetro debe ser la ruta completa. |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece el archivo de perfil de color del canal de salida. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Borra la configuración del perfil de color del canal de salida para la categoría predeterminada.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Borra la configuración del perfil de color del canal de salida para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra la configuración del perfil del canal de salida. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.imaging.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Establece la tabla de remapeo de color para la categoría predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Una matriz de pares de colores del tipo `com.aspose.imaging.ColorMap`. Cada par de colores contiene un color existente (el primer valor) y el color al que se asignará (el segundo valor). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.imaging.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Establece la tabla de remapeo de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Una matriz de pares de colores del tipo `com.aspose.imaging.ColorMap`. Cada par de colores contiene un color existente (el primer valor) y el color al que se asignará (el segundo valor). |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se establece la tabla de remapeo de color. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Borra la tabla de remapeo de color para la categoría predeterminada.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Borra la tabla de remapeo de color para una categoría especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | Un elemento de `Aspose.Imaging.ColorAdjustType` que especifica la categoría para la cual se borra la tabla de remapeo. |

### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.imaging.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Establece la tabla de remapeo de color para la categoría de pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.imaging/colormap) | Una matriz de objetos `com.aspose.imaging.ColorMap`. |

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Borra la tabla de remapeo de color del pincel de este objeto `com.aspose.imaging.ImageAttributes`.

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Establece el modo de ajuste que se utiliza para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modo | int | Un elemento de `Aspose.Imaging.WrapMode` que especifica cómo se utilizan copias repetidas de una imagen para cubrir un área. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.imaging.Color-}
```
public void setWrapMode(int mode, Color color)
```


Establece el modo de ajuste y el color usados para decidir cómo cubrir una textura a lo largo de una forma, o en los bordes de la forma. Una textura se cubre a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modo | int | Un elemento de `Aspose.Imaging.WrapMode` que especifica cómo se utilizan copias repetidas de una imagen para cubrir un área. |
| color | [Color](../../com.aspose.imaging/color) | Un objeto `com.aspose.imaging.ImageAttributes` que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode está configurado a `WrapMode.Clamp` y el rectángulo de origen pasado a DrawImage es mayor que la propia imagen. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.imaging.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Establece el modo de ajuste y el color usados para decidir cómo cubrir una textura a lo largo de una forma, o en los bordes de la forma. Una textura se cubre a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| modo | int | Un elemento de `Aspose.Imaging.WrapMode` que especifica cómo se utilizan copias repetidas de una imagen para cubrir un área. |
| color | [Color](../../com.aspose.imaging/color) | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode está configurado a `WrapMode.Clamp` y el rectángulo de origen pasado a DrawImage es mayor que la propia imagen. |
| clamp | boolean | Este parámetro no tiene efecto. Establécelo en false. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
