---
title: "BmpOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для параметров создания растровых изображений BMP и DIB предоставляет разработчикам универсальный набор инструментов для создания пользовательских изображений Bitmap BMP и Device Independent Bitmap DIB."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

API для параметров создания растровых изображений BMP и DIB предоставляет разработчикам универсальный набор инструментов для создания пользовательских изображений Bitmap (BMP) и Device Independent Bitmap (DIB). С помощью этого API вы можете точно задавать характеристики изображения, такие как количество бит на пиксель, уровень сжатия и тип сжатия, адаптируя вывод под конкретные требования. Этот богатый функциями API позволяет разработчикам легко и гибко создавать высококачественные, настроенные растровые изображения для различных приложений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Инициализирует новый экземпляр класса `BmpOptions`. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Инициализирует новый экземпляр класса `BmpOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает или задает количество бит на пиксель изображения. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Получает или задает количество бит на пиксель изображения. |
| [getCompression()](#getCompression--) | Получает тип сжатия. |
| [setCompression(long value)](#setCompression-long-) | Задает тип сжатия. |

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


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. На самом деле будет растеризована только одна страница, поскольку BMP не поддерживает многостраничный формат.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Инициализирует новый экземпляр класса `BmpOptions`.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Инициализирует новый экземпляр класса `BmpOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | Параметры BMP. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает или задает количество бит на пиксель изображения.

**Returns:**
int — Количество бит на пиксель изображения.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Получает или задает количество бит на пиксель изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Количество бит на пиксель изображения. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Создать BmpOptions.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
    saveOptions.setBitsPerPixel(8);

    // Установите ближайшую 8-битную цветовую палитру, покрывающую максимальное количество пикселей изображения, так чтобы получилось палетизированное изображение
    // было почти визуально неотличимо от непалитрового.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Сохранить без сжатия.
    // Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Установите горизонтальное и вертикальное разрешение в 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Получает тип сжатия. Тип сжатия по умолчанию — [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), который позволяет сохранять [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) с прозрачностью.

Значение: тип сжатия.

**Returns:**
long - тип сжатия.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Устанавливает тип сжатия. Тип сжатия по умолчанию — [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), который позволяет сохранять [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) с прозрачностью.

Значение: тип сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | тип сжатия. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Создать BmpOptions.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
    saveOptions.setBitsPerPixel(8);

    // Установите ближайшую 8-битную цветовую палитру, покрывающую максимальное количество пикселей изображения, так чтобы получилось палетизированное изображение
    // было почти визуально неотличимо от непалитрового.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Сохранить без сжатия.
    // Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Установите горизонтальное и вертикальное разрешение в 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Загрузить PNG‑изображение из файла.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP‑изображение сохраняется с поддержкой прозрачности по умолчанию.
    // Если вы хотите явно указать такой режим, свойство Compression объекта BmpOptions должно быть установлено в BitmapCompression.Bitfields.
    // Метод сжатия BitmapCompression.Bitfields является методом сжатия по умолчанию в BmpOptions.
    // Таким образом, тот же результат экспорта BMP‑изображения с прозрачностью можно достичь любым из следующих способов.
    // С неявными параметрами по умолчанию:
    pngImage.save(outputPathPng);
    // С явными параметрами по умолчанию:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Указание метода сжатия BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Загрузить PNG‑изображение из файла.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP‑изображение сохраняется с поддержкой прозрачности по умолчанию, что достигается использованием метода сжатия BitmapCompression.Bitfields.
    // Чтобы сохранить BMP‑изображение с методом сжатия Rgb, необходимо указать BmpOptions со свойством Compression, установленным в BitmapCompression.Rgb.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

