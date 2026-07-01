---
title: "EmfPlusTranslateWorldTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusTranslateWorldTransform ينفذ ترجمة على تحويل مساحة العالم الحالية."
type: docs
weight: 72
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusTranslateWorldTransform ينفذ ترجمة على تحويل مساحة العالم الحالية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusTranslateWorldTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. |
| [getDx()](#getDx--) | يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد المسافة الأفقية. |
| [setDx(float value)](#setDx-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد المسافة الأفقية. |
| [getDy()](#getDy--) | يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد قيمة المسافة العمودية. |
| [setDy(float value)](#setDy-float-) | يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد قيمة المسافة العمودية. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusTranslateWorldTransform`.

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
### getDx() {#getDx--}
```
public float getDx()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد المسافة الأفقية. يتم إجراء الترجمة بإنشاء مصفوفة تحويل عالمية جديدة من حقلي dx و dy.

القيمة: dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد المسافة الأفقية. يتم إجراء الترجمة بإنشاء مصفوفة تحويل عالمية جديدة من حقلي dx و dy.

القيمة: dx.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد قيمة المسافة العمودية.

القيمة: dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


يحصل أو يعيّن قيمة عائمة 32‑بت تُحدد قيمة المسافة العمودية.

القيمة: dy.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

