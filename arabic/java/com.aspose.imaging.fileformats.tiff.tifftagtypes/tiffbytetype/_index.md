---
title: "TiffByteType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع tiff byte."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

نوع tiff byte.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | يقوم بإنشاء نسخة جديدة من الفئة `TiffByteType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل أو يضبط القيم. |
| [setValues(byte[] value)](#setValues-byte---) | يحصل أو يضبط القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


يقوم بإنشاء نسخة جديدة من الفئة `TiffByteType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


يحصل أو يضبط القيم.

**Returns:**
byte[] - البيانات.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


يحصل أو يضبط القيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] | البيانات. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


يحصل على حاوية القيم.

**Returns:**
com.aspose.ms.System.Array - حاوية القيم.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


يحصل على حجم العنصر بالبايت.

**Returns:**
byte - حجم العنصر بالبايت.
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
