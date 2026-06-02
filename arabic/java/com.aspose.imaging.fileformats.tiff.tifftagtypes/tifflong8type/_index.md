---
title: "TiffLong8Type"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع Tiff unsigned 64-bit."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifflong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public class TiffLong8Type extends TiffCommonArrayType
```

نوع Tiff unsigned 64-bit.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffLong8Type(int tagId)](#TiffLong8Type-int-) | ينشئ مثيلًا جديدًا من الفئة [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tifflong8type). |
| [TiffLong8Type(int tagId, long[] values)](#TiffLong8Type-int-long---) | ينشئ مثيلًا جديدًا من الفئة [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tifflong8type). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل على القيم. |
| [setValues(long[] value)](#setValues-long---) | يضبط القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يعيّن القيمة التي يحتويها هذا النوع من البيانات. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffLong8Type(int tagId) {#TiffLong8Type-int-}
```
public TiffLong8Type(int tagId)
```


ينشئ مثيلًا جديدًا من الفئة [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tifflong8type).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### TiffLong8Type(int tagId, long[] values) {#TiffLong8Type-int-long---}
```
public TiffLong8Type(int tagId, long[] values)
```


ينشئ مثيلًا جديدًا من الفئة [TiffLong8Type](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tifflong8type).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |
| القيم | long[] |  |

### getValues() {#getValues--}
```
public final long[] getValues()
```


يحصل على القيم.

القيمة: قيم العلامة.

**Returns:**
long[] - القيم.
### setValues(long[] value) {#setValues-long---}
```
public final void setValues(long[] value)
```


يضبط القيم.

القيمة: قيم العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long[] | القيم. |

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

القيمة: نوع العلامة.

**Returns:**
int - نوع العلامة.
### getValue() {#getValue--}
```
public Object getValue()
```


يحصل على القيمة التي يحتويها هذا النوع من البيانات.

**Returns:**
java.lang.Object - القيمة التي يحتويها هذا النوع من البيانات.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


يعيّن القيمة التي يحتويها هذا النوع من البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Object | القيمة التي يحتويها هذا النوع من البيانات. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


يحصل على حجم العنصر.

**Returns:**
byte - حجم العنصر.
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
