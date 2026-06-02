---
title: "WmfColorUsageEnum"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد ColorUsage ما إذا كان جدول الألوان موجودًا في صورة نقطية مستقلة عن الجهاز (DIB) وكيفية تفسير قيمه."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

التعداد ColorUsage يحدد ما إذا كان جدول الألوان موجوداً في bitmap مستقل عن الجهاز (DIB) وكيفية تفسير قيمه.
## الحقول

| حقل | الوصف |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | يحتوي جدول الألوان على قيم RGB محددة بواسطة كائنات RGBQuad (القسم 2.2.2.20). |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | يحتوي جدول الألوان على مؤشرات 16‑بت إلى لوحة الألوان المنطقية الحالية في سياق جهاز التشغيل. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | لا يوجد جدول ألوان. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


يحتوي جدول الألوان على قيم RGB محددة بواسطة كائنات RGBQuad (القسم 2.2.2.20).

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


يحتوي جدول الألوان على مؤشرات 16‑بت إلى لوحة الألوان المنطقية الحالية في سياق جهاز التشغيل.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


لا يوجد جدول ألوان. البكسلات في DIB هي فهارس إلى لوحة الألوان المنطقية الحالية في سياق جهاز التشغيل.

