---
title: "EmfSelectObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SELECTOBJECT يضيف كائن رسومي إلى سياق جهاز تشغيل ملف الميتا الحالي."
type: docs
weight: 116
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

سجل EMR\_SELECTOBJECT يضيف كائن رسومي إلى سياق جهاز تشغيل ملف الميتا الحالي. يتم تحديد الكائن إما بواسطة فهرسه في جدول كائنات EMF (القسم 3.1.1.1) أو بقيمته من تعداد StockObject (القسم 2.1.31).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfSelectObject`. |
| [EmfSelectObject()](#EmfSelectObject--) | ينشئ مثيلاً جديداً من الفئة `EmfSelectObject`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد إما فهرس كائن رسومي في جدول كائنات EMF أو فهرس كائن مخزون من تعداد `Consts.EmfStockObject`. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد إما فهرس كائن رسومي في جدول كائنات EMF أو فهرس كائن مخزون من تعداد `Consts.EmfStockObject`. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


ينشئ مثيلاً جديداً من الفئة `EmfSelectObject`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | السجل. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


ينشئ مثيلاً جديداً من الفئة `EmfSelectObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد إما فهرس كائن رسومي في جدول كائنات EMF أو فهرس كائن مخزون من تعداد `Consts.EmfStockObject`.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد إما فهرس كائن رسومي في جدول كائنات EMF أو فهرس كائن مخزون من تعداد `Consts.EmfStockObject`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

