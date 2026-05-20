---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يوفر خيارات لتكوين مرشح التمدد الأبيض التكيفي."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

يوفر خيارات لتكوين مرشح التمدد الأبيض التكيفي. يسمح بتخصيص معلمات تمدد المخطط لتقوية مستوى الأبيض وتحسين قابلية قراءة النص الخفيف أو الصور ذات التباين المنخفض.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | ينشئ مثيلاً جديداً من فئة AdaptiveWhiteStretchFilter. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | ينشئ مثيلاً جديداً من فئة AdaptiveWhiteStretchFilter. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | يحصل على قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي. |
| [getLowPercentile()](#getLowPercentile--) | يحصل على النسبة المئوية السفلية لحساب نقطة السواد. |
| [getHighPercentile()](#getHighPercentile--) | يحصل على النسبة المئوية العليا لحساب نقطة الأبيض. |
| [getTargetWhite()](#getTargetWhite--) | يحصل على قيمة الأبيض المستهدفة التي يهدف التمدد إلى تحقيقها. |
| [getMaxScale()](#getMaxScale--) | يحصل على مقياس السطوع الأقصى المسموح به. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


ينشئ مثيلاً جديداً من فئة AdaptiveWhiteStretchFilter.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


ينشئ مثيلاً جديداً من فئة AdaptiveWhiteStretchFilter.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isGrayscale | boolean | يشير إلى ما إذا كان يجب أن يعمل المرشح في وضع التدرج الرمادي. |
| lowPercentile | int | النسبة المئوية السفلية لنقطة السواد (مثال: 10). |
| highPercentile | int | النسبة المئوية العليا لنقطة اللون الأبيض (مثال: 90). |
| targetWhite | int | قيمة اللون الأبيض المستهدف (مثال: 240). |
|  | maxScale | float | أقصى مقياس سطوع مسموح به (مثال: 1.7). |

--------------------

يقوم الخوارزم بتمديد المخطط البياني بحيث تقترب النسبة المئوية للون الأبيض من `targetWhite`، ولكن دون تجاوز `maxScale` لتجنب الإفراط في الإضاءة. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


يحصل على قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


يحصل على النسبة المئوية السفلية لحساب نقطة اللون الأسود. تُعتبر قيم البكسل التي تقع تحت هذه النسبة سوداء أثناء التمديد.

**Returns:**
int - النسبة المئوية السفلية لحساب نقطة اللون الأسود.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


يحصل على النسبة المئوية العليا لحساب نقطة اللون الأبيض. تُعتبر قيم البكسل التي تقع فوق هذه النسبة بيضاء أثناء التمديد.

**Returns:**
int - النسبة المئوية العليا لحساب نقطة اللون الأبيض.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


يحصل على قيمة الأبيض المستهدفة التي يهدف التمدد إلى تحقيقها.

**Returns:**
int - قيمة اللون الأبيض المستهدف التي يسعى التمديد لتحقيقها.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


يحصل على أقصى مقياس سطوع مسموح به. لن يتجاوز التمديد الفعلي هذا العامل لتجنب الإفراط في الإضاءة.

**Returns:**
float - أقصى مقياس سطوع مسموح به.
