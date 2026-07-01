---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن EmfPlusLinearGradientBrushOptionalData يحدد بيانات اختيارية لفرشاة تدرج خطي."
type: docs
weight: 54
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
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
| [getBlendPattern()](#getBlendPattern--) | يحصل أو يضبط نمط دمج اختياري لفرشاة التدرج الخطي. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | يحصل أو يضبط نمط دمج اختياري لفرشاة التدرج الخطي. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | يحصل على نمط الدمج كلون مسبق. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | يحصل على نمط الدمج كعوامل دمج أفقية. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | يحصل على نمط الدمج كعوامل دمج رأسية. |
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


يحصل أو يحدد نمط دمج اختياري لفرشاة التدرج الخطي. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، أو على كائن أو كائنين EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لعلامات BrushData في EmfPlusLinearGradientBrushData والأنماط المقابلة للدمج: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


يحصل أو يحدد نمط دمج اختياري لفرشاة التدرج الخطي. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، أو على كائن أو كائنين EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. الجدول أدناه يوضح التركيبات الصالحة لعلامات BrushData في EmfPlusLinearGradientBrushData والأنماط المقابلة للدمج: EmfPlusBlendFactors

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


يحصل على نمط الدمج كلون مسبق.

القيمة: نمط الدمج كلون مسبق.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


يحصل على نمط الدمج كعوامل دمج أفقية.

القيمة: نمط الدمج كعوامل دمج أفقية.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


يحصل على نمط الدمج كعوامل دمج رأسية.

القيمة: نمط الدمج كعوامل دمج عمودية.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
