---
title: "EmfFillRgn"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_FILLRGN يملأ المنطقة المحددة باستخدام الفرشاة المحددة."
type: docs
weight: 59
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

السجل EMR\_FILLRGN يملأ المنطقة المحددة باستخدام الفرشاة المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | ينشئ مثيلاً جديداً من الفئة `EmfFillRgn`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي. |
| [getRgnDataSize()](#getRgnDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| [getIhBrush()](#getIhBrush--) | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد فهرس جدول كائنات EMF للفرشاة لملء المنطقة. |
| [setIhBrush(int value)](#setIhBrush-int-) | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد فهرس جدول كائنات EMF للفرشاة لملء المنطقة. |
| [getRgnData()](#getRgnData--) | يحصل أو يضبط مصفوفة بطول RgnDataSize من البايتات التي تحتوي على كائن RegionData (القسم 2.2.24). |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | يحصل أو يضبط مصفوفة بطول RgnDataSize من البايتات التي تحتوي على كائن RegionData (القسم 2.2.24). |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfFillRgn`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


ينشئ مثيلاً جديداً من الفئة `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد فهرس جدول كائنات EMF للفرشاة لملء المنطقة.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد فهرس جدول كائنات EMF للفرشاة لملء المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


يحصل أو يضبط مصفوفة بطول RgnDataSize من البايتات التي تحتوي على كائن RegionData (القسم 2.2.24).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


يحصل أو يضبط مصفوفة بطول RgnDataSize من البايتات التي تحتوي على كائن RegionData (القسم 2.2.24).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

