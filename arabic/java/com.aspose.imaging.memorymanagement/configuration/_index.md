---
title: "التكوين"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الإعداد العالمي لإدارة الذاكرة"
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

الإعداد العالمي لإدارة الذاكرة
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int - تلميح حجم المخزن المؤقت الذي يُعرف كحد أقصى مسموح به لجميع المخازن المؤقتة الداخلية.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | تلميح حجم المخزن المؤقت الذي يُعرف كحد أقصى مسموح به لجميع المخازن المؤقتة الداخلية. |

