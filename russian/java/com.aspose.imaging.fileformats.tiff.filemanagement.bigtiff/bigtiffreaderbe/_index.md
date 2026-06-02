---
title: "BigTiffReaderBE"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Записыватель потока BigTiff с большим порядком байтов."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader), [com.aspose.imaging.fileformats.tiff.filemanagement.TiffBigEndianStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffbigendianstreamreader)
```
public class BigTiffReaderBE extends TiffBigEndianStreamReader
```

Записыватель потока BigTiff с большим порядком байтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BigTiffReaderBE(byte[] data)](#BigTiffReaderBE-byte---) | Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(StreamContainer streamContainer)](#BigTiffReaderBE-com.aspose.imaging.StreamContainer-) | Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex)](#BigTiffReaderBE-byte---int-) | Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
| [BigTiffReaderBE(byte[] data, int startIndex, int dataLength)](#BigTiffReaderBE-byte---int-int-) | Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe). |
## Методы

| Метод | Описание |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Получает размер длины значения тега. |
### BigTiffReaderBE(byte[] data) {#BigTiffReaderBE-byte---}
```
public BigTiffReaderBE(byte[] data)
```


Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |

### BigTiffReaderBE(StreamContainer streamContainer) {#BigTiffReaderBE-com.aspose.imaging.StreamContainer-}
```
public BigTiffReaderBE(StreamContainer streamContainer)
```


Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |

### BigTiffReaderBE(byte[] data, int startIndex) {#BigTiffReaderBE-byte---int-}
```
public BigTiffReaderBE(byte[] data, int startIndex)
```


Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |
| startIndex | int | Начальный индекс в `data`. |

### BigTiffReaderBE(byte[] data, int startIndex, int dataLength) {#BigTiffReaderBE-byte---int-int-}
```
public BigTiffReaderBE(byte[] data, int startIndex, int dataLength)
```


Инициализирует новый экземпляр класса [BigTiffReaderBE](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreaderbe).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |
| startIndex | int | Начальный индекс в `data`. |
| dataLength | int | Длина данных. |

### getSizeOfTagValue() {#getSizeOfTagValue--}
```
public byte getSizeOfTagValue()
```


Получает размер длины значения тега.

**Returns:**
byte — размер длины значения тега.
