---
title: "MultiPageOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый класс для форматов, поддерживающих несколько страниц."
type: docs
weight: 30
url: /ru/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Базовый класс для форматов, поддерживающих несколько страниц.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса `MultiPageOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPages()](#getPages--) | Получает или задает страницы. |
| [setPages(int[] value)](#setPages-int---) | Получает или задает страницы. |
| [getPageTitles()](#getPageTitles--) | Получает или задает заголовки страниц. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Получает или задает заголовки страниц. |
| [getTimeInterval()](#getTimeInterval--) | Получает интервал времени. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Устанавливает интервал времени. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Получает параметры растеризации страницы. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Устанавливает параметры растеризации страницы. |
| [getExportArea()](#getExportArea--) | Получает или задает область экспорта. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Получает или задает область экспорта. |
| [getMode()](#getMode--) | Получает или задает режим. |
| [setMode(int value)](#setMode-int-) | Получает или задает режим. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd) |
| [getMergeLayers()](#getMergeLayers--) | Возвращает значение, указывающее, следует ли [merge layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Устанавливает значение, указывающее, следует ли [merge layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Инициализирует страницы из массива диапазонов |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| страницы | int[] | Страницы. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| страницы | int[] | Массив страниц. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область экспорта. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Заголовки страниц. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Заголовки страниц. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область экспорта. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Тип `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Тип `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область экспорта. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Тип `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Тип `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область экспорта. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Инициализирует новый экземпляр класса `MultiPageOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Область экспорта. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Получает или задает страницы.

Значение: Страницы.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Получает или задает страницы.

Значение: Страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Обратите внимание, что если изображение цветное, оно будет автоматически преобразовано в черно‑белый формат в соответствии с опцией ниже:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // По умолчанию все страницы будут сохранены в выходной TIFF, но желаемый набор страниц можно указать явно.
        // Будут экспортированы только первая и вторая страницы.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Установите заголовки страниц.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Сохранить в TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Получает или задает заголовки страниц.

Значение: Заголовки страниц.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Получает или задает заголовки страниц.

Значение: Заголовки страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Обратите внимание, что если изображение цветное, оно будет автоматически преобразовано в черно‑белый формат в соответствии с опцией ниже:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // По умолчанию все страницы будут сохранены в выходной TIFF, но желаемый набор страниц можно указать явно.
        // Будут экспортированы только первая и вторая страницы.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Установите заголовки страниц.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Сохранить в TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


Получает интервал времени.

Значение: Временной интервал.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Устанавливает интервал времени.

Значение: Временной интервал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | временной интервал. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Получает параметры растеризации страницы.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] — параметры растеризации страницы.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Устанавливает параметры растеризации страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | параметры растеризации страницы. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Получает или задает область экспорта.

Значение: Область экспорта.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Получает или задает область экспорта.

Значение: Область экспорта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Получает или задает режим.

Значение: Режим.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Получает или задает режим.

Значение: Режим.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd)

Значение: Имена выходных слоёв.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd)

Значение: Имена выходных слоёв.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Возвращает значение, указывающее, следует ли [merge layers].

Значение: `true`, если [merge layers]; иначе `false`.

**Returns:**
boolean — значение, указывающее, следует ли [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Устанавливает значение, указывающее, следует ли [merge layers].

Значение: `true`, если [merge layers]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, следует ли [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Инициализирует страницы из массива диапазонов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Диапазоны. |

