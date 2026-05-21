---
title: "ApngOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для создания формата файлов изображений Animated PNG Animated Portable Network Graphics является динамичным инструментом для разработчиков, стремящихся создавать захватывающие анимированные изображения."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

API для создания формата файлов изображений Animated PNG (Animated Portable Network Graphics) является динамичным инструментом для разработчиков, стремящихся создавать захватывающие анимированные изображения. С настраиваемыми параметрами, такими как длительность кадра и количество повторов, этот API позволяет точно настраивать анимированный контент в соответствии с конкретными потребностями. При создании привлекательной веб-графики или интерактивных визуальных элементов вы можете использовать этот API для бесшовного внедрения изображений APNG с точным контролем параметров анимации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Инициализирует новый экземпляр класса [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Инициализирует новый экземпляр класса `ApngOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Получает количество повторов анимации. |
| [setNumPlays(int value)](#setNumPlays-int-) | Устанавливает количество повторов анимации. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Получает длительность кадра по умолчанию. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Устанавливает длительность кадра по умолчанию. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Экспорт в анимацию APNG с неограниченным количеством циклов анимации по умолчанию
    image.save("Animation1.webp.png", new ApngOptions());
    // Настройка циклов анимации
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Настройка длительности кадра по умолчанию
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Инициализирует новый экземпляр класса [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Инициализирует новый экземпляр класса `ApngOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Параметры PNG. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Возвращает количество повторов анимации. 0 указывает на бесконечный цикл.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Экспорт в анимацию APNG с неограниченным количеством циклов анимации по умолчанию
    image.save("Animation1.webp.png", new ApngOptions());
    // Настройка циклов анимации
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Устанавливает количество повторов анимации. 0 указывает на бесконечный цикл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Экспорт в анимацию APNG с неограниченным количеством циклов анимации по умолчанию
    image.save("Animation1.webp.png", new ApngOptions());
    // Настройка циклов анимации
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Получает длительность кадра по умолчанию.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Устанавливает длительность кадра по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

