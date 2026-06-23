---
title: "EmfArcTo"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_ARCTO يحدد قوسًا إهليلجيًا."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

سجل EMR\_ARCTO يحدد قوسًا إهليلجيًا. يعيد تعيين الموضع الحالي إلى نقطة النهاية للقوس.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا للفئة `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | ينشئ مثيلًا جديدًا للفئة `EmfArcTo`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي. |
| [getStart()](#getStart--) | الحصول أو تعيين كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | الحصول أو تعيين كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية. |
| [getEnd()](#getEnd--) | الحصول أو تعيين كائن WMF PointL 64‑بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | الحصول أو تعيين كائن WMF PointL 64‑بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


ينشئ مثيلًا جديدًا للفئة `EmfArcTo`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


ينشئ مثيلًا جديدًا للفئة `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


الحصول أو تعيين كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


الحصول أو تعيين كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


الحصول أو تعيين كائن WMF PointL 64‑بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


الحصول أو تعيين كائن WMF PointL 64‑بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

