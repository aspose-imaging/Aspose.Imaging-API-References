---
title: "EmfGlsBoundedRecord"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_GLSBOUNDEDRECORD يحدد دالة OpenGL مع مستطيل حدودي للإخراج."
type: docs
weight: 63
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

السجل EMR\_GLSBOUNDEDRECORD يحدد دالة OpenGL مع مستطيل حدود للإخراج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا للفئة `EmfGlsBoundedRecord`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا حدوديًا، بوحدات الجهاز، للإخراج الناتج عن تنفيذ دالة OpenGL. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا حدوديًا، بوحدات الجهاز، للإخراج الناتج عن تنفيذ دالة OpenGL. |
| [getCbData()](#getCbData--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت. |
| [setCbData(int value)](#setCbData-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت. |
| [getData()](#getData--) | يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL. |
| [setData(byte[] value)](#setData-byte---) | يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


يُنشئ مثيلًا جديدًا للفئة `EmfGlsBoundedRecord`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا حدوديًا، بوحدات الجهاز، للإخراج الناتج عن تنفيذ دالة OpenGL.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيلًا حدوديًا، بوحدات الجهاز، للإخراج الناتج عن تنفيذ دالة OpenGL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت. إذا كانت هذه القيمة صفرًا، لا يتم إرفاق أي بيانات بهذا السجل.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد حجم حقل Data بالبايت. إذا كانت هذه القيمة صفرًا، لا يتم إرفاق أي بيانات بهذا السجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لدالة OpenGL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

