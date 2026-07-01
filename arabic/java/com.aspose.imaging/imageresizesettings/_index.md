---
title: "ImageResizeSettings"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة إعدادات تغيير حجم الصورة"
type: docs
weight: 63
url: /ar/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

فئة إعدادات تغيير حجم الصورة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | ينشئ مثيلاً جديدًا من الفئة `ImageResizeSettings` مع نوع التحجيم = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) مع نوع الفلتر = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) مع طريقة تكميـن اللون = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع نوع الفلتر = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) مع طريقة تكميـن اللون = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع طريقة تكميـن اللون = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount()) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | يحصل على عدد الإدخالات |
| [setEntriesCount(int value)](#setEntriesCount-int-) | يضبط عدد الإدخالات |
| [getMode()](#getMode--) | يحصل على وضع الاستيفاء. |
| [setMode(int value)](#setMode-int-) | يضبط وضع الاستيفاء. |
| [getFilterType()](#getFilterType--) | يحصل على نوع الفلتر. |
| [setFilterType(int value)](#setFilterType-int-) | يضبط نوع الفلتر. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | يحصل على طريقة تكميـن اللون. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | يضبط طريقة تكميـن اللون. |
| [getColorCompareMethod()](#getColorCompareMethod--) | يحصل على طريقة مقارنة اللون. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | يضبط طريقة مقارنة اللون. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


ينشئ مثيلاً جديدًا من الفئة `ImageResizeSettings` مع نوع التحجيم = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) مع نوع الفلتر = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) مع طريقة تكميـن اللون = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع نوع الفلتر = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) مع طريقة تكميـن اللون = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeType | int | نوع التحجيم. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع طريقة تكميـن اللون = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeType | int | نوع التحجيم. |
| filterType | int | نوع الفلتر. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع طريقة مقارنة اللون = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeType | int | نوع التحجيم. |
| filterType | int | نوع الفلتر. |
| colorQuantizationMethod | int | طريقة تقليل الألوان. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


ينشئ مثيلاً جديدًا من الفئة [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) مع عدد إدخالات اللون = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeType | int | نوع التحجيم. |
| filterType | int | نوع الفلتر. |
| colorQuantizationMethod | int | طريقة تقليل الألوان. |
| colorCompareMethod | int | طريقة مقارنة الألوان. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


يحصل على عدد الإدخالات

**Returns:**
int - عدد الإدخالات
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


يضبط عدد الإدخالات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد الإدخالات |

### getMode() {#getMode--}
```
public int getMode()
```


يحصل على وضع الاستيفاء.

**Returns:**
int - الوضع.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


يضبط وضع الاستيفاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الوضع. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


يحصل على نوع الفلتر.

**Returns:**
int - نوع الفلتر.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


يضبط نوع الفلتر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | نوع الفلتر. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


يحصل على طريقة تكميـن اللون.

**Returns:**
int - طريقة تقليل الألوان.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


يضبط طريقة تكميـن اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | طريقة تقليل الألوان. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


يحصل على طريقة مقارنة اللون.

**Returns:**
int - طريقة مقارنة الألوان.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


يضبط طريقة مقارنة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | طريقة مقارنة الألوان. |

