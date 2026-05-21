---
title: "JpegExifData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Контейнер данных EXIF для файлов jpeg."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

Контейнер данных EXIF для файлов jpeg.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Инициализирует новый экземпляр класса `JpegExifData`. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса `JpegExifData` с данными из массива. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса `JpegExifData` с данными из массива. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Инициализирует новый экземпляр класса [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) с данными из массива. |
## Поля

| Поле | Описание |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | Максимальный разрешённый размер сегмента EXIF в байтах. |
## Методы

| Метод | Описание |
| --- | --- |
| [getArtist()](#getArtist--) | Получает или задает исполнителя. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Получает или задает исполнителя. |
| [getBitsPerSample()](#getBitsPerSample--) | Получает или задаёт количество бит на образец. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Получает или задаёт количество бит на образец. |
| [getCompression()](#getCompression--) | Получает или задаёт сжатие. |
| [setCompression(int value)](#setCompression-int-) | Получает или задаёт сжатие. |
| [getCopyright()](#getCopyright--) | Получает или задаёт авторские права. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Получает или задаёт авторские права. |
| [getDateTime()](#getDateTime--) | Получает или задаёт дату и время. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Получает или задаёт дату и время. |
| [getImageDescription()](#getImageDescription--) | Получает или задает описание изображения. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Получает или задает описание изображения. |
| [getImageLength()](#getImageLength--) | Получает или задает длину изображения. |
| [setImageLength(long value)](#setImageLength-long-) | Получает или задает длину изображения. |
| [getImageWidth()](#getImageWidth--) | Получает или задает ширину изображения. |
| [setImageWidth(long value)](#setImageWidth-long-) | Получает или задает ширину изображения. |
| [getModel()](#getModel--) | Получает или задаёт модель. |
| [setModel(String value)](#setModel-java.lang.String-) | Получает или задаёт модель. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Получает или задаёт фотометрическую интерпретацию. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Получает или задаёт фотометрическую интерпретацию. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Получает или задает планарную конфигурацию. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Получает или задает планарную конфигурацию. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Получает или задаёт хроматичность трёх основных цветов изображения. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задаёт хроматичность трёх основных цветов изображения. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Получает или задаёт эталонные чёрный и белый. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задаёт эталонные чёрный и белый. |
| [getResolutionUnit()](#getResolutionUnit--) | Получает или задает единицу разрешения. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Получает или задает единицу разрешения. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Получает или задаёт количество образцов на пиксель. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Получает или задаёт количество образцов на пиксель. |
| [getSoftware()](#getSoftware--) | Получает или задаёт программное обеспечение. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Получает или задаёт программное обеспечение. |
| [getTransferFunction()](#getTransferFunction--) | Получает или задаёт функцию передачи. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Получает или задаёт функцию передачи. |
| [getXResolution()](#getXResolution--) | Получает или задает разрешение по оси X. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси X. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Получает или задаёт коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | Получает или задаёт коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Получает или задаёт позицию компонентов хроминанс в отношении к компоненту яркости. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Получает или задаёт позицию компонентов хроминанс в отношении к компоненту яркости. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Получает или задаёт коэффициент дискретизации компонентов хроминанс относительно компонента яркости. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Получает или задаёт коэффициент дискретизации компонентов хроминанс относительно компонента яркости. |
| [getYResolution()](#getYResolution--) | Получает или задает разрешение по оси Y. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Получает или задает разрешение по оси Y. |
| [serializeExifData()](#serializeExifData--) | Сериализует данные EXIF. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Инициализирует новый экземпляр класса `JpegExifData`.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Инициализирует новый экземпляр класса `JpegExifData` с данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Массив тегов EXIF вместе с общими тегами и тегами GPS. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Инициализирует новый экземпляр класса `JpegExifData` с данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Общие теги. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги EXIF. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги GPS. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Инициализирует новый экземпляр класса [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) с данными из массива.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Массив тегов EXIF вместе с общими тегами и тегами GPS. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


Максимальный разрешённый размер сегмента EXIF в байтах.

### getArtist() {#getArtist--}
```
public String getArtist()
```


Получает или задает исполнителя.

Значение: Автор.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Получает или задает исполнителя.

Значение: Автор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Получает или задаёт количество бит на образец.

Значение: Бит на образец.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Получает или задаёт количество бит на образец.

Значение: Бит на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Получает или задаёт сжатие.

Значение: Сжатие.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Получает или задаёт сжатие.

Значение: Сжатие.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Получает или задаёт авторские права.

Значение: Авторские права.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Получает или задаёт авторские права.

Значение: Авторские права.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Получает или задаёт дату и время.

Значение: Дата и время.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Получает или задаёт дату и время.

Значение: Дата и время.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Получает или задает описание изображения.

Значение: Описание изображения.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Получает или задает описание изображения.

Значение: Описание изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Получает или задает длину изображения.

Значение: Длина изображения.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Получает или задает длину изображения.

Значение: Длина изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Получает или задает ширину изображения.

Значение: Ширина изображения.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Получает или задает ширину изображения.

Значение: Ширина изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Получает или задаёт модель.

Значение: Модель.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Получает или задаёт модель.

Значение: Модель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Получает или задаёт фотометрическую интерпретацию.

Значение: Фотометрическая интерпретация.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Получает или задаёт фотометрическую интерпретацию.

Значение: Фотометрическая интерпретация.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Получает или задает планарную конфигурацию.

Значение: Планарная конфигурация.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Получает или задает планарную конфигурацию.

Значение: Планарная конфигурация.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Получает или задаёт хроматичность трёх основных цветов изображения.

Значение: Хроматичность трёх основных цветов изображения.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Получает или задаёт хроматичность трёх основных цветов изображения.

Значение: Хроматичность трёх основных цветов изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Получает или задаёт эталонные чёрный и белый.

Значение: Ссылка на чёрный и белый.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Получает или задаёт эталонные чёрный и белый.

Значение: Ссылка на чёрный и белый.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Получает или задает единицу разрешения.

Значение: Единица разрешения.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Получает или задает единицу разрешения.

Значение: Единица разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Получает или задаёт количество образцов на пиксель.

Значение: Количество образцов на пиксель.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Получает или задаёт количество образцов на пиксель.

Значение: Количество образцов на пиксель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Получает или задаёт программное обеспечение.

Значение: Программное обеспечение.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Получает или задаёт программное обеспечение.

Значение: Программное обеспечение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Получает или задаёт функцию передачи.

Значение: Функция передачи.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Получает или задаёт функцию передачи.

Значение: Функция передачи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


Получает или задает разрешение по оси X.

Значение: Разрешение по оси X.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


Получает или задает разрешение по оси X.

Значение: Разрешение по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Получает или задаёт коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr.

Значение: Коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Получает или задаёт коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr.

Значение: Коэффициенты матрицы для преобразования данных изображения из RGB в YCbCr.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Получает или задаёт позицию компонентов хроминанс в отношении к компоненту яркости.

Значение: Позиция компонентов хроминанса относительно компонента яркости.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Получает или задаёт позицию компонентов хроминанс в отношении к компоненту яркости.

Значение: Позиция компонентов хроминанса относительно компонента яркости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Получает или задаёт коэффициент дискретизации компонентов хроминанс относительно компонента яркости.

Значение: Коэффициент дискретизации компонентов хроминанса относительно компонента яркости.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Получает или задаёт коэффициент дискретизации компонентов хроминанс относительно компонента яркости.

Значение: Коэффициент дискретизации компонентов хроминанса относительно компонента яркости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Получает или задает разрешение по оси Y.

Значение: Разрешение по оси Y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Получает или задает разрешение по оси Y.

Значение: Разрешение по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


Сериализует данные EXIF. Записывает значения тегов и их содержимое. Наибольшее влияние на размер оказывает содержимое тега миниатюры.

**Returns:**
byte[] - Сериализованные данные EXIF.

Общий размер сегмента должен быть меньше или равен MaxExifSegmentSize байтам, чтобы получить корректное jpeg-изображение. Совет: попробуйте уменьшить размер миниатюры или изменить её сжатие, если размер раздела EXIF слишком велик.
