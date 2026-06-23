---
title: "TiffDataType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع بيانات TIFF."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

نوع بيانات TIFF.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getElementSize()](#getElementSize--) | يحصل على حجم العنصر بالبايت. |
| [getDataSize()](#getDataSize--) | يحصل على حجم قيمة العلامة. |
| [getCount()](#getCount--) | يحصل على عدد العناصر. |
| [getId()](#getId--) | يحصل على معرف العلامة كرقم. |
| [getTagId()](#getTagId--) | يحصل على معرف العلامة. |
| [getTagType()](#getTagType--) | يحصل على نوع العلامة. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | يحصل على حجم البيانات محاذاة على حد 4 بايت (int) أو 8 بايت (long). |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | يحصل على حجم قيمة العلامة الإضافية بالبايت (في حال عدم قدرة العلامة على احتواء القيمة الكاملة). |
| [getValue()](#getValue--) | يحصل على القيمة التي يحتويها هذا النوع من البيانات. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| [isValid()](#isValid--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | يقرأ بيانات العلامة. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | يقارن النسخة الحالية مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كانت النسخة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | ينفذ استنساخًا عميقًا لهذه النسخة. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | يكتب بيانات العلامة. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | يكتب بيانات العلامة الإضافية. |
| [toString()](#toString--) | يعيد `System.String` الذي يمثل هذه الحالة. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


يحصل على حجم العنصر بالبايت.

**Returns:**
byte - حجم العنصر بالبايت.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


يحصل على حجم قيمة العلامة.

**Returns:**
long - حجم قيمة العلامة.
### getCount() {#getCount--}
```
public abstract long getCount()
```


يحصل على عدد العناصر.

القيمة: عدد العناصر.

**Returns:**
long - عدد العناصر.
### getId() {#getId--}
```
public final int getId()
```


يحصل على معرف العلامة كرقم.

**Returns:**
int - معرف العلامة كرقم.
### getTagId() {#getTagId--}
```
public int getTagId()
```


يحصل على معرف العلامة.

**Returns:**
int - معرف العلامة.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


يحصل على نوع العلامة.

**Returns:**
int - نوع العلامة.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


يحصل على حجم البيانات محاذاة على حد 4 بايت (int) أو 8 بايت (long).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sizeOfTagValue | byte | حجم قيمة العلامة. |

**Returns:**
long - حجم البيانات المتراصة بالبايت.
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
public abstract Object getValue()
```


يحصل على القيمة التي يحتويها هذا النوع من البيانات.

**Returns:**
java.lang.Object - القيمة.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


يضبط القيمة التي يحتويها هذا النوع من البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object | القيمة. |

### isValid() {#isValid--}
```
public boolean isValid()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات قد يتم حفظها. لا يمكن تخزين الوسم غير الصالح.

**Returns:**
boolean - `true` إذا كانت بيانات الوسم صالحة؛ وإلا `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


يقرأ بيانات العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | دفق البيانات. |
| position | long | موضع الوسم. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


يقارن النسخة الحالية مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كانت النسخة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | كائن للمقارنة مع هذه الحالة. |

**Returns:**
int - عدد صحيح موقع 32-بت يشير إلى الترتيب النسبي للكائنات التي يتم مقارنتها. قيمة الإرجاع لها المعاني التالية: القيمة المعنى أقل من الصفر هذه الحالة أصغر من `obj`. صفر هذه الحالة مساوية لـ `obj`. أكبر من الصفر هذه الحالة أكبر من `obj`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


ينفذ استنساخًا عميقًا لهذه النسخة.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


يكتب بيانات العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | دفق البيانات. |
| additionalDataOffset | long | الإزاحة لكتابة البيانات الإضافية إليها. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


يكتب بيانات العلامة الإضافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | دفق البيانات. |

**Returns:**
long - عدد البايتات الفعلية المكتوبة.
### toString() {#toString--}
```
public String toString()
```


يعيد `System.String` الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - `System.String` الذي يمثل هذه الحالة.
