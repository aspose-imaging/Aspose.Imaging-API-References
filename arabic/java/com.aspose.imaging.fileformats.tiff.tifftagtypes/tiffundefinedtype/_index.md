---
title: "TiffUndefinedType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع TIFF غير معرف."
type: docs
weight: 26
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public class TiffUndefinedType extends TiffDataType
```

نوع TIFF غير معرف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffUndefinedType(int tagId)](#TiffUndefinedType-int-) | ينشئ مثيلاً جديدًا من الفئة `TiffUndefinedType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getData()](#getData--) | يحصل أو يضبط البيانات. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يضبط البيانات. |
| [getCount()](#getCount--) | يحصل على عدد العناصر. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffUndefinedType(int tagId) {#TiffUndefinedType-int-}
```
public TiffUndefinedType(int tagId)
```


ينشئ مثيلاً جديدًا من الفئة `TiffUndefinedType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يضبط البيانات.

القيمة: البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### getCount() {#getCount--}
```
public long getCount()
```


يحصل على عدد العناصر.

القيمة: عدد العناصر.

**Returns:**
long
### getTagType() {#getTagType--}
```
public int getTagType()
```


يحصل على نوع العلامة.

القيمة: نوع العلامة.

**Returns:**
int
### getValue() {#getValue--}
```
public Object getValue()
```


يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Object |  |

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
