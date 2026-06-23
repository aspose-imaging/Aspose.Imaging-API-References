---
title: "EmfRoundRect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_ROUNDRECT يحدد مستطيلًا بزوايا مستديرة."
type: docs
weight: 111
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

السجل EMR\_ROUNDRECT يحدد مستطيلًا بزوايا مستديرة. يُرسم المستطيل باستخدام القلم الحالي ويُملأ باستخدام الفرشاة الحالية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfRoundRect`. |
| [EmfRoundRect()](#EmfRoundRect--) | يُنشئ مثيلًا جديدًا من الفئة [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الشامل-الشامل للرسم. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الشامل-الشامل للرسم. |
| [getCorner()](#getCorner--) | يحصل أو يعيّن كائن WMF SizeL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.22، والذي يحدد العرض والارتفاع، بالإحداثيات المنطقية، للقطع الناقص المستخدم لرسم الزوايا المستديرة. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | يحصل أو يعيّن كائن WMF SizeL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.22، والذي يحدد العرض والارتفاع، بالإحداثيات المنطقية، للقطع الناقص المستخدم لرسم الزوايا المستديرة. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfRoundRect`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


يُنشئ مثيلًا جديدًا من الفئة [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect).

### getBox() {#getBox--}
```
public Rectangle getBox()
```


يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الشامل-الشامل للرسم.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الشامل-الشامل للرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


يحصل أو يعيّن كائن WMF SizeL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.22، والذي يحدد العرض والارتفاع، بالإحداثيات المنطقية، للقطع الناقص المستخدم لرسم الزوايا المستديرة.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


يحصل أو يعيّن كائن WMF SizeL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.22، والذي يحدد العرض والارتفاع، بالإحداثيات المنطقية، للقطع الناقص المستخدم لرسم الزوايا المستديرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

