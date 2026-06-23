---
title: "EmfCommentBeginGroup"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COMMENT_BEGINGROUP يحدد بداية مجموعة من سجلات الرسم."
type: docs
weight: 26
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

سجل EMR\_COMMENT\_BEGINGROUP يحدد بداية مجموعة من سجلات الرسم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfCommentBeginGroup`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRectangle()](#getRectangle--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج بالإحداثيات المنطقية. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج بالإحداثيات المنطقية. |
| [getNDescription()](#getNDescription--) | يحصل أو يعيّن عدد أحرف Unicode في سلسلة الوصف الاختيارية التي تلي. |
| [setNDescription(int value)](#setNDescription-int-) | يحصل أو يعيّن عدد أحرف Unicode في سلسلة الوصف الاختيارية التي تلي. |
| [getDescription()](#getDescription--) | يحصل أو يعيّن سلسلة Unicode اختيارية منتهية بـ null تصف مجموعة السجلات هذه. |
| [setDescription(String value)](#setDescription-java.lang.String-) | يحصل أو يعيّن سلسلة Unicode اختيارية منتهية بـ null تصف مجموعة السجلات هذه. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfCommentBeginGroup`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج بالإحداثيات المنطقية.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج بالإحداثيات المنطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


يحصل أو يعيّن عدد أحرف Unicode في سلسلة الوصف الاختيارية التي تلي.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


يحصل أو يعيّن عدد أحرف Unicode في سلسلة الوصف الاختيارية التي تلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


يحصل أو يعيّن سلسلة Unicode اختيارية منتهية بـ null تصف مجموعة السجلات هذه.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


يحصل أو يعيّن سلسلة Unicode اختيارية منتهية بـ null تصف مجموعة السجلات هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

