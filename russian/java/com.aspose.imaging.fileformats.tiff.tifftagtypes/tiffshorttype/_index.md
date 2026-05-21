---
title: "TiffShortType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff короткого типа."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffShortType extends TiffCommonArrayType
```

Тип tiff короткого типа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffShortType(int tagId)](#TiffShortType-int-) | Создаёт новый экземпляр класса `TiffShortType`. |
| [TiffShortType(int tagId, int[] values)](#TiffShortType-int-int---) | Создаёт новый экземпляр класса `TiffShortType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает или задаёт данные. |
| [setValues(int[] value)](#setValues-int---) | Получает или задаёт данные. |
| [getElementSize()](#getElementSize--) | Возвращает размер элемента в байтах. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает или задает значение, которое содержит этот тип данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение, которое содержит этот тип данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffShortType(int tagId) {#TiffShortType-int-}
```
public TiffShortType(int tagId)
```


Создаёт новый экземпляр класса `TiffShortType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### TiffShortType(int tagId, int[] values) {#TiffShortType-int-int---}
```
public TiffShortType(int tagId, int[] values)
```


Создаёт новый экземпляр класса `TiffShortType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |
| значения | int[] |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Получает или задаёт данные.

Значение: данные.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Получает или задаёт данные.

Значение: данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Возвращает размер элемента в байтах.

Значение: размер элемента в байтах.

**Returns:**
byte
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Получает контейнер значений.

Значение: контейнер значений.

**Returns:**
com.aspose.ms.System.Array
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
