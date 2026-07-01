---
title: "EmfPlusMultiplyWorldTransform"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل EmfPlusMultiplyWorldTransform يضرب تحويل الفضاء العالمي الحالي بمصفوفة تحويل محددة."
type: docs
weight: 41
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

سجل EmfPlusMultiplyWorldTransform يضرب تحويل الفضاء العالمي الحالي بمصفوفة تحويل محددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | يُنشئ مثيلاً جديدًا للفئة `EmfPlusMultiplyWorldTransform`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | يحصل على قيمة تشير إلى ما إذا كان [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | يحصل أو يعيّن كائن EmfPlusTransformMatrix (القسم 2.2.2.47) الذي يحدد مصفوفة الضرب. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن EmfPlusTransformMatrix (القسم 2.2.2.47) الذي يحدد مصفوفة الضرب. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


يُنشئ مثيلاً جديدًا للفئة `EmfPlusMultiplyWorldTransform`.

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
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix (القسم 2.2.2.47) الذي يحدد مصفوفة الضرب.

القيمة: بيانات المصفوفة.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix (القسم 2.2.2.47) الذي يحدد مصفوفة الضرب.

القيمة: بيانات المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

