---
title: "TiffDoubleType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع tiff double."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

نوع tiff double.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | ينشئ مثيلًا جديدًا من الفئة `TiffDoubleType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل على القيم. |
| [setValues(double[] value)](#setValues-double---) | يضبط القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getValue()](#getValue--) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يعيّن القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


ينشئ مثيلًا جديدًا من الفئة `TiffDoubleType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public double[] getValues()
```


يحصل على القيم.

**Returns:**
double[] - القيم.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


يضبط القيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] | القيم. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


يحصل على حاوية القيم.

**Returns:**
com.aspose.ms.System.Array - حاوية القيم.
### getTagType() {#getTagType--}
```
public int getTagType()
```


يحصل على نوع العلامة.

**Returns:**
int - نوع الوسم.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


يحصل على حجم العنصر بالبايت.

**Returns:**
byte - حجم العنصر بالبايت.
### getValue() {#getValue--}
```
public Object getValue()
```


يحصل على القيمة التي يحتويها هذا النوع من البيانات.

**Returns:**
java.lang.Object - القيمة.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


يعيّن القيمة التي يحتويها هذا النوع من البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Object | القيمة. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


يكتب بيانات الوسم الإضافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | دفق البيانات. |

**Returns:**
long - عدد البايتات الفعلي المكتوبة.
