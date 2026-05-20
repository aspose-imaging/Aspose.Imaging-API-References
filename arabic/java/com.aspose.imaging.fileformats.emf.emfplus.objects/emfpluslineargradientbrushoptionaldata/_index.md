---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusLinearGradientBrushOptionalData يحدد بيانات اختيارية لفرشاة تدرج خطي."
type: docs
weight: 54
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

كائن EmfPlusLinearGradientBrushOptionalData يحدد بيانات اختيارية لفرشاة تدرج خطي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة التدرج الخطي. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة التدرج الخطي. |
| [getBlendPattern()](#getBlendPattern--) | يحصل أو يضبط نمط مزج اختياري لفرشاة التدرج الخطي. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | يحصل أو يضبط نمط مزج اختياري لفرشاة التدرج الخطي. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | يحصل على نمط المزج كألوان مسبقة. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | يحصل على نمط المزج كعوامل مزج أفقية. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | يحصل على نمط المزج كعوامل مزج عمودية. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة التدرج الخطي. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusLinearGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


يحصل أو يضبط كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة التدرج الخطي. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusLinearGradientBrushData.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


يحصل أو يضبط نمط مزج اختياري لفرشاة التدرج الخطي. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، أو على كائن أو كائنين EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لأعلام BrushData في EmfPlusLinearGradientBrushData وأنماط المزج المقابلة: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


يحصل أو يضبط نمط مزج اختياري لفرشاة التدرج الخطي. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، أو على كائن أو كائنين EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لأعلام BrushData في EmfPlusLinearGradientBrushData وأنماط المزج المقابلة: EmfPlusBlendFactors

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


يحصل على نمط المزج كألوان مسبقة.

القيمة: نمط المزج كألوان مسبقة.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


يحصل على نمط المزج كعوامل مزج أفقية.

القيمة: نمط المزج كعوامل مزج أفقية.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


يحصل على نمط المزج كعوامل مزج عمودية.

القيمة: نمط المزج كعوامل مزج عمودية.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
