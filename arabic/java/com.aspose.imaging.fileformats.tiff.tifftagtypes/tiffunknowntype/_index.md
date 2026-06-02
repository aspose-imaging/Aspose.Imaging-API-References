---
title: "TiffUnknownType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع TIFF غير معروف."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffUnknownType extends TiffDataType
```

نوع TIFF غير معروف. في حال عدم القدرة على التعرف على علامة TIFF يتم إنشاء هذا النوع.

لاحظ أن `TiffUnknownType` لا يتم تسلسله مرة أخرى إلى الدفق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)](#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-) | ينشئ مثيلاً جديدًا من الفئة `TiffUnknownType`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد العناصر. |
| [getOffsetOrValue()](#getOffsetOrValue--) | يحصل على قيمة الإزاحة لبيانات إضافية أو القيمة نفسها في حال كان العد 1. |
| [getStream()](#getStream--) | يحصل على الدفق لقراءة البيانات الإضافية منه. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | يحصل على حجم قيمة العلامة الإضافية بالبايت (في حال عدم قدرة العلامة على احتواء القيمة الكاملة). |
| [getValue()](#getValue--) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات الوسم الإضافية. |
| [toString()](#toString--) | يعيد `System.String` التي تمثل هذا المثيل. |
### TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue) {#TiffUnknownType-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-int-int-long-long-}
```
public TiffUnknownType(TiffStreamReader stream, int tagType, int tagId, long count, long offsetOrValue)
```


ينشئ مثيلاً جديدًا من الفئة `TiffUnknownType`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | الدفق للقراءة منه. |
| tagType | int | نوع العلامة. |
| tagId | int | معرف العلامة. |
| count | long | قيمة العد. |
| offsetOrValue | long | الإزاحة أو القيمة. |

### getCount() {#getCount--}
```
public long getCount()
```


يحصل على عدد العناصر.

القيمة: عدد العناصر.

**Returns:**
long
### getOffsetOrValue() {#getOffsetOrValue--}
```
public long getOffsetOrValue()
```


يحصل على قيمة الإزاحة لبيانات إضافية أو القيمة نفسها في حال كان العد 1.

القيمة: الإزاحة أو القيمة.

**Returns:**
long
### getStream() {#getStream--}
```
public TiffStreamReader getStream()
```


يحصل على الدفق لقراءة البيانات الإضافية منه.

القيمة: الدفق لقراءة البيانات منه.

**Returns:**
[TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader)
### getTagType() {#getTagType--}
```
public int getTagType()
```


يحصل على نوع العلامة.

القيمة: نوع العلامة.

**Returns:**
int
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


يحصل على حجم قيمة العلامة الإضافية بالبايت (في حال عدم قدرة العلامة على احتواء القيمة الكاملة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sizeOfTagValue | byte | حجم قيمة الوسم: 4 أو 8 لـ BigTiff. |

**Returns:**
long - حجم البيانات الإضافية بالبايت.
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
### toString() {#toString--}
```
public String toString()
```


يعيد `System.String` التي تمثل هذا المثيل.

**Returns:**
java.lang.String - `System.String` يمثل هذا المثيل.
