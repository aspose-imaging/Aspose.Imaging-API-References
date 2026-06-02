---
title: "Jpeg2000Options"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте файлы изображений JPEG2000 JP2 с помощью нашего API, используя передовую вейвлет-технологию для кодирования без потерь."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Создавайте файлы изображений JPEG2000 (JP2) с помощью нашего API, используя передовую вейвлет-технологию для кодирования без потерь. Получайте выгоду от поддержки различных кодеков, включая необратимое и без потерь сжатие, а также контейнеры метаданных XMP, обеспечивая универсальность и создание изображений высокого качества, адаптированных к вашим потребностям.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Инициализирует новый экземпляр класса `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Инициализирует новый экземпляр класса `Jpeg2000Options`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getComments()](#getComments--) | Получает или задает маркеры комментариев Jpeg. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Получает или задает маркеры комментариев Jpeg. |
| [getCodec()](#getCodec--) | Получает или задает кодек JPEG2000 |
| [setCodec(int value)](#setCodec-int-) | Получает или задает кодек JPEG2000 |
| [getCompressionRatios()](#getCompressionRatios--) | Получает или задает массив коэффициентов сжатия. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Получает или задает массив коэффициентов сжатия. |
| [getIrreversible()](#getIrreversible--) | Получает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 сжатие (по умолчанию). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 сжатие (по умолчанию). |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. На самом деле будет растеризована только одна страница, поскольку JPEG 2000 не является многостраничным форматом.
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

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Инициализирует новый экземпляр класса `Jpeg2000Options`.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Инициализирует новый экземпляр класса `Jpeg2000Options`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Параметры формата файла Jpeg2000, из которых копировать настройки. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Получает или задает маркеры комментариев Jpeg.

**Returns:**
java.lang.String[] — маркеры комментариев Jpeg.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Получает или задает маркеры комментариев Jpeg.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] | Маркеры комментариев Jpeg. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Получает или задает кодек JPEG2000

**Returns:**
int — кодек JPEG2000
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Получает или задает кодек JPEG2000

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Кодек JPEG2000 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните всё изображение красным цветом.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Использовать необратимое дискретное вейвлет-преобразование 9-7
    saveOptions.setIrreversible(true);

    // JP2 — это формат "контейнер" для кодовых потоков JPEG 2000.
    // J2K — это необработанные сжатые данные без оболочки.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Сохранить в файл
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Получает или задает массив коэффициентов сжатия. Различные коэффициенты сжатия для последовательных слоёв. Указанный коэффициент для каждого уровня качества является желаемым фактором сжатия. Требуются уменьшающиеся коэффициенты.

**Returns:**
int[] — коэффициенты сжатия.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Получает или задает массив коэффициентов сжатия. Различные коэффициенты сжатия для последовательных слоёв. Указанный коэффициент для каждого уровня качества является желаемым фактором сжатия. Требуются уменьшающиеся коэффициенты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Коэффициенты сжатия. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Получает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 сжатие (по умолчанию).

**Returns:**
boolean — значение, указывающее, используете ли вы необратимый DWT 9-7 (true) или без потерь DWT 5-3 сжатие
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 сжатие (по умолчанию).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, используете ли вы необратимый DWT 9-7 (true) или без потерь DWT 5-3 сжатие |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Создайте PNG‑изображение размером 100×100 пикселей.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Заполните всё изображение красным цветом.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Использовать необратимое дискретное вейвлет-преобразование 9-7
    saveOptions.setIrreversible(true);

    // JP2 — это формат "контейнер" для кодовых потоков JPEG 2000.
    // J2K — это необработанные сжатые данные без оболочки.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Сохранить в файл
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

