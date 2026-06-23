---
title: "EmfPlusScaleWorldTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusScaleWorldTransform ينفّذ تحجيمًا على تحويل الفضاء العالمي الحالي."
type: docs
weight: 52
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusScaleWorldTransform ينفّذ تحجيمًا على تحويل الفضاء العالمي الحالي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusScaleWorldTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. |
| [getSx()](#getSx--) | يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم الأفقي. |
| [setSx(float value)](#setSx-float-) | يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم الأفقي. |
| [getSy()](#getSy--) | يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم العمودي. |
| [setSy(float value)](#setSy-float-) | يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم العمودي. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


ينشئ مثيلًا جديدًا من الفئة `EmfPlusScaleWorldTransform`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


يحصل على قيمة تُظهر ما إذا كان [post multiplied matrix]. إذا تم ضبطه، يجب أن تُضرب مصفوفة التحويل بعديًا. إذا لم يُضبط، يجب أن تُضرب مسبقًا.

القيمة: `true` إذا كان [post multiplied matrix]؛ وإلا `false`.

**Returns:**
boolean
### getSx() {#getSx--}
```
public float getSx()
```


يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم الأفقي. يتم إجراء التحجيم بإنشاء مصفوفة تحويل جديدة من قيم الحقول Sx و Sy، كما هو موضح في الجدول التالي. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- الشكل 3: مصفوفة تحويل التحجيم

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم الأفقي. يتم إجراء التحجيم بإنشاء مصفوفة تحويل جديدة من قيم الحقول Sx و Sy، كما هو موضح في الجدول التالي. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- الشكل 3: مصفوفة تحويل التحجيم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم العمودي.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


يحصل أو يضبط قيمة عائمة 32-بت تحدد عامل التحجيم العمودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

