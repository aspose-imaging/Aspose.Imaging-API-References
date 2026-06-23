---
title: "EmfFrameRgn"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_FRAMERGN يرسم حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة."
type: docs
weight: 62
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

السجل EMR\_FRAMERGN يرسم حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديداً من الفئة `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | ينشئ مثيلاً جديداً من الفئة [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL بسعة 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL بسعة 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي. |
| [getRgnDataSize()](#getRgnDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| [getIhBrush()](#getIhBrush--) | يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد فهرس جدول كائنات الفرشاة EMF. |
| [setIhBrush(int value)](#setIhBrush-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد فهرس جدول كائنات الفرشاة EMF. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية. |
| [getRgnData()](#getRgnData--) | يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


ينشئ مثيلاً جديداً من الفئة `EmfFrameRgn`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


ينشئ مثيلاً جديداً من الفئة [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL بسعة 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL بسعة 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الحدّي.

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


يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد فهرس جدول كائنات الفرشاة EMF.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع بسعة 32 بت يحدد فهرس جدول كائنات الفرشاة EMF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


يحصل أو يعيّن مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

