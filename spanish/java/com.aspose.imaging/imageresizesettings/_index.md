---
title: "ImageResizeSettings"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase de configuración de redimensionamiento de imagen"
type: docs
weight: 63
url: /es/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Clase de configuración de redimensionamiento de imagen
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Inicializa una nueva instancia de la clase `ImageResizeSettings` con Tipo de redimensionamiento = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) con Tipo de filtro = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) con Método de cuantización de color = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Tipo de filtro = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) con Método de cuantización de color = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Método de cuantización de color = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount()) |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Obtiene el recuento de entradas |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Establece el recuento de entradas |
| [getMode()](#getMode--) | Obtiene el modo de interpolación. |
| [setMode(int value)](#setMode-int-) | Establece el modo de interpolación. |
| [getFilterType()](#getFilterType--) | Obtiene el tipo de filtro. |
| [setFilterType(int value)](#setFilterType-int-) | Establece el tipo de filtro. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Obtiene el método de cuantización de color. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Establece el método de cuantización de color. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Obtiene el método de comparación de color. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Establece el método de comparación de color. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Inicializa una nueva instancia de la clase `ImageResizeSettings` con Tipo de redimensionamiento = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) con Tipo de filtro = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) con Método de cuantización de color = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Tipo de filtro = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) con Método de cuantización de color = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeType | int | Tipo de redimensionamiento. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Método de cuantización de color = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeType | int | Tipo de redimensionamiento. |
| filterType | int | Tipo de filtro. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Método de comparación de color = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeType | int | Tipo de redimensionamiento. |
| filterType | int | Tipo de filtro. |
| colorQuantizationMethod | int | Método de cuantización de color. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Inicializa una nueva instancia de la clase [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con Recuento de entradas de color = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeType | int | Tipo de redimensionamiento. |
| filterType | int | Tipo de filtro. |
| colorQuantizationMethod | int | Método de cuantización de color. |
| colorCompareMethod | int | Método de comparación de color. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Obtiene el recuento de entradas

**Returns:**
int - El recuento de entradas
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Establece el recuento de entradas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El recuento de entradas |

### getMode() {#getMode--}
```
public int getMode()
```


Obtiene el modo de interpolación.

**Returns:**
int - El modo.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Establece el modo de interpolación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Obtiene el tipo de filtro.

**Returns:**
int - El tipo del filtro.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Establece el tipo de filtro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tipo del filtro. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Obtiene el método de cuantización de color.

**Returns:**
int - El método de cuantización de color.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Establece el método de cuantización de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El método de cuantización de color. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Obtiene el método de comparación de color.

**Returns:**
int - El método de comparación de color.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Establece el método de comparación de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El método de comparación de color. |

