---
title: "DicomImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Этот класс реализует поддержку растрового формата изображений DICOM (Digital Imaging and Communications in Medicine) и предлагает комплексное решение для обработки DICOM‑изображений с точностью и гибкостью."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Этот класс реализует поддержку растрового формата изображений Digital Imaging and Communications in Medicine (DICOM) и предлагает комплексное решение для обработки DICOM‑изображений с точностью и гибкостью. Вы можете бесшовно управлять страницами изображения, включая операции получения, добавления или удаления страниц, а также контролировать страницы по умолчанию и активные страницы. Имеются возможности работы с альфа‑каналами, внедрения метаданных XMP, изменения размеров, вращения, обрезки, бинаризации, коррекции, применения фильтров и конвертации в другие растровые форматы. Этот API позволяет разработчикам эффективно работать с DICOM‑изображениями, удовлетворяя разнообразные требования приложений в контексте медицинской визуализации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Легко инициализируйте новый экземпляр класса DicomImage с помощью этого конструктора, используя параметры dicomOptions. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Инициализируйте новый экземпляр класса DicomImage плавно, используя параметры stream и loadOptions в этом конструкторе. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Создайте новый экземпляр класса DicomImage, используя параметр stream в этом конструкторе. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPageCount()](#getPageCount--) | Получите общее количество страниц изображения с помощью этого интуитивного свойства. |
| [getPages()](#getPages--) | Получите доступ к страницам изображения с помощью этого интуитивного свойства. |
| [getFileInfo()](#getFileInfo--) | Получите ценную информацию заголовка из файла DICOM без усилий с помощью этого интуитивного свойства. |
| [getDicomPages()](#getDicomPages--) | Получите доступ к страницам изображения с помощью этого интуитивного свойства. |
| [getActivePage()](#getActivePage--) | Получите доступ к активной странице изображения с помощью этого интуитивного свойства. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Управляйте активной страницей изображения с помощью этого интуитивного свойства. |
| [getActivePageIndex()](#getActivePageIndex--) | Получите индекс активной страницы без усилий с помощью этого интуитивного свойства. |
| [getFileFormat()](#getFileFormat--) | Получите значение формата файла без усилий с помощью этого интуитивного свойства. |
| [hasAlpha()](#hasAlpha--) | Определите, имеет ли изображение альфа-канал, без усилий с помощью этого интуитивного свойства. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Расширьте свою коллекцию изображений, добавив новую страницу с помощью этого интуитивного метода. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Сохраните данные объекта, записав их в указанное место файла (индексатор + имя файла) вместе с заданным форматом файла и параметрами. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Отрегулируйте разрешение этого [RasterImage](../../com.aspose.imaging/rasterimage) с точностью, используя этот простой метод. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Измените размер изображения, сохраняя его пропорции, с помощью этого удобного метода. |
| [addPage()](#addPage--) | Добавьте новую страницу в конец списка страниц изображения с помощью этого простого метода. |
| [insertPage(int pageIndex)](#insertPage-int-) | Вставьте новую страницу в список страниц изображения по указанному индексу с помощью этого интуитивного метода. |
| [removePage(int pageIndex)](#removePage-int-) | Удалите страницу по указанному индексу из списка страниц с помощью этого удобного метода. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Поверните изображение вокруг его центра с помощью этого удобного метода. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Отрегулируйте размер изображения с помощью этого простого метода. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Отрегулируйте ширину изображения, сохраняя его пропорции, с помощью этого удобного метода. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Отрегулируйте высоту изображения, сохраняя его пропорции, с помощью этого удобного для пользователя метода. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Легко манипулируйте активным кадром, вращая, отражая или выполняя оба действия одновременно с помощью этого простого метода. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Улучшите текущее изображение, применяя эффекты дизеринга с помощью этого простого метода. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрежьте изображение, чтобы удалить нежелательные области и сосредоточиться на важном содержании, с помощью этого простого метода. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Отрегулируйте область обрезки изображения, применяя смещения, с помощью этого универсального метода. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Легко преобразуйте изображение в бинарный формат, используя предопределенный порог, с помощью этого простого метода. |
| [binarizeOtsu()](#binarizeOtsu--) | Примените пороговое преобразование Оцу для бинаризации изображения, автоматически определяя оптимальное значение порога на основе гистограммы изображения. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Бинаризуйте изображения с помощью адаптивного алгоритма пороговой обработки Брэдли, используя интегральную бинаризацию для повышения производительности. |
| [grayscale()](#grayscale--) | Легко преобразуйте изображения в их градации серого, упрощая задачи визуального анализа и обработки. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Повышайте качество изображения и корректируйте его с помощью гамма‑коррекции, мощной техники тонкой настройки визуального вида. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Добейтесь точной настройки цветов, применяя гамма‑коррекцию независимо к красному, зелёному и синему компонентам изображения. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Повышайте яркость изображения с помощью регулировки `brightness`, параметризованного метода, позволяющего разработчикам точно настраивать светимость изображений. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Улучшайте контраст [Image](../../com.aspose.imaging/image) с помощью этого удобного метода, который регулирует разницу между светлыми и тёмными областями. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Легко улучшайте отдельные области вашего изображения, применяя фильтры к заданным прямоугольникам. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяйте размер вашего изображения с помощью этого простого метода изменения размеров. |
| [cacheData()](#cacheData--) | Этот метод эффективно кэширует данные, оптимизируя производительность и обеспечивая быстрый доступ при необходимости. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Загрузить изображение
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Нарисуйте что‑нибудь с помощью векторной графики.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Сохраните пиксели нарисованного изображения. Они теперь находятся на первой странице изображения Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Добавьте несколько страниц после, сделав их темнее.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Добавьте несколько страниц перед основной страницей, сделав их ярче.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Сохраните созданное многостраничное изображение в выходной файл.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Инициализируйте новый экземпляр класса DicomImage без усилий с помощью этого конструктора, используя параметры dicomOptions. Идеально подходит для разработчиков, желающих быстро и эффективно работать с объектами [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) в своих проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Параметры dicom (пока игнорируются). |
| width | int | Ширина. |
| height | int | Высота. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Создайте новый экземпляр класса DicomImage плавно, используя поток и параметры loadOptions в этом конструкторе. Идеально подходит для разработчиков, желающих быстро и эффективно начать работу с объектами [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) в своих проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Создайте новый экземпляр класса DicomImage, используя параметр потока в этом конструкторе. Идеально подходит для разработчиков, ищущих упрощённый способ инициализировать объекты [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) из существующих потоков данных в своих проектах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получите общее количество страниц изображения с помощью этого интуитивного свойства. Идеально для разработчиков, которым нужен быстрый доступ к числу страниц в изображении, обеспечивая эффективную навигацию и управление.

**Returns:**
int — количество страниц.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получайте доступ к страницам изображения с помощью этого интуитивного свойства. Идеально для разработчиков, желающих взаимодействовать с отдельными страницами изображения, обеспечивая плавную навигацию и манипуляцию.

**Returns:**
com.aspose.imaging.Image[] — страницы.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Легко получайте ценную информацию заголовка из файла DICOM с помощью этого интуитивного свойства. Идеально для разработчиков, которым нужен быстрый доступ к важным деталям, содержащимся в файле DICOM, обеспечивая эффективное извлечение и анализ данных.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Получайте доступ к страницам изображения с помощью этого интуитивного свойства. Идеально для разработчиков, желающих взаимодействовать с отдельными страницами изображения, обеспечивая плавную навигацию и манипуляцию.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] — страницы.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Получайте доступ к активной странице изображения с помощью этого интуитивного свойства. Идеально для разработчиков, желающих динамически переключаться между страницами в многостраничных изображениях, обеспечивая эффективную навигацию и обработку.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Управляйте активной страницей изображения с помощью этого интуитивного свойства. Идеально для разработчиков, желающих динамически переключаться между страницами в многостраничных изображениях, обеспечивая эффективную навигацию и обработку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | активная страница. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Легко получайте индекс активной страницы с помощью этого интуитивного свойства. Идеально для разработчиков, которым нужен быстрый доступ к текущему индексу страницы в многостраничных изображениях, обеспечивая эффективную навигацию и обработку.

**Returns:**
int — индекс активной страницы.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Легко получайте значение формата файла с помощью этого интуитивного свойства. Идеально для разработчиков, которым нужен быстрый доступ к формату файлов изображения, обеспечивая эффективную обработку и работу в зависимости от типа файла.

**Returns:**
long - значение формата файла [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получите информацию о том, содержит ли изображение альфа‑канал, без усилий с помощью этого интуитивного свойства. Идеально для разработчиков, желающих определить, содержит ли изображение информацию о прозрачности, обеспечивая точную работу с данными альфа‑канала в задачах обработки изображений.

**Returns:**
boolean - true, если изображение имеет альфа‑канал.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Расширьте свою коллекцию изображений, добавив новую страницу с помощью этого интуитивного метода. Идеально для разработчиков, желающих динамически добавлять страницы к многостраничным изображениям, обеспечивая бесшовное расширение и организацию содержимого изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Страница для добавления. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Сохраните данные объекта, записав их в указанное место файла (индексатор + имя файла) вместе с заданным форматом файла и параметрами. Идеально для разработчиков, желающих безопасно хранить данные в различных форматах, сохраняя гибкость и контроль над параметрами сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Отрегулируйте разрешение этого [RasterImage](../../com.aspose.imaging/rasterimage) с точностью, используя этот простой метод. Идеально для разработчиков, желающих адаптировать разрешение изображения к конкретным требованиям, обеспечивая оптимальное качество отображения и управление размером файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение в точках на дюйм для [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Вертикальное разрешение в точках на дюйм для [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Измените размер изображения, сохраняя его пропорции, с помощью этого удобного метода. Идеально для разработчиков, желающих пропорционально изменять размеры изображения, обеспечивая согласованность и сохранение оригинальных пропорций содержимого. Пропорциональное изменение размера будет масштабировать каждый кадр согласно соотношению `newWidth`/width и `newHeight`/height.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Добавьте новую страницу в конец списка страниц изображения с помощью этого простого метода. Идеально для разработчиков, желающих динамически расширять многостраничные изображения, обеспечивая бесшовную интеграцию и организацию содержимого изображения.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Вставьте новую страницу в список страниц изображения в указанном индексе с помощью этого интуитивного метода. Идеально для разработчиков, желающих точно контролировать расположение страниц в многостраничных изображениях, обеспечивая бесшовную организацию и настройку содержимого изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Нарисуйте что‑нибудь с помощью векторной графики.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Сохраните пиксели нарисованного изображения. Они теперь находятся на первой странице изображения Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Добавьте несколько страниц после, сделав их темнее.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Добавьте несколько страниц перед основной страницей, сделав их ярче.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Сохраните созданное многостраничное изображение в выходной файл.
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Удалите страницу с указанным индексом из списка страниц с помощью этого удобного метода. Идеально для разработчиков, желающих точно контролировать управление многостраничными изображениями, обеспечивая бесшовную организацию и настройку содержимого изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | int | Индекс страницы. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Поверните изображение вокруг его центра с помощью этого удобного метода. Идеально для разработчиков, желающих динамически регулировать ориентацию изображения, обеспечивая оптимальное представление и выравнивание в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только `` содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Загрузите DICOM‑изображение из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Поверните изображение вокруг центра на 60 градусов по часовой стрелке.
        // Используйте серый цвет в качестве фона.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Обратите внимание, что если изображение цветное, оно будет автоматически преобразовано в формат градаций серого в соответствии с приведёнными ниже параметрами.
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // Создайте массив TIFF‑кадров.
        // Количество кадров равно количеству страниц DJVU.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Сохраните каждую страницу как отдельный TIFF‑кадр.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // Создайте TIFF‑кадр на основе DICOM‑страницы.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Сформируйте TIFF‑изображение из кадров.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // Сохранить в файл.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Отрегулируйте размер изображения с помощью этого простого метода. Идеально для разработчиков, желающих динамически изменять размер изображений, обеспечивая их бесшовную интеграцию в различные контексты и макеты в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Отрегулируйте ширину изображения, сохраняя его пропорции, с помощью этого удобного метода. Идеально для разработчиков, желающих пропорционально изменять размер изображений, обеспечивая согласованные и визуально привлекательные результаты в разных средах отображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
В этом примере загружается DICOM‑изображение и масштабируется пропорционально с использованием различных методов изменения размера. Указывается только ширина, высота вычисляется автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Отрегулируйте высоту изображения, сохраняя его соотношение сторон, с помощью этого удобного метода. Идеально подходит для разработчиков, желающих динамически изменять размер изображений, сохраняя их пропорции, обеспечивая оптимальное отображение и удобство использования в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
В этом примере загружается DICOM‑изображение и масштабируется пропорционально с использованием различных методов изменения размера. Указывается только высота, ширина вычисляется автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Легко манипулируйте активным кадром, вращая, отражая или выполняя оба действия одновременно с помощью этого простого метода. Идеально подходит для разработчиков, которым необходимо динамически корректировать ориентацию конкретных кадров в последовательностях изображений, обеспечивая оптимальное представление и выравнивание.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращающего отражения. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Поверните, отразите и сохраните в выходной файл.
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Улучшите текущее изображение, применив эффекты дизеринга с помощью этого простого метода. Идеально подходит для разработчиков, стремящихся добавить текстуру и глубину изображениям, улучшая их визуальное качество и общую привлекательность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Выполнить пороговое дизеринг с использованием 4-битовой цветовой палитры, содержащей 16 цветов.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Выполнить дизеринг Флойда с использованием 1-битовой цветовой палитры, содержащей только 2 цвета — черный и белый.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрежьте изображение, чтобы удалить нежелательные области и сосредоточиться на важном содержании, используя этот простой метод. Идеально подходит для разработчиков, желающих настроить визуальную композицию изображений, гарантируя эффективную передачу желаемого сообщения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |


**Example: The following example crops a DICOM image.**
В следующем примере изображение DICOM обрезается. Область обрезки указывается через Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Обрежьте изображение. Область обрезки — прямоугольный центральный участок изображения.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Сохраните обрезанное изображение в PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Отрегулируйте область обрезки изображения, применяя смещения с помощью этого универсального метода. Идеально подходит для разработчиков, которым нужен точный контроль над процессом обрезки, обеспечивая сохранение важных деталей при удалении ненужных элементов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Левый сдвиг. |
| rightShift | int | Правый сдвиг. |
| topShift | int | Верхний сдвиг. |
| bottomShift | int | Нижний сдвиг. |


**Example: The following example crops a DICOM image.**
В следующем примере изображение DICOM обрезается. Область обрезки задаётся через отступы Left, Top, Right, Bottom.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Обрезать снова. Установите отступ в размере 10 % от размера изображения.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Сохраните обрезанное изображение в PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Легко преобразуйте изображение в бинарный формат, используя предопределённый порог, с помощью этого простого метода. Идеально подходит для разработчиков, желающих упростить задачи обработки изображений, сегментируя их на передний план и фон на основе заданных уровней интенсивности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
В следующем примере DICOM‑изображение бинаризуется с предопределённым порогом. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Бинаризуйте изображение с пороговым значением 127.
    // Если соответствующее серое значение пикселя больше 127, ему будет присвоено значение 255, иначе 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Примените пороговое значение Оцу для бинаризации изображения, автоматически определяя оптимальное значение порога на основе гистограммы изображения. Идеально подходит для разработчиков, ищущих надёжный метод сегментации изображений на области переднего плана и фона с минимальным вмешательством.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
В следующем примере DICOM‑изображение бинаризуется с использованием порога Оцу. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Бинаризуйте изображение с пороговой обработкой Оцу.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Бинаризуйте изображения с помощью адаптивного порогового алгоритма Брэдли, используя интегральную пороговую обработку для повышения производительности. Идеально подходит для разработчиков, желающих автоматически сегментировать изображения на основе локальных вариаций яркости, обеспечивая точное обнаружение и извлечение объектов при разных условиях освещения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |
| windowSize | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя. |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
В следующем примере DICOM‑изображение бинаризуется с использованием адаптивного порогового алгоритма Брэдли и указанного размера окна. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Бинаризуйте изображение с разницей яркости 5. Яркость определяется как разница между пикселем и средним значением 10 × 10 окна пикселей, центрированного вокруг этого пикселя.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Легко преобразуйте изображения в их градации серого, упрощая визуальный анализ и задачи обработки. Идеально подходит для разработчиков, стремящихся улучшить чёткость изображений, снизить сложность и облегчить эффективные алгоритмы на основе градаций серого для различных приложений.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
В следующем примере цветное DICOM‑изображение преобразуется в градацию серого. Изображения в градациях серого состоят исключительно из оттенков серого и содержат только информацию об интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Повышайте качество изображения и регулируйте его с помощью гамма‑коррекции, мощной техники тонкой настройки визуального вида. Идеально подходит для разработчиков, стремящихся оптимизировать представление изображений, корректировать цветовой баланс и обеспечивать согласованную отрисовку на разных устройствах и в разных средах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Установите коэффициент гаммы для красного, зелёного и синего каналов.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Добейтесь точной настройки цветов, применяя гамма‑коррекцию независимо к красному, зелёному и синему компонентам изображения. Этот метод обеспечивает точный цветовой баланс и оптимальный визуальный результат, удовлетворяя потребности разработчиков, желающих детальный контроль над отрисовкой изображения и точностью цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Установите отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Повышайте яркость изображения, регулируя `brightness`, параметризованный метод, позволяющий разработчикам точно настраивать светимость изображений. Эта удобная функция даёт разработчикам возможность беспрепятственно управлять яркостью изображения, предоставляя гибкость и контроль над визуальной эстетикой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Установите значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Повышайте контраст [Image](../../com.aspose.imaging/image) с помощью этого удобного метода, который регулирует разницу между светлыми и тёмными областями. Улучшайте визуальную чёткость и определённость без усилий, предоставляя разработчикам интуитивный контроль над контрастом изображения для оптимальной отрисовки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Установите значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Легко улучшайте отдельные области вашего изображения, применяя фильтры к заданным прямоугольникам. Этот метод предоставляет разработчикам точный контроль над манипуляциями с изображением, позволяя целенаправленно настраивать их для достижения желаемых визуальных эффектов без труда.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Параметры. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Отрегулируйте размер вашего изображения с помощью этого простого метода изменения размера. Независимо от того, нужно ли вам уменьшить или увеличить изображение, эта функция гарантирует эффективное и точное выполнение ваших потребностей в изменении размера, делая её идеальной для разработчиков, ищущих быстрые и простые корректировки размеров изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Адаптивный алгоритм, основанный на взвешенной и смешанной рациональной функции и интерполяции lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Небольшой прямоугольный фильтр
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Количество цветов в палитре.
resizeSettings.setEntriesCount(256);

// Квантование цветов не используется
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Эвклидов метод
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Сохранить в PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Этот метод эффективно кэширует данные, оптимизируя производительность и обеспечивая быстрый доступ при необходимости. Идеально подходит для разработчиков, стремящихся повысить скорость и эффективность своих приложений за счёт интеллектуального управления ресурсами данных.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение из DICOM‑файла.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Этот вызов кэширует все страницы, чтобы не происходила дополнительная загрузка данных из базового потока данных.
    image.cacheData();

    // Или вы можете кэшировать страницы по отдельности.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

