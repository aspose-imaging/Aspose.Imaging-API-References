---
title: "BmpImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Вы можете без труда работать с файлами Bitmap BMP и Device Independent Bitmap DIB, обеспечивая эффективную манипуляцию и обработку растровых изображений."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Вы можете без труда работать с файлами Bitmap (BMP) и Device Independent Bitmap (DIB), обеспечивая эффективную манипуляцию и обработку растровых изображений. Выполняя различные операции с изображениями, этот API упрощает рабочий процесс, предлагая разработчикам надежный набор инструментов для работы с форматами BMP и DIB в их программных приложениях.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Начните без труда использовать класс BmpImage с этим конструктором, который инициализирует новый экземпляр. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Без труда создайте новый экземпляр класса [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) с помощью этого конструктора, используя указанные параметры, такие как путь, bitsPerPixel и сжатие. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Начните без труда использовать класс [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), инициализируя новый экземпляр этим конструктором, используя поток в качестве входных данных. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Начните беспрепятственно работать с классом [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), создав новый экземпляр с использованием потока и указанных параметров, таких как bitsPerPixel и сжатие. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Без труда создайте новый экземпляр класса [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), инициализировав его объектом RasterImage. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Начните беспрепятственно работать с классом [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), создав новый экземпляр с использованием rasterImage и указанных параметров, таких как bitsPerPixel и сжатие. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Начните без труда использовать класс [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), создав новый экземпляр с указанными параметрами ширины и высоты. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Начните беспрепятственно использовать класс [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), инициализировав новый экземпляр с параметрами, такими как ширина, высота, глубина цвета и палитра. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Легко создайте новый экземпляр класса [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) с помощью этого конструктора, указывая такие параметры, как ширина, высота, bitsPerPixel и палитра. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Быстро получите основные сведения о вашем растровом изображении с помощью этой простой функции. |
| [getFileFormat()](#getFileFormat--) | Легко получить значение формата файла с помощью этого удобного свойства. |
| [getRawDataFormat()](#getRawDataFormat--) | Легко определите формат ваших необработанных данных с помощью этой удобной функции. |
| [getRawLineSize()](#getRawLineSize--) | Быстро узнайте размер каждой необработанной строки в байтах с помощью этого простого свойства. |
| [getCompression()](#getCompression--) | Легко получите тип сжатия, используемый для изображения, с помощью этого свойства. |
| [getWidth()](#getWidth--) | Легко получите ширину изображения с помощью этого свойства. |
| [getHeight()](#getHeight--) | Легко получите высоту изображения с помощью этого свойства. |
| [getBitsPerPixel()](#getBitsPerPixel--) | С легкостью получите количество бит на пиксель изображения, используя это свойство. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Это свойство позволяет вам легко получить или установить горизонтальное разрешение, измеряемое в пикселях на дюйм, объекта [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Это свойство позволяет вам легко получить или установить горизонтальное разрешение, измеряемое в пикселях на дюйм, объекта [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getVerticalResolution()](#getVerticalResolution--) | Легко получите или задайте вертикальное разрешение, измеряемое в пикселях на дюйм, этого объекта [RasterImage](../../com.aspose.imaging/rasterimage) с помощью этого свойства. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Легко получите или задайте вертикальное разрешение, измеряемое в пикселях на дюйм, этого объекта [RasterImage](../../com.aspose.imaging/rasterimage) с помощью этого свойства. |
| [hasAlpha()](#hasAlpha--) | Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Легко отрегулируйте разрешение вашего [RasterImage](../../com.aspose.imaging/rasterimage) с помощью этого удобного метода. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Легко получите параметры по умолчанию с помощью этого простого метода. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Создать BMP‑изображение размером 100 × 100 пикселей.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Заполните изображение простым линейным градиентом от красного к черному.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

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


## Example: The example shows how to export a BmpImage with the Rgb compression type.

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


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Начните использовать класс BmpImage без усилий с помощью этого конструктора, который инициализирует новый экземпляр. Идеально подходит для разработчиков, желающих быстро и эффективно приступить к работе с объектами [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Легко создайте новый экземпляр класса [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) с помощью этого конструктора, используя указанные параметры, такие как путь, bitsPerPixel и сжатие. Идеально подходит для разработчиков, желающих быстро и эффективно инициализировать объекты BmpImage с точным контролем над характеристиками изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |
| bitsPerPixel | int | Биты на пиксель. |
| сжатие | long | Сжатие, которое следует использовать. |
| horizontalResolution | double | Горизонтальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |
| verticalResolution | double | Вертикальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Начните использовать класс [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) без усилий, инициализируя новый экземпляр с помощью этого конструктора и используя поток в качестве входных данных. Идеально подходит для разработчиков, ищущих удобный способ работы с объектами BmpImage из различных источников данных, обеспечивая гибкость и простоту интеграции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Начните работать с классом [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) без проблем, создав новый экземпляр с использованием потока и указанных параметров, таких как bitsPerPixel и сжатие. Идеально подходит для разработчиков, ищущих простой способ обработки объектов BmpImage, обеспечивая гибкость и эффективность в их проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |
| bitsPerPixel | int | Биты на пиксель. |
| сжатие | long | Сжатие, которое следует использовать. |
| horizontalResolution | double | Горизонтальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |
| verticalResolution | double | Вертикальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Легко создайте новый экземпляр класса [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage), инициализировав его объектом RasterImage. Идеально подходит для разработчиков, желающих без проблем конвертировать существующие растровые изображения в формат BmpImage, обеспечивая совместимость и простоту интеграции в их проекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с которым инициализируются данные пикселей и палитры. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Начните работать с классом [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) без проблем, создав новый экземпляр с использованием rasterImage и указанных параметров, таких как bitsPerPixel и сжатие. Идеально подходит для разработчиков, ищущих простой способ обработки объектов BmpImage, обеспечивая гибкость и эффективность в их проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с которым инициализируются данные пикселей и палитры. |
| bitsPerPixel | int | Биты на пиксель. |
| сжатие | long | Сжатие, которое следует использовать. |
| horizontalResolution | double | Горизонтальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |
| verticalResolution | double | Вертикальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Начните использовать класс [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) без усилий, создав новый экземпляр с указанными параметрами ширины и высоты. Идеально подходит для разработчиков, ищущих удобный способ создания объектов BmpImage с пользовательскими размерами, обеспечивая гибкость и простоту интеграции в их проекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Начните использовать класс [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) без проблем, инициализируя новый экземпляр с параметрами, такими как ширина, высота, глубина цвета и палитра. Идеально подходит для разработчиков, ищущих простой способ создавать объекты BmpImage с пользовательскими размерами и настройками цветов, обеспечивая гибкость и эффективность в их проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |
| bitsPerPixel | int | Биты на пиксель. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Легко создайте новый экземпляр класса [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) с помощью этого конструктора, указывая параметры, такие как ширина, высота, bitsPerPixel и палитра. Идеально подходит для разработчиков, ищущих удобный способ генерировать объекты BmpImage с пользовательскими размерами и настройками цветов, обеспечивая гибкость и простоту интеграции в их проекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |
| bitsPerPixel | int | Биты на пиксель. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |
| сжатие | long | Сжатие, которое следует использовать. |
| horizontalResolution | double | Горизонтальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |
| verticalResolution | double | Вертикальное разрешение. Обратите внимание, что из‑за округления полученное разрешение может немного отличаться от переданного. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Быстро получайте важные сведения о вашем bitmap‑изображении с помощью этой простой функции. Идеально подходит для разработчиков, которым необходимо извлекать информацию заголовка их изображений.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Количество цветов палитры, необходимых для отображения bitmap: 0
//Количество цветов палитры, используемых в bitmap: 0
//Сжатие bitmap: 0
//Высота bitmap: 100
//Ширина bitmap: 100
//Размер необработанных данных bitmap в байтах: 40000
//Количество плоскостей: 1
//Горизонтальное разрешение bitmap в пикселях на метр: 0
//Вертикальное разрешение bitmap в пикселях на метр: 0
//Количество бит на пиксель: 32
//Маски дополнительных битов: null
//Размер заголовка в байтах: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Легко получить значение формата файла с помощью этого удобного свойства. Идеально для разработчиков, которым нужен быстрый доступ к информации о формате файла.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// Вспомогательный класс, используемый в основном примере ниже.
class Utils {
    // Вспомогательный метод для получения строкового представления формата файла.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Вот основной пример
Utils utils = new Utils();

// Создайте BMP‑изображение 32‑bpp размером 100 × 100 пикселей.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Создайте BMP‑изображение 24‑bpp размером 100 × 100 пикселей.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// В большинстве случаев BMP не поддерживает альфа‑канал, поэтому вывод, вероятно, будет выглядеть так:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, использованные каналы: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, использованные каналы: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Легко получайте формат ваших необработанных данных с помощью этой удобной функции. Идеально подходит для разработчиков, желающих быстро получать важную информацию о формате их данных.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Формат пикселя: Rgb24Bpp, использованные каналы: 8,8,8
//Размер необработанной строки в байтах: 1500
//Сжатие bitmap: 0
//Ширина битмапа: 500
//Высота битмапа: 500
//Количество бит на пиксель: 24
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
//Установить значения разрешения в 96 dpi
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Быстро получайте размер каждой необработанной строки в байтах с помощью этого простого свойства. Идеально для разработчиков, которым необходимо эффективно работать с необработанными данными изображения.

**Returns:**
int - Размер необработанной строки в байтах.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Формат пикселя: Rgb24Bpp, использованные каналы: 8,8,8
//Размер необработанной строки в байтах: 1500
//Сжатие bitmap: 0
//Ширина битмапа: 500
//Высота битмапа: 500
//Количество бит на пиксель: 24
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
//Установить значения разрешения в 96 dpi
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Легко получайте тип сжатия, используемый для изображения, с помощью этого свойства. Отлично подходит для разработчиков, которым нужно быстро получать информацию о сжатии изображения.

**Returns:**
long - Сжатие изображения [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// Вспомогательный класс, используемый в основном примере ниже.
class Utils {
    // Вспомогательный метод для получения строкового представления формата файла.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Вот основной пример
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Создайте монохромную палитру, содержащую только красный и зелёный цвета.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Создайте BMP‑изображение с 8 бит на пиксель размером 100 × 100 пикселей.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Заполните всё изображение красным цветом.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Сохраните изображение в поток, чтобы получить размер выходного изображения.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// Вывод может выглядеть так:
// Сжатие=RGB
// Количество бит на пиксель=8
// Размеры изображения=100 × 100
// Размер необработанной строки=100
// Размер вывода в байтах=11078
// ---------------------------------------------
// Сжатие=RLE8
// Количество бит на пиксель=8
// Размеры изображения=100 × 100
// Размер необработанной строки=100
// Размер вывода в байтах=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Легко получайте ширину изображения с помощью этого свойства. Идеально для разработчиков, ищущих быструю информацию о размерах изображения.

**Returns:**
int - Ширина изображения в пикселях.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Формат пикселя: Rgb24Bpp, использованные каналы: 8,8,8
//Размер необработанной строки в байтах: 1500
//Сжатие bitmap: 0
//Ширина битмапа: 500
//Высота битмапа: 500
//Количество бит на пиксель: 24
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
//Установить значения разрешения в 96 dpi
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Легко получайте высоту изображения с помощью этого свойства. Идеально для разработчиков, которым нужен быстрый доступ к информации о размерах изображения.

**Returns:**
int - Высота изображения в пикселях.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Формат пикселя: Rgb24Bpp, использованные каналы: 8,8,8
//Размер необработанной строки в байтах: 1500
//Сжатие bitmap: 0
//Ширина битмапа: 500
//Высота битмапа: 500
//Количество бит на пиксель: 24
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
//Установить значения разрешения в 96 dpi
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Легко получайте количество бит на пиксель изображения с помощью этого свойства. Отлично подходит для разработчиков, ищущих быструю информацию о качестве и глубине изображения.

**Returns:**
int — Количество бит на пиксель изображения.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Формат пикселя: Rgb24Bpp, использованные каналы: 8,8,8
//Размер необработанной строки в байтах: 1500
//Сжатие bitmap: 0
//Ширина битмапа: 500
//Высота битмапа: 500
//Количество бит на пиксель: 24
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
//Установить значения разрешения в 96 dpi
//Горизонтальное разрешение, в пикселях на дюйм: 96.012
//Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Это свойство позволяет вам легко получать или задавать горизонтальное разрешение, измеряемое в пикселях на дюйм, объекта [RasterImage](../../com.aspose.imaging/rasterimage). Идеально для разработчиков, которым нужен точный контроль над разрешением изображения в их приложениях.

**Returns:**
double - Горизонтальное разрешение.

Обратите внимание, что по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода \#setResolution(double, double).setResolution(double, double) для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Получить горизонтальное и вертикальное разрешение BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 0.0
// Вертикальное разрешение, в пикселях на дюйм: 0.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 96.012
// Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Это свойство позволяет вам легко получать или задавать горизонтальное разрешение, измеряемое в пикселях на дюйм, объекта [RasterImage](../../com.aspose.imaging/rasterimage). Идеально для разработчиков, которым нужен точный контроль над разрешением изображения в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Горизонтальное разрешение. |

--------------------

Обратите внимание, что по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода \#setResolution(double, double).setResolution(double, double) для обновления обоих значений разрешения одним вызовом. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Легко получить или задать вертикальное разрешение, измеряемое в пикселях на дюйм, этого объекта [RasterImage](../../com.aspose.imaging/rasterimage) с помощью этого свойства. Идеально для разработчиков, которым нужен точный контроль над разрешением изображения в их приложениях.

**Returns:**
double - Вертикальное разрешение.

--------------------

Обратите внимание, что по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода \#setResolution(double, double).setResolution(double, double) для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Получить горизонтальное и вертикальное разрешение BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 0.0
// Вертикальное разрешение, в пикселях на дюйм: 0.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 96.012
// Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Легко получить или задать вертикальное разрешение, измеряемое в пикселях на дюйм, этого объекта [RasterImage](../../com.aspose.imaging/rasterimage) с помощью этого свойства. Идеально для разработчиков, которым нужен точный контроль над разрешением изображения в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Вертикальное разрешение. |

--------------------

Обратите внимание, что по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода \#setResolution(double, double).setResolution(double, double) для обновления обоих значений разрешения одним вызовом. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал.

**Returns:**
boolean — значение, указывающее, есть ли у этого экземпляра альфа‑канал.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Легко отрегулировать разрешение вашего [RasterImage](../../com.aspose.imaging/rasterimage) с помощью этого удобного метода. Идеально для разработчиков, стремящихся к точному контролю над разрешением изображения в своих приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение в точках на дюйм для [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Вертикальное разрешение в точках на дюйм для [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Получить горизонтальное и вертикальное разрешение BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 0.0
// Вертикальное разрешение, в пикселях на дюйм: 0.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 96.012
// Вертикальное разрешение, в пикселях на дюйм: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Легко получить параметры по умолчанию с помощью этого простого метода. Идеально для разработчиков, которым нужен быстрый доступ к настройкам или конфигурациям изображения по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
