---
title: "ImageParameters"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры DNG‑изображения"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

Параметры DNG‑изображения
## Методы

| Метод | Описание |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Получает версию DNG. |
| [getDescription()](#getDescription--) | Получает описание цветов (RGBG, RGBE, GMCY или GBTG). |
| [getModel()](#getModel--) | Получает модель камеры. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Получает производителя камеры. |
| [isFoveon()](#isFoveon--) | Получает матрицу foveon. |
| [getSoftware()](#getSoftware--) | Получает программное обеспечение. |
| [getRawCount()](#getRawCount--) | Получает количество RAW‑изображений в файле (0 означает, что файл не распознан). |
| [getFilters()](#getFilters--) | Получает битовую маску, описывающую порядок цветовых пикселей в матрице. |
| [getColorsCount()](#getColorsCount--) | Получает цвета. |
| [getXmpData()](#getXmpData--) | Получает данные XMP. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Получает массив трансляции для мозаики CFA формата DNG. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Получает версию DNG.

Значение: Версия DNG.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Получает описание цветов (RGBG, RGBE, GMCY или GBTG).

Значение: cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Получает модель камеры.

Значение: Модель.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Получает производителя камеры.

Значение: make.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Получает матрицу foveon.

Значение: is foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Получает программное обеспечение.

Значение: Программное обеспечение.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Получает количество RAW‑изображений в файле (0 означает, что файл не распознан).

Значение: raw count.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Получает битовую маску, описывающую порядок цветовых пикселей в матрице.

Значение: filters.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Получает цвета.

Значение: colors.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Получает данные XMP.

Значение: XMP data.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Получает массив трансляции для мозаики CFA формата DNG.

Значение: xtrans.

**Returns:**
java.lang.String[]
