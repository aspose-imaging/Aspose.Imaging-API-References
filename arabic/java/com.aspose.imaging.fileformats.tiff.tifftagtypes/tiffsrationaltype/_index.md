---
title: "TiffSRationalType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع TIFF الموقّع النسبي."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffSRationalType extends TiffCommonArrayType
```

نوع TIFF الموقّع النسبي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffSRationalType(int tagId)](#TiffSRationalType-int-) | يقوم بإنشاء نسخة جديدة من الفئة `TiffSRationalType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل أو يضبط القيم. |
| [setValues(TiffSRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---) | يحصل أو يضبط القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffSRationalType(int tagId) {#TiffSRationalType-int-}
```
public TiffSRationalType(int tagId)
```


يقوم بإنشاء نسخة جديدة من الفئة `TiffSRationalType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public TiffSRational[] getValues()
```


يحصل أو يضبط القيم.

القيمة: القيم.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[]
### setValues(TiffSRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void setValues(TiffSRational[] value)
```


يحصل أو يضبط القيم.

القيمة: القيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

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
