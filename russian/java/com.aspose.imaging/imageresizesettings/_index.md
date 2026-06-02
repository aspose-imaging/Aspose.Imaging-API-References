---
title: "ImageResizeSettings"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс настроек изменения размера изображения"
type: docs
weight: 63
url: /ru/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Класс настроек изменения размера изображения
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Инициализирует новый экземпляр класса `ImageResizeSettings` с типом изменения размера = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) с типом фильтра = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) с методом квантования цвета = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с типом фильтра = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) с методом квантования цвета = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с методом квантования цвета = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount()) |
## Методы

| Метод | Описание |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Получает количество записей |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Устанавливает количество записей |
| [getMode()](#getMode--) | Получает режим интерполяции. |
| [setMode(int value)](#setMode-int-) | Устанавливает режим интерполяции. |
| [getFilterType()](#getFilterType--) | Получает тип фильтра. |
| [setFilterType(int value)](#setFilterType-int-) | Устанавливает тип фильтра. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Получает метод квантования цвета. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Устанавливает метод квантования цвета. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Получает метод сравнения цвета. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Устанавливает метод сравнения цвета. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Инициализирует новый экземпляр класса `ImageResizeSettings` с типом изменения размера = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) с типом фильтра = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) с методом квантования цвета = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с типом фильтра = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) с методом квантования цвета = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeType | int | Тип изменения размера. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с методом квантования цвета = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeType | int | Тип изменения размера. |
| filterType | int | Тип фильтра. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с методом сравнения цвета = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeType | int | Тип изменения размера. |
| filterType | int | Тип фильтра. |
| colorQuantizationMethod | int | Метод квантования цвета. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Инициализирует новый экземпляр класса [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) с количеством записей цвета = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeType | int | Тип изменения размера. |
| filterType | int | Тип фильтра. |
| colorQuantizationMethod | int | Метод квантования цвета. |
| colorCompareMethod | int | Метод сравнения цветов. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Получает количество записей

**Returns:**
int - Количество записей
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Устанавливает количество записей

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Количество записей |

### getMode() {#getMode--}
```
public int getMode()
```


Получает режим интерполяции.

**Returns:**
int - Режим.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Устанавливает режим интерполяции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Режим. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Получает тип фильтра.

**Returns:**
int - Тип фильтра.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Устанавливает тип фильтра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Тип фильтра. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Получает метод квантования цвета.

**Returns:**
int - Метод квантования цветов.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Устанавливает метод квантования цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Метод квантования цветов. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Получает метод сравнения цвета.

**Returns:**
int - Метод сравнения цветов.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Устанавливает метод сравнения цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Метод сравнения цветов. |

