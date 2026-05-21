---
title: "EmfPlusTextureBrushOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائن EmfPlusTextureBrushOptionalData بيانات اختيارية لفرشاة نسيج."
type: docs
weight: 78
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

يحدد كائن EmfPlusTextureBrushOptionalData بيانات اختيارية لفرشاة نسيج.

ملاحظة كل حقل في هذا الكائن اختياري وقد لا يكون موجودًا في حقل OptionalData لكائن EmfPlusTextureBrushData (القسم 2.2.2.45)، اعتمادًا على أعلام BrushData (القسم 2.1.2.1) المحددة في حقل BrushDataFlags. على الرغم من أنه غير عملي تمثيل كل تركيبة ممكنة من الحقول الموجودة أو الغائبة، يحدد هذا القسم ترتيبها النسبي في الكائن. المسؤولية على المُنفّذ تحديد أي الحقول موجودة فعليًا في سجل الميتافايل المعطى، وفك تجميع البيانات لكل حقل على حدة وبالطريقة المناسبة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل الفضاء العالمي إلى الفضاء الجهاز للفرشاة النسيجية. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل الفضاء العالمي إلى الفضاء الجهاز للفرشاة النسيجية. |
| [getImageObject()](#getImageObject--) | يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل الفضاء العالمي إلى الفضاء الجهاز للفرشاة النسيجية. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusTextureBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل الفضاء العالمي إلى الفضاء الجهاز للفرشاة النسيجية. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusTextureBrushData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. يجب أن يكون هذا الحقل موجودًا إذا كان حجم سجل EmfPlusObject (القسم 2.3.5.1) الذي يحدد هذه الفرشاة النسيجية كبيرًا بما يكفي لاستيعاب كائن EmfPlusImage بالإضافة إلى الحقول المطلوبة لكائن EmfPlusTextureBrushData واختياريًا كائن EmfPlusTransformMatrix.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. يجب أن يكون هذا الحقل موجودًا إذا كان حجم سجل EmfPlusObject (القسم 2.3.5.1) الذي يحدد هذه الفرشاة النسيجية كبيرًا بما يكفي لاستيعاب كائن EmfPlusImage بالإضافة إلى الحقول المطلوبة لكائن EmfPlusTextureBrushData واختياريًا كائن EmfPlusTransformMatrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

