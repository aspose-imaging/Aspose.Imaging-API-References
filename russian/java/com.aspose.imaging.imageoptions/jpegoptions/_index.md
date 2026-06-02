---
title: "JpegOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте высококачественные JPEG‑изображения без усилий с помощью нашего API, предлагающего регулируемые уровни сжатия для оптимизации размера хранения без ущерба качеству изображения."
type: docs
weight: 26
url: /ru/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Создавайте высококачественные JPEG‑изображения без усилий с помощью нашего API, предлагающего регулируемые уровни сжатия для оптимизации размера хранения без ущерба качеству изображения. Получайте поддержку различных типов сжатия, почти без потерь кодирования, профилей цветов RGB и CMYK, а также данных EXIF, JFIF и контейнеров XMP, обеспечивая гибкие и настраиваемые варианты для ваших потребностей в создании изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Инициализирует новый экземпляр класса `JpegOptions`. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Инициализирует новый экземпляр класса `JpegOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Получает значение предела выделения памяти по умолчанию. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Устанавливает предельный размер выделения памяти по умолчанию. |
| [getJfif()](#getJfif--) | Получает jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Устанавливает jfif. |
| [getComment()](#getComment--) | Получает комментарий JPEG‑файла. |
| [setComment(String value)](#setComment-java.lang.String-) | Устанавливает комментарий JPEG‑файла. |
| [getExifData()](#getExifData--) | Получает контейнер данных Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Устанавливает данные Exif. |
| [getJpegExifData()](#getJpegExifData--) | Получить контейнер данных Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Получить или установить контейнер данных Exif |
| [getCompressionType()](#getCompressionType--) | Получает тип сжатия. |
| [setCompressionType(int value)](#setCompressionType-int-) | Задает тип сжатия. |
| [getColorType()](#getColorType--) | Получает тип цвета для JPEG‑изображения. |
| [setColorType(int value)](#setColorType-int-) | Устанавливает тип цвета для JPEG‑изображения. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Получает количество бит на канал для без потерь JPEG‑изображения. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Устанавливает количество бит на канал для без потерь JPEG‑изображения. |
| [getQuality()](#getQuality--) | Получает качество изображения. |
| [setQuality(int value)](#setQuality-int-) | Устанавливает качество изображения. |
| [getScaledQuality()](#getScaledQuality--) | Масштабированное качество. |
| [getRdOptSettings()](#getRdOptSettings--) | Получает настройки оптимизатора RD. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Устанавливает настройки оптимизатора RD. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Целевой профиль цвета RGB для CMYK JPEG‑изображений. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Целевой профиль цвета RGB для CMYK JPEG‑изображений. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Целевой профиль цвета CMYK для CMYK JPEG‑изображений. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Целевой профиль цвета CMYK для CMYK JPEG‑изображений. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Получает границу различий JPEG‑LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG‑LS). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Устанавливает границу различий JPEG‑LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG‑LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Получает режим чередования JPEG‑LS. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Устанавливает режим чередования JPEG‑LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Получает предустановленные параметры JPEG‑LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Устанавливает предустановленные параметры JPEG-LS. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Получает горизонтальные субдискретизации для каждого компонента. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Устанавливает горизонтальные субдискретизации для каждого компонента. |
| [getVerticalSampling()](#getVerticalSampling--) | Получает вертикальные субдискретизации для каждого компонента. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Устанавливает вертикальные субдискретизации для каждого компонента. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Получает режим округления образца для приведения 8‑битного значения к n‑битному. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Устанавливает режим округления образца для приведения 8‑битного значения к n‑битному. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Получает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа‑канал. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Устанавливает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа‑канал. |
| [getResolutionUnit()](#getResolutionUnit--) | Получает единицу измерения разрешения. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Устанавливает единицу измерения разрешения. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
В этом примере демонстрируется использование различных классов из пространства имен SaveOptions для экспорта. Изображение типа Gif загружается в экземпляр класса Image, а затем экспортируется в несколько форматов.
``` java
String dir = "c:\\temp\\";

//Загрузите существующее изображение (типа Gif) в экземпляр класса Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Экспорт в формат BMP с использованием параметров по умолчанию.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Экспорт в формат JPEG с использованием параметров по умолчанию.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Экспорт в формат PNG с использованием параметров по умолчанию.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Экспорт в формат TIFF с использованием параметров по умолчанию.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. На самом деле будет растеризована только одна страница, поскольку JPEG не поддерживает многостраничный формат.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
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

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Инициализирует новый экземпляр класса `JpegOptions`.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Инициализирует новый экземпляр класса `JpegOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Параметры JPEG. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Получает значение предела выделения памяти по умолчанию.

**Returns:**
int — предел выделения памяти по умолчанию.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Устанавливает предельный размер выделения памяти по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Предел выделения памяти по умолчанию. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Получает jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Устанавливает jfif.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


Получает комментарий JPEG‑файла.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Устанавливает комментарий JPEG‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Получает контейнер данных Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Устанавливает данные Exif.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Данные Exif. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Получить контейнер данных Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Получить или установить контейнер данных Exif

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Получает тип сжатия.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Задает тип сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Создайте JPEG‑изображение размером 100×100 пикселей.
// Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Количество бит на канал равно 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.setBitsPerChannel((byte) 8);

// Установите прогрессивный тип сжатия.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Установите качество изображения. Это значение от 1 до 100.
createOptions.setQuality(100);

// Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Это стандартный параметр для JPEG‑изображений.
// Два хрома‑компонента (Cb и Cr) могут быть уменьшены по пропускной способности, субдискретизированы, сжаты.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Заполните изображение градиентом оттенков серого
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Сохранить в файл.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает тип цвета для JPEG‑изображения.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Создайте JPEG‑изображение размером 100×100 пикселей.
// Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Количество бит на канал равно 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.setBitsPerChannel((byte) 8);

// Установите прогрессивный тип сжатия.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Установите качество изображения. Это значение от 1 до 100.
createOptions.setQuality(100);

// Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Это стандартный параметр для JPEG‑изображений.
// Два хрома‑компонента (Cb и Cr) могут быть уменьшены по пропускной способности, субдискретизированы, сжаты.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Заполните изображение градиентом оттенков серого
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Сохранить в файл.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Устанавливает тип цвета для JPEG‑изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Загрузите BMP‑изображение из файла.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Выполните некоторую обработку изображения.

    // Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Количество бит на канал равно 8.
    // Когда используется палитра, индекс цвета сохраняется в данных изображения вместо самого цвета.
    saveOptions.setBitsPerChannel((byte) 8);

    // Установите прогрессивный тип сжатия.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Установите качество изображения. Это значение от 1 до 100.
    saveOptions.setQuality(100);

    // Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Если исходное изображение цветное, оно будет преобразовано в градации серого.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Используйте палитру, чтобы уменьшить размер вывода.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Получает количество бит на канал для без потерь JPEG‑изображения. Сейчас поддерживается от 2 до 8 бит на канал.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Устанавливает количество бит на канал для без потерь JPEG‑изображения. Сейчас поддерживается от 2 до 8 бит на канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Создайте JPEG‑изображение размером 100×100 пикселей.
// Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Количество бит на канал равно 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.setBitsPerChannel((byte) 8);

// Установите прогрессивный тип сжатия.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Установите качество изображения. Это значение от 1 до 100.
createOptions.setQuality(100);

// Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Это стандартный параметр для JPEG‑изображений.
// Два хрома‑компонента (Cb и Cr) могут быть уменьшены по пропускной способности, субдискретизированы, сжаты.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Заполните изображение градиентом оттенков серого
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Сохранить в файл.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Получает качество изображения.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Устанавливает качество изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Создайте JPEG‑изображение размером 100×100 пикселей.
// Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Количество бит на канал равно 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.setBitsPerChannel((byte) 8);

// Установите прогрессивный тип сжатия.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Установите качество изображения. Это значение от 1 до 100.
createOptions.setQuality(100);

// Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Это стандартный параметр для JPEG‑изображений.
// Два хрома‑компонента (Cb и Cr) могут быть уменьшены по пропускной способности, субдискретизированы, сжаты.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Заполните изображение градиентом оттенков серого
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Сохранить в файл.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Масштабированное качество.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Получает настройки оптимизатора RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Устанавливает настройки оптимизатора RD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | Настройки оптимизатора RD. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Целевой профиль цвета RGB для CMYK JPEG‑изображений. Используется при сохранении изображений. Должен использоваться вместе с CMYKColorProfile для корректного преобразования цветов.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Целевой профиль цвета RGB для CMYK JPEG‑изображений. Используется при сохранении изображений. Должен использоваться вместе с CMYKColorProfile для корректного преобразования цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
В следующем примере PNG загружается и сохраняется в CMYK JPEG с использованием пользовательского ICC‑профиля. Затем CMYK JPEG загружается и сохраняется обратно в PNG. Преобразование цветов из RGB в CMYK и из CMYK в RGB выполняется с помощью пользовательских ICC‑профилей.
``` java
String dir = "c:\\temp\\";

// Загрузить PNG и сохранить его в CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Использовать пользовательские ICC‑профили
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Загрузить CMYK JPEG и сохранить его в PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Использовать пользовательские ICC‑профили
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Целевой профиль цвета CMYK для CMYK JPEG‑изображений. Используется при сохранении изображений. Должен использоваться вместе с RGBColorProfile для корректного преобразования цветов.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Целевой профиль цвета CMYK для CMYK JPEG‑изображений. Используется при сохранении изображений. Должен использоваться вместе с RGBColorProfile для корректного преобразования цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
В следующем примере PNG загружается и сохраняется в CMYK JPEG с использованием пользовательского ICC‑профиля. Затем CMYK JPEG загружается и сохраняется обратно в PNG. Преобразование цветов из RGB в CMYK и из CMYK в RGB выполняется с помощью пользовательских ICC‑профилей.
``` java
String dir = "c:\\temp\\";

// Загрузить PNG и сохранить его в CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Использовать пользовательские ICC‑профили
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Загрузить CMYK JPEG и сохранить его в PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Использовать пользовательские ICC‑профили
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Получает границу различий JPEG‑LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG‑LS).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Устанавливает границу различий JPEG‑LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG‑LS).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Получает режим чередования JPEG‑LS.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Устанавливает режим чередования JPEG‑LS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Получает предустановленные параметры JPEG‑LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Устанавливает предустановленные параметры JPEG-LS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Получает горизонтальные субдискретизации для каждого компонента.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Устанавливает горизонтальные субдискретизации для каждого компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Получает вертикальные субдискретизации для каждого компонента.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Устанавливает вертикальные субдискретизации для каждого компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Получает режим округления образца для приведения 8‑битного значения к n‑битному значению. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Устанавливает режим округления образца для приведения 8‑битного значения к n‑битному значению. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Получает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа‑канал.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Устанавливает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа‑канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Получает единицу измерения разрешения.

**Returns:**
byte — единица разрешения.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Создайте JPEG‑изображение размером 100×100 пикселей.
// Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Количество бит на канал равно 8, 8, 8 для компонентов Y, Cr, Cb соответственно.
createOptions.setBitsPerChannel((byte) 8);

// Установите прогрессивный тип сжатия.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Установите качество изображения. Это значение от 1 до 100.
createOptions.setQuality(100);

// Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Это стандартный параметр для JPEG‑изображений.
// Два хрома‑компонента (Cb и Cr) могут быть уменьшены по пропускной способности, субдискретизированы, сжаты.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Заполните изображение градиентом оттенков серого
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Сохранить в файл.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Устанавливает единицу измерения разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | единица разрешения. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Загрузите BMP‑изображение из файла.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Выполните некоторую обработку изображения.

    // Используйте дополнительные параметры, чтобы указать требуемые параметры изображения.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Количество бит на канал равно 8.
    // Когда используется палитра, индекс цвета сохраняется в данных изображения вместо самого цвета.
    saveOptions.setBitsPerChannel((byte) 8);

    // Установите прогрессивный тип сжатия.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Установите качество изображения. Это значение от 1 до 100.
    saveOptions.setQuality(100);

    // Установите горизонтальное/вертикальное разрешение в 96 точек на дюйм.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Если исходное изображение цветное, оно будет преобразовано в градации серого.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Используйте палитру, чтобы уменьшить размер вывода.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

