---
title: "EmfArcTo"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_ARCTO يحدد قوسًا بيضاويًا."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfarcto/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfArcTo extends EmfDrawingRecordType
```

السجل EMR\_ARCTO يحدد قوسًا بيضاويًا. يعيد تعيين الموضع الحالي إلى نقطة النهاية للقوس.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfArcTo(EmfRecord source)](#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfArcTo`. |
| [EmfArcTo()](#EmfArcTo--) | يُنشئ مثيلًا جديدًا من الفئة `EmfArcTo`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط. |
| [getStart()](#getStart--) | يحصل أو يضبط كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | يحصل أو يضبط كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية. |
| [getEnd()](#getEnd--) | يحصل أو يعيّن كائن WMF PointL 64-بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | يحصل أو يعيّن كائن WMF PointL 64-بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية. |
### EmfArcTo(EmfRecord source) {#EmfArcTo-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfArcTo(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfArcTo`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfArcTo() {#EmfArcTo--}
```
public EmfArcTo()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfArcTo`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


يحصل أو يضبط كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


يحصل أو يضبط كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


يحصل أو يعيّن كائن WMF PointL 64-بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


يحصل أو يعيّن كائن WMF PointL 64-بت يحدد إحداثيات نقطة النهاية الشعاعية الثانية، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

