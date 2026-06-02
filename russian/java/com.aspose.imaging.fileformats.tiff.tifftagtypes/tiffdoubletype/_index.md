---
title: "TiffDoubleType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип tiff double."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

Тип tiff double.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Создаёт новый экземпляр класса `TiffDoubleType`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getValues()](#getValues--) | Получает значения. |
| [setValues(double[] value)](#setValues-double---) | Устанавливает значения. |
| [getValuesContainer()](#getValuesContainer--) | Получает контейнер значений. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getElementSize()](#getElementSize--) | Возвращает размер элемента в байтах. |
| [getValue()](#getValue--) | Получает значение, содержащееся в этом типе данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Устанавливает значение, содержащееся в этом типе данных. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Создаёт новый экземпляр класса `TiffDoubleType`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagId | int | Идентификатор тега. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Получает значения.

**Returns:**
double[] - Значения.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Устанавливает значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double[] | Значения. |

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
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Возвращает размер элемента в байтах.

**Returns:**
byte - Размер элемента в байтах.
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
