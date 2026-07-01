---
title: "ColorMatrixFlag"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد أنواع الصور والألوان التي سيتأثر بها إعدادات تعديل اللون والتدرج الرمادي لـ ."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

يحدد أنواع الصور والألوان التي سيتأثر بها إعدادات تعديل اللون والتدرج الرمادي لـ [ImageAttributes](../../com.aspose.imaging/imageattributes).
## الحقول

| حقل | الوصف |
| --- | --- |
| [Default](#Default) | جميع قيم الألوان، بما في ذلك الظلال الرمادية، يتم تعديلها بواسطة نفس مصفوفة تعديل اللون. |
| [SkipGrays](#SkipGrays) | جميع الألوان يتم تعديلها، لكن الظلال الرمادية لا يتم تعديلها. |
| [AltGrays](#AltGrays) | فقط الظلال الرمادية يتم تعديلها. |
### Default {#Default}
```
public static final int Default
```


جميع قيم الألوان، بما في ذلك الظلال الرمادية، يتم تعديلها بواسطة نفس مصفوفة تعديل اللون.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


جميع الألوان يتم تعديلها، لكن الظلال الرمادية لا يتم تعديلها. الظل الرمادي هو أي لون له نفس القيمة لمكوّناته الحمراء والخضراء والزرقاء.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


فقط الظلال الرمادية يتم تعديلها.

