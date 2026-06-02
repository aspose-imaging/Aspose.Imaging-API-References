---
title: "EmfPie"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_PIE يحدد شريحة على شكل فطيرة محصورة بتقاطع إهليلج وخطين شعاعيين."
type: docs
weight: 82
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

سجل EMR\_PIE يحدد شريحة على شكل فطيرة محصورة بتقاطع إهليلج وخطين شعاعيين. يتم رسم حدود الفطيرة باستخدام القلم الحالي وتعبئتها باستخدام الفرشاة الحالية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPie` class. |
| [EmfPie()](#EmfPie--) | ينشئ مثيلًا جديدًا من الفئة `EmfPie` class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي شاملًا شاملًا. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي شاملًا شاملًا. |
| [getStart()](#getStart--) | يحصل أو يعيّن كائنات WMF PointL 64-بت، المحددة في [MS-WMF] القسم 2.2.2.15، والتي تحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الأول. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | يحصل أو يعيّن كائنات WMF PointL 64-بت، المحددة في [MS-WMF] القسم 2.2.2.15، والتي تحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الأول. |
| [getEnd()](#getEnd--) | يحصل أو يعيّن كائن PointL 64-بت الذي يحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الثاني. |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | يحصل أو يعيّن كائن PointL 64-بت الذي يحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الثاني. |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPie` class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


ينشئ مثيلًا جديدًا من الفئة `EmfPie` class.

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


يحصل أو يعيّن كائنات WMF PointL 64-بت، المحددة في [MS-WMF] القسم 2.2.2.15، والتي تحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الأول.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


يحصل أو يعيّن كائنات WMF PointL 64-بت، المحددة في [MS-WMF] القسم 2.2.2.15، والتي تحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


يحصل أو يعيّن كائن PointL 64-بت الذي يحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الثاني.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


يحصل أو يعيّن كائن PointL 64-بت الذي يحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الثاني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

