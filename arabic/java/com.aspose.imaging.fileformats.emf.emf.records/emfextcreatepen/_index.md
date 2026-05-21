---
title: "EmfExtCreatePen"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EMR_EXTCREATEPEN يحدد قلمًا منطقيًا موسعًا لعمليات الرسومات."
type: docs
weight: 52
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

سجل EMR\_EXTCREATEPEN يحدد قلمًا منطقيًا موسعًا لعمليات الرسومات. يمكن تحديد DIB اختياري لاستخدامه كنمط الخط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreatePen`. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreatePen`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIhPen()](#getIhPen--) | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد فهرس كائن القلم المنطقي الموسع في جدول كائنات EMF (القسم 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد فهرس كائن القلم المنطقي الموسع في جدول كائنات EMF (القسم 3.1.1.1). |
| [getElp()](#getElp--) | يحصل أو يعيّن كائن LogPenEx (القسم 2.2.20) الذي يحدد قلمًا منطقيًا موسعًا مع سمات تشمل مصفوفة نمط خط اختيارية. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | يحصل أو يعيّن كائن LogPenEx (القسم 2.2.20) الذي يحدد قلمًا منطقيًا موسعًا مع سمات تشمل مصفوفة نمط خط اختيارية. |
| [getBitmapBuffer()](#getBitmapBuffer--) | يحصل أو يعيّن مخزنًا اختياريًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | يحصل أو يعيّن مخزنًا اختياريًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreatePen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | السجل. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


يُنشئ مثيلًا جديدًا من الفئة `EmfExtCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد فهرس كائن القلم المنطقي الموسع في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


يحصل أو يعيّن عدد صحيح غير موقع 32-بت يحدد فهرس كائن القلم المنطقي الموسع في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


يحصل أو يعيّن كائن LogPenEx (القسم 2.2.20) الذي يحدد قلمًا منطقيًا موسعًا مع سمات تشمل مصفوفة نمط خط اختيارية.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


يحصل أو يعيّن كائن LogPenEx (القسم 2.2.20) الذي يحدد قلمًا منطقيًا موسعًا مع سمات تشمل مصفوفة نمط خط اختيارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


يحصل أو يعيّن مخزنًا اختياريًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). ليس من الضروري أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_EXTCREATEPEN.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


يحصل أو يعيّن مخزنًا اختياريًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). ليس من الضروري أن يكون متجاورًا مع الجزء الثابت من سجل EMR\_EXTCREATEPEN.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

