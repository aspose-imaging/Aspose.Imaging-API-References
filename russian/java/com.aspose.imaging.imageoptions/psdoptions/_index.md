---
title: "PsdOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте изображения Photoshop Document PSD с помощью нашего API, предлагающего разнообразные параметры, включая различные версии формата, методы сжатия, цветовые режимы и количество битов на цветовой канал."
type: docs
weight: 40
url: /ru/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Создавайте изображения Photoshop Document (PSD) с помощью нашего API, предлагающего разнообразные параметры, включая различные версии формата, методы сжатия, цветовые режимы и количество битов на цветовой канал. Бесшовно обрабатывайте контейнеры метаданных XMP, обеспечивая всестороннюю обработку изображений с использованием возможностей формата PSD, таких как слои изображений, маски слоёв и информация о файле, для настройки и креативности в ваших проектах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Инициализирует новый экземпляр класса `PsdOptions`. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Инициализирует новый экземпляр класса `PsdOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Получить или установить контейнер данных XMP |
| [getVersion()](#getVersion--) | Получает или задает версию файла PSD. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию файла PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Получает или задает метод сжатия PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Получает или задает метод сжатия PSD. |
| [getPsdVersion()](#getPsdVersion--) | Получает версию формата файла. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Устанавливает версию формата файла. |
| [getColorMode()](#getColorMode--) | Получает или задает цветовой режим PSD. |
| [setColorMode(short value)](#setColorMode-short-) | Получает или задает цветовой режим PSD. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Получает или задает количество битов на цветовой канал. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Получает или задает количество битов на цветовой канал. |
| [getChannelsCount()](#getChannelsCount--) | Получает количество цветовых каналов. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Устанавливает количество цветовых каналов. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Получает значение, указывающее, следует ли — удалить глобальный ресурс текстового движка — используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствия шрифтов, связанных с текстовыми слоями). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Устанавливает значение, указывающее, следует ли — удалить глобальный ресурс текстового движка — используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствия шрифтов, связанных с текстовыми слоями). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Получает значение, указывающее, следует ли [refresh image preview data] — опция, используемая для повышения совместимости с другими просмотрщиками PSD‑изображений. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Устанавливает значение, указывающее, следует ли [refresh image preview data] — опция, используемая для повышения совместимости с другими просмотрщиками PSD‑изображений. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Получает параметры векторизации PSD. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Устанавливает параметры векторизации PSD. |

## Example: This example demonstrates the use of Aspose.
В этом примере демонстрируется использование Aspose.Imaging for Java API для преобразования изображений в формат PSD. Чтобы достичь этой цели, пример загружает существующее изображение, а затем сохраняет его обратно в формат PSD.
``` java

// Создайте экземпляр класса image и инициализируйте его существующим файлом через путь к файлу.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Создайте экземпляр класса PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Установите CompressionMethod как RLE.
    // Примечание: Другой поддерживаемый CompressionMethod — CompressionMethod.RAW [Без сжатия].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Установите ColorMode в GrayScale.
    // Примечание: Другие поддерживаемые ColorModes — ColorModes.Bitmap и ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Сохраните изображение на диск с указанными настройками PsdOptions.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортируйте только первые две страницы. Эти страницы будут представлены в виде слоёв в результирующем PSD.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Инициализирует новый экземпляр класса `PsdOptions`.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Инициализирует новый экземпляр класса `PsdOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Параметры. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Получить или установить контейнер данных XMP

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает версию файла PSD.

Значение: Версия файла PSD.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает версию файла PSD.

Значение: Версия файла PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Определите линейный градиент от синего к прозрачному.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните PNG‑изображение линейным градиентом от синего к прозрачному.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Следующие параметры будут использованы для сохранения PNG‑изображения в формат PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Количество бит на канал.
    saveOptions.setChannelBitsCount((byte) 8);

    // Количество каналов. Один канал для каждой цветовой компоненты R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Цветовой режим
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Без сжатия.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Версия по умолчанию — 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // Сжатие RLE позволяет уменьшить размер выходного изображения.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Вывод может выглядеть так:
    // Размер PSD‑изображения с сжатием RAW: 40090.
    // Размер PSD‑изображения с сжатием RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Получает или задает метод сжатия PSD.

Значение: Метод сжатия.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Получает или задает метод сжатия PSD.

Значение: Метод сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |


**Example: This example demonstrates the use of Aspose.**
В этом примере демонстрируется использование Aspose.Imaging for Java API для преобразования изображений в формат PSD. Чтобы достичь этой цели, пример загружает существующее изображение, а затем сохраняет его обратно в формат PSD.
``` java

// Создайте экземпляр класса image и инициализируйте его существующим файлом через путь к файлу.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Создайте экземпляр класса PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Установите CompressionMethod как RLE.
    // Примечание: Другой поддерживаемый CompressionMethod — CompressionMethod.RAW [Без сжатия].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Установите ColorMode в GrayScale.
    // Примечание: Другие поддерживаемые ColorModes — ColorModes.Bitmap и ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Сохраните изображение на диск с указанными настройками PsdOptions.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Получает версию формата файла. Это может быть PSD или PSB.

Значение: Версия формата файла.

**Returns:**
byte - версия формата файла.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Устанавливает версию формата файла. Может быть PSD или PSB.

Значение: Версия формата файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | версия формата файла. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Получает или задает цветовой режим PSD.

Значение: режим цвета.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Получает или задает цветовой режим PSD.

Значение: режим цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |


**Example: This example demonstrates the use of Aspose.**
В этом примере демонстрируется использование Aspose.Imaging for Java API для преобразования изображений в формат PSD. Чтобы достичь этой цели, пример загружает существующее изображение, а затем сохраняет его обратно в формат PSD.
``` java

// Создайте экземпляр класса image и инициализируйте его существующим файлом через путь к файлу.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Создайте экземпляр класса PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Установите CompressionMethod как RLE.
    // Примечание: Другой поддерживаемый CompressionMethod — CompressionMethod.RAW [Без сжатия].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Установите ColorMode в GrayScale.
    // Примечание: Другие поддерживаемые ColorModes — ColorModes.Bitmap и ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Сохраните изображение на диск с указанными настройками PsdOptions.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Получает или задает количество битов на цветовой канал.

Значение: количество бит на канал цвета.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Получает или задает количество битов на цветовой канал.

Значение: количество бит на канал цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Определите линейный градиент от синего к прозрачному.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните PNG‑изображение линейным градиентом от синего к прозрачному.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Следующие параметры будут использованы для сохранения PNG‑изображения в формат PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Количество бит на канал.
    saveOptions.setChannelBitsCount((byte) 8);

    // Количество каналов. Один канал для каждой цветовой компоненты R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Цветовой режим
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Без сжатия.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Версия по умолчанию — 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // Сжатие RLE позволяет уменьшить размер выходного изображения.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Вывод может выглядеть так:
    // Размер PSD‑изображения с сжатием RAW: 40090.
    // Размер PSD‑изображения с сжатием RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Получает количество цветовых каналов.

**Returns:**
short - количество цветовых каналов.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Устанавливает количество цветовых каналов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Количество цветовых каналов. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Определите линейный градиент от синего к прозрачному.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните PNG‑изображение линейным градиентом от синего к прозрачному.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Следующие параметры будут использованы для сохранения PNG‑изображения в формат PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Количество бит на канал.
    saveOptions.setChannelBitsCount((byte) 8);

    // Количество каналов. Один канал для каждой цветовой компоненты R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Цветовой режим
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Без сжатия.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Версия по умолчанию — 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // Сжатие RLE позволяет уменьшить размер выходного изображения.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Вывод может выглядеть так:
    // Размер PSD‑изображения с сжатием RAW: 40090.
    // Размер PSD‑изображения с сжатием RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Получает значение, указывающее, следует ли — удалить глобальный ресурс текстового движка — используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствующих шрифтов в текстовых слоях). После использования этой опции пользователю необходимо выполнить следующее в открытом в Photoshop файле: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые окончательные изменения макета.

**Returns:**
boolean - `true`, если [remove global text engine resource]; иначе `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Устанавливает значение, указывающее, следует ли — удалить глобальный ресурс текстового движка — используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствующих шрифтов в текстовых слоях). После использования этой опции пользователю необходимо выполнить следующее в открытом в Photoshop файле: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые окончательные изменения макета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если [remove global text engine resource]; иначе `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Получает значение, указывающее, следует ли [refresh image preview data] — опция, используемая для повышения совместимости с другими просмотрщиками PSD‑изображений.

**Returns:**
boolean - `true`, если [refresh image preview data]; иначе `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Устанавливает значение, указывающее, следует ли [refresh image preview data] — опция, используемая для повышения совместимости с другими просмотрщиками PSD‑изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если [refresh image preview data]; иначе `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Получает параметры векторизации PSD.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Устанавливает параметры векторизации PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | опции векторизации PSD. |

