---
title: "EmfCommentMultiFormats"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_COMMENT_MULTIFORMATS يحدد صورة بأشكال رسومية متعددة."
type: docs
weight: 30
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

سجل EMR_COMMENT_MULTIFORMATS يحدد صورة بأكثر من تنسيق رسومي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُهيئ نسخة جديدة من الفئة `EmfCommentMultiFormats`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج، بالإحداثيات المنطقية. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج، بالإحداثيات المنطقية. |
| [getAFormats()](#getAFormats--) | يحصل أو يعيّن مصفوفة بطول CountFormats من صيغ الرسومات، المحددة بواسطة كائنات EmrFormat (القسم 2.2.4)، بترتيب الأولوية. |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | يحصل أو يعيّن مصفوفة بطول CountFormats من صيغ الرسومات، المحددة بواسطة كائنات EmrFormat (القسم 2.2.4)، بترتيب الأولوية. |
| [getFormatData()](#getFormatData--) | يحصل أو يعيّن مصفوفة بطول متغيّر من البايتات لبيانات الصورة لجميع صيغ الرسومات الموجودة في هذا السجل. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | يحصل أو يعيّن مصفوفة بطول متغيّر من البايتات لبيانات الصورة لجميع صيغ الرسومات الموجودة في هذا السجل. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


يُهيئ نسخة جديدة من الفئة `EmfCommentMultiFormats`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج، بالإحداثيات المنطقية.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الناتج، بالإحداثيات المنطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


يحصل أو يعيّن مصفوفة بطول CountFormats من صيغ الرسومات، المحددة بواسطة كائنات EmrFormat (القسم 2.2.4)، بترتيب الأولوية.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


يحصل أو يعيّن مصفوفة بطول CountFormats من صيغ الرسومات، المحددة بواسطة كائنات EmrFormat (القسم 2.2.4)، بترتيب الأولوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


يحصل أو يعيّن مصفوفة بطول متغيّر من البايتات لبيانات الصورة لجميع صيغ الرسومات الموجودة في هذا السجل. حجم البيانات لكل صورة يُوفره حقل DataSize في كائن EmrFormat المقابل. وبالتالي، يكون الحجم الكلي لهذا الحقل هو مجموع قيم DataSize في جميع كائنات EmrFormat. صيغة الرسومات للبيانات لكل صورة تُحدد بواسطة حقل Signature في كائن EmrFormat المقابل.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


يحصل أو يعيّن مصفوفة بطول متغيّر من البايتات لبيانات الصورة لجميع صيغ الرسومات الموجودة في هذا السجل. حجم البيانات لكل صورة يُوفره حقل DataSize في كائن EmrFormat المقابل. وبالتالي، يكون الحجم الكلي لهذا الحقل هو مجموع قيم DataSize في جميع كائنات EmrFormat. صيغة الرسومات للبيانات لكل صورة تُحدد بواسطة حقل Signature في كائن EmrFormat المقابل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[][] |  |

