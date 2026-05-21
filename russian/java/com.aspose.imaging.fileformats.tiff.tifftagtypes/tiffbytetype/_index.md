---
title: "TiffByteType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff byte."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

Тип tiff byte.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | Создаёт новый экземпляр класса `TiffByteType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает или задает значения. |
| [setValues(byte[] value)](#setValues-byte---) | Получает или задает значения. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getElementSize()](#getElementSize--) | Возвращает размер элемента в байтах. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает или задает значение, которое содержит этот тип данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение, которое содержит этот тип данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


Создаёт новый экземпляр класса `TiffByteType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Получает или задает значения.

**Returns:**
byte[] - данные.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Получает или задает значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] | Данные. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Получает контейнер значений.

**Returns:**
com.aspose.ms.System.Array - Контейнер значений.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Возвращает размер элемента в байтах.

**Returns:**
byte - Размер элемента в байтах.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Возвращает тип тега.

**Returns:**
int - тип тега.
### getValue() {#getValue--}
```
public Object getValue()
```


Получает или задает значение, которое содержит этот тип данных.

**Returns:**
java.lang.Object - значение.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Получает или задает значение, которое содержит этот тип данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение. |

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
