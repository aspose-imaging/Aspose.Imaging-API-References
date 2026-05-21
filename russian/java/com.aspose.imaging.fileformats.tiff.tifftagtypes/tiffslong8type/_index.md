---
title: "TiffSLong8Type"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип Tiff unsigned 64-bit."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

Тип Tiff unsigned 64-bit.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | Создаёт новый экземпляр класса [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type). |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает значения. |
| [setValues(long[] values)](#setValues-long---) | Устанавливает значения. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает значение, содержащееся в этом типе данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает значение, содержащееся в этом типе данных. |
| [getElementSize()](#getElementSize--) | Получает размер элемента. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


Создаёт новый экземпляр класса [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Получает значения.

Значение: значения тега.

**Returns:**
long[] - значения.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


Устанавливает значения.

Значение: значения тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значения | long[] | Значения. |

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


Получает значение, содержащееся в этом типе данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение, которое содержит этот тип данных. |

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
