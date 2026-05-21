---
title: "JpegImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Эффективно манипулируйте растровыми изображениями JPEG с помощью нашего API, предоставляющего поддержку различных цветовых профилей, таких как RGB и CMYK, настраиваемого разрешения в битах на пиксель и обработки контейнеров метаданных EXIF, JFIF и XMP."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Эффективно манипулируйте растровыми изображениями JPEG с помощью нашего API, предлагающего поддержку различных цветовых профилей, таких как RGB и CMYK, настраиваемого разрешения в битах на пиксель и обработки контейнеров метаданных EXIF, JFIF и XMP. Наслаждайтесь автоматическим вращением на основе данных ориентации и выбирайте из разных уровней сжатия, включая JPEG без потерь, чтобы достичь оптимального качества изображения и баланса размера файла для ваших проектов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | Класс [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) инициализируется без усилий путем вызова его конструктора с указанным параметром пути. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Инициализируйте объект изображения JPEG с помощью класса [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage), используя параметр потока. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Инициализируйте новый экземпляр класса [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с параметром растрового изображения. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Создайте новый экземпляр класса [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с указанными параметрами ширины и высоты. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Инициализируйте новый объект [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с предоставленными параметрами JPEG. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Получите формат изображения без усилий с помощью этого свойства. |
| [getJpegOptions()](#getJpegOptions--) | Получите доступ к параметрам JPEG, используемым при создании или загрузке этого экземпляра [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с легкостью. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите глубину цвета изображения без труда с помощью этого свойства, предоставляющего информацию о насыщенности цветового или градационного представления. |
| [getComment()](#getComment--) | Управляйте комментариями JPEG-файла с помощью этого свойства, позволяющего добавлять или получать описательные аннотации, связанные с изображением. |
| [setComment(String value)](#setComment-java.lang.String-) | Управляйте комментариями JPEG-файла с помощью этого свойства, позволяющего добавлять или получать описательные аннотации, связанные с изображением. |
| [getJpegExifData()](#getJpegExifData--) | Получает экземпляр Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Управляйте данными EXIF с помощью этого свойства, позволяющего добавлять или получать метаданные, связанные с изображением. |
| [getExifData()](#getExifData--) | Получает данные Exif; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Устанавливает данные Exif; |
| [getHeight()](#getHeight--) | Легко получите высоту изображения с помощью этого свойства. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Это свойство предоставляет доступ к горизонтальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Это свойство предоставляет доступ к горизонтальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм. |
| [getJfif()](#getJfif--) | Это свойство позволяет получить доступ к данным JFIF (JPEG File Interchange Format) или изменить их, связанные с JPEG-изображением. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Это свойство позволяет получить доступ к данным JFIF (JPEG File Interchange Format) или изменить их, связанные с JPEG-изображением. |
| [getRawDataFormat()](#getRawDataFormat--) | Это свойство извлекает формат необработанных данных изображения, указывающий, как структурированы и закодированы данные изображения. |
| [getVerticalResolution()](#getVerticalResolution--) | Это свойство управляет вертикальным разрешением, выраженным в пикселях на дюйм, для связанного [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Это свойство управляет вертикальным разрешением, выраженным в пикселях на дюйм, для связанного [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getWidth()](#getWidth--) | Это свойство получает ширину изображения, выраженную в пикселях. |
| [getRgbColorProfile()](#getRgbColorProfile--) | RGB‑цветовой профиль для JPEG‑изображений CMYK и YCCK обеспечивает точное преобразование и представление цветов. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | RGB‑цветовой профиль для JPEG‑изображений CMYK и YCCK обеспечивает точное преобразование и представление цветов. |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK‑цветовой профиль, связанный с JPEG‑изображениями CMYK и YCCK, обеспечивает точное преобразование цветов и их достоверность. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK‑цветовой профиль, связанный с JPEG‑изображениями CMYK и YCCK, обеспечивает точное преобразование цветов и их достоверность. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | RGBColorProfile необходим для точного преобразования цветов JPEG‑изображений CMYK и YCCK во время процесса сохранения. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | RGBColorProfile необходим для точного преобразования цветов JPEG‑изображений CMYK и YCCK во время процесса сохранения. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | CMYK‑цветовой профиль имеет решающее значение для точного преобразования цветов JPEG‑изображений CMYK и YCCK во время процесса сохранения. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK‑цветовой профиль имеет решающее значение для точного преобразования цветов JPEG‑изображений CMYK и YCCK во время процесса сохранения. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Получает или изменяет флаг, указывающий, игнорируется ли встроенный цветовой профиль. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Получает или изменяет флаг, указывающий, игнорируется ли встроенный цветовой профиль. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает исходные параметры изображения этого экземпляра [Image](../../com.aspose.imaging/image). |
| [removeMetadata()](#removeMetadata--) | Удаляет метаданные этого экземпляра изображения, устанавливая значения `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) и `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) в `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Устанавливает разрешение для указанного [RasterImage](../../com.aspose.imaging/rasterimage), обеспечивая точное масштабирование и возможности печати. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Загрузите JPEG‑изображение из файла.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Выполните некоторую обработку изображения.
    // Сохраните в другой JPEG‑файл.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


Класс [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) инициализируется без усилий путем вызова его конструктора с указанным параметром пути. Этот конструктор обеспечивает беспрепятственное создание JPEG‑изображений, гарантируя быструю интеграцию в ваши проекты без труда.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Инициализируйте объект JPEG‑изображения с помощью класса [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) используя параметр потока. Этот конструктор упрощает работу с JPEG‑изображениями, предлагая простой подход для их интеграции в ваши проекты без усилий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Инициализируйте новый экземпляр класса [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с параметром растрового изображения. Этот конструктор предоставляет удобный способ создания JPEG‑изображений непосредственно из растровых изображений, упрощая рабочий процесс работы с JPEG‑изображениями в ваших приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с которым инициализируются данные пикселей и палитры. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Создайте новый экземпляр класса [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с указанными параметрами ширины и высоты. Этот конструктор позволяет создавать JPEG‑изображения с пользовательскими размерами, предоставляя гибкость в управлении размерами изображений в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Инициализируйте новый объект [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) с предоставленными параметрами JPEG. Этот конструктор позволяет настроить различные параметры JPEG‑изображения, такие как уровень сжатия, качество и дополнительные параметры, обеспечивая точный контроль над получаемым форматом изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Параметры JPEG. |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите формат изображения без усилий с помощью этого свойства. Оно предоставляет ценную информацию о формате файла, способствуя бесшовной интеграции и проверкам совместимости на различных платформах и в приложениях.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Получите доступ к параметрам JPEG, использованным при создании или загрузке этого экземпляра [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage), без труда. Это свойство предоставляет ценную информацию о конкретных применённых настройках, позволяя пользователям эффективно понимать и воспроизводить процессы обработки изображений. Будь то уровни сжатия, настройки качества или другие параметры, это свойство обеспечивает необходимые сведения для бесшовного манипулирования изображениями.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//Вывод выглядит так:
//Количество бит на канал: 8
//Максимальный допустимый размер всех внутренних буферов: 0
//Тип цвета: YCbCr
//Тип сжатия: Baseline
//Качество изображения: 75
//Сэмплинг компонента 0: 1x1
//Сэмплинг компонента 1: 1x1
//Сэмплинг компонента 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получите глубину пикселей изображения без труда с помощью этого свойства, получая представление о насыщенности цветового или градационного отображения. Будь то яркая фотография или монохромная иллюстрация, это свойство предоставляет важную информацию о визуальной сложности изображения.

**Returns:**
int — Количество бит на пиксель изображения.
### getComment() {#getComment--}
```
public String getComment()
```


Управляйте комментариями JPEG‑файлов с помощью этого свойства, позволяя добавлять или получать описательные аннотации, связанные с изображением. Будь то пометка изображений метаданными или добавление дополнительного контекста, это свойство обеспечивает гибкость в организации и классификации ваших JPEG‑файлов.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Управляйте комментариями JPEG‑файлов с помощью этого свойства, позволяя добавлять или получать описательные аннотации, связанные с изображением. Будь то пометка изображений метаданными или добавление дополнительного контекста, это свойство обеспечивает гибкость в организации и классификации ваших JPEG‑файлов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Получает экземпляр Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Управляйте данными EXIF с помощью этого свойства, позволяя добавлять или получать метаданные, связанные с изображением. Будь то извлечение информации о настройках камеры или изменение существующих метаданных, это свойство обеспечивает гибкость в управлении контейнером данных EXIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Получает данные Exif;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//Вывод выглядит так:
//Общие данные EXIF
//------------------------------------------
//Версия EXIF: [B@163e4e87
//Серийный номер камеры: 7100536
//Цветовое пространство: SRgb
//Яркость:
//Контраст: Нормальный
//Гамма:
//Резкость: 0
//Диафрагма: 4.64(4643856 / 1000000)
//Режим экспозиции: Ручной
//Смещение экспозиции: 0.67(4 / 6)
//Время экспозиции: 0.01(1 / 160)
//Фокусное расстояние: 145.00(1450 / 10)
//Единица разрешения фокальной плоскости: см
//Модель объектива: 70.0 - 200.0 мм f/ 4.0
//Скорость затвора: 7.32(7321928 / 1000000)
//Данные JPEG EXIF
//------------------------------------------
//Производитель камеры: NIKON CORPORATION
//Модель камеры: NIKON D5
//Фотометрическая интерпретация: 0
//Автор:
//Авторские права:
//Описание изображения:
//Ориентация: Верхний левый
//Программное обеспечение: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Устанавливает данные Exif;

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Данные Exif; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Легко получайте высоту изображения с помощью этого свойства. Оно обеспечивает быстрый доступ к вертикальному размеру изображения, позволяя эффективно определить его размер и соотношение сторон без необходимости в сложных вычислениях или дополнительных методах.

**Returns:**
int - Высота изображения в пикселях.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Это свойство предоставляет доступ к горизонтальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм. Устанавливая или получая это значение, вы можете точно контролировать разрешение изображения, гарантируя, что оно соответствует вашим конкретным требованиям к качеству и чёткости.

**Returns:**
double - Горизонтальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Получить горизонтальное и вертикальное разрешение BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 300.0
// Вертикальное разрешение, в пикселях на дюйм: 300.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 96.0
// Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Это свойство предоставляет доступ к горизонтальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм. Устанавливая или получая это значение, вы можете точно контролировать разрешение изображения, гарантируя, что оно соответствует вашим конкретным требованиям к качеству и чёткости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Горизонтальное разрешение. |

Обратите внимание, что по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода `setResolution` для обновления обоих значений разрешения одним вызовом. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Это свойство позволяет получить доступ к данным JFIF (JPEG File Interchange Format) или изменить их, связанные с JPEG‑изображением. JFIF является стандартным форматом для обмена JPEG‑сжатыми изображениями между компьютерами и другими устройствами. Получая или устанавливая это свойство, вы можете работать с данными JFIF, которые могут включать информацию, такую как разрешение изображения, соотношение сторон и миниатюра.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Это свойство позволяет получить доступ к данным JFIF (JPEG File Interchange Format) или изменить их, связанные с JPEG‑изображением. JFIF является стандартным форматом для обмена JPEG‑сжатыми изображениями между компьютерами и другими устройствами. Получая или устанавливая это свойство, вы можете работать с данными JFIF, которые могут включать информацию, такую как разрешение изображения, соотношение сторон и миниатюра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Это свойство извлекает формат необработанных данных изображения, который указывает, как данные изображения структурированы и закодированы. Понимание формата необработанных данных необходимо для эффективной обработки или манипулирования данными изображения. Оно предоставляет представление о внутреннем представлении изображения, например, сжато ли оно, закодировано в определённом цветовом пространстве или сохранено в конкретном файловом формате. Доступ к этому свойству позволяет получить ценную информацию о структуре данных изображения, что даёт возможность выполнять различные операции или оптимизации, адаптированные к его конкретному формату.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Это свойство управляет вертикальным разрешением, выраженным в пикселях на дюйм, для связанного [RasterImage](../../com.aspose.imaging/rasterimage). Регулировка этого разрешения влияет на размер и качество изображения при печати или отображении в фиксированном физическом размере. Устанавливая это свойство, вы контролируете плотность вертикального расположения пикселей изображения, что сказывается на общей чёткости и резкости.

**Returns:**
double - Вертикальное разрешение.

Обратите внимание, что по умолчанию это значение всегда равно 72, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Получить горизонтальное и вертикальное разрешение BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 300.0
// Вертикальное разрешение, в пикселях на дюйм: 300.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 96.0
// Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Это свойство управляет вертикальным разрешением, выраженным в пикселях на дюйм, для связанного [RasterImage](../../com.aspose.imaging/rasterimage). Регулировка этого разрешения влияет на размер и качество изображения при печати или отображении в фиксированном физическом размере. Устанавливая это свойство, вы контролируете плотность вертикального расположения пикселей изображения, что сказывается на общей чёткости и резкости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Вертикальное разрешение. |

Обратите внимание, что по умолчанию это значение всегда равно 72, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Это свойство получает ширину изображения в пикселях. Оно предоставляет важную информацию о размерах изображения, позволяя точно отрисовывать, изменять или отображать данные изображения.

**Returns:**
int - Ширина изображения в пикселях.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


RGB‑цветовой профиль для JPEG‑изображений CMYK и YCCK обеспечивает точное преобразование и представление цветов. Он должен использоваться вместе с CMYKColorProfile для поддержания согласованности и достоверности цветовой отрисовки. Такое сочетание необходимо для приложений, требующих точного управления цветом и воспроизведения изображений, гарантируя правильную интерпретацию и отображение RGB‑данных.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


RGB‑цветовой профиль для JPEG‑изображений CMYK и YCCK обеспечивает точное преобразование и представление цветов. Он должен использоваться вместе с CMYKColorProfile для поддержания согласованности и достоверности цветовой отрисовки. Такое сочетание необходимо для приложений, требующих точного управления цветом и воспроизведения изображений, гарантируя правильную интерпретацию и отображение RGB‑данных.

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


CMYK‑цветовой профиль, связанный с JPEG‑изображениями CMYK и YCCK, обеспечивает точное преобразование цветов и их достоверность. Он работает совместно с RGBColorProfile, гарантируя точное представление цветов на различных устройствах и в приложениях. Такое сочетание критически важно для поддержания согласованности цветовой отрисовки и достижения оптимального качества изображения.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK‑цветовой профиль, связанный с JPEG‑изображениями CMYK и YCCK, обеспечивает точное преобразование цветов и их достоверность. Он работает совместно с RGBColorProfile, гарантируя точное представление цветов на различных устройствах и в приложениях. Такое сочетание критически важно для поддержания согласованности цветовой отрисовки и достижения оптимального качества изображения.

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

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


RGBColorProfile необходим для точного преобразования цветов JPEG‑изображений CMYK и YCCK при сохранении. В сочетании с CMYKColorProfile он обеспечивает правильную отрисовку цветов и поддерживает согласованность на разных устройствах и в приложениях. Такое сочетание критически важно для сохранения задуманного цветового представления и получения высококачественного вывода изображения.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


RGBColorProfile необходим для точного преобразования цветов JPEG‑изображений CMYK и YCCK при сохранении. В сочетании с CMYKColorProfile он обеспечивает правильную отрисовку цветов и поддерживает согласованность на разных устройствах и в приложениях. Такое сочетание критически важно для сохранения задуманного цветового представления и получения высококачественного вывода изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


CMYK‑цветовой профиль имеет решающее значение для точного преобразования цветов JPEG‑изображений CMYK и YCCK при сохранении. Он работает в паре с RGBColorProfile, обеспечивая правильное представление цветов и поддерживая согласованность и качество на разных устройствах и в программном обеспечении. Такая синхронизация критически важна для получения точной и надёжной цветовой отрисовки в окончательно сохранённых изображениях.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


CMYK‑цветовой профиль имеет решающее значение для точного преобразования цветов JPEG‑изображений CMYK и YCCK при сохранении. Он работает в паре с RGBColorProfile, обеспечивая правильное представление цветов и поддерживая согласованность и качество на разных устройствах и в программном обеспечении. Такая синхронизация критически важна для получения точной и надёжной цветовой отрисовки в окончательно сохранённых изображениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Получает или изменяет флаг, указывающий, игнорируется ли встроенный цветовой профиль. Установив этот флаг, пользователи могут задать, следует ли использовать профиль по умолчанию вместо встроенного. Эта опция обеспечивает больший контроль над управлением цветом, облегчая настройку для согласованности и совместимости на различных платформах и в приложениях.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Получает или изменяет флаг, указывающий, игнорируется ли встроенный цветовой профиль. Установив этот флаг, пользователи могут задать, следует ли использовать профиль по умолчанию вместо встроенного. Эта опция обеспечивает больший контроль над управлением цветом, облегчая настройку для согласованности и совместимости на различных платформах и в приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает исходные параметры изображения этого экземпляра [Image](../../com.aspose.imaging/image).

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Удаляет метаданные этого экземпляра изображения, устанавливая значения `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) и `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) в `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Устанавливает разрешение для указанного [RasterImage](../../com.aspose.imaging/rasterimage), обеспечивая точное масштабирование и возможности печати. Этот метод позволяет пользователям адаптировать разрешение изображения под их конкретные требования, будь то цифровой дисплей или физическое воспроизведение. Установив разрешение, пользователи могут оптимизировать качество изображения и обеспечить совместимость с различными устройствами вывода и носителями, улучшая общее визуальное восприятие и удобство использования изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dpiX | double | Горизонтальное разрешение, в точках на дюйм, `RasterImage`. |
| dpiY | double | Вертикальное разрешение, в точках на дюйм, `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Получить горизонтальное и вертикальное разрешение BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 300.0
// Вертикальное разрешение, в пикселях на дюйм: 300.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 96.0
// Вертикальное разрешение, в пикселях на дюйм: 96.0
```

