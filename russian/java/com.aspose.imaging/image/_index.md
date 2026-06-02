---
title: "Image"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Изображение является базовым классом для всех типов изображений."
type: docs
weight: 56
url: /ru/java/com.aspose.imaging/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.imaging.IObjectWithBounds](../../com.aspose.imaging/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler, [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler, IMetadataContainer
```

Изображение является базовым классом для всех типов изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-) | Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Определяет, можно ли загрузить изображение из указанного потока. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные `loadOptions`. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.ImageOptionsBase-int-int-) | Создаёт новое изображение, используя указанные параметры создания. |
| [create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)](#create-com.aspose.imaging.ImageOptionsBase-int-int-int---) | Создаёт экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) из предоставленного массива пикселей. |
| [create(Image[] images)](#create-com.aspose.imaging.Image---) | Создаёт новое изображение, используя указанные изображения в качестве страниц |
| [create(MultipageCreateOptions multipageCreateOptions)](#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-) | Создаёт указанные параметры создания многостраничного изображения. |
| [create(String[] files, boolean throwExceptionOnLoadError)](#create-java.lang.String---boolean-) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(String[] files)](#create-java.lang.String---) | Создаёт многостраничное изображение, содержащее указанные файлы. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.imaging.Image---boolean-) | Создаёт новое изображение, используя указанные изображения в качестве страниц. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Получает формат файла. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.imaging.LoadOptions-) | Загружает новое изображение из указанного пути к файлу или URL. |
| [load(String filePath)](#load-java.lang.String-) | Загружает новое изображение из указанного пути к файлу или URL. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Загружает новое изображение из указанного потока. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Загружает новое изображение из указанного потока. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загружает новое изображение из указанного потока. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Получает формат файла. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-) | Получает прямоугольник, который вписывается в текущее изображение. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-) | Получает прямоугольник, который вписывается в текущее изображение. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Получает пропорциональную ширину. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Получает пропорциональную высоту. |
| [removeMetadata()](#removeMetadata--) | Удаляет метаданные. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Пытается установить экземпляр `metadata`, если этот объект [Image](../../com.aspose.imaging/image) поддерживает и реализует тип [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getBounds()](#getBounds--) | Получает границы изображения. |
| [getContainer()](#getContainer--) | Получает контейнер `Image`. |
| [getPalette()](#getPalette--) | Получает цветовую палитру. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Устанавливает цветовую палитру. |
| [isUsePalette()](#isUsePalette--) | Получает значение, указывающее, используется ли палитра изображения. |
| [getSize()](#getSize--) | Получает размер изображения. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Получает монитор прерываний. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-) | Устанавливает монитор прерываний. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | Получает значение, указывающее, включена ли автоматическая настройка палитры. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Устанавливает значение, указывающее, включена ли автоматическая настройка палитры. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Получает значение, указывающее, имеет ли изображение фоновой цвет. |
| [getFileFormat()](#getFileFormat--) | Легко получить значение формата файла с помощью этого удобного свойства. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает значение фонового цвета. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Получает или задает значение, указывающее, имеет ли изображение фоновой цвет. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Получает или задает значение фонового цвета. |
| [getMetadata()](#getMetadata--) | Получает метаданные изображения. |
| [getExifData()](#getExifData--) | Получает данные Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Устанавливает данные Exif. |
| [getXmpData()](#getXmpData--) | Получает данные Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Устанавливает данные Xmp. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Получает информацию обработчика события прогресса. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Получает информацию обработчика события прогресса. |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.imaging.ImageOptionsBase-) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Изменяет размер изображения. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер изображения. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает параметры, основанные на настройках оригинального файла. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Изменяет ширину пропорционально. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Изменяет высоту пропорционально. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Изменяет ширину пропорционально. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Изменяет высоту пропорционально. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет ширину пропорционально. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет высоту пропорционально. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [rotate(float angle)](#rotate-float-) | Поворачивает изображение вокруг центра. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает указанный прямоугольник. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрезает изображение со сдвигами. |
| [save()](#save--) | Сохраняет данные изображения в базовый поток. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет изображение в указанное расположение файла. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Устанавливает палитру изображения. |
| [getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)](#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---) | Преобразует в aps. |

## Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.
В этом примере создаётся новый файл Image в некотором расположении на диске, указанном свойством Source экземпляра BmpOptions. Перед созданием фактического изображения устанавливаются несколько свойств экземпляра BmpOptions. Особенно свойство Source, которое в данном случае указывает на реальное расположение на диске.
``` java
// Создайте экземпляр BmpOptions и задайте его различные свойства
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
// Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Создайте экземпляр Image и инициализируйте его экземпляром BmpOptions, вызвав метод Create
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Выполните некоторую обработку изображения

    // Сохраните все изменения
    image.save();
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


## Example: Determine if the palette is used by the image.

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Определяет, можно ли загрузить изображение из указанного пути к файлу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |

**Returns:**
логический - `true`, если изображение может быть загружено из указанного файла; иначе `false`.

**Example: This example determines whether image can be loaded from a file.**

``` java

// Используйте абсолютный путь к файлу
boolean canLoad = com.aspose.imaging.Image.canLoad("c:\\temp\\sample.gif");
```

### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Определяет, можно ли загрузить изображение из указанного пути к файлу и, при желании, используя указанные параметры открытия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

**Returns:**
логический - `true`, если изображение может быть загружено из указанного файла; иначе `false`.
### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Определяет, можно ли загрузить изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружать. |

**Returns:**
логический - `true`, если изображение может быть загружено из указанного потока; иначе `false`.

**Example: This example determines whether image can be loaded from a file stream.**

``` java
String dir = "c:\\temp\\";

boolean canLoad;

// Используйте файловый поток
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
try {
    canLoad = com.aspose.imaging.Image.canLoad(stream);
} finally {
    stream.close();
}

// Следующие данные не являются действительным потоком изображения, поэтому CanLoad возвращает false.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    canLoad = com.aspose.imaging.Image.canLoad(stream);
}
```

### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Определяет, можно ли загрузить изображение из указанного потока и, при желании, используя указанные `loadOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружать. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

**Returns:**
логический - `true`, если изображение может быть загружено из указанного потока; иначе `false`.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Создаёт новое изображение, используя указанные параметры создания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры изображения. |
| width | int | Ширина. |
| height | int | Высота. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The newly created image.

**Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.**
В этом примере создаётся новый файл Image в некотором расположении на диске, указанном свойством Source экземпляра BmpOptions. Перед созданием фактического изображения устанавливаются несколько свойств экземпляра BmpOptions. Особенно свойство Source, которое в данном случае указывает на реальное расположение на диске.
``` java
// Создайте экземпляр BmpOptions и задайте его различные свойства
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
// Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Создайте экземпляр Image и инициализируйте его экземпляром BmpOptions, вызвав метод Create
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Выполните некоторую обработку изображения

    // Сохраните все изменения
    image.save();
} finally {
    image.dispose();
}
```

### create(ImageOptionsBase imageOptions, int width, int height, int[] pixels) {#create-com.aspose.imaging.ImageOptionsBase-int-int-int---}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```


Создаёт экземпляр [RasterImage](../../com.aspose.imaging/rasterimage) из предоставленного массива пикселей. Проверяет, что указанные ширина и высота соответствуют размерам данных пикселей. Этот метод может использоваться только когда библиотека находится в лицензированном режиме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры, используемые для создания [RasterImage](../../com.aspose.imaging/rasterimage). |
| width | int | Ширина [RasterImage](../../com.aspose.imaging/rasterimage). |
| height | int | Высота [RasterImage](../../com.aspose.imaging/rasterimage). |
| пиксели | int[] | Массив значений пикселей, используемый для заполнения изображения. |

**Returns:**
[Image](../../com.aspose.imaging/image) - A [RasterImage](../../com.aspose.imaging/rasterimage) populated with the provided pixel data.
### create(Image[] images) {#create-com.aspose.imaging.Image---}
```
public static Image create(Image[] images)
```


Создаёт новое изображение, используя указанные изображения в качестве страниц

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Изображения. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### create(MultipageCreateOptions multipageCreateOptions) {#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-}
```
public static Image create(MultipageCreateOptions multipageCreateOptions)
```


Создаёт указанные параметры создания многостраничного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| multipageCreateOptions | [MultipageCreateOptions](../../com.aspose.imaging.imageoptions/multipagecreateoptions) | Параметры создания многостраничного изображения. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files, boolean throwExceptionOnLoadError) {#create-java.lang.String---boolean-}
```
public static Image create(String[] files, boolean throwExceptionOnLoadError)
```


Создаёт многостраничное изображение, содержащее указанные файлы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файлы | java.lang.String[] | Файлы. |
| throwExceptionOnLoadError | boolean | если установлено `true` [выбрасывать исключение при ошибке загрузки]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files) {#create-java.lang.String---}
```
public static Image create(String[] files)
```


Создаёт многостраничное изображение, содержащее указанные файлы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файлы | java.lang.String[] | Файлы. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(Image[] images, boolean disposeImages) {#create-com.aspose.imaging.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Создаёт новое изображение, используя указанные изображения в качестве страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Изображения. |
| disposeImages | boolean | если установлено `true` [освобождать изображения]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Получает формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Путь к файлу. |

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли файл быть загружен. |

**Returns:**
long - Определённый формат файла.

**Example: This example shows how to determine the image format without loading the entire image from a file.**

``` java
String dir = "c:\\temp\\";

// Используйте абсолютный путь к файлу
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Строковое представление формата файла.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Загружает новое изображение из указанного пути к файлу или URL. Если `filePath` является путём к файлу, метод просто открывает файл. Если `filePath` является URL, метод загружает файл, сохраняет его как временный и открывает.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу или URL для загрузки изображения. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Загружает новое изображение из указанного пути к файлу или URL. Если `filePath` является путём к файлу, метод просто открывает файл. Если `filePath` является URL, метод загружает файл, сохраняет его как временный и открывает.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу или URL для загрузки изображения. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the loading of an existing Image file into an instance of com.**
Этот пример демонстрирует загрузку существующего файла Image в экземпляр com.aspose.imaging.Image с использованием указанного пути к файлу.
``` java
// Создайте экземпляр Image и инициализируйте его существующим файлом изображения, расположенным на диске.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Выполните некоторую обработку изображения.
} finally {
    image.dispose();
}
```

### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл для загрузки изображения. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл для загрузки изображения. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Загружает новое изображение из указанного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the use of InputStream object to load an existing Image file**

``` java
// Создайте экземпляр FileInputStream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.bmp");
try {
    // Создайте экземпляр класса Image и загрузите существующий файл через объект FileStream, вызвав метод Load
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(stream);
    try {
        // Выполните некоторую обработку изображения.
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Получает формат файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток. |

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли быть загружен поток. |

**Returns:**
long - Определённый формат файла.

**Example: This example shows how to determine the image format without loading the entire image from a file stream.**

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

String dir = "c:\\temp\\";

// Используйте файловый поток
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Следующие данные не являются действительным потоком изображения, поэтому GetFileFormat возвращает FileFormat.Undefined.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Вывод может выглядеть так:
// Формат файла — BMP
// Формат файла — UNDEFINED
```

### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Получает прямоугольник, который вписывается в текущее изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, для получения подходящего прямоугольника. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Получает прямоугольник, который вписывается в текущее изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник, для получения подходящего прямоугольника. |
| пиксели | int[] | 32-битные пиксели ARGB. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Получает пропорциональную ширину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |
| newHeight | int | Новая высота. |

**Returns:**
int — Пропорциональная ширина.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Получает пропорциональную высоту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |
| newWidth | int | Новая ширина. |

**Returns:**
int — Пропорциональная высота.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Удаляет метаданные.

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Пытается установить экземпляр `metadata`, если этот объект [Image](../../com.aspose.imaging/image) поддерживает и реализует тип [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Метаданные. |

**Returns:**
boolean - True, если экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует тип [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); иначе false.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int — Количество бит на пиксель изображения.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает границы изображения.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The image bounds.
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Получает контейнер `Image`.

Значение: контейнер `Image`.

Если это свойство не равно null, это указывает, что изображение содержится внутри другого изображения.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Устанавливает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |

### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Получает значение, указывающее, используется ли палитра изображения.

Значение: `true`, если палитра используется в изображении; иначе `false`.

**Returns:**
boolean — значение, указывающее, используется ли палитра изображения.

**Example: Determine if the palette is used by the image.**

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### getSize() {#getSize--}
```
public Size getSize()
```


Получает размер изображения.

**Returns:**
[Size](../../com.aspose.imaging/size) - The image size.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Загрузите изображение DJVU из файлового потока.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Вывод может выглядеть так:
//Общее количество страниц: 2
//Номер активной страницы:    1
//Номер первой страницы:     1
//Номер последней страницы:      2
//--------------------------------------------------
//Номер страницы:     1
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
//--------------------------------------------------
//Номер страницы:     2
//Размер страницы:       { Width = 2481, Height = 3508}
//Исходный формат страницы: RgbIndexed1Bpp, использовано каналов: 1
```

### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Получает монитор прерываний.

**Returns:**
[InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) - the interrupt monitor.
### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Устанавливает монитор прерываний.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) | монитор прерываний. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: Подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int — подсказка размера буфера, определяющая максимальный допустимый размер для всех внутренних буферов.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: Подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | подсказка размера буфера, определяющая максимальный допустимый размер для всех внутренних буферов. |

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


Получает значение, указывающее, включена ли автоматическая настройка палитры.

**Returns:**
boolean — `true`, если включена автоматическая настройка палитры; иначе `false`.
### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Устанавливает значение, указывающее, включена ли автоматическая настройка палитры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если включена автоматическая настройка палитры; иначе `false`. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Получает значение, указывающее, имеет ли изображение фоновой цвет.

**Returns:**
boolean
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Легко получить значение формата файла с помощью этого удобного свойства. Идеально для разработчиков, которым нужен быстрый доступ к информации о формате файла.

**Returns:**
long
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает или задает значение фонового цвета.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Получает или задает значение, указывающее, имеет ли изображение фоновой цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Получает или задает значение фонового цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Получает метаданные изображения.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Получает данные Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Устанавливает данные Exif.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | данные Exif. |

### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Получает данные Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public final void setXmpData(XmpPacketWrapper value)
```


Устанавливает данные Xmp.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | данные Xmp. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public final ProgressEventHandler getIProgressEventHandler()
```


Получает информацию обработчика события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Получает информацию обработчика события прогресса.

Значение: Информация обработчика события прогресса.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### canSave(ImageOptionsBase options) {#canSave-com.aspose.imaging.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры сохранения для использования. |

**Returns:**
boolean — `true`, если изображение может быть сохранено в указанный формат файла, представленный переданными параметрами сохранения; иначе `false`.

**Example: This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    saveOptions.setQuality(50);

    // Определить, может ли изображение быть сохранено в JPEG
    boolean canSave = image.canSave(saveOptions);
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Изменяет размер изображения. По умолчанию используется [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |


**Example: The following example shows how to resize a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";

String[] files = new String[]{"image3.emf", "image4.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Resize_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resize(image.getWidth() / 4, image.getHeight() / 4);
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```


**Example: The following example shows how to resize SVG image and save it to PNG.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1431\\";
String[] fileNames = new String[] {
                "Logotype.svg",
                "sample_car.svg",
                "rg1024_green_grapes.svg",
                "MidMarkerFigure.svg",
                "embeddedFonts.svg"
        };

com.aspose.imaging.PointF[] scales = new com.aspose.imaging.PointF[] {
                new com.aspose.imaging.PointF(0.5f, 0.5f),
                new com.aspose.imaging.PointF(1f, 1f),
                new com.aspose.imaging.PointF(2f, 2f),
                new com.aspose.imaging.PointF(3.5f, 9.2f),
        };

for (String inputFile : fileNames) {
    for (com.aspose.imaging.PointF scale : scales) {
        String outputFile = String.format("%s_%2.2f_%2.2f.png", inputFile, scale.getX(), scale.getY());
        com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + inputFile);
        try {
            image.resize((int) (image.getWidth() * scale.getX()), (int) (image.getHeight() * scale.getY()));
            image.save(dir + outputFile, new com.aspose.imaging.imageoptions.PngOptions());
        }
        finally {
            image.close();
        }
    }
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |


**Example: This example loads an image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
}
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
}
```


**Example: This example loads a multi-page ODG image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Сохранить в PNG с параметрами по умолчанию.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Параметры экспорта маскирования
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Использовать кластеризацию GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Фоновый цвет будет прозрачным.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Уменьшение размера изображения для ускорения процесса сегментации
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Разделите исходное изображение на несколько кластеров (сегментов).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Получение маски переднего плана
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Увеличьте размер маски до размера оригинального изображения
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Применение маски к оригинальному изображению для получения сегмента переднего плана
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image and export it to PNG format.**

``` java
// Загрузить EPS‑изображение
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Изменить размер изображения с использованием метода кубической интерполяции Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // Экспортировать изображение в формат PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменяет размер изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |


**Example: This example loads an image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing settings.**

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
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Уменьшить в 2 раза с помощью адаптивного пересэмплинга.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image using advanced settings.**

``` java
// Загрузить EPS‑изображение
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Установить режим интерполяции
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Установить тип фильтра
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Устанавливает метод сравнения цветов
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Установить метод квантования цветов
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Изменить размер изображения с использованием расширенных настроек масштабирования
    image.resize(400, 400, resizeSettings);

    // Экспортировать изображение в формат PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Получает параметры по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загрузим черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его, используя метод `DataStreamSupporter.Save(string)`, будет получено PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу `Image.Save(string, ImageOptionsBase)` в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Изменяет ширину пропорционально. По умолчанию используется [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Изменяет высоту пропорционально. По умолчанию используется [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
В этом примере загружается изображение и пропорционально изменяется с использованием различных методов масштабирования. Указывается только ширина, высота рассчитывается автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
{
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Изменяет высоту пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| resizeType | int | Тип масштабирования. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
В этом примере загружается изображение и пропорционально изменяется с использованием различных методов масштабирования. Указывается только высота, ширина рассчитывается автоматически.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием ресэмплинга ближайшего соседа.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Увеличить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Уменьшить в 2 раза с использованием билинейного ресэмплинга.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Параметры экспорта маскирования
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Использовать кластеризацию GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Фоновый цвет будет прозрачным.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Уменьшение размера изображения для ускорения процесса сегментации
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Разделите исходное изображение на несколько кластеров (сегментов).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Получение маски переднего плана
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Увеличьте размер маски до размера оригинального изображения
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Применение маски к оригинальному изображению для получения сегмента переднего плана
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Изменяет ширину пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки масштабирования изображения. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Изменяет высоту пропорционально.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки масштабирования изображения. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения/отражения. |


**Example: This example demonstrates the use of Rotate operation on an image.**
В этом примере демонстрируется использование операции Rotate над изображением. Пример загружает существующий файл изображения из некоторого места на диске и выполняет операцию Rotate над изображением в соответствии со значением перечисления com.aspose.imaging.RotateFlipType
``` java
// Создайте экземпляр класса image и инициализируйте его существующим файлом изображения через путь к файлу
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Поверните изображение на 180 градусов вокруг оси X
    image.rotateFlip(com.aspose.imaging.RotateFlipType.Rotate180FlipX);

    // Сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Поворачивает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезает указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |


**Example: The following example crops a raster image.**
В следующем примере происходит обрезка растрового изображения. Область обрезки указывается через com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Обрежьте изображение. Область обрезки — прямоугольный центральный участок изображения.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    image.crop(area);

    // Сохраните обрезанное изображение в PNG
    image.save(dir + "sample.Crop.png");
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Обрезает изображение со сдвигами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Левый сдвиг. |
| rightShift | int | Правый сдвиг. |
| topShift | int | Верхний сдвиг. |
| bottomShift | int | Нижний сдвиг. |


**Example: The following example crops a raster image.**
В следующем примере происходит обрезка растрового изображения. Область обрезки задаётся через отступы Left, Top, Right, Bottom.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Обрезать снова. Установите отступ в размере 10 % от размера изображения.
    int horizontalMargin = rasterImage.getWidth() / 10;
    int verticalMargin = rasterImage.getHeight() / 10;
    image.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Сохраните обрезанное изображение в PNG.
    image.save(dir + "sample.Crop.png");
}
```

### save() {#save--}
```
public final void save()
```


Сохраняет данные изображения в базовый поток.


**Example: The following example shows how to save an entire BMP image or part of it to a file or stream.**

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Преобразовать в черно-белое изображение
    bmpImage.binarizeOtsu();

    // Сохранить в то же место с параметрами по умолчанию.
    image.save();

    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Палитра содержит только два цвета: чёрный и белый в данном случае.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.createMonochrome());

    // Для всех монохромных изображений (включая черно-белые) достаточно выделять 1 бит на пиксель.
    saveOptions.setBitsPerPixel(1);

    // Сохранить в другое место с указанными параметрами.
    image.save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Сохранить только центральную часть изображения.
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(image.getWidth() / 4, image.getHeight() / 4, image.getWidth() / 2, image.getHeight() / 2);
    image.save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Сохранить всё изображение в поток памяти
    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions);
        System.out.println("The size of the whole image in bytes: " + stream.size());
    } finally {
        stream.close();
    }

    // Сохранить центральную часть изображения в поток памяти
    stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions, bounds);
        System.out.println("The size of the central part of the image in bytes: " + stream.size());
    } finally {
        stream.close();
    }
} finally {
    image.close();
}

//Вывод может выглядеть так:
//Размер полного изображения в байтах: 1662
//Размер центральной части изображения в байтах: 462
```

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет изображение в указанное расположение файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для сохранения изображения. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры. |


**Example: This example shows the simple steps to Save an Image.**
В этом примере показаны простые шаги по сохранению изображения. Чтобы продемонстрировать эту операцию, мы загружаем существующий файл из некоторого места на диске и сохраняем изображение в формате PSD.
``` java
// Загрузить существующий файл с диска.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Сохранить изображение в формате PSD по пути к файлу с настройками PsdOptions по умолчанию
    image.save("C:\\temp\\output.psd", new com.aspose.imaging.imageoptions.PsdOptions());
} finally {
    image.dispose();
}
```

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |


**Example: The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Сохранить верхнюю половину изображения в файл PNG.
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    image.save(dir + "output.png", saveOptions, bounds);
} finally {
    image.dispose();
}
```

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл, в который сохраняются данные изображения. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Файл, в который сохраняются данные изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры сохранения. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняются данные изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры сохранения. |


**Example: This example shows the process of saving an Image to memory buffer.**
Этот пример демонстрирует процесс сохранения изображения в буфер памяти. Чтобы продемонстрировать эту операцию, пример загружает существующий файл из некоторого расположения на диске и сохраняет изображение в формате PSD.
``` java
java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
try {            //Create an instance of image class and initialize it with an existing image file through File path
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
    try {
        //Сохранить изображение в поток памяти PSD с настройками по умолчанию PsdOptions
        image.save(stream, new com.aspose.imaging.imageoptions.PsdOptions());
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняются данные изображения. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры сохранения. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |


**Example: The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    java.io.OutputStream outputStream = new java.io.FileOutputStream(dir + "sample.output.png");
    try {
        // Сохранить верхнюю половину изображения в файловый поток.
        image.save(outputStream, saveOptions, bounds);
    } finally {
        outputStream.close();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Устанавливает палитру изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber) {#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---}
```
public InputStream getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)
```


Преобразует в aps.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Параметры изображения. |
| clippingRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник обрезки. |
| pageNumber | int[] | Номер страницы. |

**Returns:**
java.io.InputStream - Сериализованный поток
