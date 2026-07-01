---
title: "EmfPlusLevelsEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LevelsEffect يحدد التعديلات على الإضاءات والظلال المتوسطة والظلال في الصورة."
type: docs
weight: 51
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusobject)، [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging/fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

كائن LevelsEffect يحدد تعديلات على الإضاءات، النغمات المتوسطة، والظلال في صورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHighlight()](#getHighlight--) | الحصول أو تعيين يحدد مقدار إضاءة الإضاءات في الصورة. |
| [setHighlight(int value)](#setHighlight-int-) | الحصول أو تعيين يحدد مقدار إضاءة الإضاءات في الصورة. |
| [getMidTone()](#getMidTone--) | الحصول أو تعيين يحدد مقدار إضاءة أو تعتيم الظلال المتوسطة في الصورة. |
| [setMidTone(int value)](#setMidTone-int-) | الحصول أو تعيين يحدد مقدار إضاءة أو تعتيم الظلال المتوسطة في الصورة. |
| [getShadow()](#getShadow--) | الحصول أو تعيين يحدد مقدار تعتيم الظلال في الصورة. |
| [setShadow(int value)](#setShadow-int-) | الحصول أو تعيين يحدد مقدار تعتيم الظلال في الصورة. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


الحصول أو تعيين يحدد مقدار إضاءة الإضاءات في الصورة. قيم قنوات اللون في الطرف العلوي من نطاق الشدة تُعدل أكثر من القيم القريبة من الوسط أو الطرف السفلي، مما يعني إمكانية إضاءة الصورة دون فقدان التباين بين الأجزاء الداكنة. 0 \\u2264 value < يحدد أن الإضاءات التي تتجاوز نسبة الشدة هذا الحد SHOULD 100 تُزاد. 100 يحدد أن الإضاءات MUST NOT تتغير.

القيمة: الإضاءة.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


الحصول أو تعيين يحدد مقدار إضاءة الإضاءات في الصورة. قيم قنوات اللون في الطرف العلوي من نطاق الشدة تُعدل أكثر من القيم القريبة من الوسط أو الطرف السفلي، مما يعني إمكانية إضاءة الصورة دون فقدان التباين بين الأجزاء الداكنة. 0 \\u2264 value < يحدد أن الإضاءات التي تتجاوز نسبة الشدة هذا الحد SHOULD 100 تُزاد. 100 يحدد أن الإضاءات MUST NOT تتغير.

القيمة: الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


الحصول أو تعيين يحدد مقدار إضاءة أو تعتيم الظلال المتوسطة في الصورة. قيم قنوات اللون في وسط نطاق الشدة تُعدل أكثر من القيم القريبة من الطرفين العلوي أو السفلي، مما يعني إمكانية إضاءة أو تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر ظلاماً وإضاءةً. -100 \\u2264 value < 0 يحدد أن الظلال المتوسطة تُصبح أغمق. 0 يحدد أن الظلال المتوسطة MUST NOT تتغير. 0 < value \\u2264 100 يحدد أن الظلال المتوسطة تُصبح أفتح.

القيمة: الظل المتوسط.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


الحصول أو تعيين يحدد مقدار إضاءة أو تعتيم الظلال المتوسطة في الصورة. قيم قنوات اللون في وسط نطاق الشدة تُعدل أكثر من القيم القريبة من الطرفين العلوي أو السفلي، مما يعني إمكانية إضاءة أو تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر ظلاماً وإضاءةً. -100 \\u2264 value < 0 يحدد أن الظلال المتوسطة تُصبح أغمق. 0 يحدد أن الظلال المتوسطة MUST NOT تتغير. 0 < value \\u2264 100 يحدد أن الظلال المتوسطة تُصبح أفتح.

القيمة: الظل المتوسط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


الحصول أو تعيين يحدد مقدار تعتيم الظلال في الصورة. قيم قنوات اللون في الطرف السفلي من نطاق الشدة تُعدل أكثر من القيم القريبة من الوسط أو الطرف العلوي، مما يعني إمكانية تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر إضاءةً. 0 يحدد أن الظلال MUST NOT تتغير. 0 < value \\u2264 100 يحدد أن الظلال التي تقل نسبتها عن هذا الحد تُصبح أغمق.

القيمة: الظل.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


الحصول أو تعيين يحدد مقدار تعتيم الظلال في الصورة. قيم قنوات اللون في الطرف السفلي من نطاق الشدة تُعدل أكثر من القيم القريبة من الوسط أو الطرف العلوي، مما يعني إمكانية تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر إضاءةً. 0 يحدد أن الظلال MUST NOT تتغير. 0 < value \\u2264 100 يحدد أن الظلال التي تقل نسبتها عن هذا الحد تُصبح أغمق.

القيمة: الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

