---
title: "EmfExtFloodFill"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_EXTFLOODFILL يملأ مساحة من سطح العرض بالفرشاة الحالية"
type: docs
weight: 54
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtFloodFill extends EmfDrawingRecordType
```

السجل EMR\_EXTFLOODFILL يملأ مساحة من سطح العرض بالفرشاة الحالية
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExtFloodFill(EmfRecord source)](#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfExtFloodFill`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStart()](#getStart--) | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15)، الذي يحدد الإحداثيات بوحدات منطقية حيث يبدأ التعبئة. |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15)، الذي يحدد الإحداثيات بوحدات منطقية حيث يبدأ التعبئة. |
| [getArgb32Color()](#getArgb32Color--) | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8)، الذي يُستخدم مع FloodFillMode لتحديد المنطقة التي سيتم ملئها. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8)، الذي يُستخدم مع FloodFillMode لتحديد المنطقة التي سيتم ملئها. |
| [getFloodFillMode()](#getFloodFillMode--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام قيمة اللون لتحديد المنطقة لعملية ملء الفيض. |
| [setFloodFillMode(int value)](#setFloodFillMode-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام قيمة اللون لتحديد المنطقة لعملية ملء الفيض. |
### EmfExtFloodFill(EmfRecord source) {#EmfExtFloodFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtFloodFill(EmfRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfExtFloodFill`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getStart() {#getStart--}
```
public Point getStart()
```


يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15)، الذي يحدد الإحداثيات بوحدات منطقية حيث يبدأ التعبئة.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


يحصل أو يضبط كائن WMF PointL ([MS-WMF] القسم 2.2.2.15)، الذي يحدد الإحداثيات بوحدات منطقية حيث يبدأ التعبئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8)، الذي يُستخدم مع FloodFillMode لتحديد المنطقة التي سيتم ملئها.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8)، الذي يُستخدم مع FloodFillMode لتحديد المنطقة التي سيتم ملئها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getFloodFillMode() {#getFloodFillMode--}
```
public int getFloodFillMode()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام قيمة اللون لتحديد المنطقة لعملية ملء الفيض. يجب أن تكون القيمة ضمن تعداد FloodFill (القسم 2.1.13).

**Returns:**
int
### setFloodFillMode(int value) {#setFloodFillMode-int-}
```
public void setFloodFillMode(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد كيفية استخدام قيمة اللون لتحديد المنطقة لعملية ملء الفيض. يجب أن تكون القيمة ضمن تعداد FloodFill (القسم 2.1.13).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

