---
title: "EmfDrawEscape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_DRAWESCAPE يمرّر معلومات تعسفية إلى برنامج تشغيل الطابعة."
type: docs
weight: 44
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfDrawEscape extends EmfEscapeRecordType
```

سجل EMR\_DRAWESCAPE يمرّر معلومات تعسفية إلى برنامج تشغيل الطابعة. الهدف هو أن تؤدي هذه المعلومات إلى تنفيذ الرسم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfDrawEscape(EmfRecord source)](#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfDrawEscape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCjIn()](#getCjIn--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي تُمرّر إلى برنامج تشغيل الطابعة. |
| [setCjIn(int value)](#setCjIn-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي تُمرّر إلى برنامج تشغيل الطابعة. |
| [getData()](#getData--) | يحصل أو يعيّن البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. |
### EmfDrawEscape(EmfRecord source) {#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDrawEscape(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfDrawEscape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي تُمرّر إلى برنامج تشغيل الطابعة.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي تُمرّر إلى برنامج تشغيل الطابعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. يجب أن تكون هناك بايتات cjIn متاحة.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. يجب أن تكون هناك بايتات cjIn متاحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

