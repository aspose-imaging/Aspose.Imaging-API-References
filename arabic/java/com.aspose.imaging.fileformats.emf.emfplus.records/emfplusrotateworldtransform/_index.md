---
title: "EmfPlusRotateWorldTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusRotateWorldTransform ينفّذ دورانًا على تحويل الفضاء العالمي الحالي."
type: docs
weight: 50
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusRotateWorldTransform ينفّذ دورانًا على تحويل الفضاء العالمي الحالي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلًا جديدًا للفئة `EmfPlusRotateWorldTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. |
| [getAngle()](#getAngle--) | يحصل أو يعيّن قيمة عائمة 32‑bit تحدد زاوية الدوران بالدرجات. |
| [setAngle(float value)](#setAngle-float-) | يحصل أو يعيّن قيمة عائمة 32‑bit تحدد زاوية الدوران بالدرجات. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


يُنشئ مثيلًا جديدًا للفئة `EmfPlusRotateWorldTransform`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | المصدر. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. إذا تم تعيينها، يجب أن يُضرب مصفوف التحويل بعديًا. إذا لم يتم تعيينها، يجب أن يُضرب مسبقًا.

القيمة: `true` إذا كان [post multiplied matrix]؛ وإلا `false`.

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


يحصل أو يعيّن قيمة عائمة 32‑bit تحدد زاوية الدوران بالدرجات. يتم تنفيذ العملية بإنشاء مصفوفة تحويل جديدة من المخطط التالي: --------------------------------- | sin(Angle) | cos(Angle) | 0 | | cos(Angle) | sin(Angle) | 0 | --------------------------------- الشكل 2: مصفوفة تحويل الدوران. يتم ضرب تحويل الفضاء العالمي الحالي بهذه المصفوفة، وتصبح النتيجة التحويل العالمي الحالي الجديد. يحدد حقل Flags ترتيب الضرب.

القيمة: الزاوية.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑bit تحدد زاوية الدوران بالدرجات. يتم تنفيذ العملية بإنشاء مصفوفة تحويل جديدة من المخطط التالي: --------------------------------- | sin(Angle) | cos(Angle) | 0 | | cos(Angle) | sin(Angle) | 0 | --------------------------------- الشكل 2: مصفوفة تحويل الدوران. يتم ضرب تحويل الفضاء العالمي الحالي بهذه المصفوفة، وتصبح النتيجة التحويل العالمي الحالي الجديد. يحدد حقل Flags ترتيب الضرب.

القيمة: الزاوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

