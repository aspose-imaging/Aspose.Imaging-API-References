---
title: "ImageOptionsBase"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовые параметры изображения."
type: docs
weight: 62
url: /ru/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Базовые параметры изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Возвращает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |
| [getXmpData()](#getXmpData--) | Получает контейнер метаданных XMP. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Устанавливает контейнер метаданных XMP. |
| [getExifData()](#getExifData--) | Получает данные Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Устанавливает данные Exif. |
| [getSource()](#getSource--) | Получает источник, в котором создаётся изображение. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Получает или устанавливает источник, в котором создаётся изображение. |
| [getPalette()](#getPalette--) | Получает цветовую палитру. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Устанавливает цветовую палитру. |
| [getResolutionSettings()](#getResolutionSettings--) | Получает настройки разрешения. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Устанавливает настройки разрешения. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Получает параметры векторной растеризации. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Устанавливает параметры векторной растеризации. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Параметры многостраничного режима. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Параметры многостраничного режима. |
| [getFullFrame()](#getFullFrame--) | Получает значение, указывающее, является ли [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Устанавливает значение, указывающее, является ли [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает обработчик события прогресса. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Устанавливает обработчик события прогресса. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Пытается установить экземпляр `metadata`, если данный экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Возвращает значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте.

**Returns:**
boolean — значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, сохранять ли оригинальные метаданные изображения при экспорте. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает контейнер метаданных XMP.

Значение: контейнер данных XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Устанавливает контейнер метаданных XMP.

Значение: контейнер данных XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | контейнер метаданных XMP. |

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

### getSource() {#getSource--}
```
public Source getSource()
```


Получает источник, в котором создаётся изображение.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Получает или устанавливает источник, в котором создаётся изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | Источник, в котором создаётся изображение. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Устанавливает цветовую палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Создать BMP‑изображение размером 100 × 100 пикселей.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Линейный градиент от левого верхнего до правого нижнего угла изображения.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Заполнить всё изображение кистью линейного градиента.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Получить ближайшую 8‑битную палитру цветов, покрывающую как можно больше пикселей, так чтобы палитровое изображение
    // было почти визуально неотличимо от непалитрового.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8‑битная палитра содержит не более 256 цветов.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// Вывод выглядит так:
// Размер палетизированного изображения составляет 11078 байт.
// Размер непалетизированного изображения составляет 40054 байт.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Получает настройки разрешения.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Устанавливает настройки разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


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

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


Получает параметры векторной растеризации.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Устанавливает параметры векторной растеризации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Параметры векторной растеризации. |

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

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Параметры многостраничного режима.

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Параметры многостраничного режима.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Получает значение, указывающее, является ли [full frame].

Значение: `true`, если [full frame]; иначе `false`.

**Returns:**
boolean - значение, указывающее, является ли [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Устанавливает значение, указывающее, является ли [full frame].

Значение: `true`, если [full frame]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, является ли [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Получает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Устанавливает обработчик события прогресса.

Значение: обработчик события прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | обработчик события прогресса. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Пример использования отдельных обработчиков событий прогресса операции для загрузки/экспорта.
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// Журнал STDOUT может выглядеть так:
//        Событие загрузки Инициализация : 1/4
//        Событие загрузки Предобработка : 2/4
//        Событие загрузки Обработка : 3/4
//        Событие загрузки Завершение : 4/4
//        Событие экспорта Инициализация : 1/4
//        Событие экспорта Предобработка : 2/4
//        Событие экспорта Обработка : 3/4
//        Событие экспорта RelativeProgress : 1/1
//        Событие загрузки RelativeProgress : 1/1
//        Событие экспорта Завершение : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Клонирует этот экземпляр.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Пытается установить экземпляр `metadata`, если данный экземпляр [Image](../../com.aspose.imaging/image) поддерживает и реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Метаданные. |

**Returns:**
boolean - True, если экземпляр [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) поддерживает и/или реализует экземпляр [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat); иначе false.
