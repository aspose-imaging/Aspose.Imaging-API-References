---
title: "EmfPlusHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusHeader يحدد بداية بيانات EMF في ملف الميتا."
type: docs
weight: 40
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

سجل EmfPlusHeader يحدد بداية بيانات EMF+ في ملف الميتا. يجب أن يكون سجل EmfPlusHeader مضمنًا في سجل EMF EMR\_COMMENT\_EMFPLUS، والذي يجب أن يكون السجل الذي يلي مباشرةً رأس EMF في ملف الميتا. يتم تحديد سجل EMR\_COMMENT\_EMFPLUS في [MS-EMF] القسم 2.3.3.2.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلًا جديدًا من الفئة `EmfPlusHeader`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDualMode()](#getDualMode--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | يحصل أو يعيّن أعلام EMF plus. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | يحصل أو يعيّن أعلام EMF plus. |
| [getLogicalDpiX()](#getLogicalDpiX--) | يحصل أو يعيّن قيمة dpi المنطقية x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | يحصل أو يعيّن قيمة dpi المنطقية x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | يحصل أو يعيّن قيمة dpi المنطقية y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | يحصل أو يعيّن قيمة dpi المنطقية y. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن الإصدار. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | يحصل أو يعيّن الإصدار. |
| [isValid()](#isValid--) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل صالحًا. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


يُنشئ مثيلًا جديدًا من الفئة `EmfPlusHeader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. إذا تم تعيينه، فإن هذه العلامة تشير إلى أن ملف الميتا هذا هو "dual-mode"، مما يعني أنه يحتوي على مجموعتين من السجلات، كل واحدة تحدد محتوى الرسومات بالكامل. إذا لم يتم تعيينه، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+، وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذه العلامة، يجب أن تكون سجلات EMF وحدها كافية لتحديد محتوى الرسومات. لاحظ أنه سواء تم تعيين علامة "dual-mode" أم لا، فإن بعض سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF+. يتم تحديد سجلات التحكم في EMF في [MS-EMF] القسم 2.3.4.

القيمة: `true` إذا كان [dual mode]؛ وإلا `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. إذا تم تعيينه، فإن هذه العلامة تشير إلى أن ملف الميتا هذا هو "dual-mode"، مما يعني أنه يحتوي على مجموعتين من السجلات، كل واحدة تحدد محتوى الرسومات بالكامل. إذا لم يتم تعيينه، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+، وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذه العلامة، يجب أن تكون سجلات EMF وحدها كافية لتحديد محتوى الرسومات. لاحظ أنه سواء تم تعيين علامة "dual-mode" أم لا، فإن بعض سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF+. يتم تحديد سجلات التحكم في EMF في [MS-EMF] القسم 2.3.4.

القيمة: `true` إذا كان [dual mode]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف الميتا تم تسجيله بسياق جهاز مرجعي لعرض الفيديو. إذا لم يتم تعيينها، تم تسجيل ملف الميتا بسياق جهاز مرجعي لطابعة.

القيمة: `true` إذا كان [video display]؛ وإلا `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف الميتا تم تسجيله بسياق جهاز مرجعي لعرض الفيديو. إذا لم يتم تعيينها، تم تسجيل ملف الميتا بسياق جهاز مرجعي لطابعة.

القيمة: `true` إذا كان [video display]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


يحصل أو يعيّن أعلام EMF plus. عدد صحيح غير موقع 32‑بت يحتوي على معلومات حول كيفية تسجيل ملف الميتا هذا. إذا تم تعيين البت الـ31 من الحقل، فإن هذه العلامة تشير إلى أن ملف الميتا تم تسجيله بسياق جهاز مرجعي لعرض الفيديو. إذا لم يتم تعيينه، تم تسجيل ملف الميتا بسياق جهاز مرجعي لطابعة.

القيمة: أعلام EMF plus.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


يحصل أو يعيّن أعلام EMF plus. عدد صحيح غير موقع 32‑بت يحتوي على معلومات حول كيفية تسجيل ملف الميتا هذا. إذا تم تعيين البت الـ31 من الحقل، فإن هذه العلامة تشير إلى أن ملف الميتا تم تسجيله بسياق جهاز مرجعي لعرض الفيديو. إذا لم يتم تعيينه، تم تسجيل ملف الميتا بسياق جهاز مرجعي لطابعة.

القيمة: أعلام EMF plus.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


يحصل أو يعيّن dpi المنطقي x. عدد صحيح غير موقع 32‑بت يحدد الدقة الأفقية التي تم تسجيل ملف الميتا بها، بوحدة بكسل لكل بوصة.

القيمة: dpi المنطقي x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


يحصل أو يعيّن dpi المنطقي x. عدد صحيح غير موقع 32‑بت يحدد الدقة الأفقية التي تم تسجيل ملف الميتا بها، بوحدة بكسل لكل بوصة.

القيمة: dpi المنطقي x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


يحصل أو يعيّن قيمة dpi y المنطقي. عدد صحيح غير موقع 32‑بت يحدد الدقة العمودية التي تم تسجيل ملف الميتا لها، بوحدات الخطوط لكل بوصة

القيمة: dpi y المنطقي.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


يحصل أو يعيّن قيمة dpi y المنطقي. عدد صحيح غير موقع 32‑بت يحدد الدقة العمودية التي تم تسجيل ملف الميتا لها، بوحدات الخطوط لكل بوصة

القيمة: dpi y المنطقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


يحصل أو يعيّن الإصدار. كائن EmfPlusGraphicsVersion (القسم 2.2.2.19) الذي يحدد نسخة رسومات نظام التشغيل التي استُخدمت لإنشاء ملف الميتا هذا.

القيمة: الإصدار.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


يحصل أو يعيّن الإصدار. كائن EmfPlusGraphicsVersion (القسم 2.2.2.19) الذي يحدد نسخة رسومات نظام التشغيل التي استُخدمت لإنشاء ملف الميتا هذا.

القيمة: الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion) |  |

### isValid() {#isValid--}
```
public boolean isValid()
```


يحصل على قيمة تشير إلى ما إذا كان هذا المثيل صالحًا.

القيمة: `true` إذا كانت هذه الحالة صالحة؛ وإلا `false`.

**Returns:**
boolean
