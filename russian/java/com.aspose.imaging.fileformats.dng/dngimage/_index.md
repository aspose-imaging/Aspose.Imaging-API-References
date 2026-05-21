---
title: "DngImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для обработки формата изображений DNG Digital Negative, используемого в цифровой фотографии, предоставляющего всестороннюю поддержку RAW‑файлов и метаданных."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

API для обработки формата файлов изображений DNG (Digital Negative), используемого в цифровой фотографии, предоставляя всестороннюю поддержку RAW‑файлов и метаданных. Предназначенный для работы с цифровыми камерами разных производителей, он позволяет разработчикам управлять такими аспектами, как количество бит на пиксель, извлекать внутренние данные и эффективно регулировать баланс изображения. Благодаря возможностям обновления и сохранения данных изображения без проблем, этот API дает разработчикам возможность работать с файлами DNG, обеспечивая высококачественные результаты и гибкие варианты обработки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DngImage()](#DngImage--) | Инициализируйте новый экземпляр класса [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) без усилий. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Узнайте количество бит на пиксель в изображении без усилий с помощью этого свойства. |
| [getHeight()](#getHeight--) | Получите высоту изображения с помощью этого свойства. |
| [getWidth()](#getWidth--) | Получите доступ к ширине изображения с помощью этого свойства. |
| [getFileFormat()](#getFileFormat--) | Определите формат файла вашего изображения с помощью этого свойства. |
| [getImgData()](#getImgData--) | Управляйте данными изображения с помощью этого свойства. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Управляйте данными изображения с помощью этого свойства. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // Преобразует метку времени в читаемую строку.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // Экспортировать в PNG с параметрами по умолчанию.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Производитель камеры:              Leica
// Модель камеры:                     M8 Digital Camera
// Количество цветов:                     3
// Описание цветов:               RGBG
// Версия DNG:                      16777216
// Количество RAW‑изображений в файле: 1
// Программное обеспечение:                         1.107
// Порядок цветовых пикселей:        10110100101101001011010010110100
// Диафрагма:                         0
// Описание:
// Фокусное расстояние:                     50
// Чувствительность ISO:                  160
// Серийный номер изображения:       0
// Скорость затвора:                    12
// Дата съёмки:                 8/3/2007 3:13:49 AM
```

### DngImage() {#DngImage--}
```
public DngImage()
```


Инициализируйте новый экземпляр класса [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) без усилий. Идеально подходит для разработчиков, желающих быстро и эффективно начать использовать объекты DngImage в своих проектах.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Узнайте количество бит на пиксель в изображении без усилий с помощью этого свойства. Идеально для быстрого и точного понимания глубины пикселей изображения.

Значение: количество бит на пиксель изображения.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получите высоту изображения с помощью этого свойства. Идеально для определения вертикального размера изображения без проблем.

Значение: высота изображения.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получите доступ к ширине изображения с помощью этого свойства. Идеально для быстрого и эффективного получения горизонтального размера изображения.

Значение: ширина изображения.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Определите формат файла вашего изображения с помощью этого свойства. Идеально для понимания формата — простые и понятные детали.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Управляйте данными изображения с помощью этого свойства. Независимо от того, извлекаете вы их или обновляете, это свойство обеспечивает беспрепятственный доступ к данным изображения для эффективной манипуляции.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Управляйте данными изображения с помощью этого свойства. Независимо от того, извлекаете вы их или обновляете, это свойство обеспечивает беспрепятственный доступ к данным изображения для эффективной манипуляции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | Данные изображения. |

