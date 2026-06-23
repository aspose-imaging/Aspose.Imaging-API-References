---
title: "EmfRectangle"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_RECTANGLE يرسم مستطيلًا."
type: docs
weight: 107
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

سجل EMR\_RECTANGLE يرسم مستطيلًا. يتم تحديد حدود المستطيل باستخدام القلم الحالي وتعبئته باستخدام الفرشاة الحالية.

الموضع الحالي لا يُستخدم ولا يُحدَّث بواسطة Rectangle. إذا تم استخدام قلم PS\_NULL، فإن أبعاد المستطيل تكون أقل ببيكسل واحد في الارتفاع وأقل ببيكسل واحد في العرض.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfRectangle`. |
| [EmfRectangle()](#EmfRectangle--) | ينشئ مثيلاً جديدًا من الفئة `EmfRectangle`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBox()](#getBox--) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الشامل-الشامل للرسم. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي يحدد المستطيل الشامل-الشامل للرسم. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfRectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


ينشئ مثيلاً جديدًا من الفئة `EmfRectangle`.

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

