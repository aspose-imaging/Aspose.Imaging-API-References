---
title: "WmfTextAlignmentModeFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد Flags وضع TextAlignmentMode العلاقة بين نقطة المرجع ومستطيل الحد لتحديد محاذاة النص."
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

تحدد Flags وضع TextAlignmentMode العلاقة بين نقطة المرجع ومستطيل الحد لتحديد محاذاة النص. يمكن دمج هذه Flags لتحديد خيارات متعددة، مع القيد أن يتم اختيار Flag واحدة فقط تُغيّر موضع الرسم في playback device context. يتم تنفيذ محاذاة النص الأفقية عندما يكون للخط خط أساس افتراضي أفقي.

--------------------

تحدد flags وضع TextAlignmentMode ثلاثة مكونات مختلفة لمحاذاة النص: - يتم تحديد الموضع الأفقي لنقطة المرجع بواسطة TA_RIGHT و TA_CENTER؛ إذا كانت تلك البتات غير مفعلة، يجب أن يكون المحاذاة TA_LEFT. - يتم تحديد الموضع الرأسي لنقطة المرجع بواسطة TA_BOTTOM و TA_BASELINE؛ إذا كانت تلك البتات غير مفعلة، يجب أن يكون المحاذاة TA_TOP. - يتم تحديد ما إذا كان يجب تحديث موضع الإخراج في playback device context بعد إخراج النص بواسطة TA_UPDATECP؛ إذا كانت تلك البت غير مفعلة، يجب ألا يتم تحديث الموضع. هذا هو السبب في تعريف ثلاث قيم صفرية مختلفة في التعداد؛ فهي تمثل الحالات الافتراضية للمكونات الثلاثة لمحاذاة النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | يجب ألا يتم تحديث موضع الرسم في playback device context بعد كل استدعاء لإخراج النص. |
| [Left](#Left) | يجب أن تكون النقطة المرجعية على الحافة اليسرى للمستطيل المحيط. |
| [Top](#Top) | يجب أن تكون النقطة المرجعية على الحافة العلوية للمستطيل المحيط. |
| [Updatecp](#Updatecp) | يجب تحديث موضع الرسم في playback device context بعد كل استدعاء لإخراج النص. |
| [Right](#Right) | يجب أن تكون النقطة المرجعية على الحافة اليمنى للمستطيل المحيط. |
| [Center](#Center) | يجب أن تكون نقطة المرجع محاذاة أفقياً مع مركز مستطيل الحد. |
| [Bottom](#Bottom) | يجب أن تكون النقطة المرجعية على الحافة السفلية للمستطيل المحيط. |
| [Baseline](#Baseline) | يجب أن تكون النقطة المرجعية على خط الأساس للنص. |
| [Rtlreading](#Rtlreading) | يجب تنسيق النص بترتيب قراءة من اليمين إلى اليسار، بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | الوسط) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | خط الأساس) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


يجب ألا يتم تحديث موضع الرسم في playback device context بعد كل استدعاء لإخراج النص. يجب تمرير نقطة المرجع إلى دالة إخراج النص.

### Left {#Left}
```
public static final int Left
```


يجب أن تكون النقطة المرجعية على الحافة اليسرى للمستطيل المحيط.

### Top {#Top}
```
public static final int Top
```


يجب أن تكون النقطة المرجعية على الحافة العلوية للمستطيل المحيط.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


يجب تحديث موضع الرسم في playback device context بعد كل استدعاء لإخراج النص. يجب استخدامها كنقطة مرجع.

### Right {#Right}
```
public static final int Right
```


يجب أن تكون النقطة المرجعية على الحافة اليمنى للمستطيل المحيط.

### Center {#Center}
```
public static final int Center
```


يجب أن تكون نقطة المرجع محاذاة أفقياً مع مركز مستطيل الحد.

### Bottom {#Bottom}
```
public static final int Bottom
```


يجب أن تكون النقطة المرجعية على الحافة السفلية للمستطيل المحيط.

### Baseline {#Baseline}
```
public static final int Baseline
```


يجب أن تكون النقطة المرجعية على خط الأساس للنص.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


يجب تنسيق النص بترتيب قراءة من اليمين إلى اليسار، بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. يجب تطبيق ذلك فقط عندما يكون الخط المحدد في playback device context إما عبريًا أو عربيًا.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


يمثل مجموعات محاذاة النص الأفقية (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


يمثل مجموعات محاذاة النص العمودية (Top | Bottom | Baseline)

