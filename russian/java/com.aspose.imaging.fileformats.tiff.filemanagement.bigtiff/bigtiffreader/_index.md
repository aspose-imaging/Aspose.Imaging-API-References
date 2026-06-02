---
title: "BigTiffReader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Читатель BigTiff с маленьким порядком байтов."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker, [com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
```
public class BigTiffReader extends TiffStreamReader
```

Читатель BigTiff с маленьким порядком байтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BigTiffReader(byte[] data)](#BigTiffReader-byte---) | Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(StreamContainer streamContainer)](#BigTiffReader-com.aspose.imaging.StreamContainer-) | Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex)](#BigTiffReader-byte---int-) | Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
| [BigTiffReader(byte[] data, int startIndex, int dataLength)](#BigTiffReader-byte---int-int-) | Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader). |
## Методы

| Метод | Описание |
| --- | --- |
| [getSizeOfTagValue()](#getSizeOfTagValue--) | Получает размер длины значения тега. |
### BigTiffReader(byte[] data) {#BigTiffReader-byte---}
```
public BigTiffReader(byte[] data)
```


Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |

### BigTiffReader(StreamContainer streamContainer) {#BigTiffReader-com.aspose.imaging.StreamContainer-}
```
public BigTiffReader(StreamContainer streamContainer)
```


Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |

### BigTiffReader(byte[] data, int startIndex) {#BigTiffReader-byte---int-}
```
public BigTiffReader(byte[] data, int startIndex)
```


Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |
| startIndex | int | Начальный индекс в `data`. |

### BigTiffReader(byte[] data, int startIndex, int dataLength) {#BigTiffReader-byte---int-int-}
```
public BigTiffReader(byte[] data, int startIndex, int dataLength)
```


Инициализирует новый экземпляр класса [BigTiffReader](../../com.aspose.imaging.fileformats.tiff.filemanagement.bigtiff/bigtiffreader).

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
