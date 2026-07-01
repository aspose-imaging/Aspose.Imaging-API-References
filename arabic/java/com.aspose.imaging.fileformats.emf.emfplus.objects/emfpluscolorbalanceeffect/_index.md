---
title: "EmfPlusColorBalanceEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن ColorBalanceEffect يحدد التعديلات على النسب النسبية للأحمر والأخضر والأزرق في الصورة."
type: docs
weight: 26
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

كائن ColorBalanceEffect يحدد تعديلات على النسب النسبية للأحمر والأخضر والأزرق في الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأحمر في الصورة. |
| [setCyanRed(int value)](#setCyanRed-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأحمر في الصورة. |
| [getMagentaGreen()](#getMagentaGreen--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأخضر في الصورة. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأخضر في الصورة. |
| [getYellowBlue()](#getYellowBlue--) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأزرق في الصورة. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأزرق في الصورة. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأحمر في الصورة. يجب أن تكون هذه القيمة ضمن النطاق -100 إلى 100، مع التأثيرات التالية: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار اللون الأحمر في الصورة ويجب أن يزيد مقدار اللون السيان. 0 قيمة 0 تحدد أن كميات اللون الأحمر والسين لا يجب أن تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار اللون الأحمر في الصورة ويجب أن يقل مقدار اللون السيان.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأحمر في الصورة. يجب أن تكون هذه القيمة ضمن النطاق -100 إلى 100، مع التأثيرات التالية: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار اللون الأحمر في الصورة ويجب أن يزيد مقدار اللون السيان. 0 قيمة 0 تحدد أن كميات اللون الأحمر والسين لا يجب أن تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار اللون الأحمر في الصورة ويجب أن يقل مقدار اللون السيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأخضر في الصورة. يجب أن تكون هذه القيمة ضمن النطاق -100 إلى 100، مع التأثيرات التالية: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار اللون الأخضر في الصورة ويجب أن يزيد مقدار اللون الماجنتا. 0 قيمة 0 تحدد أن كميات اللون الأخضر والماجنتا لا يجب أن تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار اللون الأخضر في الصورة ويجب أن يقل مقدار اللون الماجنتا.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأخضر في الصورة. يجب أن تكون هذه القيمة ضمن النطاق -100 إلى 100، مع التأثيرات التالية: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار اللون الأخضر في الصورة ويجب أن يزيد مقدار اللون الماجنتا. 0 قيمة 0 تحدد أن كميات اللون الأخضر والماجنتا لا يجب أن تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار اللون الأخضر في الصورة ويجب أن يقل مقدار اللون الماجنتا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأزرق في الصورة. يجب أن تكون هذه القيمة ضمن النطاق -100 إلى 100، مع التأثيرات التالية: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار اللون الأزرق في الصورة ويجب أن يزيد مقدار اللون الأصفر. 0 قيمة 0 تحدد أن كميات اللون الأزرق والأصفر لا يجب أن تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار اللون الأزرق في الصورة ويجب أن يقل مقدار اللون الأصفر.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


يحصل أو يضبط عددًا صحيحًا موقعًا 32‑بت يحدد تغييرًا في مقدار اللون الأزرق في الصورة. يجب أن تكون هذه القيمة ضمن النطاق -100 إلى 100، مع التأثيرات التالية: -100 \u2264 value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار اللون الأزرق في الصورة ويجب أن يزيد مقدار اللون الأصفر. 0 قيمة 0 تحدد أن كميات اللون الأزرق والأصفر لا يجب أن تتغير. 0 < value \u2264 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار اللون الأزرق في الصورة ويجب أن يقل مقدار اللون الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

