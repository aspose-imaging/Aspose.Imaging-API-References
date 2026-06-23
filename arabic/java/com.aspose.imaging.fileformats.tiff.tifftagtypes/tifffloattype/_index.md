---
title: "TiffFloatType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع tiff float."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

نوع tiff float.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | يقوم بإنشاء نسخة جديدة من الفئة `TiffFloatType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل على القيم. |
| [setValues(float[] value)](#setValues-float---) | يضبط القيم. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات العلامة الإضافية. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


يقوم بإنشاء نسخة جديدة من الفئة `TiffFloatType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public float[] getValues()
```


يحصل على القيم.

**Returns:**
float[] - القيم.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


يضبط القيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] | القيم. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


يحصل على حجم العنصر بالبايت.

**Returns:**
byte - حجم العنصر بالبايت.
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
int - نوع العلامة.
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


يضبط القيمة التي يحتويها هذا النوع من البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


يكتب بيانات العلامة الإضافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | دفق البيانات. |

**Returns:**
long - عدد البايتات الفعلية المكتوبة.
