---
title: "TiffImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Обрабатывайте растровые изображения формата Tagged Image File Format (TIFF) с помощью нашего API, предоставляющего полную поддержку различных разрешений и расширенных возможностей редактирования, таких как манипуляция данными EXIF и альфа‑каналы."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Обрабатывайте растровые изображения формата Tagged Image File Format (TIFF) с помощью нашего API, предлагающего полную поддержку различных разрешений и расширенных возможностей редактирования, таких как манипуляция данными EXIF и альфа‑каналы. Нормализуйте углы сканированных изображений, изменяйте размер, преобразуйте в градации серого и легко применяйте фильтры, гамма‑коррекции и настройки параметров изображения. Бесшовно работайте с многокадровыми TIFF‑файлами, создавайте графические пути, добавляйте фигуры и без усилий сохраняйте изображения в различные форматы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Инициализируйте новый объект класса [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), указывая параметр кадра. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Создайте новый экземпляр класса [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), передав список кадров в качестве параметра. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Получите значение формата файла, связанное с изображением. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Укажите, требуется ли предварительное умножение компонентов, обеспечивая эффективную обработку визуальных элементов. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Укажите, требуется ли предварительное умножение компонентов, обеспечивая эффективную обработку визуальных элементов. |
| [getByteOrder()](#getByteOrder--) | Переключайте порядок байтов в TIFF‑файлах без проблем, обеспечивая точный контроль над интерпретацией данных. |
| [setByteOrder(int value)](#setByteOrder-int-) | Переключайте порядок байтов в TIFF‑файлах без проблем, обеспечивая точный контроль над интерпретацией данных. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получите горизонтальное разрешение указанного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, облегчая точную настройку и возможности рендеринга. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Изменяет горизонтальное разрешение указанного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, облегчая точную настройку и возможности рендеринга. |
| [getVerticalResolution()](#getVerticalResolution--) | Получите вертикальное разрешение назначенного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, позволяя точные настройки и оптимизацию рендеринга. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Получите вертикальное разрешение назначенного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, позволяя точные настройки и оптимизацию рендеринга. |
| [getActiveFrame()](#getActiveFrame--) | Управляйте активным кадром без проблем, облегчая динамическую навигацию и манипуляцию в заданном контексте. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Управляйте активным кадром без проблем, облегчая динамическую навигацию и манипуляцию в заданном контексте. |
| [getFrames()](#getFrames--) | Получите массив экземпляров [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), обеспечивая всесторонний доступ и манипуляцию отдельными кадрами в TIFF‑изображении. |
| [getPageCount()](#getPageCount--) | Получите общее количество страниц в указанном документе, облегчая эффективную навигацию и управление многостраничным содержимым. |
| [getPages()](#getPages--) | Получайте страницы документа без проблем, позволяя динамическую навигацию и манипуляцию внутри структуры содержимого. |
| [hasAlpha()](#hasAlpha--) | Определите, содержит ли изображение альфа‑канал, предоставляя важную информацию для операций рендеринга и композитинга. |
| [removeMetadata()](#removeMetadata--) | Удаляет метаданные этого экземпляра изображения, устанавливая значение `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) в `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Получите параметры, полученные из настроек оригинального файла, обеспечивая бесшовное сохранение ключевых параметров, таких как глубина цвета и другие важные атрибуты исходного изображения. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Внедрите новую страницу в существующее изображение без проблем, расширяя его содержимое и универсальность. |
| [alignResolutions()](#alignResolutions--) | Реализуйте вспомогательный метод AlignResolutions для синхронизации горизонтального и вертикального разрешений, обеспечивая единообразие размеров изображения. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Устанавливает разрешение для указанного [RasterImage](../../com.aspose.imaging/rasterimage), обеспечивая точный контроль над рендерингом изображения и свойствами отображения. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Используйте метод NormalizeAngle, специально разработанный для сканированных текстовых документов, чтобы исправить наклонные сканы, обеспечивая точное выравнивание. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Бесшовно внедрите указанный кадр в изображение, расширяя его содержимое и универсальность. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Бесшовно добавьте кадры из указанного изображения в текущий кадр, консолидируя их содержимое и повышая гибкость композиции. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Бесшовно интегрируйте массив кадров в изображение, обогащая его содержимое и универсальность. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Вставьте новый кадр в указанную позицию в последовательность кадров, обеспечивая точный контроль над расположением кадров. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Бесшовно замените кадр в заданной позиции другим кадром, облегчая динамическое управление кадрами в последовательности изображений. |
| [removeFrame(int index)](#removeFrame-int-) | Легко удалите кадр, идентифицированный по индексу, из последовательности изображений, упрощая управление кадрами в вашем приложении. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Эффективно удалите указанный кадр из последовательности изображений, облегчая упрощённое управление кадрами в вашем приложении. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Выполните пропорциональное изменение размера изображения, сохраняя его соотношение сторон при корректировке размеров. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Отрегулируйте ширину изображения, сохраняя его соотношение сторон, обеспечивая пропорциональное изменение размера для оптимального визуального представления. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Выполните пропорциональную корректировку высоты изображения, сохраняя его соотношение сторон для поддержания визуальной целостности. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Выполните вращение, отражение или их комбинацию исключительно на активном кадре. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Выполните дизеринг текущего изображения, чтобы улучшить его визуальное качество и уменьшить артефакты цветовых полос. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрежьте изображение, используя указанную прямоугольную область, позволяя точно выбрать нужное содержимое. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Выполните обрезку изображения, указав смещения влево, вправо, вверх и вниз. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Примените бинаризацию к изображению, используя предопределённый порог, преобразуя его в бинарное изображение с чётко различимыми передним и задним планами. |
| [binarizeOtsu()](#binarizeOtsu--) | Используйте пороговое значение Оцу для выполнения бинаризации изображения, автоматически определяя оптимальное значение порога на основе гистограммы изображения. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Реализуйте бинаризацию изображения, используя адаптивный пороговый алгоритм Брэдли с интегральным порогом изображения. |
| [grayscale()](#grayscale--) | Преобразуйте изображение в его градацию серого, превратив его в одноканальное изображение, где каждый пиксель представляет интенсивность. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Примените гамма‑коррекцию к изображению, регулируя интенсивность пикселей для достижения желаемого цветового баланса. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Выполните гамма‑коррекцию изображения, используя отдельные коэффициенты для красного, зелёного и синего каналов, позволяя точно настроить цветовой баланс и контраст. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Реализуйте настройку `brightness` для изображения, позволяя изменять общий уровень яркости. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Повышайте контраст [Image](../../com.aspose.imaging/image) экземпляра, усиливая различия между светлыми и тёмными областями. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Отфильтруйте содержимое в указанном прямоугольнике, применяя заданный фильтр обработки изображения для улучшения или изменения выбранной области. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Настройте размер изображения согласно указанным параметрам, позволяя точно контролировать размеры, соотношение сторон и поведение масштабирования. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Создайте GraphicsPath, используя PathResources из TIFF‑изображения
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Нарисуйте красную линию и сохраните изображение
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Создайте прямоугольную Figure для GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Создайте GraphicsPath, используя нашу Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Установите PathResources, используя GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Сохраните изображение
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Инициализируйте новый объект класса [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), указывая параметр frame. Этот конструктор облегчает создание экземпляра TiffImage, позволяя разработчикам задавать кадр, который будет загружен или обработан, упрощая задачи работы с TIFF‑изображениями в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | TIFF‑кадр, с которым инициализировать изображение. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Создайте новый экземпляр класса [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), передавая список кадров в качестве параметра. Этот конструктор позволяет инициализировать объект TiffImage с несколькими кадрами, обеспечивая эффективную работу и обработку последовательностей TIFF‑изображений в программных приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Кадры. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите значение формата файла, связанное с изображением. Это свойство является важным элементом извлечения метаданных изображения, позволяя программным приложениям эффективно определять и интерпретировать формат данных изображения.

**Returns:**
long — значение формата файла
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Укажите, требуется ли премультипликация компонентов, обеспечивая эффективную работу с визуальными элементами. Улучшите процессы рендеринга, переключая это свойство, упрощая графические рабочие процессы для оптимальной производительности.

**Returns:**
boolean — `true`, если компоненты должны быть премультиплицированы; иначе `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Укажите, требуется ли премультипликация компонентов, обеспечивая эффективную работу с визуальными элементами. Улучшите процессы рендеринга, переключая это свойство, упрощая графические рабочие процессы для оптимальной производительности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если компоненты должны быть премультиплицированы; иначе `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Сохранить пиксели для всего изображения.
    image.savePixels(image.getBounds(), colors);

    // Пиксели хранятся в оригинальном изображении в непреумноженной форме.
    // Необходимо явно указать соответствующую опцию, чтобы получить преумноженные цветовые компоненты.
    // Преумноженные цветовые компоненты вычисляются по формулам:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//Вывод будет выглядеть так:
//Исходный цвет: Color [A=127, R=255, G=0, B=0]
//Премультиплицированный цвет: Color [A=127, R=127, G=0, B=0]
//Исходный цвет: Color [A=127, R=0, G=255, B=0]
//Премультиплицированный цвет: Color [A=127, R=0, G=127, B=0]
//Исходный цвет: Color [A=127, R=0, G=0, B=255]
//Премультиплицированный цвет: Color [A=127, R=0, G=0, B=127]
//Исходный цвет: Color [A=127, R=255, G=255, B=0]
//Премультиплицированный цвет: Color [A=127, R=127, G=127, B=0]
//Исходный цвет: Color [A=127, R=255, G=0, B=255]
//Предмультиплицированный цвет: Color [A=127, R=127, G=0, B=127]
//Исходный цвет: Color [A=127, R=0, G=255, B=255]
//Предмультиплицированный цвет: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Переключайте порядок байтов для файлов TIFF без усилий, обеспечивая точный контроль над интерпретацией данных. Дайте вашим приложениям гибкость адаптироваться к различным спецификациям файлов, повышая совместимость и эффективность обработки данных.

**Returns:**
int — порядок байтов TIFF.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Переключайте порядок байтов для файлов TIFF без усилий, обеспечивая точный контроль над интерпретацией данных. Дайте вашим приложениям гибкость адаптироваться к различным спецификациям файлов, повышая совместимость и эффективность обработки данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Порядок байтов TIFF. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получите горизонтальное разрешение указанного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, обеспечивая точную настройку и возможности рендеринга. Легко получайте важные метаданные изображения, упрощая рабочие процессы обработки изображений для улучшения пользовательского опыта.

**Returns:**
double - Горизонтальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Получите горизонтальное и вертикальное разрешение TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 96.0
// Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Изменяет горизонтальное разрешение указанного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, обеспечивая точную настройку и возможности рендеринга. Легко получайте важные метаданные изображения, упрощая рабочие процессы обработки изображений для улучшения пользовательского опыта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Горизонтальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Получите вертикальное разрешение назначенного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, позволяя точные настройки и оптимизацию рендеринга. Легко используйте важные данные изображения для упрощения процессов обработки, обеспечивая высшее качество и производительность в ваших приложениях.

**Returns:**
double - Вертикальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Получите горизонтальное и вертикальное разрешение TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 96.0
// Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Получите вертикальное разрешение назначенного [Image](../../com.aspose.imaging/image) в пикселях на дюйм, позволяя точные настройки и оптимизацию рендеринга. Легко используйте важные данные изображения для упрощения процессов обработки, обеспечивая высшее качество и производительность в ваших приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Вертикальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Управляйте активным кадром без усилий, облегчая динамическую навигацию и манипуляцию в заданном контексте. Позвольте вашему приложению эффективно взаимодействовать с мультимедийным контентом, повышая вовлечённость пользователей и продуктивность.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Это Font и Brush для рисования текста на отдельных кадрах.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Создать 5 кадров
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Создать PNG‑изображение и нарисовать на нём номер страницы.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Создать кадр на основе PNG‑изображения.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Добавить кадр к TIFF‑изображению.
        tiffImage.addFrame(frame);
    }

    // Изображение было создано с единственным кадром по умолчанию. Давайте удалим его.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Не забудьте освободить кадр, если вы не собираетесь добавлять его в другое TiffImage.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Управляйте активным кадром без усилий, облегчая динамическую навигацию и манипуляцию в заданном контексте. Позвольте вашему приложению эффективно взаимодействовать с мультимедийным контентом, повышая вовлечённость пользователей и продуктивность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Активный кадр. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Это Font и Brush для рисования текста на отдельных кадрах.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Создать 5 кадров
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Создать PNG‑изображение и нарисовать на нём номер страницы.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Создать кадр на основе PNG‑изображения.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Добавить кадр к TIFF‑изображению.
        tiffImage.addFrame(frame);
    }

    // Изображение было создано с единственным кадром по умолчанию. Давайте удалим его.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Не забудьте освободить кадр, если вы не собираетесь добавлять его в другое TiffImage.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Получите массив экземпляров [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), обеспечивая полный доступ и манипуляцию отдельными кадрами в изображении TIFF. Используйте возможности этого массива для упрощения рабочих процессов обработки изображений, обеспечивая точный контроль и оптимизацию визуального контента.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] — массив [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe).

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Это Font и Brush для рисования текста на отдельных кадрах.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Создать 5 кадров
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Создать PNG‑изображение и нарисовать на нём номер страницы.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Создать кадр на основе PNG‑изображения.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Добавить кадр к TIFF‑изображению.
        tiffImage.addFrame(frame);
    }

    // Изображение было создано с единственным кадром по умолчанию. Давайте удалим его.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Не забудьте освободить кадр, если вы не собираетесь добавлять его в другое TiffImage.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получите общее количество страниц в указанном документе, облегчая эффективную навигацию и управление многостраничным содержимым. Внедрите эту функцию для улучшения пользовательского опыта, обеспечивая бесшовный доступ к полной структуре документа.

**Returns:**
int — количество страниц.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получайте страницы документа без усилий, позволяя динамическую навигацию и манипуляцию внутри структуры контента. Обеспечьте приложению эффективный доступ к отдельным страницам, упрощая обработку документов и улучшая взаимодействие с пользователем.

**Returns:**
com.aspose.imaging.Image[] — страницы.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Определите, содержит ли изображение альфа-канал, предоставляя важную информацию для операций рендеринга и композитинга. Интегрируйте эту функцию для оптимизации визуальных процессов обработки, обеспечивая точное представление и манипуляцию прозрачными элементами.

**Returns:**
boolean — `true`, если присутствует альфа-канал.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Если активный кадр TIFF содержит альфа-канал, то всё изображение TIFF считается имеющим альфа-канал.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Удаляет метаданные этого экземпляра изображения, устанавливая значение `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) в `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получите параметры, полученные из настроек исходного файла, обеспечивая бесшовное сохранение ключевых параметров, таких как глубина цвета и другие важные атрибуты оригинального изображения. Используйте этот метод для поддержания точности и согласованности при обработке изображений, гарантируя оптимальные результаты без лишних изменений. Например, если мы загружаем черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), будет получено PNG‑изображение с 8‑битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их в метод [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Бесшовно добавьте новую страницу в существующее изображение, расширяя его содержимое и возможности. Используйте этот метод для улучшения составления и управления документами, обеспечивая эффективную работу с многостраничными изображениями в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Страница для добавления. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Реализуйте вспомогательный метод AlignResolutions для синхронизации горизонтального и вертикального разрешения, обеспечивая единообразие размеров изображения. Эта функция упрощает рабочие процессы обработки изображений, согласуя параметры разрешения и оптимизируя визуальное качество и согласованность на различных платформах и устройствах.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Устанавливает разрешение для указанного [RasterImage](../../com.aspose.imaging/rasterimage), позволяя точно управлять рендерингом и свойствами отображения изображения. Интегрируйте эту функцию для оптимизации визуального вывода и обеспечения совместимости с различными устройствами вывода и платформами, улучшая общий пользовательский опыт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение в точках на дюйм для [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Вертикальное разрешение в точках на дюйм для [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Получите горизонтальное и вертикальное разрешение TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 96.0
// Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Используйте метод NormalizeAngle, специально разработанный для сканированных текстовых документов, чтобы исправить наклонные сканы и обеспечить точное выравнивание. Бесшовно интегрируйте эту функцию в ваши рабочие процессы обработки текста, повышая читаемость и качество документов, улучшая общую эффективность распознавания и анализа текста. Этот метод использует методы [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) и [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeProportionally | boolean | Если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями вращённого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Бесшовно внедрите указанный кадр в изображение, расширяя его содержимое и возможности. Используйте этот метод для улучшения композиции и управления изображениями, обеспечивая эффективную работу с многокадровыми изображениями в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Кадр для добавления. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Это Font и Brush для рисования текста на отдельных кадрах.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Создать 5 кадров
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Создать PNG‑изображение и нарисовать на нём номер страницы.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Создать кадр на основе PNG‑изображения.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Добавить кадр к TIFF‑изображению.
        tiffImage.addFrame(frame);
    }

    // Изображение было создано с единственным кадром по умолчанию. Давайте удалим его.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Не забудьте освободить кадр, если вы не собираетесь добавлять его в другое TiffImage.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Бесшовно добавьте кадры из указанного изображения в текущий кадр, объединяя их содержимое и повышая гибкость композиции. Интегрируйте этот метод для упрощения управления и манипуляций кадрами в вашем приложении, облегчая эффективную работу с многокадровыми изображениями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | Исходное изображение. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Бесшовно интегрируйте массив кадров в изображение, обогащая его содержимое и возможности. Используйте этот метод для улучшения композиции и управления изображениями, позволяя эффективно работать с многокадровыми изображениями в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Массив кадров для добавления |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Вставьте новый кадр в указанную позицию индекса в последовательность кадров, обеспечивая точный контроль над расположением кадров. Используйте этот метод для эффективного управления последовательностями кадров, облегчая динамическую манипуляцию и организацию содержимого изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Кадр для вставки. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Бесшовно замените кадр в указанной позиции другим кадром, облегчая динамическое управление кадрами в последовательности изображений. Интегрируйте этот метод для повышения гибкости и точности манипуляций кадрами, обеспечивая оптимальную организацию и представление содержимого изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция кадра, начиная с нуля. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Кадр для замены. |

Примечание: не забудьте освободить/закрыть кадр, если вы не собираетесь добавлять его в другое TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Легко удалите кадр, определенный по индексу, из последовательности изображений, упрощая управление кадрами в вашем приложении. Интегрируйте эту функцию для повышения эффективности и точности манипуляций кадрами, обеспечивая бесшовную организацию и представление содержимого изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | index | int | Индекс кадра, подлежащего удалению. |

--------------------

Примечание: не забудьте вызвать Dispose для кадра, если вы не собираетесь добавлять его в другое TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Это Font и Brush для рисования текста на отдельных кадрах.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Создать 5 кадров
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Создать PNG‑изображение и нарисовать на нём номер страницы.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Создать кадр на основе PNG‑изображения.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Добавить кадр к TIFF‑изображению.
        tiffImage.addFrame(frame);
    }

    // Изображение было создано с единственным кадром по умолчанию. Давайте удалим его.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Не забудьте освободить кадр, если вы не собираетесь добавлять его в другое TiffImage.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Эффективно удалите указанный кадр из последовательности изображений, упрощая управление кадрами в вашем приложении. Интегрируйте эту функцию для повышения точности и гибкости манипуляций кадрами, обеспечивая бесшовную организацию и представление содержимого изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Кадр для удаления. |

--------------------

Примечание: не забудьте вызвать Dispose для кадра, если вы не собираетесь добавлять его в другое TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Выполните пропорциональное изменение размера изображения, сохраняя его соотношение сторон при корректировке размеров. Используйте этот метод для динамического масштабирования изображений в вашем приложении, обеспечивая согласованное визуальное представление целостности содержимого. Пропорциональное изменение размера будет масштабировать каждый кадр согласно соотношению `newWidth`/width и `newHeight`/height.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Отрегулируйте ширину изображения, сохраняя его соотношение сторон, обеспечивая пропорциональное изменение размера для оптимального визуального представления. Используйте этот метод для динамического масштабирования изображений в вашем приложении, способствуя согласованному и эстетически приятному рендерингу в различных контекстах отображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
В этом примере загружается TIFF‑изображение и пропорционально изменяется его размер с использованием различных методов масштабирования. Указана только ширина, высота рассчитывается автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
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


Выполните пропорциональную корректировку высоты изображения, сохраняя его соотношение сторон для поддержания визуальной целостности. Используйте этот метод для динамического изменения размеров изображений в вашем приложении, обеспечивая оптимальное отображение на различных платформах и устройствах без потери качества контента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
В этом примере загружается TIFF‑изображение и пропорционально изменяется его размер с использованием различных методов масштабирования. Указана только высота, ширина рассчитывается автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
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


Выполните вращение, отражение или их комбинацию исключительно для активного кадра. Этот метод позволяет точно управлять отдельными кадрами в последовательности изображений, повышая гибкость редактирования и композиции изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Это вспомогательный класс.
class Utils {
    // Получает строковое представление типа вращающего отражения.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Вот основной пример
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Поверните, отразите и сохраните в выходной файл.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Примените дизеринг к текущему изображению, чтобы улучшить его визуальное качество и уменьшить артефакты цветовых полос. Интегрируйте этот метод в ваш конвейер обработки изображений, чтобы обеспечить более плавные переходы между цветами, улучшая общую внешность и чёткость изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ditheringMethod | int | Метод дизеринга. |
| bitsCount | int | Окончательное количество бит для дизеринга. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Пользовательская палитра для дизеринга. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Выполнить пороговое дизеринг с использованием 4-битовой цветовой палитры, содержащей 16 цветов.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Выполнить дизеринг Флойда с использованием 1-битовой цветовой палитры, содержащей только 2 цвета — черный и белый.
    // Чем больше указано бит, тем выше качество и тем больше размер выходного изображения.
    // Обратите внимание, что в данный момент поддерживаются только 1-битовые, 4-битовые и 8-битовые палитры.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрежьте изображение, используя указанный прямоугольный регион, позволяя точно выбрать нужный контент. Интегрируйте этот метод в ваш конвейер обработки изображений для эффективного удаления нежелательных областей и фокусировки на важных деталях, улучшая общую чёткость и композицию изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |


**Example: The following example crops a TIFF image.**
В следующем примере изображение TIFF обрезается. Область обрезки указывается через Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Обрежьте изображение. Область обрезки — прямоугольный центральный участок изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Сохраните обрезанное изображение в PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Выполните обрезку изображения, указав сдвиги слева, справа, сверху и снизу. Этот метод обеспечивает точный выбор нужной части изображения, позволяя эффективно удалять нежелательные области и сосредотачиваться на важном содержимом. Интегрируйте эту функциональность в ваш конвейер обработки изображений для улучшения чёткости и композиции по мере необходимости в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Левый сдвиг. |
| rightShift | int | Правый сдвиг. |
| topShift | int | Верхний сдвиг. |
| bottomShift | int | Нижний сдвиг. |


**Example: The following example crops a TIFF image.**
В следующем примере изображение TIFF обрезается. Область обрезки задаётся через отступы Left, Top, Right, Bottom.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Обрезать снова. Установите отступ в размере 10 % от размера изображения.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Сохраните обрезанное изображение в PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Примените бинаризацию к изображению, используя предопределённый порог, преобразуя его в бинарное изображение с чётко различимыми областями переднего и заднего плана. Включите этот метод в ваш конвейер обработки изображений для облегчения задач сегментации и извлечения признаков, повышая точность и эффективность анализа изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | byte | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе — 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
В следующем примере TIFF‑изображение бинаризуется с предопределённым порогом. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Бинаризуйте изображение с пороговым значением 127.
    // Если соответствующее серое значение пикселя больше 127, ему будет присвоено значение 255, иначе 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Используйте пороговое значение Оцу для выполнения бинаризации изображения, автоматически определяя оптимальное значение порога на основе гистограммы изображения. Интегрируйте этот метод в ваш конвейер обработки изображений для эффективной сегментации и извлечения признаков, повышая точность и надёжность задач анализа изображений в вашем приложении.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
В следующем примере TIFF‑изображение бинаризуется с помощью пороговой обработки Оцу. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Бинаризуйте изображение с пороговой обработкой Оцу.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Реализуйте бинаризацию изображения, используя адаптивный пороговый алгоритм Брэдли с интегральным изображением. Этот подход динамически вычисляет локальные пороги на основе соседства пикселей, повышая адаптивность к различным условиям освещения и обеспечивая надёжную сегментацию для последующих задач обработки в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightnessDifference | double | Разница яркости между пикселем и средним значением окна s × s пикселей, центрированного вокруг этого пикселя. |
| windowSize | int | Размер окна s × s пикселей, центрированного вокруг этого пикселя. |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
В следующем примере TIFF‑изображение бинаризуется с помощью адаптивного порогового алгоритма Брэдли с указанным размером окна. Бинарные изображения содержат только 2 цвета — чёрный и белый.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Бинаризуйте изображение с разницей яркости 5. Яркость определяется как разница между пикселем и средним значением 10 × 10 окна пикселей, центрированного вокруг этого пикселя.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Преобразуйте изображение в его градацию серого, превратив его в одноканальное изображение, где каждый пиксель представляет интенсивность. Интегрируйте этот метод в ваш конвейер обработки изображений для упрощения анализа и повышения совместимости с алгоритмами, работающими с градациями серого, облегчая различные задачи компьютерного зрения и анализа изображений в вашем приложении.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
В следующем примере цветное TIFF‑изображение преобразуется в градацию серого. Градуированные изображения состоят исключительно из оттенков серого и содержат только информацию об интенсивности.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Примените гамма‑коррекцию к изображению, регулируя интенсивность пикселей для достижения желаемого цветового баланса. Включите этот метод в ваш конвейер обработки изображений, чтобы улучшить визуальное качество и повысить точность последующего анализа или отображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Установите коэффициент гаммы для красного, зелёного и синего каналов.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Выполните гамма‑коррекцию изображения, используя отдельные коэффициенты для красного, зелёного и синего каналов, позволяя точно настраивать цветовой баланс и контраст. Интегрируйте этот метод в ваш конвейер обработки изображений для точного контроля над цветопередачей и повышения визуальной достоверности в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gammaRed | float | Коэффициент гаммы для красного канала |
| gammaGreen | float | Коэффициент гаммы для зелёного канала |
| gammaBlue | float | Коэффициент гаммы для синего канала |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Установите отдельные коэффициенты гаммы для красного, зелёного и синего каналов.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Реализуйте регулировку `brightness` для изображения, позволяя изменять общий уровень яркости. Включите этот метод в ваш конвейер обработки изображений, чтобы улучшить видимость и повысить визуальное качество изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Установите значение яркости. Допустимые значения яркости находятся в диапазоне [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Повышайте контраст объекта [Image](../../com.aspose.imaging/image), усиливая различия между светлыми и тёмными областями. Интегрируйте эту функциональность для улучшения визуальной чёткости и общего качества изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| contrast | float | Значение контрастности (в диапазоне [-100; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Установите значение контрастности. Допустимые значения контрастности находятся в диапазоне [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Отфильтруйте содержимое в указанном прямоугольнике, применяя заданный фильтр обработки изображений для улучшения или изменения выбранного региона. Интегрируйте этот метод в ваш процесс манипуляции изображениями, чтобы достичь целевых улучшений или трансформаций в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Параметры. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Примените медианный фильтр с размером прямоугольника 5 ко всему изображению.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Примените билатеральный сглаживающий фильтр с размером ядра 5 ко всему изображению.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Примените гауссов фильтр размытия с радиусом 5 и значением sigma 4.0 ко всему изображению.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Примените фильтр Гаусса-Винера с радиусом 5 и значением smooth 4.0 ко всему изображению.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Примените фильтр движения Винера с длиной 5, значением smooth 4.0 и углом 90,0 градусов ко всему изображению.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Примените фильтр резкости с размером ядра 5 и значением sigma 4.0 ко всему изображению.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Отрегулируйте размер изображения на основе указанных настроек, позволяя точно контролировать размеры, соотношение сторон и поведение масштабирования. Интегрируйте этот метод в ваш рабочий процесс обработки изображений, чтобы выполнить индивидуальные операции изменения размера, адаптированные к конкретным требованиям вашего приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Сохранить в PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

