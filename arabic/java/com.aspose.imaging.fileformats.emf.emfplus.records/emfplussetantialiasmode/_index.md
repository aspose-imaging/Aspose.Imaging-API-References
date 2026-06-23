---
title: "EmfPlusSetAntiAliasMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusSetAntiAliasMode يحدد وضعية مضاد التعرجات لإخراج النص."
type: docs
weight: 54
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

سجل EmfPlusSetAntiAliasMode يحدد وضعية مضاد التعرجات لإخراج النص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusSetAntiAliasMode`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | يحصل أو يضبط وضع التنعيم. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | يحصل أو يضبط وضع التنعيم. |
| [getAntiAliasing()](#getAntiAliasing--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusSetAntiAliasMode`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


يحصل أو يضبط وضع التنعيم. (7 بت): قيمة وضع التنعيم، من تعداد SmoothingMode (القسم 2.1.1.28).

القيمة: وضع التنعيم.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


يحصل أو يضبط وضع التنعيم. (7 بت): قيمة وضع التنعيم، من تعداد SmoothingMode (القسم 2.1.1.28).

القيمة: وضع التنعيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [anti aliasing]. إذا تم الضبط، يجب تنفيذ anti-aliasing. إذا لم يتم الضبط، يجب عدم تنفيذ anti-aliasing.

القيمة: `true` إذا كان [anti aliasing]؛ وإلا `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان [anti aliasing]. إذا تم الضبط، يجب تنفيذ anti-aliasing. إذا لم يتم الضبط، يجب عدم تنفيذ anti-aliasing.

القيمة: `true` إذا كان [anti aliasing]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

