---
title: "EmfPlusLevelsEffect"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن LevelsEffect يحدد تعديلات على الإضاءات والوسطيات والظلال في صورة."
type: docs
weight: 51
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusLevelsEffect extends EmfPlusImageEffectsObjectType
```

كائن LevelsEffect يحدد التعديلات على الإضاءات، النغمات المتوسطة، والظلال في صورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHighlight()](#getHighlight--) | يحصل أو يعيّن ما يحدد مقدار إضاءة الإضاءات في الصورة. |
| [setHighlight(int value)](#setHighlight-int-) | يحصل أو يعيّن ما يحدد مقدار إضاءة الإضاءات في الصورة. |
| [getMidTone()](#getMidTone--) | يحصل أو يعيّن ما يحدد مقدار إضاءة أو تعتيم الوسطيات في الصورة. |
| [setMidTone(int value)](#setMidTone-int-) | يحصل أو يعيّن ما يحدد مقدار إضاءة أو تعتيم الوسطيات في الصورة. |
| [getShadow()](#getShadow--) | يحصل أو يعيّن ما يحدد مقدار تعتيم الظلال في الصورة. |
| [setShadow(int value)](#setShadow-int-) | يحصل أو يعيّن ما يحدد مقدار تعتيم الظلال في الصورة. |
### EmfPlusLevelsEffect() {#EmfPlusLevelsEffect--}
```
public EmfPlusLevelsEffect()
```


### getHighlight() {#getHighlight--}
```
public int getHighlight()
```


يحصل أو يعيّن ما يحدد مقدار إضاءة الإضاءات في الصورة. قيم قنوات اللون في الطرف العالي من نطاق الشدة تُعدَّل أكثر من القيم القريبة من الوسط أو الطرف المنخفض، مما يعني إمكانية إضاءة الصورة دون فقدان التباين بين الأجزاء الداكنة. 0 \u2264 value < يحدد أن الإضاءات التي تتجاوز نسبة الشدة هذا العتبة SHOULD تُزاد إلى 100. 100 يحدد أن الإضاءات MUST NOT تتغير.

القيمة: الإضاءة.

**Returns:**
int
### setHighlight(int value) {#setHighlight-int-}
```
public void setHighlight(int value)
```


يحصل أو يعيّن ما يحدد مقدار إضاءة الإضاءات في الصورة. قيم قنوات اللون في الطرف العالي من نطاق الشدة تُعدَّل أكثر من القيم القريبة من الوسط أو الطرف المنخفض، مما يعني إمكانية إضاءة الصورة دون فقدان التباين بين الأجزاء الداكنة. 0 \u2264 value < يحدد أن الإضاءات التي تتجاوز نسبة الشدة هذا العتبة SHOULD تُزاد إلى 100. 100 يحدد أن الإضاءات MUST NOT تتغير.

القيمة: الإضاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getMidTone() {#getMidTone--}
```
public int getMidTone()
```


يحصل أو يعيّن ما يحدد مقدار إضاءة أو تعتيم الوسطيات في الصورة. قيم قنوات اللون في وسط نطاق الشدة تُعدَّل أكثر من القيم القريبة من الطرف العالي أو المنخفض، مما يعني إمكانية إضاءة أو تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر ظلامًا وإضاءةً. -100 \u2264 value < 0 يحدد أن الوسطيات تُصبح أغمق. 0 يحدد أن الوسطيات MUST NOT تتغير. 0 < value \u2264 100 يحدد أن الوسطيات تُصبح أفتح.

القيمة: الوسط.

**Returns:**
int
### setMidTone(int value) {#setMidTone-int-}
```
public void setMidTone(int value)
```


يحصل أو يعيّن ما يحدد مقدار إضاءة أو تعتيم الوسطيات في الصورة. قيم قنوات اللون في وسط نطاق الشدة تُعدَّل أكثر من القيم القريبة من الطرف العالي أو المنخفض، مما يعني إمكانية إضاءة أو تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر ظلامًا وإضاءةً. -100 \u2264 value < 0 يحدد أن الوسطيات تُصبح أغمق. 0 يحدد أن الوسطيات MUST NOT تتغير. 0 < value \u2264 100 يحدد أن الوسطيات تُصبح أفتح.

القيمة: الوسط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getShadow() {#getShadow--}
```
public int getShadow()
```


يحصل أو يعيّن ما يحدد مقدار تعتيم الظلال في الصورة. قيم قنوات اللون في الطرف المنخفض من نطاق الشدة تُعدَّل أكثر من القيم القريبة من الوسط أو الطرف العالي، مما يعني إمكانية تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر إضاءةً. 0 يحدد أن الظلال MUST NOT تتغير. 0 < value \u2264 100 يحدد أن الظلال التي تقل نسبتها عن هذا العتبة SHOULD تُصبح أغمق.

القيمة: الظل.

**Returns:**
int
### setShadow(int value) {#setShadow-int-}
```
public void setShadow(int value)
```


يحصل أو يعيّن ما يحدد مقدار تعتيم الظلال في الصورة. قيم قنوات اللون في الطرف المنخفض من نطاق الشدة تُعدَّل أكثر من القيم القريبة من الوسط أو الطرف العالي، مما يعني إمكانية تعتيم الصورة دون فقدان التباين بين الأجزاء الأكثر إضاءةً. 0 يحدد أن الظلال MUST NOT تتغير. 0 < value \u2264 100 يحدد أن الظلال التي تقل نسبتها عن هذا العتبة SHOULD تُصبح أغمق.

القيمة: الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

