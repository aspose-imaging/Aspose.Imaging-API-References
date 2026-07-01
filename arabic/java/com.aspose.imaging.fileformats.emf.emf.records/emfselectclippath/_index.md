---
title: "EmfSelectClipPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_SELECTCLIPPATH يحدد المسار الحالي كمنطقة تقليم لسياق جهاز التشغيل، حيث يجمع المنطقة الجديدة مع أي منطقة تقليم موجودة باستخدام الوضع المحدد."
type: docs
weight: 115
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

السجل EMR\_SELECTCLIPPATH يحدد المسار الحالي كمنطقة قص لسياق جهاز التشغيل، ويجمع المنطقة الجديدة مع أي منطقة قص موجودة باستخدام الوضع المحدد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfSelectClipPath`. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | ينشئ مثيلًا جديدًا من الفئة `EmfSelectClipPath`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المسار. |
| [setRegionMode(int value)](#setRegionMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المسار. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfSelectClipPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


ينشئ مثيلًا جديدًا من الفئة `EmfSelectClipPath`.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المسار. يجب أن تكون القيمة ضمن تعداد RegionMode (القسم 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المسار. يجب أن تكون القيمة ضمن تعداد RegionMode (القسم 2.1.29).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

