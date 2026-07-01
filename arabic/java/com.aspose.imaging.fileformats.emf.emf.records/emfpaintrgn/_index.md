---
title: "EmfPaintRgn"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_PAINTRGN يرسم المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل."
type: docs
weight: 80
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

سجل EMR\_PAINTRGN يرسم المنطقة المحددة باستخدام الفرشاة المحددة حاليًا في سياق جهاز التشغيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPaintRgn`. |
| [EmfPaintRgn()](#EmfPaintRgn--) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPaintRgn`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل على كائن WMF RectL بحجم 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يضبط كائن WMF RectL بحجم 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي. |
| [getRgnDataSize()](#getRgnDataSize--) | يحصل على عدد صحيح غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت. |
| [getRgnData()](#getRgnData--) | يحصل على مصفوفة بايت بطول RgnDataSize تحدد كائن RegionData (القسم 2.2.24)، بوحدات منطقية. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | يضبط مصفوفة بايت بطول RgnDataSize تحدد كائن RegionData (القسم 2.2.24)، بوحدات منطقية. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfPaintRgn`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfPaintRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل على كائن WMF RectL بحجم 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يضبط كائن WMF RectL بحجم 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


يحصل على عدد صحيح غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


يضبط عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


يحصل على مصفوفة بايت بطول RgnDataSize تحدد كائن RegionData (القسم 2.2.24)، بوحدات منطقية.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


يضبط مصفوفة بايت بطول RgnDataSize تحدد كائن RegionData (القسم 2.2.24)، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

