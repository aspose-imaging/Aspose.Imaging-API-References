---
title: "WmfGamutMappingIntent"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد GamutMappingIntent يحدد العلاقة بين الألوان المنطقية والفيزيائية."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

تعداد GamutMappingIntent يحدد العلاقة بين الألوان المنطقية والفيزيائية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | يحدد أن نقطة اللون الأبيض ينبغي الحفاظ عليها. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | يحدد أن التشبع ينبغي الحفاظ عليه. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | يحدد أنه ينبغي الحفاظ على مطابقة لونية. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | يحدد أنه ينبغي الحفاظ على التباين. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


يحدد أنه ينبغي الحفاظ على نقطة اللون الأبيض. عادةً ما يُستخدم عندما يجب مطابقة الألوان المنطقية مع أقرب لون مادي في نطاق ألوان الوجهة. Intent: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


يحدد أنه ينبغي الحفاظ على التشبع. عادةً ما يُستخدم للمخططات التجارية وغيرها من الحالات التي لا يتطلب فيها التمويه. Intent: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


يحدد أنه ينبغي الحفاظ على مطابقة لونية. عادةً ما يُستخدم لتصاميم الجرافيك والألوان المسماة. Intent: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


يحدد أنه ينبغي الحفاظ على التباين. عادةً ما يُستخدم للصور الفوتوغرافية والصور الطبيعية. Intent: Picture ICC name: Perceptual

