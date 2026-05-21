---
title: "PngOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте высококачественные растровые изображения Portable Network Graphics PNG без усилий с помощью нашего API, предлагающего настраиваемые параметры уровней сжатия, битов на пиксель, глубины и альфа‑бит."
type: docs
weight: 38
url: /ru/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Создавайте высококачественные растровые изображения Portable Network Graphics (PNG) без усилий с помощью нашего API, предлагающего настраиваемые параметры уровней сжатия, битов на пиксель, глубины и альфа‑бит. Бесшовно обрабатывайте контейнеры метаданных XMP, обеспечивая всестороннее управление метаданными изображений, и позволяя вам точно настраивать PNG‑изображения в соответствии с вашими требованиями.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PngOptions()](#PngOptions--) | Инициализирует новый экземпляр класса `PngOptions`. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Инициализирует новый экземпляр класса `PngOptions`. |
## Поля

| Поле | Описание |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Уровень сжатия по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getColorType()](#getColorType--) | Получает тип цвета. |
| [setColorType(int value)](#setColorType-int-) | Устанавливает тип цвета. |
| [getProgressive()](#getProgressive--) | Возвращает значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) прогрессивным. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Устанавливает значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) прогрессивным. |
| [getFilterType()](#getFilterType--) | Возвращает тип фильтра, используемый при сохранении PNG‑файла. |
| [setFilterType(int value)](#setFilterType-int-) | Устанавливает тип фильтра, используемый при сохранении PNG‑файла. |
| [getCompressionLevel()](#getCompressionLevel--) | Возвращает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Устанавливает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | Возвращает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | Устанавливает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getBitDepth()](#getBitDepth--) | Возвращает значения глубины цвета в диапазоне 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Устанавливает значения глубины цвета в диапазоне 1, 2, 4, 8, 16. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. На самом деле будет растеризована только одна страница, поскольку PNG не поддерживает многостраничный формат.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Инициализирует новый экземпляр класса `PngOptions`.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Инициализирует новый экземпляр класса `PngOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Параметры PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Уровень сжатия по умолчанию.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Получает тип цвета.

Значение: тип цвета.

**Returns:**
int — тип цвета.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Устанавливает тип цвета.

Значение: тип цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | тип цвета. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Загружает PNG‑изображение        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Использовать индексированный тип цвета
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Использовать максимальное сжатие
    options.setCompressionLevel(9);
    // Получить ближайшую 8‑битную палитру цветов, покрывающую как можно больше пикселей, так чтобы палитровое изображение
    // было почти визуально неотличимо от непалитрового.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Размер выходного файла должен быть значительно уменьшен
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
// Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните изображение синим полупрозрачным градиентом.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Используйте прогрессивную загрузку.
    saveOptions.setProgressive(true);

    // Установите горизонтальное и вертикальное разрешение в 96 пикселей на дюйм.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Каждый пиксель представляет собой тройку (красный, зелёный, синий), за которой следует альфа‑канал.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Установите максимальный уровень сжатия.
    saveOptions.setCompressionLevel(9);

    // Это наилучшее сжатие, но с самой медленной скоростью выполнения.
    // Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр для каждой строки данных.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Количество битов на канал.
    saveOptions.setBitDepth((byte) 8);

    // Сохранить в файл.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Возвращает значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) прогрессивным.

Значение: `` если прогрессивный; иначе, ``.

**Returns:**
boolean — значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) прогрессивным.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Устанавливает значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) прогрессивным.

Значение: `` если прогрессивный; иначе, ``.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) прогрессивным. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Загружает PNG‑изображение        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Использовать индексированный тип цвета
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Использовать максимальное сжатие
    options.setCompressionLevel(9);
    // Получить ближайшую 8‑битную палитру цветов, покрывающую как можно больше пикселей, так чтобы палитровое изображение
    // было почти визуально неотличимо от непалитрового.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Размер выходного файла должен быть значительно уменьшен
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// Количество битов на цветовой канал
createOptions.setBitDepth((byte) 8);

// Каждый пиксель представляет собой тройку (красный, зелёный, синий), за которой следует альфа‑компонент.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// Максимальный уровень сжатия.
createOptions.setCompressionLevel(9);

// Использование фильтров позволяет более эффективно сжимать непрерывные тональные изображения.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Использовать прогрессивную загрузку
createOptions.setProgressive(true);

// Создать PNG‑изображение с пользовательскими параметрами.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполнить изображение полупрозрачным градиентом.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Сохранить в файл.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Возвращает тип фильтра, используемый при сохранении PNG‑файла.

**Returns:**
int — тип фильтра, используемый при сохранении PNG‑файла.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Устанавливает тип фильтра, используемый при сохранении PNG‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | тип фильтра, используемый при сохранении PNG‑файла. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Вспомогательный класс
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// Вот основной пример
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Установить тип фильтра
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//Вывод может выглядеть так:
//Тип фильтра — None, размер выходного изображения — 116845 байт.
//Тип фильтра — Up, размер выходного изображения — 86360 байт.
//Тип фильтра — Sub, размер выходного изображения — 94907 байт.
//Тип фильтра — Paeth, размер выходного изображения — 86403 байт.
//Тип фильтра — Avg, размер выходного изображения — 89956 байт.
//Тип фильтра — Adaptive, размер выходного изображения — 97248 байт.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Возвращает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int — уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Устанавливает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Загружает PNG‑изображение        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Использовать индексированный тип цвета
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Использовать максимальное сжатие
    options.setCompressionLevel(9);
    // Получить ближайшую 8‑битную палитру цветов, покрывающую как можно больше пикселей, так чтобы палитровое изображение
    // было почти визуально неотличимо от непалитрового.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Размер выходного файла должен быть значительно уменьшен
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
// Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните изображение синим полупрозрачным градиентом.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Используйте прогрессивную загрузку.
    saveOptions.setProgressive(true);

    // Установите горизонтальное и вертикальное разрешение в 96 пикселей на дюйм.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Каждый пиксель представляет собой тройку (красный, зелёный, синий), за которой следует альфа‑канал.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Установите максимальный уровень сжатия.
    saveOptions.setCompressionLevel(9);

    // Это наилучшее сжатие, но с самой медленной скоростью выполнения.
    // Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр для каждой строки данных.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Количество битов на канал.
    saveOptions.setBitDepth((byte) 8);

    // Сохранить в файл.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


Возвращает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int — уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


Устанавливает уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | уровень сжатия [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Возвращает значения глубины цвета в диапазоне 1, 2, 4, 8, 16.

Обратите внимание на следующие ограничения:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte — значения глубины цвета в диапазоне 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Устанавливает значения глубины цвета в диапазоне 1, 2, 4, 8, 16.

Обратите внимание на следующие ограничения:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | значения глубины цвета в диапазоне 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
// Вы также можете загрузить изображение любого поддерживаемого формата из файла или потока.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните изображение синим полупрозрачным градиентом.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Используйте прогрессивную загрузку.
    saveOptions.setProgressive(true);

    // Установите горизонтальное и вертикальное разрешение в 96 пикселей на дюйм.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Каждый пиксель представляет собой тройку (красный, зелёный, синий), за которой следует альфа‑канал.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Установите максимальный уровень сжатия.
    saveOptions.setCompressionLevel(9);

    // Это наилучшее сжатие, но с самой медленной скоростью выполнения.
    // Адаптивная фильтрация означает, что процесс сохранения выберет наиболее подходящий фильтр для каждой строки данных.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Количество битов на канал.
    saveOptions.setBitDepth((byte) 8);

    // Сохранить в файл.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

