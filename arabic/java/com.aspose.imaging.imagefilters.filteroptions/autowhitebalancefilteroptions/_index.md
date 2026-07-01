---
title: "AutoWhiteBalanceFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يوفر خيارات التكوين لمرشح التوازن الأبيض التلقائي."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

يوفر خيارات التكوين لمرشح Auto White Balance. يسمح بضبط معلمات تمديد التباين وتوسيع القنوات لتحسين مظهر الصور الرقمية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | يُنشئ مثيلًا جديدًا من الفئة [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | يحصل على النسبة المئوية العليا المستهدفة لتمديد التباين. |
| [getTargetValue()](#getTargetValue--) | يحصل على القيمة المستهدفة للنسبة المئوية العليا. |
| [getMaxScale()](#getMaxScale--) | يُرجع عامل التحجيم الأقصى لكل قناة. |
| [getLowPercentile()](#getLowPercentile--) | النسبة المئوية المنخفضة لنقطة الأسود، تُستخدم للحماية من الظلام (الافتراضي: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | الإزاحة من النسبة المئوية المنخفضة التي أدناه لا يتم تمديد البكسلات الداكنة (حماية). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


يُنشئ مثيلًا جديدًا من الفئة [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lowPercentile | int | النسبة المئوية المنخفضة لنقطة الأسود، تُستخدم للحماية من الظلام (الافتراضي: 3). |
| targetHighPercentile | int | النسبة المئوية العالية المستهدفة لتوسيع التباين (الافتراضي 97). |
| targetValue | int | القيمة المستهدفة للنسبة المئوية العالية (الافتراضي 255). |
| maxScale | float | عامل التحجيم الأقصى لكل قناة (الافتراضي 1.4f). |
| protectedDarkOffset | int | الإزاحة من النسبة المئوية المنخفضة التي أدناه لا يتم تمديد البكسلات الداكنة (حماية). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


يُرجع النسبة المئوية العالية المستهدفة لتوسيع التباين. يحدد أي نسبة إضاءة سيتم ربطها بالقيمة المستهدفة.

**Returns:**
int - النسبة المئوية العالية المستهدفة لتوسيع التباين.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


يُرجع القيمة المستهدفة للنسبة المئوية العالية. ستُستخدم هذه القيمة كمرجع أبيض لتوسيع التباين.

**Returns:**
int - القيمة المستهدفة للنسبة المئوية العالية.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


يُرجع عامل التحجيم الأقصى لكل قناة. يحد من تضخيم أي قناة لتجنب التحولات اللونية المفرطة.

**Returns:**
float - عامل التحجيم الأقصى لكل قناة.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


النسبة المئوية المنخفضة لنقطة الأسود، تُستخدم للحماية من الظلام (الافتراضي: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


الإزاحة من النسبة المئوية المنخفضة التي أدناه لا يتم تمديد البكسلات الداكنة (حماية).

**Returns:**
int
