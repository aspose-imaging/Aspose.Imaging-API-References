---
title: "RawDataSettings"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los ajustes de datos sin procesar"
type: docs
weight: 92
url: /es/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Los ajustes de datos sin procesar
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Instancia vacía inicializada. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Inicializar una copia de `origin`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Obtiene el formato de datos de píxel |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Establece el formato de datos de píxel |
| [getColorPalette()](#getColorPalette--) | Obtiene la paleta de colores |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Establece la paleta de colores |
| [getDitheringMethod()](#getDitheringMethod--) | Obtiene el método de tramado a usar para la conversión de datos sin procesar |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Establece el método de tramado a usar para la conversión de datos sin procesar |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Obtiene el convertidor de color indexado |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Establece el convertidor de color indexado |
| [getCustomColorConverter()](#getCustomColorConverter--) | Obtiene el convertidor de color personalizado |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Establece el convertidor de color personalizado |
| [getFallbackIndex()](#getFallbackIndex--) | Obtiene el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [getLineSize()](#getLineSize--) | Obtiene el tamaño de línea de píxeles en bytes para el procesamiento de datos sin procesar |
| [setLineSize(int value)](#setLineSize-int-) | Establece el tamaño de línea de píxeles en bytes para el procesamiento de datos sin procesar |
| [<T>copy()](#-T-copy--) | Crea una copia superficial. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Instancia vacía inicializada.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Inicializa una copia de `origin`. Usado en [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | La instancia de la cual hacer una copia. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Obtiene el formato de datos de píxel

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Establece el formato de datos de píxel

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | El formato de datos de píxel |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Obtiene la paleta de colores

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Establece la paleta de colores

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Obtiene el método de tramado a usar para la conversión de datos sin procesar

**Returns:**
int - El método de tramado a usar para la conversión de datos sin procesar
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Establece el método de tramado a usar para la conversión de datos sin procesar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El método de tramado a usar para la conversión de datos sin procesar |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Obtiene el convertidor de color indexado

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Establece el convertidor de color indexado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | El convertidor de color indexado |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Obtiene el convertidor de color personalizado

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Establece el convertidor de color personalizado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | El convertidor de color personalizado |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Obtiene el índice de reserva a usar cuando el índice de la paleta está fuera de los límites

**Returns:**
int - El índice de reserva a usar cuando el índice de la paleta está fuera de los límites
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El índice de reserva a usar cuando el índice de la paleta está fuera de los límites |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Obtiene el tamaño de línea de píxeles en bytes para el procesamiento de datos sin procesar

**Returns:**
int - El tamaño de línea de píxeles en bytes para el procesamiento de datos sin procesar
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Establece el tamaño de línea de píxeles en bytes para el procesamiento de datos sin procesar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tamaño de línea de píxeles en bytes para el procesamiento de datos brutos |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Crea una copia superficial.

**Returns:**
T - Una copia superficial.
