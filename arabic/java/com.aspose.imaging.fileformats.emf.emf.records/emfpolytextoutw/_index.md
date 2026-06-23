---
title: "EmfPolyTextOutW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_POLYTEXTOUTW يرسم سلسلة أو أكثر من النصوص Unicode باستخدام الخط الحالي وألوان النص."
type: docs
weight: 98
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

سجل EMR\_POLYTEXTOUTW يرسم سلسلة نصية Unicode واحدة أو أكثر باستخدام الخط الحالي وألوان النص.

يتم تحديد الخط وألوان النص المستخدمة للإخراج عبر خصائص في الحالة الحالية لسياق جهاز التشغيل. يجب محاكاة EMR\_POLYTEXTOUTW بسلسلة من سجلات EMR\_EXTTEXTOUTW (القسم 2.3.5.7)، سجل واحد لكل سلسلة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfPolyTextOutW`. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | يُنشئ مثيلًا جديدًا من الفئة `EmfPolyTextOutW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد المستطيل الحدودي بوحدات الجهاز. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد المستطيل الحدودي بوحدات الجهاز. |
| [getIGraphicsMode()](#getIGraphicsMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات الحالي، من تعداد GraphicsMode (القسم 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات الحالي، من تعداد GraphicsMode (القسم 2.1.16). |
| [getExScale()](#getExScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE. |
| [getWEmrText()](#getWEmrText--) | يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج بترميزات Unicode 16‑بت UTF16-LE، مع سمات النص وقيم التباعد. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج بترميزات Unicode 16‑بت UTF16-LE، مع سمات النص وقيم التباعد. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPolyTextOutW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPolyTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد المستطيل الحدودي بوحدات الجهاز.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد المستطيل الحدودي بوحدات الجهاز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات الحالي، من تعداد GraphicsMode (القسم 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات الحالي، من تعداد GraphicsMode (القسم 2.1.16).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM\_COMPATIBLE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج بترميزات Unicode 16‑بت UTF16-LE، مع سمات النص وقيم التباعد. يتم تحديد عدد كائنات EmrText بواسطة cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج بترميزات Unicode 16‑بت UTF16-LE، مع سمات النص وقيم التباعد. يتم تحديد عدد كائنات EmrText بواسطة cStrings.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

