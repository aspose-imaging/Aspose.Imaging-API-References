---
title: "EmfExcludeClipRect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_EXCLUDECLIPRECT يحدد منطقة قطع جديدة تتكون من منطقة القطع الحالية مطروحًا منها المستطيل المحدد."
type: docs
weight: 50
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

السجل EMR\_EXCLUDECLIPRECT يحدد منطقة قطع جديدة تتكون من منطقة القطع الحالية مطروحًا منها المستطيل المحدد. لاحظ أن الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfExcludeClipRect`. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | ينشئ مثيلًا جديدًا من الفئة `EmfExcludeClipRect`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getClip()](#getClip--) | يحصل على كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل القطع بوحدات منطقية. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل القطع بوحدات منطقية. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfExcludeClipRect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


ينشئ مثيلًا جديدًا من الفئة `EmfExcludeClipRect`.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


يحصل على كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل القطع بوحدات منطقية.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل القطع بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

