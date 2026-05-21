---
title: "EmfPlusHeader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusHeader يحدد بداية بيانات EMF في ملف التعريف."
type: docs
weight: 40
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusHeader extends EmfPlusControlRecordType
```

سجل EmfPlusHeader يحدد بداية بيانات EMF+ في ملف التعريف. يجب تضمين سجل EmfPlusHeader داخل سجل EMF EMR\_COMMENT\_EMFPLUS، والذي يجب أن يكون السجل الذي يلي مباشرة رأس EMF في ملف التعريف. يتم تحديد سجل EMR\_COMMENT\_EMFPLUS في القسم 2.3.3.2 من [MS-EMF].
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusHeader(EmfPlusRecord source)](#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلاً جديدًا من الفئة `EmfPlusHeader`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDualMode()](#getDualMode--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. |
| [setDualMode(boolean value)](#setDualMode-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. |
| [getVideoDisplay()](#getVideoDisplay--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. |
| [setVideoDisplay(boolean value)](#setVideoDisplay-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. |
| [getEmfPlusFlags()](#getEmfPlusFlags--) | يحصل أو يعيّن علامات EMF plus. |
| [setEmfPlusFlags(int value)](#setEmfPlusFlags-int-) | يحصل أو يعيّن علامات EMF plus. |
| [getLogicalDpiX()](#getLogicalDpiX--) | يحصل أو يعيّن قيمة الـ dpi المنطقي x. |
| [setLogicalDpiX(int value)](#setLogicalDpiX-int-) | يحصل أو يعيّن قيمة الـ dpi المنطقي x. |
| [getLogicalDpiY()](#getLogicalDpiY--) | يحصل أو يعيّن قيمة الـ dpi المنطقي y. |
| [setLogicalDpiY(int value)](#setLogicalDpiY-int-) | يحصل أو يعيّن قيمة الـ dpi المنطقي y. |
| [getVersion()](#getVersion--) | يحصل أو يعيّن الإصدار. |
| [setVersion(EmfPlusGraphicsVersion value)](#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-) | يحصل أو يعيّن الإصدار. |
| [isValid()](#isValid--) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل صالحًا. |
### EmfPlusHeader(EmfPlusRecord source) {#EmfPlusHeader-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusHeader(EmfPlusRecord source)
```


ينشئ مثيلاً جديدًا من الفئة `EmfPlusHeader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getDualMode() {#getDualMode--}
```
public boolean getDualMode()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف هذا \"dual-mode\"، مما يعني أنه يحتوي على مجموعتين من السجلات، كل منهما يحدد بالكامل محتوى الرسومات. إذا لم تُعيّن، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+، وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذه العلامة، يجب أن تكون سجلات EMF وحدها كافية لتعريف محتوى الرسومات. لاحظ أنه سواء تم تعيين علامة \"dual-mode\" أم لا، فإن بعض سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF+. يتم تحديد سجلات التحكم في EMF في القسم 2.3.4 من [MS-EMF].

القيمة: `true` إذا كان [dual mode]؛ وإلا `false`.

**Returns:**
boolean
### setDualMode(boolean value) {#setDualMode-boolean-}
```
public void setDualMode(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف هذا \"dual-mode\"، مما يعني أنه يحتوي على مجموعتين من السجلات، كل منهما يحدد بالكامل محتوى الرسومات. إذا لم تُعيّن، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+، وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذه العلامة، يجب أن تكون سجلات EMF وحدها كافية لتعريف محتوى الرسومات. لاحظ أنه سواء تم تعيين علامة \"dual-mode\" أم لا، فإن بعض سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF+. يتم تحديد سجلات التحكم في EMF في القسم 2.3.4 من [MS-EMF].

القيمة: `true` إذا كان [dual mode]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getVideoDisplay() {#getVideoDisplay--}
```
public boolean getVideoDisplay()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف تم تسجيله باستخدام سياق جهاز مرجعي لعرض الفيديو. إذا لم تُعيّن، تم تسجيل ملف التعريف باستخدام سياق جهاز مرجعي لطابعة.

القيمة: `true` إذا كان [video display]؛ وإلا `false`.

**Returns:**
boolean
### setVideoDisplay(boolean value) {#setVideoDisplay-boolean-}
```
public void setVideoDisplay(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض الفيديو. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف تم تسجيله باستخدام سياق جهاز مرجعي لعرض الفيديو. إذا لم تُعيّن، تم تسجيل ملف التعريف باستخدام سياق جهاز مرجعي لطابعة.

القيمة: `true` إذا كان [video display]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getEmfPlusFlags() {#getEmfPlusFlags--}
```
public int getEmfPlusFlags()
```


يحصل أو يعيّن علامات EMF plus. عدد صحيح غير موقع 32 بت يحتوي على معلومات حول كيفية تسجيل هذا ملف التعريف. إذا تم تعيين البت الـ31 من الحقل، فإن هذه العلامة تشير إلى أن ملف التعريف تم تسجيله باستخدام سياق جهاز مرجعي لعرض الفيديو. إذا لم تُعيّن، تم تسجيل ملف التعريف باستخدام سياق جهاز مرجعي لطابعة.

القيمة: علامات EMF plus.

**Returns:**
int
### setEmfPlusFlags(int value) {#setEmfPlusFlags-int-}
```
public void setEmfPlusFlags(int value)
```


يحصل أو يعيّن علامات EMF plus. عدد صحيح غير موقع 32 بت يحتوي على معلومات حول كيفية تسجيل هذا ملف التعريف. إذا تم تعيين البت الـ31 من الحقل، فإن هذه العلامة تشير إلى أن ملف التعريف تم تسجيله باستخدام سياق جهاز مرجعي لعرض الفيديو. إذا لم تُعيّن، تم تسجيل ملف التعريف باستخدام سياق جهاز مرجعي لطابعة.

القيمة: علامات EMF plus.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLogicalDpiX() {#getLogicalDpiX--}
```
public int getLogicalDpiX()
```


يحصل أو يعيّن الـ dpi المنطقي x. عدد صحيح غير موقع 32 بت يحدد الدقة الأفقية التي تم تسجيل ملف التعريف من أجلها، بوحدات البكسل لكل بوصة.

القيمة: الـ dpi المنطقي x.

**Returns:**
int
### setLogicalDpiX(int value) {#setLogicalDpiX-int-}
```
public void setLogicalDpiX(int value)
```


يحصل أو يعيّن الـ dpi المنطقي x. عدد صحيح غير موقع 32 بت يحدد الدقة الأفقية التي تم تسجيل ملف التعريف من أجلها، بوحدات البكسل لكل بوصة.

القيمة: الـ dpi المنطقي x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getLogicalDpiY() {#getLogicalDpiY--}
```
public int getLogicalDpiY()
```


يحصل أو يعيّن الـ dpi المنطقي y. عدد صحيح غير موقع 32 بت يحدد الدقة العمودية التي تم تسجيل ملف التعريف من أجلها، بوحدات الخطوط لكل بوصة.

القيمة: الـ dpi المنطقي y.

**Returns:**
int
### setLogicalDpiY(int value) {#setLogicalDpiY-int-}
```
public void setLogicalDpiY(int value)
```


يحصل أو يعيّن الـ dpi المنطقي y. عدد صحيح غير موقع 32 بت يحدد الدقة العمودية التي تم تسجيل ملف التعريف من أجلها، بوحدات الخطوط لكل بوصة.

القيمة: الـ dpi المنطقي y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getVersion() {#getVersion--}
```
public EmfPlusGraphicsVersion getVersion()
```


يحصل أو يعيّن الإصدار. كائن EmfPlusGraphicsVersion (القسم 2.2.2.19) يحدد إصدار رسومات نظام التشغيل الذي تم استخدامه لإنشاء هذا ملف التعريف.

القيمة: الإصدار.

**Returns:**
[EmfPlusGraphicsVersion](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion)
### setVersion(EmfPlusGraphicsVersion value) {#setVersion-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsVersion-}
```
public void setVersion(EmfPlusGraphicsVersion value)
```


يحصل أو يعيّن الإصدار. كائن EmfPlusGraphicsVersion (القسم 2.2.2.19) يحدد إصدار رسومات نظام التشغيل الذي تم استخدامه لإنشاء هذا ملف التعريف.

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

القيمة: `true` إذا كان هذا المثيل صالحًا؛ وإلا `false`.

**Returns:**
boolean
