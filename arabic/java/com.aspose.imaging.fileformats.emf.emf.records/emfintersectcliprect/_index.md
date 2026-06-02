---
title: "EmfIntersectClipRect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_INTERSECTCLIPRECT يحدد منطقة قطع جديدة من تقاطع منطقة القطع الحالية والمستطيل المحدد."
type: docs
weight: 66
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

سجل EMR\_INTERSECTCLIPRECT يحدد منطقة قطع جديدة من تقاطع منطقة القطع الحالية والمستطيل المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfIntersectClipRect`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getClip()](#getClip--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل بوحدات منطقية. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل بوحدات منطقية. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfIntersectClipRect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل بوحدات منطقية.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

