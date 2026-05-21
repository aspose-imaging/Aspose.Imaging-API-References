---
title: "EmfGlsRecord"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_GLSRECORD يحدد دالة OpenGL."
type: docs
weight: 64
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

السجل EMR\_GLSRECORD يحدد دالة OpenGL.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا من الفئة `EmfGlsRecord`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCbData()](#getCbData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت. |
| [getData()](#getData--) | يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


يُنشئ مثيلاً جديدًا من الفئة `EmfGlsRecord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت. إذا كان هذا القيمة صفرًا، لا يتم إرفاق أي بيانات بهذا السجل.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم حقل Data بالبايت. إذا كان هذا القيمة صفرًا، لا يتم إرفاق أي بيانات بهذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

