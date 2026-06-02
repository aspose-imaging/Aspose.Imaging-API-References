---
title: "EmfFrameRgn"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_FRAMERGN يرسم حدًا حول المنطقة المحددة باستخدام الفرشاة المحددة."
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
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يقوم بإنشاء نسخة جديدة من الفئة `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | يقوم بإنشاء نسخة جديدة من الفئة [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يضبط كائن WMF RectL 128-بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يضبط كائن WMF RectL 128-بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط. |
| [getRgnDataSize()](#getRgnDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت. |
| [getIhBrush()](#getIhBrush--) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للفرشاة. |
| [setIhBrush(int value)](#setIhBrush-int-) | يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للفرشاة. |
| [getWidth()](#getWidth--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية. |
| [getHeight()](#getHeight--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية. |
| [getRgnData()](#getRgnData--) | يحصل أو يضبط مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | يحصل أو يضبط مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


يقوم بإنشاء نسخة جديدة من الفئة `EmfFrameRgn`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


يقوم بإنشاء نسخة جديدة من الفئة [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يضبط كائن WMF RectL 128-بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يضبط كائن WMF RectL 128-بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل المحيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة، بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للفرشاة.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


يحصل أو يضبط عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع ضربة الفرشاة الأفقية، بوحدات منطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


يحصل أو يضبط مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


يحصل أو يضبط مصفوفة بايت بطول RgnDataSize التي تحدد كائن RegionData، بوحدات منطقية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

