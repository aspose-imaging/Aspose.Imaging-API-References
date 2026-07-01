---
title: "EmfExtSelectClipRgn"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_EXTSELECTCLIPRGN يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد."
type: docs
weight: 55
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

سجل EMR\_EXTSELECTCLIPRGN يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | ينشئ مثيلاً جديدًا من الفئة `EmfExtSelectClipRgn`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة بالبايت. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة بالبايت. |
| [getRegionMode()](#getRegionMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المنطقة. |
| [setRegionMode(int value)](#setRegionMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المنطقة. |
| [getRgnData()](#getRgnData--) | يحصل أو يعيّن مصفوفة بطول RgnDataSize من البايتات تحدد كائن RegionData بوحدات منطقية. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | يحصل أو يعيّن مصفوفة بطول RgnDataSize من البايتات تحدد كائن RegionData بوحدات منطقية. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfExtSelectClipRgn`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


ينشئ مثيلاً جديدًا من الفئة `EmfExtSelectClipRgn`.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة بالبايت.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المنطقة. يجب أن تكون القيمة ضمن تعداد RegionMode (القسم 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المنطقة. يجب أن تكون القيمة ضمن تعداد RegionMode (القسم 2.1.29).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


يحصل أو يعيّن مصفوفة من البايت بطول RgnDataSize تحدد كائن RegionData بالوحدات المنطقية. إذا كان RegionMode هو RGN\_COPY، يمكن حذف هذه البيانات ويجب أن يتم تعيين منطقة القص إلى منطقة القص الافتراضية (NULL).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


يحصل أو يعيّن مصفوفة من البايت بطول RgnDataSize تحدد كائن RegionData بالوحدات المنطقية. إذا كان RegionMode هو RGN\_COPY، يمكن حذف هذه البيانات ويجب أن يتم تعيين منطقة القص إلى منطقة القص الافتراضية (NULL).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

