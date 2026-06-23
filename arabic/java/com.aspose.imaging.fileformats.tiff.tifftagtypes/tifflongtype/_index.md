---
title: "TiffLongType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع tiff long."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflongtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffLongType extends TiffCommonArrayType
```

نوع tiff long.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffLongType(int tagId)](#TiffLongType-int-) | يقوم بإنشاء نسخة جديدة من الفئة `TiffLongType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل أو يعيّن القيم. |
| [setValues(long[] value)](#setValues-long---) | يحصل أو يعيّن القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات العلامة الإضافية. |
### TiffLongType(int tagId) {#TiffLongType-int-}
```
public TiffLongType(int tagId)
```


يقوم بإنشاء نسخة جديدة من الفئة `TiffLongType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public long[] getValues()
```


يحصل أو يعيّن القيم.

القيمة: القيم.

**Returns:**
long[]
### setValues(long[] value) {#setValues-long---}
```
public void setValues(long[] value)
```


يحصل أو يعيّن القيم.

القيمة: القيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


يحصل على حاوية القيم.

القيمة: حاوية القيم.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


يحصل على حجم العنصر بالبايت.

القيمة: حجم العنصر بالبايت.

**Returns:**
byte
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
| value | java.lang.Object |  |

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
