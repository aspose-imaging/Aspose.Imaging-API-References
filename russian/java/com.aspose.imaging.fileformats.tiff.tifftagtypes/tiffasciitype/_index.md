---
title: "TiffASCIIType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff ascii."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

Тип tiff ascii.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Инициализирует новый экземпляр класса `TiffASCIIType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | Получает или задает текст. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает текст. |
| [getCount()](#getCount--) | Возвращает количество элементов. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает или задает значение, которое содержит этот тип данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение, которое содержит этот тип данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Инициализирует новый экземпляр класса `TiffASCIIType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getText() {#getText--}
```
public String getText()
```


Получает или задает текст.

**Returns:**
java.lang.String - Текст.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Получает или задает текст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Текст. |

### getCount() {#getCount--}
```
public long getCount()
```


Возвращает количество элементов.

**Returns:**
long - количество элементов.
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
