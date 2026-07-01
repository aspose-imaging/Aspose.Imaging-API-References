---
title: "EmfAngleArc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_ANGLEARC يحدد قطعة خط من قوس."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

سجل EMR\_ANGLEARC يحدد قطعة خط من قوس. يتم رسم قطعة الخط من الموضع الحالي إلى بداية القوس. يُرسم القوس على محيط دائرة ذات نصف قطر ومركز محددين. يتم تعريف طول القوس بواسطة زوايا البداية والامتداد المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfAngleArc`. |
| [EmfAngleArc()](#EmfAngleArc--) | يُنشئ نسخة جديدة من الفئة `EmfAngleArc`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCenter()](#getCenter--) | يحصل أو يضبط كائن WMF PointL 64 بت، المحدد في القسم 2.2.2.15 من [MS-WMF]، والذي يحدد الإحداثيات المنطقية لمركز الدائرة. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | يحصل أو يضبط كائن WMF PointL 64 بت، المحدد في القسم 2.2.2.15 من [MS-WMF]، والذي يحدد الإحداثيات المنطقية لمركز الدائرة. |
| [getRadius()](#getRadius--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد نصف قطر الدائرة، بوحدات منطقية. |
| [setRadius(int value)](#setRadius-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد نصف قطر الدائرة، بوحدات منطقية. |
| [getStartAngle()](#getStartAngle--) | يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية بداية القوس، بالدرجات. |
| [setStartAngle(float value)](#setStartAngle-float-) | يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية بداية القوس، بالدرجات. |
| [getSweepAngle()](#getSweepAngle--) | يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية امتداد القوس، بالدرجات. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية امتداد القوس، بالدرجات. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfAngleArc`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


يُنشئ نسخة جديدة من الفئة `EmfAngleArc`.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


يحصل أو يضبط كائن WMF PointL 64 بت، المحدد في القسم 2.2.2.15 من [MS-WMF]، والذي يحدد الإحداثيات المنطقية لمركز الدائرة.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


يحصل أو يضبط كائن WMF PointL 64 بت، المحدد في القسم 2.2.2.15 من [MS-WMF]، والذي يحدد الإحداثيات المنطقية لمركز الدائرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد نصف قطر الدائرة، بوحدات منطقية.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد نصف قطر الدائرة، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية بداية القوس، بالدرجات.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية بداية القوس، بالدرجات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية امتداد القوس، بالدرجات.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


يحصل أو يضبط عددًا عائمًا 32 بت يحدد زاوية امتداد القوس، بالدرجات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

