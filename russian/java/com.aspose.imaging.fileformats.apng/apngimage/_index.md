---
title: "ApngImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для Animated PNG (Animated Portable Network Graphics) — универсальное решение для разработчиков, желающих интегрировать анимированный контент в свои приложения."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

API для Animated PNG (Animated Portable Network Graphics) является универсальным решением для разработчиков, желающих интегрировать анимированный контент в свои приложения. Этот API предоставляет обширный контроль над настройками кадров, позволяя пользователям задавать параметры, специфичные для каждого кадра, включая длительность цикла и настройки PNG‑файлов. С помощью этого функционального инструмента вы можете без труда управлять и оптимизировать отображение APNG‑изображений, импортировать и экспортировать изображения, улучшая динамические и интерактивные аспекты ваших приложений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Начните работу с классом [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage), инициализируя новый экземпляр без труда. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Быстро получайте информацию о формате файла с помощью этого удобного свойства. |
| [getPageCount()](#getPageCount--) | Получайте общее количество страниц в вашем файле изображения без труда с помощью этого свойства. |
| [getPages()](#getPages--) | Без труда получайте доступ к страницам вашего изображения с помощью этого удобного свойства. |
| [getNumPlays()](#getNumPlays--) | Без труда контролируйте количество повторов вашей анимации с помощью этого универсального свойства. |
| [setNumPlays(int value)](#setNumPlays-int-) | Без труда контролируйте количество повторов вашей анимации с помощью этого универсального свойства. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Легко регулируйте длительность кадра по умолчанию при создании новых кадров с помощью этого гибкого свойства. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Легко регулируйте длительность кадра по умолчанию при создании новых кадров с помощью этого гибкого свойства. |
| [getInterlaced()](#getInterlaced--) | Быстро определяйте, является ли объект [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) чересстрочным, с помощью этого удобного свойства. |
| [getOriginalOptions()](#getOriginalOptions--) | Получайте параметры, основанные на исходных настройках файла, без труда с помощью этого интуитивного метода. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Легко получите параметры по умолчанию с помощью этого простого метода. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Быстро получайте дату и время последнего изменения ресурсного изображения с помощью этого удобного метода. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Добавляйте новую страницу в изображение без труда с помощью этого интуитивного метода. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Без труда расширяйте коллекцию кадров, добавляя новый кадр в конец, с помощью этого интуитивного метода. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Расширяйте свою коллекцию кадров без проблем, добавляя новый кадр к ней с этим интуитивным методом. |
| [insertFrame(int index)](#insertFrame-int-) | Без труда вставляйте новый кадр в свою коллекцию кадров в указанное место с этим интуитивным методом. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Вставляет новый кадр в собственную коллекцию кадров в указанном индексе. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Вставляет новый кадр в собственную коллекцию кадров в указанном индексе. |
| [popFrameAt(int index)](#popFrameAt-int-) | Удаляйте и получайте кадр в указанном индексе из вашей коллекции кадров с помощью этого интуитивного метода. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Удаляйте кадр в указанном индексе из вашей коллекции кадров без проблем с этим методом. |
| [removeAllFrames()](#removeAllFrames--) | Очищайте свою коллекцию кадров, удаляя все кадры, с помощью этого интуитивного метода. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Устанавливайте указанное растровое изображение в качестве изображения по умолчанию для текущей анимации без труда с помощью этого метода. |
| [resetDefaultImage()](#resetDefaultImage--) | Удалите ранее установленное изображение по умолчанию с помощью этого интуитивного метода. |

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

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Начните работу с классом [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage), инициализируя новый экземпляр без усилий. Идеально подходит для разработчиков, желающих быстро и эффективно начать использовать объекты ApngImage в своих проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Параметры. |
| width | int | Ширина. |
| height | int | Высота. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Быстро получайте информацию о формате файла с помощью этого удобного свойства. Идеально подходит для разработчиков, которым необходимо легко получать детали о формате их файлов Apng.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получайте общее количество страниц в вашем файле изображения без усилий с помощью этого свойства. Идеально подходит для разработчиков, которым нужен быстрый доступ к информации о числе страниц.

Значение: количество страниц.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Без усилий получайте доступ к страницам вашего изображения с помощью этого удобного свойства. Идеально подходит для разработчиков, ищущих быстрый и простой доступ к отдельным страницам для их обработки.

Значение: Страницы.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Без усилий контролируйте количество повторов вашей анимации с помощью этого универсального свойства. Идеально подходит для разработчиков, желающих точный контроль над поведением анимации, с поддержкой бесконечного цикла, если значение равно 0.

Значение: количество повторов.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Без усилий контролируйте количество повторов вашей анимации с помощью этого универсального свойства. Идеально подходит для разработчиков, желающих точный контроль над поведением анимации, с поддержкой бесконечного цикла, если значение равно 0.

Значение: количество повторов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Легко регулируйте длительность кадра по умолчанию при создании новых кадров с помощью этого гибкого свойства. Идеально подходит для разработчиков, желающих эффективно настраивать тайминг кадров в своих анимациях.

Значение: длительность кадра по умолчанию в миллисекундах.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Легко регулируйте длительность кадра по умолчанию при создании новых кадров с помощью этого гибкого свойства. Идеально подходит для разработчиков, желающих эффективно настраивать тайминг кадров в своих анимациях.

Значение: длительность кадра по умолчанию в миллисекундах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Быстро определяйте, является ли объект [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) интерлейсированным, используя это удобное свойство. Идеально подходит для разработчиков, которым необходимо легко проверять статус интерлейсинга PNG‑изображений.

Значение: `true`, если интерлейсировано; иначе `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получайте параметры на основе настроек оригинального файла без усилий с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих получить и использовать настройки, соответствующие характеристикам оригинального файла. Это может помочь сохранить глубину цвета и другие параметры оригинального изображения без изменений. Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), будет получено PNG‑изображение с 8‑битным цветом. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битным цветом, используйте этот метод для получения соответствующих параметров сохранения и передайте их в метод [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Получайте параметры по умолчанию без усилий с помощью этого простого метода. Идеально подходит для разработчиков, желающих быстрый доступ к настройкам изображений Apng по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Быстро получайте дату и время последнего изменения ресурсного изображения с помощью этого удобного метода. Идеально подходит для разработчиков, которым необходимо отслеживать изменения и эффективно управлять ресурсами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| useDefault | boolean | если установлено в `true`, использует информацию из FileInfo в качестве значения по умолчанию. |

**Returns:**
java.util.Date - Дата и время последнего изменения ресурсного изображения.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Добавляйте новую страницу в изображение без усилий с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих динамически расширять содержимое своих файлов изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Страница для добавления. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

Легко добавляйте новый кадр в конец вашей коллекции кадров с помощью этого простого метода. Идеально подходит для разработчиков, желающих динамически расширять свою коллекцию кадров для анимаций с многокадровыми изображениями. Новый кадр будет создан в соответствии с размером текущего изображения.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Без усилий расширяйте свою коллекцию кадров, добавляя новый кадр в конец с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих динамически улучшать анимации многокадровых изображений. Содержимое нового кадра будет заполнено из указанного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение кадра. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Расширяйте свою коллекцию кадров без проблем, добавляя новый кадр с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих обогатить свои анимации многокадровых изображений. Содержимое нового кадра будет заполнено из указанного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение кадра. |
| frameTime | long | Длительность кадра в миллисекундах. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Без усилий вставляйте новый кадр в вашу коллекцию кадров в указанное место с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих точный контроль над расположением кадров в анимациях многокадровых изображений. Новый кадр будет создан в соответствии с размером текущего изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Вставляет новый кадр в собственную коллекцию кадров по указанному индексу. Содержимое нового кадра будет заполнено из указанного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение кадра. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Вставляет новый кадр в собственную коллекцию кадров по указанному индексу. Содержимое нового кадра будет заполнено из указанного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение кадра. |
| frameTime | long | Длительность кадра в миллисекундах. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Удаляйте и получайте кадр по указанному индексу из вашей коллекции кадров с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих эффективного управления кадрами в своих анимациях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Удаляйте кадр по указанному индексу из вашей коллекции кадров без проблем с помощью этого метода. Идеально подходит для разработчиков, желающих упрощённое управление кадрами в их многокадровых изображениях. Кадр, подлежащий удалению, будет освобождён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Очистите свою коллекцию кадров, удалив все кадры с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих сбросить или обновить свои анимации.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Установите указанное растровое изображение в качестве изображения по умолчанию для текущей анимации без усилий с помощью этого метода. Отлично подходит для разработчиков, желающих настроить изображение по умолчанию в своих анимациях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Удалите ранее установленное изображение по умолчанию с помощью этого интуитивного метода. Идеально подходит для разработчиков, желающих сбросить или очистить изображение по умолчанию в своей анимации. После этого изображение по умолчанию становится первым кадром в собственной коллекции кадров (его нельзя удалить с помощью этого метода).

