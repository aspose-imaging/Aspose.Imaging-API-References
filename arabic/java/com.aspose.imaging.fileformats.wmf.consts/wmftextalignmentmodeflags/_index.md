---
title: "WmfTextAlignmentModeFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد علامات TextAlignmentMode العلاقة بين نقطة المرجع ومستطيل الحدود لمحاذاة النص."
type: docs
weight: 36
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

تحدد علامات TextAlignmentMode العلاقة بين نقطة المرجع ومستطيل الحدود، لمحاذاة النص. يمكن دمج هذه العلامات لتحديد خيارات متعددة، مع القيد أن يتم اختيار علامة واحدة فقط تغير موضع الرسم في سياق جهاز التشغيل. يتم تنفيذ محاذاة النص الأفقية عندما يكون للخط خط أساس افتراضي أفقي.

--------------------

تحدد علامات TextAlignmentMode ثلاثة مكونات مختلفة لمحاذاة النص: - يتم تحديد الموضع الأفقي لنقطة المرجع بواسطة TA\\_RIGHT و TA\\_CENTER؛ إذا كانت تلك البتات غير مفعلة، يجب أن يكون المحاذاة TA\\_LEFT. - يتم تحديد الموضع الرأسي لنقطة المرجع بواسطة TA\\_BOTTOM و TA\\_BASELINE؛ إذا كانت تلك البتات غير مفعلة، يجب أن يكون المحاذاة TA\\_TOP. - يتم تحديد ما إذا كان يجب تحديث موضع الإخراج في سياق جهاز التشغيل بعد إخراج النص بواسطة TA\\_UPDATECP؛ إذا كانت تلك البت غير مفعلة، يجب عدم تحديث الموضع. هذا هو السبب في تعريف ثلاث قيم صفرية مختلفة في التعداد؛ فهي تمثل الحالات الافتراضية للمكونات الثلاثة لمحاذاة النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | يجب عدم تحديث موضع الرسم في سياق جهاز التشغيل بعد كل استدعاء لإخراج النص. |
| [Left](#Left) | يجب أن تكون نقطة المرجع على الحافة اليسرى للمستطيل المحيط. |
| [Top](#Top) | يجب أن تكون نقطة المرجع على الحافة العلوية للمستطيل المحيط. |
| [Updatecp](#Updatecp) | يجب تحديث موضع الرسم في سياق جهاز التشغيل بعد كل استدعاء لإخراج النص. |
| [Right](#Right) | يجب أن تكون نقطة المرجع على الحافة اليمنى للمستطيل المحيط. |
| [Center](#Center) | يجب محاذاة نقطة المرجع أفقيًا مع مركز مستطيل الحدود. |
| [Bottom](#Bottom) | يجب أن تكون نقطة المرجع على الحافة السفلية للمستطيل المحيط. |
| [Baseline](#Baseline) | يجب أن تكون نقطة المرجع على خط الأساس للنص. |
| [Rtlreading](#Rtlreading) | يجب ترتيب النص بترتيب القراءة من اليمين إلى اليسار، بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | المركز) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | خط الأساس) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


يجب عدم تحديث موضع الرسم في سياق جهاز التشغيل بعد كل استدعاء لإخراج النص. يجب تمرير نقطة المرجع إلى دالة إخراج النص.

### Left {#Left}
```
public static final int Left
```


يجب أن تكون نقطة المرجع على الحافة اليسرى للمستطيل المحيط.

### Top {#Top}
```
public static final int Top
```


يجب أن تكون نقطة المرجع على الحافة العلوية للمستطيل المحيط.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


يجب تحديث موضع الرسم في سياق جهاز التشغيل بعد كل استدعاء لإخراج النص. يجب استخدامه كنقطة مرجعية.

### Right {#Right}
```
public static final int Right
```


يجب أن تكون نقطة المرجع على الحافة اليمنى للمستطيل المحيط.

### Center {#Center}
```
public static final int Center
```


يجب محاذاة نقطة المرجع أفقيًا مع مركز مستطيل الحدود.

### Bottom {#Bottom}
```
public static final int Bottom
```


يجب أن تكون نقطة المرجع على الحافة السفلية للمستطيل المحيط.

### Baseline {#Baseline}
```
public static final int Baseline
```


يجب أن تكون نقطة المرجع على خط الأساس للنص.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


يجب ترتيب النص بترتيب القراءة من اليمين إلى اليسار، بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. يجب تطبيق ذلك فقط عندما يكون الخط المحدد في سياق جهاز التشغيل إما عبريًا أو عربيًا.

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

