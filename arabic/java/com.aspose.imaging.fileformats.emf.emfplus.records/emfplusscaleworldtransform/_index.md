---
title: "EmfPlusScaleWorldTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يسجل EmfPlusScaleWorldTransform ينفّذ تحجيمًا على تحويل الفضاء العالمي الحالي."
type: docs
weight: 52
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

يسجل EmfPlusScaleWorldTransform ينفّذ تحجيمًا على تحويل الفضاء العالمي الحالي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | ينشئ نسخة جديدة من الفئة `EmfPlusScaleWorldTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. |
| [getSx()](#getSx--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس الأفقي. |
| [setSx(float value)](#setSx-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس الأفقي. |
| [getSy()](#getSy--) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس العمودي. |
| [setSy(float value)](#setSy-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس العمودي. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


ينشئ نسخة جديدة من الفئة `EmfPlusScaleWorldTransform`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


يحصل على قيمة تشير إلى ما إذا كانت [مصفوفة مضروبة لاحقًا]. إذا تم التعيين، يجب أن تُضرب مصفوفة التحويل لاحقًا. إذا لم يتم التعيين، يجب أن تُضرب مسبقًا.

القيمة: `true` إذا كان [post multiplied matrix]؛ وإلا `false`.

**Returns:**
boolean
### getSx() {#getSx--}
```
public float getSx()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس الأفقي. يتم إجراء التحجيم بإنشاء مصفوفة تحويل جديدة من قيم الحقول Sx وSy، كما هو موضح في الجدول التالي. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- الشكل 3: مصفوفة تحويل المقياس

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس الأفقي. يتم إجراء التحجيم بإنشاء مصفوفة تحويل جديدة من قيم الحقول Sx وSy، كما هو موضح في الجدول التالي. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- الشكل 3: مصفوفة تحويل المقياس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس العمودي.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تحدد عامل المقياس العمودي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

