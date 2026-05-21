---
title: "TiffASCIIType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع tiff ascii."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

نوع tiff ascii.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | ينشئ مثيلاً جديداً من الفئة `TiffASCIIType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | يحصل أو يضبط النص. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط النص. |
| [getCount()](#getCount--) | يحصل على عدد العناصر. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


ينشئ مثيلاً جديداً من الفئة `TiffASCIIType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getText() {#getText--}
```
public String getText()
```


يحصل أو يضبط النص.

**Returns:**
java.lang.String - النص.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يحصل أو يضبط النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | النص. |

### getCount() {#getCount--}
```
public long getCount()
```


يحصل على عدد العناصر.

**Returns:**
long - عدد العناصر.
### getTagType() {#getTagType--}
```
public int getTagType()
```


يحصل على نوع العلامة.

**Returns:**
int - نوع الوسم.
### getValue() {#getValue--}
```
public Object getValue()
```


يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات.

**Returns:**
java.lang.Object - القيمة.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات.

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
