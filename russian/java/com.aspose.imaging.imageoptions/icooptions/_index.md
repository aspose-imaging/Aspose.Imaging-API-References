---
title: "IcoOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте пользовательские ICO‑файлы изображений для значков приложений без усилий с помощью нашего API, позволяющего без проблем представлять ваше программное обеспечение."
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.imageoptions/icooptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class IcoOptions extends ImageOptionsBase
```

Создавайте пользовательские ICO‑файлы изображений для значков приложений без усилий с помощью нашего API, позволяющего без проблем представлять ваше программное обеспечение. Наш API поддерживает PNG и BMP кадры изображений с различными значениями битов на пиксель, обеспечивая гибкость и совместимость для ваших потребностей в создании значков.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [IcoOptions()](#IcoOptions--) | Инициализирует новый экземпляр класса [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) с форматом кадра ICO, равным Png, и bitsPerPixel, равным 32. |
| [IcoOptions(IcoOptions options)](#IcoOptions-com.aspose.imaging.imageoptions.IcoOptions-) |  |
| [IcoOptions(long format)](#IcoOptions-long-) | Инициализирует новый экземпляр класса [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) с форматом кадра ICO, равным [`format`], и bitsPerPixel, равным 32. |
| [IcoOptions(long format, int bitsPerPixel)](#IcoOptions-long-int-) | Инициализирует новый экземпляр класса [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) | Получает формат кадра ICO. |
| [setFormat(long value)](#setFormat-long-) | Задает формат кадра ICO. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает значение битов на пиксель. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Задает значение битов на пиксель. |
### IcoOptions() {#IcoOptions--}
```
public IcoOptions()
```


Инициализирует новый экземпляр класса [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) с форматом кадра ICO, равным Png, и bitsPerPixel, равным 32.

### IcoOptions(IcoOptions options) {#IcoOptions-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoOptions(IcoOptions options)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) |  |

### IcoOptions(long format) {#IcoOptions-long-}
```
public IcoOptions(long format)
```


Инициализирует новый экземпляр класса [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) с форматом кадра ICO, равным [`format`], и bitsPerPixel, равным 32.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | long | Формат кадра ICO. Обратите внимание, что изображение ICO поддерживает только изображения [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png) и [FileFormat.Bmp](../../com.aspose.imaging/fileformat\#Bmp) в качестве записей. |

### IcoOptions(long format, int bitsPerPixel) {#IcoOptions-long-int-}
```
public IcoOptions(long format, int bitsPerPixel)
```


Инициализирует новый экземпляр класса [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | long | Формат кадра ICO. Обратите внимание, что изображение ICO поддерживает только изображения [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png) и [FileFormat.Bmp](../../com.aspose.imaging/fileformat\#Bmp) в качестве записей. |
| bitsPerPixel | int | Значение битов на пиксель. |

### getFormat() {#getFormat--}
```
public final long getFormat()
```


Получает формат кадра ICO.

**Returns:**
long — формат кадра ICO.
### setFormat(long value) {#setFormat-long-}
```
public final void setFormat(long value)
```


Задает формат кадра ICO.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | формат кадра ICO. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


Получает значение битов на пиксель.

**Returns:**
int — значение битов на пиксель.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


Задает значение битов на пиксель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | значение битов на пиксель. |

