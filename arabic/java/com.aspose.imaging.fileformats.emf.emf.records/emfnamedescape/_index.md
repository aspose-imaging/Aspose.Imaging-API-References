---
title: "EmfNamedEscape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل MR_NAMEDESCAPE يمرر معلومات تعسفية إلى برنامج تشغيل طابعة محدد."
type: docs
weight: 75
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

سجل MR\_NAMEDESCAPE يمرر معلومات عشوائية إلى برنامج تشغيل طابعة محدد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfNamedEscape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات في حقل DriverName. |
| [setCjDriver(int value)](#setCjDriver-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات في حقل DriverName. |
| [getCjIn()](#getCjIn--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
| [setCjIn(int value)](#setCjIn-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة. |
| [getDriverName()](#getDriverName--) | يحصل أو يضبط سلسلة من أحرف Unicode 16‑بت تحدد اسم برنامج تشغيل الطابعة الذي سيتلقى البيانات. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | يحصل أو يضبط سلسلة من أحرف Unicode 16‑بت تحدد اسم برنامج تشغيل الطابعة الذي سيتلقى البيانات. |
| [getData()](#getData--) | يحصل أو يضبط البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يضبط البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfNamedEscape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد عدد البايتات في حقل DriverName. يجب أن تكون هذه القيمة عددًا زوجيًا.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد عدد البايتات في حقل DriverName. يجب أن تكون هذه القيمة عددًا زوجيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات التي يجب تمريرها إلى برنامج تشغيل الطابعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


يحصل أو يضبط سلسلة من أحرف Unicode 16‑بت تحدد اسم برنامج تشغيل الطابعة الذي سيتلقى البيانات. يجب أن يكون طول هذه القيمة cjDriver بايت، ويجب أن تنتهي بحرف null.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


يحصل أو يضبط سلسلة من أحرف Unicode 16‑بت تحدد اسم برنامج تشغيل الطابعة الذي سيتلقى البيانات. يجب أن يكون طول هذه القيمة cjDriver بايت، ويجب أن تنتهي بحرف null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يضبط البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. يجب أن تكون هناك cjIn بايت متاحة.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يضبط البيانات التي تُمرّر إلى برنامج تشغيل الطابعة. يجب أن تكون هناك cjIn بايت متاحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

