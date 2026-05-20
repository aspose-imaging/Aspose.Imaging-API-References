---
title: "التكوين"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "التكوين العالمي لإدارة الذاكرة"
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

التكوين العالمي لإدارة الذاكرة
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الإيجابية تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int - تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الإيجابية تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |

