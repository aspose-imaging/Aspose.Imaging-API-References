---
title: "ImageOtherParameters"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Другие параметры изображения"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Другие параметры изображения
## Методы

| Метод | Описание |
| --- | --- |
| [getDescription()](#getDescription--) | Получает описание изображения. |
| [getArtist()](#getArtist--) | Получает автора изображения. |
| [getTimestamp()](#getTimestamp--) | Получает дату съёмки. |
| [getShotOrder()](#getShotOrder--) | Получает серийный номер изображения. |
| [getAperture()](#getAperture--) | Получает диафрагму. |
| [getShutterSpeed()](#getShutterSpeed--) | Получает выдержку. |
| [getGpsData()](#getGpsData--) | Получает данные GPS. |
| [getFocalLength()](#getFocalLength--) | Получает длину фокусного расстояния. |
| [getIsoSpeed()](#getIsoSpeed--) | Получает чувствительность ISO. |

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

### getDescription() {#getDescription--}
```
public String getDescription()
```


Получает описание изображения.

Значение: Описание.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Получает автора изображения.

Значение: Автор.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Получает дату съёмки.

Значение: Метка времени.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Получает серийный номер изображения.

Значение: Порядок снимка.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Получает диафрагму.

Значение: Диафрагма.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Получает выдержку.

Значение: Выдержка.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Получает данные GPS.

Значение: Данные GPS.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Получает длину фокусного расстояния.

Значение: длина фокуса.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Получает чувствительность ISO.

Значение: ISO‑скорость.

**Returns:**
float
