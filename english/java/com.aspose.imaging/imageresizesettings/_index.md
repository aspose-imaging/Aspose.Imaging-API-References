---
title: ImageResizeSettings
second_title: Aspose.Imaging for Java API Reference
description: Image resize settings class
type: docs
weight: 63
url: /java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Image resize settings class
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Initializes a new instance of the `ImageResizeSettings` class with Resize type = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) with Filter type = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) with Color quantization method = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Filter type = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) with Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Color entry count = 0 (\#getEntriesCount().getEntriesCount()) |
## Methods

| Method | Description |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Gets the entries count |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Sets the entries count |
| [getMode()](#getMode--) | Gets the interpolation mode. |
| [setMode(int value)](#setMode-int-) | Sets the interpolation mode. |
| [getFilterType()](#getFilterType--) | Gets the type of the filter. |
| [setFilterType(int value)](#setFilterType-int-) | Sets the type of the filter. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Gets the color quantization method. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Sets the color quantization method. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Gets the color compare method. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Sets the color compare method. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Initializes a new instance of the `ImageResizeSettings` class with Resize type = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) with Filter type = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) with Color quantization method = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Filter type = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) with Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeType | int | Resize type. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Color quantization method = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeType | int | Resize type. |
| filterType | int | Filter type. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Color compare method = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) with Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeType | int | Resize type. |
| filterType | int | Filter type. |
| colorQuantizationMethod | int | Color quantization method. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Initializes a new instance of the [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) class with Color entry count = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeType | int | Resize type. |
| filterType | int | Filter type. |
| colorQuantizationMethod | int | Color quantization method. |
| colorCompareMethod | int | Color compare method. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Gets the entries count

**Returns:**
int - The entries count
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Sets the entries count

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The entries count |

### getMode() {#getMode--}
```
public int getMode()
```


Gets the interpolation mode.

**Returns:**
int - The mode.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Sets the interpolation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The mode. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Gets the type of the filter.

**Returns:**
int - The type of the filter.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Sets the type of the filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The type of the filter. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Gets the color quantization method.

**Returns:**
int - The color quantization method.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Sets the color quantization method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The color quantization method. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Gets the color compare method.

**Returns:**
int - The color compare method.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Sets the color compare method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The color compare method. |

