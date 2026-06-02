---
title: "EmfArc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_ARC يحدد قوسًا بيضاويًا."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArc extends EmfDrawingRecordType
```

سجل EMR\_ARC يحدد قوسًا بيضاويًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfArc(EmfRecord source)](#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfArc`. |
| [EmfArc()](#EmfArc--) | ينشئ مثيلًا جديدًا من الفئة `EmfArc`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي شاملًا شاملًا. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي شاملًا شاملًا. |
| [getStart()](#getStart--) | يحصل أو يعيّن كائن WMF PointL 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة بدء القوس، بوحدات منطقية. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | يحصل أو يعيّن كائن WMF PointL 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة بدء القوس، بوحدات منطقية. |
| [getEnd()](#getEnd--) | يحصل أو يعيّن كائن WMF PointL 64 بت يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة النهاية للقوس، بوحدات منطقية. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | يحصل أو يعيّن كائن WMF PointL 64 بت يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة النهاية للقوس، بوحدات منطقية. |
### EmfArc(EmfRecord source) {#EmfArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArc(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfArc`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfArc() {#EmfArc--}
```
public EmfArc()
```


ينشئ مثيلًا جديدًا من الفئة `EmfArc`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي شاملًا شاملًا.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي شاملًا شاملًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


يحصل أو يعيّن كائن WMF PointL 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة بدء القوس، بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


يحصل أو يعيّن كائن WMF PointL 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة بدء القوس، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


يحصل أو يعيّن كائن WMF PointL 64 بت يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة النهاية للقوس، بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


يحصل أو يعيّن كائن WMF PointL 64 بت يحدد إحداثيات نقطة النهاية للخط الشعاعي الذي يحدد نقطة النهاية للقوس، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

