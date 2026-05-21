---
title: "TiffFloatType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff float."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

Тип tiff float.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | Создаёт новый экземпляр класса `TiffFloatType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает значения. |
| [setValues(float[] value)](#setValues-float---) | Устанавливает значения. |
| [getElementSize()](#getElementSize--) | Возвращает размер элемента в байтах. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getValue()](#getValue--) | Получает значение, содержащееся в этом типе данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Устанавливает значение, содержащееся в этом типе данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


Создаёт новый экземпляр класса `TiffFloatType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getValues() {#getValues--}
```
public float[] getValues()
```


Получает значения.

**Returns:**
float[] - Значения.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


Устанавливает значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] | Значения. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Возвращает размер элемента в байтах.

**Returns:**
byte - Размер элемента в байтах.
### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Получает контейнер значений.

**Returns:**
com.aspose.ms.System.Array - Контейнер значений.
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


Получает значение, содержащееся в этом типе данных.

**Returns:**
java.lang.Object - значение.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Устанавливает значение, содержащееся в этом типе данных.

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
