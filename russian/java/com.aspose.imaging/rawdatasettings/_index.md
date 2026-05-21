---
title: "RawDataSettings"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Настройки необработанных данных"
type: docs
weight: 92
url: /ru/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Настройки необработанных данных
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Инициализирован пустой экземпляр. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Инициализировать копию `origin`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Получает формат данных пикселей |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Устанавливает формат данных пикселей |
| [getColorPalette()](#getColorPalette--) | Получает цветовую палитру |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Устанавливает цветовую палитру |
| [getDitheringMethod()](#getDitheringMethod--) | Получает метод дизеринга, используемый для преобразования необработанных данных |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Устанавливает метод дизеринга, используемый для преобразования необработанных данных |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Получает индексированный конвертер цветов |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Устанавливает индексированный конвертер цветов |
| [getCustomColorConverter()](#getCustomColorConverter--) | Получает пользовательский конвертер цветов |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Устанавливает пользовательский конвертер цветов |
| [getFallbackIndex()](#getFallbackIndex--) | Получает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Устанавливает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| [getLineSize()](#getLineSize--) | Получает размер строки пикселей в байтах для обработки необработанных данных |
| [setLineSize(int value)](#setLineSize-int-) | Устанавливает размер строки пикселей в байтах для обработки необработанных данных |
| [<T>copy()](#-T-copy--) | Создает поверхностную копию. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Инициализирован пустой экземпляр.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Инициализирует копию `origin`. Используется в [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Экземпляр, копию которого нужно создать. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Получает формат данных пикселей

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Устанавливает формат данных пикселей

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Формат данных пикселей |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Получает цветовую палитру

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Устанавливает цветовую палитру

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Получает метод дизеринга, используемый для преобразования необработанных данных

**Returns:**
int - Метод дизеринга, используемый для преобразования необработанных данных
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Устанавливает метод дизеринга, используемый для преобразования необработанных данных

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Метод дизеринга, используемый для преобразования необработанных данных |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Получает индексированный конвертер цветов

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Устанавливает индексированный конвертер цветов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Индексированный конвертер цветов |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Получает пользовательский конвертер цветов

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Устанавливает пользовательский конвертер цветов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Пользовательский конвертер цветов |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Получает запасной индекс, используемый, когда индекс палитры выходит за пределы

**Returns:**
int - Запасной индекс, используемый, когда индекс палитры выходит за пределы
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Устанавливает запасной индекс, используемый, когда индекс палитры выходит за пределы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Запасной индекс, используемый, когда индекс палитры выходит за пределы |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Получает размер строки пикселей в байтах для обработки необработанных данных

**Returns:**
int - Размер строки пикселей в байтах для обработки необработанных данных
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Устанавливает размер строки пикселей в байтах для обработки необработанных данных

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Размер строки пикселей в байтах для обработки необработанных данных |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Создает поверхностную копию.

**Returns:**
T - поверхностная копия.
