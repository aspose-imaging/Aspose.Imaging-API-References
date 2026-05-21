---
title: "TiffUndefinedType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff неопределённый."
type: docs
weight: 26
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

Тип tiff неопределённый.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | Создаёт новый экземпляр класса `TiffUndefinedType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getData()](#getData--) | Получает или задаёт данные. |
| [setData(byte[] value)](#setData-byte---) | Получает или задаёт данные. |
| [getCount()](#getCount--) | Возвращает количество элементов. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает или задает значение, которое содержит этот тип данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение, которое содержит этот тип данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


Создаёт новый экземпляр класса `TiffUndefinedType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задаёт данные.

Значение: данные.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задаёт данные.

Значение: данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


Возвращает количество элементов.

Значение: количество элементов.

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


Возвращает тип тега.

Значение: тип тега.

**Returns:**
int
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
