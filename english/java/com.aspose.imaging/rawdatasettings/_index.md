---
title: RawDataSettings
second_title: Aspose.Imaging for Java API Reference
description: The raw data settings
type: docs
weight: 92
url: /java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

The raw data settings
## Constructors

| Constructor | Description |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Initialized an empty instance. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Initialize a copy of `origin`. |
## Methods

| Method | Description |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Gets the pixel data format |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Sets the pixel data format |
| [getColorPalette()](#getColorPalette--) | Gets the color palette |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Sets the color palette |
| [getDitheringMethod()](#getDitheringMethod--) | Gets the dithering method to use for raw data conversion |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Sets the dithering method to use for raw data conversion |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Gets the indexed color converter |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Sets the indexed color converter |
| [getCustomColorConverter()](#getCustomColorConverter--) | Gets the custom color converter |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Sets the custom color converter |
| [getFallbackIndex()](#getFallbackIndex--) | Gets the fallback index to use when palette index is out of bounds |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Sets the fallback index to use when palette index is out of bounds |
| [getLineSize()](#getLineSize--) | Gets the pixels line size in bytes for raw data processing |
| [setLineSize(int value)](#setLineSize-int-) | Sets the pixels line size in bytes for raw data processing |
| [<T>copy()](#-T-copy--) | Creates a shallow copy. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Initialized an empty instance.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Initialize a copy of `origin`. Used in [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | The instance to make a copy of. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Gets the pixel data format

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Sets the pixel data format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | The pixel data format |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Gets the color palette

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Sets the color palette

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Gets the dithering method to use for raw data conversion

**Returns:**
int - The dithering method to use for raw data conversion
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Sets the dithering method to use for raw data conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The dithering method to use for raw data conversion |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Gets the indexed color converter

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Sets the indexed color converter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | The indexed color converter |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Gets the custom color converter

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Sets the custom color converter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | The custom color converter |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Gets the fallback index to use when palette index is out of bounds

**Returns:**
int - The fallback index to use when palette index is out of bounds
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Sets the fallback index to use when palette index is out of bounds

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The fallback index to use when palette index is out of bounds |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Gets the pixels line size in bytes for raw data processing

**Returns:**
int - The pixels line size in bytes for raw data processing
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Sets the pixels line size in bytes for raw data processing

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The pixels line size in bytes for raw data processing |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Creates a shallow copy.

**Returns:**
T - A shallow copy.
