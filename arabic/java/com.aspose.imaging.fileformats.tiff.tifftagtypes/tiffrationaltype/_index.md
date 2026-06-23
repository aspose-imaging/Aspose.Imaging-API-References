---
title: "TiffRationalType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع TIFF Rational."
type: docs
weight: 19
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffRationalType extends TiffCommonArrayType
```

نوع TIFF Rational.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffRationalType(int tagId)](#TiffRationalType-int-) | ينشئ مثلاً جديداً من الفئة `TiffRationalType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل أو يعيّن القيم. |
| [setValues(TiffRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يعيّن القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات العلامة الإضافية. |
### TiffRationalType(int tagId) {#TiffRationalType-int-}
```
public TiffRationalType(int tagId)
```


ينشئ مثلاً جديداً من الفئة `TiffRationalType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public TiffRational[] getValues()
```


يحصل أو يعيّن القيم.

القيمة: القيم.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setValues(TiffRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setValues(TiffRational[] value)
```


يحصل أو يعيّن القيم.

القيمة: القيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

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
