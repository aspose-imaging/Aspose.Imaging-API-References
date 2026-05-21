---
title: "BigTiffOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для создания растровых изображений в формате BigTIFF специально разработан для удовлетворения уникальных требований приложений, использующих крупномасштабные данные сканеров."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

API для создания растрового формата изображений BigTIFF специально разработан для удовлетворения уникальных требований приложений, использующих крупномасштабные данные сканеров. Этот API облегчает бесшовную генерацию формата BigTIFF, который объединяет несколько TIFF‑изображений в одно комплексное изображение. Он обеспечивает эффективную обработку больших объёмов данных изображений, предоставляя разработчикам мощный инструмент для создания и манипулирования высокоразрешёнными многокадровыми форматами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions). По умолчанию используется порядок байтов little endian.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | int | Ожидаемый формат файла Tiff. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Источник параметров. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Теги для инициализации параметров. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Инициализирует новый экземпляр класса [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | int | Ожидаемый формат файла Tiff. |
| byteOrder | int | Порядок байтов формата файла tiff, который следует использовать. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Клонирует этот экземпляр.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
