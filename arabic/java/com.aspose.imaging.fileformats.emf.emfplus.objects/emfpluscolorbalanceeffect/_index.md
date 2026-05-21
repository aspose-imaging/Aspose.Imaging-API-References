---
title: "EmfPlusColorBalanceEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن ColorBalanceEffect يحدد التعديلات على النسب النسبية للأحمر والأخضر والأزرق في الصورة."
type: docs
weight: 26
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

كائن ColorBalanceEffect يحدد تعديلات على النسب النسبية للأحمر والأخضر والأزرق في صورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأحمر في الصورة. |
| [setCyanRed(int value)](#setCyanRed-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأحمر في الصورة. |
| [getMagentaGreen()](#getMagentaGreen--) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأخضر في الصورة. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأخضر في الصورة. |
| [getYellowBlue()](#getYellowBlue--) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأزرق في الصورة. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأزرق في الصورة. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأحمر في الصورة. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100، مع التأثيرات التالية: -100 ≤ value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار الأحمر في الصورة ويجب أن يزيد مقدار السيان. 0 قيمة 0 تعني أن كميات الأحمر والسيان يجب ألا تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار الأحمر في الصورة ويجب أن يقل مقدار السيان.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأحمر في الصورة. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100، مع التأثيرات التالية: -100 ≤ value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار الأحمر في الصورة ويجب أن يزيد مقدار السيان. 0 قيمة 0 تعني أن كميات الأحمر والسيان يجب ألا تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار الأحمر في الصورة ويجب أن يقل مقدار السيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأخضر في الصورة. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100، مع التأثيرات التالية: -100 ≤ value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار الأخضر في الصورة ويجب أن يزيد مقدار الماجنتا. 0 قيمة 0 تعني أن كميات الأخضر والماجنتا يجب ألا تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار الأخضر في الصورة ويجب أن يقل مقدار الماجنتا.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأخضر في الصورة. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100، مع التأثيرات التالية: -100 ≤ value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار الأخضر في الصورة ويجب أن يزيد مقدار الماجنتا. 0 قيمة 0 تعني أن كميات الأخضر والماجنتا يجب ألا تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار الأخضر في الصورة ويجب أن يقل مقدار الماجنتا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأزرق في الصورة. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100، مع التأثيرات التالية: -100 ≤ value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار الأزرق في الصورة ويجب أن يزيد مقدار الأصفر. 0 قيمة 0 تعني أن كميات الأزرق والأصفر يجب ألا تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار الأزرق في الصورة ويجب أن يقل مقدار الأصفر.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


يحصل أو يعيّن عددًا صحيحًا موقعًا بسعة 32 بت يحدد التغيير في كمية الأزرق في الصورة. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100، مع التأثيرات التالية: -100 ≤ value < 0 كلما انخفضت القيمة، يجب أن يقل مقدار الأزرق في الصورة ويجب أن يزيد مقدار الأصفر. 0 قيمة 0 تعني أن كميات الأزرق والأصفر يجب ألا تتغير. 0 < value ≤ 100 كلما ارتفعت القيمة، يجب أن يزيد مقدار الأزرق في الصورة ويجب أن يقل مقدار الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

