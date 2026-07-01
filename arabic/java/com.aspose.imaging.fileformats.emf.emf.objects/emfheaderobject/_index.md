---
title: "EmfHeaderObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن Header يحدد رأس ملف EMF الميتافايل."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

كائن Header يعرّف رأس ملف EMF التعريفي. يحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل ملف التعريف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | يُهيئ نسخة جديدة من الفئة `EmfHeaderObject`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBounds()](#getBounds--) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد الحدود المستطيلة شاملة-شاملة بوحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في ملف التعريف. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد الحدود المستطيلة شاملة-شاملة بوحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في ملف التعريف. |
| [getFrame()](#getFrame--) | يحصل أو يعيّن كائن WMF RectL الذي يحدد الأبعاد المستطيلة شاملة-شاملة، بوحدات .01 مليمتر، لمستطيل يحيط بالصورة المخزنة في ملف التعريف. |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | يحصل أو يعيّن كائن WMF RectL الذي يحدد الأبعاد المستطيلة شاملة-شاملة، بوحدات .01 مليمتر، لمستطيل يحيط بالصورة المخزنة في ملف التعريف. |
| [getRecordSignature()](#getRecordSignature--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد توقيع السجل. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد توقيع السجل. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن Version (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد قابلية التفاعل لملف EMF التعريفي. |
| [setVersion(int value)](#setVersion-int-) | يحصل أو يعيّن Version (4 بايت): عدد صحيح غير موقّع 32‑بت يحدد قابلية التفاعل لملف EMF التعريفي. |
| [getBytes()](#getBytes--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد حجم ملف التعريف بالبايت. |
| [setBytes(int value)](#setBytes-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد حجم ملف التعريف بالبايت. |
| [getRecords()](#getRecords--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد السجلات في ملف التعريف. |
| [setRecords(int value)](#setRecords-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد السجلات في ملف التعريف. |
| [getHandles()](#getHandles--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يحدد عدد كائنات الرسومات التي ستُستخدم أثناء معالجة ملف التعريف. |
| [setHandles(short value)](#setHandles-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يحدد عدد كائنات الرسومات التي ستُستخدم أثناء معالجة ملف التعريف. |
| [getReserved()](#getReserved--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يجب أن يكون 0x0000 ويجب تجاهله. |
| [setReserved(short value)](#setReserved-short-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يجب أن يكون 0x0000 ويجب تجاهله. |
| [getNDesription()](#getNDesription--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد الأحرف في المصفوفة التي تحتوي على وصف محتويات ملف التعريف. |
| [setNDesription(int value)](#setNDesription-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد الأحرف في المصفوفة التي تحتوي على وصف محتويات ملف التعريف. |
| [getOffDescription()](#getOffDescription--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد الإزاحة من بداية هذا السجل إلى المصفوفة التي تحتوي على وصف محتويات ملف التعريف. |
| [setOffDescription(int value)](#setOffDescription-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد الإزاحة من بداية هذا السجل إلى المصفوفة التي تحتوي على وصف محتويات ملف التعريف. |
| [getNPalEntries()](#getNPalEntries--) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد الإدخالات في لوحة ألوان ملف التعريف. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد الإدخالات في لوحة ألوان ملف التعريف. |
| [getDevice()](#getDevice--) | يحصل أو يعيّن كائن WMF SizeL ([MS-WMF] القسم 2.2.2.22) الذي يحدد حجم الجهاز المرجعي بالبكسل. |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | يحصل أو يعيّن كائن WMF SizeL ([MS-WMF] القسم 2.2.2.22) الذي يحدد حجم الجهاز المرجعي بالبكسل. |
| [getMillimeters()](#getMillimeters--) | يحصل أو يعيّن كائن WMF SizeL الذي يحدد حجم الجهاز المرجعي بالمليمترات. |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | يحصل أو يعيّن كائن WMF SizeL الذي يحدد حجم الجهاز المرجعي بالمليمترات. |
| [getValid()](#getValid--) | يحصل على قيمة تشير إلى ما إذا كان هذا `EmfHeaderObject` صالحًا. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


يُهيئ نسخة جديدة من الفئة `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد الحدود المستطيلة شاملة-شاملة بوحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في ملف التعريف.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد الحدود المستطيلة شاملة-شاملة بوحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في ملف التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


يحصل أو يعيّن كائن WMF RectL الذي يحدد الأبعاد المستطيلة شاملة-شاملة، بوحدات .01 مليمتر، لمستطيل يحيط بالصورة المخزنة في ملف التعريف.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


يحصل أو يعيّن كائن WMF RectL الذي يحدد الأبعاد المستطيلة شاملة-شاملة، بوحدات .01 مليمتر، لمستطيل يحيط بالصورة المخزنة في ملف التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد توقيع السجل. يجب أن يكون هذا ENHMETA\_SIGNATURE، من تعداد FormatSignature (القسم 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد توقيع السجل. يجب أن يكون هذا ENHMETA\_SIGNATURE، من تعداد FormatSignature (القسم 2.1.14).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


الحصول أو تعيين الإصدار (4 بايت): عدد صحيح غير موقع 32‑بت يحدد التوافقية لملف EMF. يجب أن يكون هذا 0x00010000

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


الحصول أو تعيين الإصدار (4 بايت): عدد صحيح غير موقع 32‑بت يحدد التوافقية لملف EMF. يجب أن يكون هذا 0x00010000

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد حجم ملف التعريف بالبايت.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد حجم ملف التعريف بالبايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد السجلات في ملف التعريف.

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد عدد السجلات في ملف التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يحدد عدد كائنات الرسومات التي ستُستخدم أثناء معالجة ملف التعريف.

**Returns:**
قصير
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يحدد عدد كائنات الرسومات التي ستُستخدم أثناء معالجة ملف التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يجب أن يكون 0x0000 ويجب تجاهله.

**Returns:**
قصير
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 16‑بت يجب أن يكون 0x0000 ويجب تجاهله.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | قصير |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد عدد الأحرف في المصفوفة التي تحتوي على وصف محتويات ملف الميتافايل. يكون هذا صفرًا إذا لم يكن هناك سلسلة وصف.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد عدد الأحرف في المصفوفة التي تحتوي على وصف محتويات ملف الميتافايل. يكون هذا صفرًا إذا لم يكن هناك سلسلة وصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد الإزاحة من بداية هذا السجل إلى المصفوفة التي تحتوي على وصف محتويات ملف التعريف.

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


يحصل أو يعيّن عددًا صحيحًا غير موقّع 32‑بت يحدد الإزاحة من بداية هذا السجل إلى المصفوفة التي تحتوي على وصف محتويات ملف التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد عدد الإدخالات في لوحة ألوان ملف الميتافايل. تقع اللوحة في سجل EMR\_EOF

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد عدد الإدخالات في لوحة ألوان ملف الميتافايل. تقع اللوحة في سجل EMR\_EOF

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


يحصل أو يعيّن كائن WMF SizeL ([MS-WMF] القسم 2.2.2.22) الذي يحدد حجم الجهاز المرجعي بالبكسل.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


يحصل أو يعيّن كائن WMF SizeL ([MS-WMF] القسم 2.2.2.22) الذي يحدد حجم الجهاز المرجعي بالبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


يحصل أو يعيّن كائن WMF SizeL الذي يحدد حجم الجهاز المرجعي بالمليمترات.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


يحصل أو يعيّن كائن WMF SizeL الذي يحدد حجم الجهاز المرجعي بالمليمترات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


يحصل على قيمة تشير إلى ما إذا كان هذا `EmfHeaderObject` صالحًا.

القيمة: `true` إذا كان صالحًا؛ وإلا `false`.

**Returns:**
boolean
