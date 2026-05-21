---
title: "TiffSLong8Type"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع Tiff unsigned 64-bit."
type: docs
weight: 21
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff.tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

نوع Tiff unsigned 64-bit.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | يقوم بإنشاء نسخة جديدة من [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) الفئة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValues()](#getValues--) | يحصل على القيم. |
| [setValues(long[] values)](#setValues-long---) | يضبط القيم. |
| [getValuesContainer()](#getValuesContainer--) | يحصل على حاوية القيم. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getValue()](#getValue--) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


يقوم بإنشاء نسخة جديدة من [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type) الفئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagId | int | معرف العلامة. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


يحصل على القيم.

القيمة: قيم العلامة.

**Returns:**
long[] - القيم.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


يضبط القيم.

القيمة: قيم العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيم | long[] | القيم. |

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


يحصل على القيمة التي يحتويها هذا النوع من البيانات.

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
