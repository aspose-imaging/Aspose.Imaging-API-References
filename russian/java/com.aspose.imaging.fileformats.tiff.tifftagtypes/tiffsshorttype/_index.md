---
title: "TiffSShortType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff со знаковым коротким типом."
type: docs
weight: 24
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsshorttype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffSShortType extends TiffCommonArrayType
```

Тип tiff со знаковым коротким типом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffSShortType(int tagId)](#TiffSShortType-int-) | Инициализирует новый экземпляр класса `TiffSShortType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает или задает значения. |
| [setValues(short[] value)](#setValues-short---) | Получает или задает значения. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getElementSize()](#getElementSize--) | Возвращает размер элемента в байтах. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает или задает значение, которое содержит этот тип данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение, которое содержит этот тип данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffSShortType(int tagId) {#TiffSShortType-int-}
```
public TiffSShortType(int tagId)
```


Инициализирует новый экземпляр класса `TiffSShortType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getValues() {#getValues--}
```
public short[] getValues()
```


Получает или задает значения.

Значение: значения.

**Returns:**
short[]
### setValues(short[] value) {#setValues-short---}
```
public void setValues(short[] value)
```


Получает или задает значения.

Значение: значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Получает контейнер значений.

Значение: контейнер значений.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Возвращает размер элемента в байтах.

Значение: размер элемента в байтах.

**Returns:**
byte
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
