---
title: "GifOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для создания растровых файлов Graphical Interchange Format GIF предоставляет разработчикам всесторонние возможности для генерации GIF‑изображений с точным контролем."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

API для создания растровых файлов Graphical Interchange Format (GIF) предоставляет разработчикам всесторонние возможности для генерации GIF‑изображений с точным контролем. С возможностями установки фонового цвета, цветовой палитры, разрешения, типа чередования строк, прозрачного цвета, контейнера метаданных XMP и сжатия изображения, этот API обеспечивает гибкость и эффективность при создании оптимизированных и визуально привлекательных GIF‑файлов, адаптированных к конкретным требованиям приложения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifOptions()](#GifOptions--) | Инициализирует новый экземпляр класса `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Инициализирует новый экземпляр класса `GifOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Получает или задаёт значение, указывающее, применяется ли коррекция палитры. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Получает или задаёт значение, указывающее, применяется ли коррекция палитры. |
| [getLoopsCount()](#getLoopsCount--) | Получает количество циклов (по умолчанию 1 цикл) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Задаёт количество циклов (по умолчанию 1 цикл) |
| [getColorResolution()](#getColorResolution--) | Получает или задаёт разрешение цвета GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Получает или задаёт разрешение цвета GIF. |
| [isPaletteSorted()](#isPaletteSorted--) | Получает или задаёт значение, указывающее, отсортированы ли элементы палитры. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Получает или задаёт значение, указывающее, отсортированы ли элементы палитры. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Получает или задаёт соотношение сторон пикселя GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Получает или задаёт соотношение сторон пикселя GIF. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Получает или задаёт индекс фонового цвета GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Получает или задаёт индекс фонового цвета GIF. |
| [hasTrailer()](#hasTrailer--) | Получает или задаёт значение, указывающее, имеет ли GIF трейлер. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Получает или задаёт значение, указывающее, имеет ли GIF трейлер. |
| [getInterlaced()](#getInterlaced--) | True, если изображение должно быть чередованным. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True, если изображение должно быть чередованным. |
| [getMaxDiff()](#getMaxDiff--) | Получает или задаёт максимальную допустимую разницу пикселей. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Получает или задаёт максимальную допустимую разницу пикселей. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает фоновый цвет. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Задаёт фоновый цвет. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, имеет ли GIF‑изображение прозрачный цвет. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Устанавливает значение, указывающее, имеет ли GIF‑изображение прозрачный цвет. |

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


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. Эти страницы будут представлены как анимированные кадры в результирующем GIF.
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

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Инициализирует новый экземпляр класса `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Инициализирует новый экземпляр класса `GifOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | Параметры GIF. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Получает или задаёт значение, указывающее, применяется ли коррекция палитры.

**Returns:**
boolean — `true`, если применяется коррекция палитры; иначе `false`.

Коррекция палитры означает, что каждый раз при экспорте изображения в GIF исходные цвета изображения будут анализироваться для построения наилучшей соответствующей палитры (в случае, если палитра изображения не существует или не указана в параметрах). Процесс анализа занимает некоторое время, однако результирующее изображение будет иметь наилучшую соответствующую цветовую палитру, и результат будет визуально лучше.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Получает или задаёт значение, указывающее, применяется ли коррекция палитры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | `true`, если применяется коррекция палитры; иначе `false`. |

Коррекция палитры означает, что каждый раз при экспорте изображения в GIF исходные цвета изображения будут анализироваться для построения наилучшей соответствующей палитры (в случае, если палитра изображения не существует или не указана в параметрах). Процесс анализа занимает некоторое время, однако результирующее изображение будет иметь наилучшую соответствующую цветовую палитру, и результат будет визуально лучше. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Количество бит, необходимых для хранения цвета, минус 1.
    saveOptions.setColorResolution((byte) 7);

    // Коррекция палитры означает, что каждый раз при экспорте изображения в GIF исходные цвета изображения будут анализироваться
    // для построения наилучшей соответствующей палитры (в случае, если палитра изображения не существует или не указана в параметрах)
    saveOptions.setDoPaletteCorrection(true);

    // Загрузите GIF‑изображение прогрессивным способом.
    // Интерлейсированный GIF не отображает свои сканирующие линии линейно сверху вниз, а переупорядочивает их
    // чтобы содержимое GIF становилось видимым даже до завершения загрузки.
    saveOptions.setInterlaced(true);

    // Сохранить как GIF без потерь.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Установите максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями.
    // Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 означает очень лёгкое сжатие, 200 — сильное.
    saveOptions.setMaxDiff(80);

    // Сохранить как GIF с потерями.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Вывод может выглядеть так:
//Размер GIF без потерь: 212816 байт.
//Размер GIF с потерями: 89726 байт.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Получает количество циклов (по умолчанию 1 цикл)

Значение: количество циклов.

**Returns:**
int — количество циклов (по умолчанию 1 цикл)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Задаёт количество циклов (по умолчанию 1 цикл)

Значение: количество циклов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | количество циклов (по умолчанию 1 цикл) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Получает или задаёт разрешение цвета GIF.

**Returns:**
byte — разрешение цвета.

Разрешение цвета — количество битов на основной цвет, доступных оригинальному изображению, минус 1. Это значение представляет размер всей палитры, из которой были выбраны цвета графики, а не количество фактически использованных цветов в графике. Например, если значение в этом поле равно 3, то у палитры оригинального изображения было 4 бита на основной цвет, доступных для создания изображения. Это значение следует установить, чтобы указать насыщенность оригинальной палитры, даже если не каждый цвет из полной палитры доступен на исходной машине.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Получает или задаёт разрешение цвета GIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | byte | Разрешение цвета. |

Разрешение цвета — количество битов на основной цвет, доступных оригинальному изображению, минус 1. Это значение представляет размер всей палитры, из которой были выбраны цвета графики, а не количество фактически использованных цветов в графике. Например, если значение в этом поле равно 3, то у палитры оригинального изображения было 4 бита на основной цвет, доступных для создания изображения. Это значение следует установить, чтобы указать насыщенность оригинальной палитры, даже если не каждый цвет из полной палитры доступен на исходной машине. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Количество бит, необходимых для хранения цвета, минус 1.
    saveOptions.setColorResolution((byte) 7);

    // Коррекция палитры означает, что каждый раз при экспорте изображения в GIF исходные цвета изображения будут анализироваться
    // для построения наилучшей соответствующей палитры (в случае, если палитра изображения не существует или не указана в параметрах)
    saveOptions.setDoPaletteCorrection(true);

    // Загрузите GIF‑изображение прогрессивным способом.
    // Интерлейсированный GIF не отображает свои сканирующие линии линейно сверху вниз, а переупорядочивает их
    // чтобы содержимое GIF становилось видимым даже до завершения загрузки.
    saveOptions.setInterlaced(true);

    // Сохранить как GIF без потерь.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Установите максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями.
    // Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 означает очень лёгкое сжатие, 200 — сильное.
    saveOptions.setMaxDiff(80);

    // Сохранить как GIF с потерями.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Вывод может выглядеть так:
//Размер GIF без потерь: 212816 байт.
//Размер GIF с потерями: 89726 байт.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Получает или задаёт значение, указывающее, отсортированы ли элементы палитры.

**Returns:**
boolean - `true` если элементы палитры отсортированы; иначе `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Получает или задаёт значение, указывающее, отсортированы ли элементы палитры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true` если элементы палитры отсортированы; иначе `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Получает или задаёт соотношение сторон пикселя GIF.

Отношение сторон пикселя - фактор, используемый для вычисления приближённого соотношения сторон пикселя в оригинальном изображении. Если значение поля не равно 0, это приближение соотношения сторон вычисляется по формуле: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Отношение сторон пикселя определяется как отношение ширины пикселя к его высоте. Диапазон значений в этом поле позволяет задавать самый широкий пиксель 4:1 до самого высокого пикселя 1:4 с шагом 1/64. Значения: 0 — информация о соотношении сторон не указана. 1..255 — значение, используемое в вычислении.

**Returns:**
byte - Соотношение сторон пикселя GIF.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Получает или задаёт соотношение сторон пикселя GIF.

Отношение сторон пикселя - фактор, используемый для вычисления приближённого соотношения сторон пикселя в оригинальном изображении. Если значение поля не равно 0, это приближение соотношения сторон вычисляется по формуле: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Отношение сторон пикселя определяется как отношение ширины пикселя к его высоте. Диапазон значений в этом поле позволяет задавать самый широкий пиксель 4:1 до самого высокого пикселя 1:4 с шагом 1/64. Значения: 0 — информация о соотношении сторон не указана. 1..255 — значение, используемое в вычислении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Соотношение сторон пикселя GIF. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Получает или задаёт индекс фонового цвета GIF.

**Returns:**
byte - Индекс фонового цвета GIF.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Получает или задаёт индекс фонового цвета GIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Индекс фонового цвета GIF. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Получает или задаёт значение, указывающее, имеет ли GIF трейлер.

**Returns:**
boolean - `true` если у GIF есть трейлер; иначе `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Получает или задаёт значение, указывающее, имеет ли GIF трейлер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true` если у GIF есть трейлер; иначе `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True, если изображение должно быть чередованным.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True, если изображение должно быть чередованным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Количество бит, необходимых для хранения цвета, минус 1.
    saveOptions.setColorResolution((byte) 7);

    // Коррекция палитры означает, что каждый раз при экспорте изображения в GIF исходные цвета изображения будут анализироваться
    // для построения наилучшей соответствующей палитры (в случае, если палитра изображения не существует или не указана в параметрах)
    saveOptions.setDoPaletteCorrection(true);

    // Загрузите GIF‑изображение прогрессивным способом.
    // Интерлейсированный GIF не отображает свои сканирующие линии линейно сверху вниз, а переупорядочивает их
    // чтобы содержимое GIF становилось видимым даже до завершения загрузки.
    saveOptions.setInterlaced(true);

    // Сохранить как GIF без потерь.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Установите максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями.
    // Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 означает очень лёгкое сжатие, 200 — сильное.
    saveOptions.setMaxDiff(80);

    // Сохранить как GIF с потерями.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Вывод может выглядеть так:
//Размер GIF без потерь: 212816 байт.
//Размер GIF с потерями: 89726 байт.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Получает или задает максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями. Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 — очень лёгкое сжатие, 200 — сильное. Оно работает лучше всего, когда вводится небольшая потеря, и из‑за ограничений алгоритма сжатия очень высокие уровни потери не дают значительного выигрыша. Диапазон допустимых значений: [0, 1000].

**Returns:**
int - Диапазон допустимых значений.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Получает или задает максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями. Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 — очень лёгкое сжатие, 200 — сильное. Оно работает лучше всего, когда вводится небольшая потеря, и из‑за ограничений алгоритма сжатия очень высокие уровни потери не дают значительного выигрыша. Диапазон допустимых значений: [0, 1000].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Диапазон допустимых значений. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Заполните всё изображение градиентом от синего к желтому.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Количество бит, необходимых для хранения цвета, минус 1.
    saveOptions.setColorResolution((byte) 7);

    // Коррекция палитры означает, что каждый раз при экспорте изображения в GIF исходные цвета изображения будут анализироваться
    // для построения наилучшей соответствующей палитры (в случае, если палитра изображения не существует или не указана в параметрах)
    saveOptions.setDoPaletteCorrection(true);

    // Загрузите GIF‑изображение прогрессивным способом.
    // Интерлейсированный GIF не отображает свои сканирующие линии линейно сверху вниз, а переупорядочивает их
    // чтобы содержимое GIF становилось видимым даже до завершения загрузки.
    saveOptions.setInterlaced(true);

    // Сохранить как GIF без потерь.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Установите максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями.
    // Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 означает очень лёгкое сжатие, 200 — сильное.
    saveOptions.setMaxDiff(80);

    // Сохранить как GIF с потерями.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Вывод может выглядеть так:
//Размер GIF без потерь: 212816 байт.
//Размер GIF с потерями: 89726 байт.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Получает фоновый цвет.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Задаёт фоновый цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | цвет фона. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Получает значение, указывающее, имеет ли GIF‑изображение прозрачный цвет. Если возвращаемое значение `null`, это свойство переопределяется контекстом исходного изображения.

**Returns:**
java.lang.Boolean - значение, указывающее, имеет ли GIF‑изображение прозрачный цвет.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Задаёт значение, указывающее, имеет ли GIF‑изображение прозрачный цвет. Если возвращаемое значение `null`, это свойство переопределяется контекстом исходного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Boolean | значение, указывающее, имеет ли GIF‑изображение прозрачный цвет. |

