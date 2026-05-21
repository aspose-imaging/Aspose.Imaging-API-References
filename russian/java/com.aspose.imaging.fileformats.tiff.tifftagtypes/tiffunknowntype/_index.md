---
title: "TiffUnknownType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Неизвестный тип tiff."
type: docs
weight: 27
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

Неизвестный тип TIFF. Если тег TIFF не может быть распознан, создаётся этот тип.

Обратите внимание, что `TiffUnknownType` не сериализуется обратно в поток.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | Создаёт новый экземпляр класса `TiffUnknownType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Возвращает количество элементов. |
| [getOffsetOrValue()](#getOffsetOrValue--) | Получает значение смещения для дополнительных данных или самого значения, если количество равно 1. |
| [getStream()](#getStream--) | Получает поток для чтения дополнительных данных. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Возвращает дополнительный размер значения тега в байтах (в случае, если тег не может вместить всё значение). |
| [getValue()](#getValue--) | Получает или задает значение, которое содержит этот тип данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение, которое содержит этот тип данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
| [toString()](#toString--) | Возвращает `System.String`, представляющий этот экземпляр. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


Создаёт новый экземпляр класса `TiffUnknownType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Поток для чтения. |
| tagType | int | Тип тега. |
| tagId | int | Идентификатор тега. |
| count | long | Значение счётчика. |
| offsetOrValue | long | Смещение или значение. |

### getCount() {#getCount--}
```
public long getCount()
```


Возвращает количество элементов.

Значение: количество элементов.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


Получает значение смещения для дополнительных данных или самого значения, если количество равно 1.

Значение: Смещение или значение.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


Получает поток для чтения дополнительных данных.

Значение: Поток для чтения данных.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


Возвращает тип тега.

Значение: тип тега.

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Возвращает дополнительный размер значения тега в байтах (в случае, если тег не может вместить всё значение).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeOfTagValue | byte | Размер значения тега: 4 или 8 для BigTiff. |

**Returns:**
long - размер дополнительных данных в байтах.
### getValue() {#getValue--}
```
public Object getValue()
```


Получает или задает значение, которое содержит этот тип данных.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Получает или задает значение, которое содержит этот тип данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Записывает дополнительные данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Поток данных. |

**Returns:**
long - Фактически записанные байты.
### toString() {#toString--}
```
public String toString()
```


Возвращает `System.String`, представляющий этот экземпляр.

**Returns:**
java.lang.String - `System.String`, представляющая этот экземпляр.
