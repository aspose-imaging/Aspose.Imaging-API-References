---
title: "ClaheFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يوفر خيارات لتكوين مرشح تساوي التدرج التكيفي المحدود بالتباين CLAHE."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

يوفر خيارات لتكوين مرشح تعديل التباين المحدود بالتاريخ التكيفي (CLAHE).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | ينشئ مثيلًا جديدًا من الفئة [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) بالمعلمات المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | يحصل على قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | يحصل على عدد البلاطات في الاتجاه الأفقي. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | يحصل على عدد البلاطات في الاتجاه العمودي. |
| [getClipLimit()](#getClipLimit--) | يحصل على عتبة تحديد التباين. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


ينشئ مثيلًا جديدًا من الفئة [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) بالمعلمات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isGrayscale | boolean | يشير إلى ما إذا كان يجب أن يعمل المرشح في وضع التدرج الرمادي. |
| tilesNumberHorizontal | int | عدد البلاطات أفقيًا. القيمة الافتراضية هي 8. |
| tilesNumberVertical | int | عدد البلاطات عموديًا. القيمة الافتراضية هي 8. |
| clipLimit | double | عتبة تحديد التباين. القيمة الافتراضية هي 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


يحصل على قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان المرشح يعمل في وضع التدرج الرمادي.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


يحصل على عدد البلاطات في الاتجاه الأفقي. يحدد عدد المناطق التي تُقسم الصورة إليها أفقيًا لتسوية التباين المحلي.

**Returns:**
int - عدد البلاطات في الاتجاه الأفقي.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


يحصل على عدد البلاطات في الاتجاه العمودي. يحدد عدد المناطق التي تُقسم الصورة إليها عموديًا لتسوية التباين المحلي.

**Returns:**
int - عدد البلاطات في الاتجاه العمودي.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


يحصل على عتبة تحديد التباين. القيم الأعلى تسمح بمزيد من التباين؛ القيم الأقل تحد من التعزيز لمنع تضخيم الضوضاء.

**Returns:**
double - عتبة تحديد التباين.
