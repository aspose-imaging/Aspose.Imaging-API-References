---
title: "EmfCreateMonoBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "السجل EMR_CREATEMONOBRUSH يعرّف فرشاة نمط أحادية اللون لعمليات الرسومات."
type: docs
weight: 39
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

السجل EMR\\_CREATEMONOBRUSH يعرّف فرشاة نمط أحادية اللون لعمليات الرسومات. يتم تحديد النمط بواسطة DIB أحادي اللون.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ نسخة جديدة من الفئة `EmfCreateMonoBrush`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن فرشاة النمط الأحادي اللون في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن فرشاة النمط الأحادي اللون في جدول كائنات EMF (القسم 3.1.1.1). |
| [getUsage()](#getUsage--) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس DIB. |
| [setUsage(int value)](#setUsage-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | يحصل أو يعيّن مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


يُنشئ نسخة جديدة من الفئة `EmfCreateMonoBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | المصدر. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن فرشاة النمط الأحادي اللون في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديلّه.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن فرشاة النمط الأحادي اللون في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديلّه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس DIB. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس DIB. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


يحصل أو يعيّن مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_CREATEDIBPATTERNBRUSHPT.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_CREATEDIBPATTERNBRUSHPT.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

