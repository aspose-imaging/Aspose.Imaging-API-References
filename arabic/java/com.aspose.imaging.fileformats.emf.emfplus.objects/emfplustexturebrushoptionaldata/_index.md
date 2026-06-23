---
title: "EmfPlusTextureBrushOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusTextureBrushOptionalData يحدد بيانات اختيارية لفرشاة النسيج."
type: docs
weight: 78
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

كائن EmfPlusTextureBrushOptionalData يحدد بيانات اختيارية لفرشاة النسيج.

ملاحظة كل حقل في هذا الكائن اختياري وقد لا يكون موجودًا في حقل OptionalData لكائن EmfPlusTextureBrushData (القسم 2.2.2.45)، اعتمادًا على أعلام BrushData (القسم 2.1.2.1) المحددة في حقل BrushDataFlags الخاص به. على الرغم من أنه ليس عمليًا تمثيل كل تركيبة محتملة من الحقول الموجودة أو الغائبة، يحدد هذا القسم ترتيبها النسبي في الكائن. المسؤول عن التنفيذ هو المسؤول عن تحديد الحقول الموجودة فعليًا في سجل الميتافايل المعطى، وعن فك ترميز البيانات لكل حقل على حدة وبشكل مناسب.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز لفرشاة النسيج. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز لفرشاة النسيج. |
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


يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز لفرشاة النسيج. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusTextureBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز لفرشاة النسيج. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusTextureBrushData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. يجب أن يكون هذا الحقل موجودًا إذا كان حجم سجل EmfPlusObject (القسم 2.3.5.1) الذي يعرّف هذه فرشاة النسيج كبيرًا بما يكفي لاستيعاب كائن EmfPlusImage بالإضافة إلى الحقول المطلوبة لكائن EmfPlusTextureBrushData وربما كائن EmfPlusTransformMatrix.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. يجب أن يكون هذا الحقل موجودًا إذا كان حجم سجل EmfPlusObject (القسم 2.3.5.1) الذي يعرّف هذه فرشاة النسيج كبيرًا بما يكفي لاستيعاب كائن EmfPlusImage بالإضافة إلى الحقول المطلوبة لكائن EmfPlusTextureBrushData وربما كائن EmfPlusTransformMatrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

