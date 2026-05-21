---
title: "TiffLong8Type"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип Tiff unsigned 64-bit."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

Тип Tiff unsigned 64-bit.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | Создаёт новый экземпляр класса [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type). |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | Создаёт новый экземпляр класса [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type). |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает значения. |
| [setValues(long[] value)](#setValues-long---) | Устанавливает значения. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает значение, содержащееся в этом типе данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Устанавливает значение, содержащееся в этом типе данных. |
| [getElementSize()](#getElementSize--) | Получает размер элемента. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


Создаёт новый экземпляр класса [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


Создаёт новый экземпляр класса [TiffLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |
| значения | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Получает значения.

Значение: значения тега.

**Returns:**
long[] - значения.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


Устанавливает значения.

Значение: значения тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long[] | значения. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Получает контейнер значений.

**Returns:**
com.aspose.ms.System.Array - контейнер значений.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Возвращает тип тега.

Значение: тип тега.

**Returns:**
int - тип тега.
### getValue() {#getValue--}
```
public Object getValue()
```


Получает значение, содержащееся в этом типе данных.

**Returns:**
java.lang.Object - значение, которое содержит этот тип данных.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Устанавливает значение, содержащееся в этом типе данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | значение, которое содержит этот тип данных. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Получает размер элемента.

**Returns:**
byte - размер элемента.
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
