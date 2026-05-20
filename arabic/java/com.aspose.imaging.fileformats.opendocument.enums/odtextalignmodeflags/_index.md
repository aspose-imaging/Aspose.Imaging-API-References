---
title: "OdTextAlignModeFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أعلام وضع محاذاة نص المستند المفتوح."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdTextAlignModeFlags extends System.Enum
```

أعلام وضع محاذاة نص المستند المفتوح.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | يجب ألا يتم تحديث موضع الرسم في playback device context بعد كل استدعاء لإخراج النص. |
| [Left](#Left) | يجب أن تكون النقطة المرجعية على الحافة اليسرى للمستطيل المحيط. |
| [Top](#Top) | يجب أن تكون النقطة المرجعية على الحافة العلوية للمستطيل المحيط. |
| [Updatecp](#Updatecp) | يجب تحديث موضع الرسم في playback device context بعد كل استدعاء لإخراج النص. |
| [Right](#Right) | يجب أن تكون النقطة المرجعية على الحافة اليمنى للمستطيل المحيط. |
| [Center](#Center) | يجب أن تكون نقطة المرجع محاذاة أفقياً مع مركز مستطيل الحد. |
| [Justify](#Justify) | يجب محاذاة النص بطريقة تجعل كل سطر نصي في الفقرة له نفس الطول. |
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

### Justify {#Justify}
```
public static final int Justify
```


يجب محاذاة النص بطريقة تجعل كل سطر نصي في الفقرة له نفس الطول.

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

