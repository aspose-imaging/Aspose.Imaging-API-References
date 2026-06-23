---
title: "TiffSByteType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع tiff signed byte."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffSByteType extends TiffCommonArrayType
```

نوع tiff signed byte.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffSByteType(int tagId)](#TiffSByteType-int-) | يقوم بإنشاء نسخة جديدة من الفئة `TiffSByteType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل أو يعيّن القيم. |
| [setValues(byte[] value)](#setValues-byte---) | يحصل أو يعيّن القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات العلامة الإضافية. |
### TiffSByteType(int tagId) {#TiffSByteType-int-}
```
public TiffSByteType(int tagId)
```


يقوم بإنشاء نسخة جديدة من الفئة `TiffSByteType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


يحصل أو يعيّن القيم.

القيمة: البيانات.

**Returns:**
byte[]
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


يحصل أو يعيّن القيم.

القيمة: البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

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
