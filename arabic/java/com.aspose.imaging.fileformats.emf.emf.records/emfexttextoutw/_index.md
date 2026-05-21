---
title: "EmfExtTextOutW"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_EXTTEXTOUTW يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص."
type: docs
weight: 57
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfExtTextOutW extends EmfDrawingRecordType
```

السجل EMR\_EXTTEXTOUTW يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExtTextOutW(EmfRecord source)](#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfExtTextOutW`. |
| [EmfExtTextOutW()](#EmfExtTextOutW--) | يُنشئ مثيلاً جديدًا للفئة `EmfExtTextOutW`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL (القسم [MS-WMF] 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL (القسم [MS-WMF] 2.2.2.19). |
| [getIGraphicsMode()](#getIGraphicsMode--) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد وضع الرسومات من تعداد GraphicsMode (القسم 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد وضع الرسومات من تعداد GraphicsMode (القسم 2.1.16). |
| [getExScale()](#getExScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور X لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. |
| [setExScale(float value)](#setExScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور X لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. |
| [getEyScale()](#getEyScale--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور Y لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. |
| [setEyScale(float value)](#setEyScale-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور Y لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. |
| [getWEmrText()](#getWEmrText--) | يحصل أو يعيّن كائن EmrText (القسم 2.2.5) الذي يحدد سلسلة الإخراج في أحرف Unicode UTF16-LE 16‑بت، مع سمات النص وقيم التباعد. |
| [setWEmrText(EmfText value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-) | يحصل أو يعيّن كائن EmrText (القسم 2.2.5) الذي يحدد سلسلة الإخراج في أحرف Unicode UTF16-LE 16‑بت، مع سمات النص وقيم التباعد. |
### EmfExtTextOutW(EmfRecord source) {#EmfExtTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtTextOutW(EmfRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfExtTextOutW`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### EmfExtTextOutW() {#EmfExtTextOutW--}
```
public EmfExtTextOutW()
```


يُنشئ مثيلاً جديدًا للفئة `EmfExtTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL (القسم [MS-WMF] 2.2.2.19). لا يُستخدم ويجب تجاهله عند الاستلام.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL (القسم [MS-WMF] 2.2.2.19). لا يُستخدم ويجب تجاهله عند الاستلام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد وضع الرسومات من تعداد GraphicsMode (القسم 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد وضع الرسومات من تعداد GraphicsMode (القسم 2.1.16).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور X لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب استخدام هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور X لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب استخدام هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM\_COMPATIBLE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور Y لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب استخدام هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس لتطبيقه على المحور Y لتحويل وحدات مساحة الصفحة إلى وحدات .01 مم. يجب استخدام هذا فقط إذا كان وضع الرسومات المحدد بواسطة iGraphicsMode هو GM\_COMPATIBLE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText getWEmrText()
```


يحصل أو يعيّن كائن EmrText (القسم 2.2.5) الذي يحدد سلسلة الإخراج في أحرف Unicode UTF16-LE 16‑بت، مع سمات النص وقيم التباعد.

**Returns:**
[EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext)
### setWEmrText(EmfText value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText-}
```
public void setWEmrText(EmfText value)
```


يحصل أو يعيّن كائن EmrText (القسم 2.2.5) الذي يحدد سلسلة الإخراج في أحرف Unicode UTF16-LE 16‑بت، مع سمات النص وقيم التباعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfText](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

