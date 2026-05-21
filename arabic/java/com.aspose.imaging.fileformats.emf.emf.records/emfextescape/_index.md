---
title: "EmfExtEscape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_EXTESCAPE يمرّر معلومات عشوائية إلى برنامج تشغيل الطابعة."
type: docs
weight: 53
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfExtEscape extends EmfEscapeRecordType
```

سجل EMR\_EXTESCAPE يمرّر معلومات عشوائية إلى برنامج تشغيل الطابعة. الهدف هو أن هذه المعلومات لا تؤدي إلى تنفيذ أي رسم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExtEscape(EmfRecord source)](#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfExtEscape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCjIn()](#getCjIn--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
| [setCjIn(int value)](#setCjIn-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
| [getData()](#getData--) | يحصل أو يعيّن البيانات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن البيانات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
### EmfExtEscape(EmfRecord source) {#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtEscape(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfExtEscape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن البيانات التي يجب تمريرها إلى برنامج تشغيل الطابعة. يجب أن تكون هناك بايتات cjIn متاحة.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن البيانات التي يجب تمريرها إلى برنامج تشغيل الطابعة. يجب أن تكون هناك بايتات cjIn متاحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

