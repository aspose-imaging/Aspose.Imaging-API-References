---
title: "EmfChord"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_CHORD يحدد وترًا وهو منطقة محصورة بتقاطع قطع ناقص ومقطع خط يُسمى القاطع."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfchord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfChord extends EmfDrawingRecordType
```

السجل EMR\_CHORD يحدد وترًا، وهو منطقة محصورة بتقاطع قطع ناقص ومقطع خط يُسمى القاطع. يُرسم الوتر باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfChord(EmfRecord source)](#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfChord`. |
| [EmfChord()](#EmfChord--) | يُنشئ مثيلًا جديدًا من الفئة `EmfChord`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط شاملة-شاملة. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط شاملة-شاملة. |
| [getStart()](#getStart--) | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف بداية الوتر. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف بداية الوتر. |
| [getEnd()](#getEnd--) | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف نهاية الوتر. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف نهاية الوتر. |
### EmfChord(EmfRecord source) {#EmfChord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfChord(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfChord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfChord() {#EmfChord--}
```
public EmfChord()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfChord`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط شاملة-شاملة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط شاملة-شاملة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


يحصل أو يعيّن كائن WMF PointL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف بداية الوتر.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


يحصل أو يعيّن كائن WMF PointL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف بداية الوتر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


يحصل أو يعيّن كائن WMF PointL بحجم 64 بت يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف نهاية الوتر.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


يحصل أو يعيّن كائن WMF PointL بحجم 64 بت يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تُعرّف نهاية الوتر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

