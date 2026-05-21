---
title: "Enum WmfGamutMappingIntent"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfGamutMappingIntent enum. يحدد تعداد GamutMappingIntent العلاقة بين الألوان المنطقية والفيزيائية."
type: docs
weight: 8370
url: /ar/net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
## WmfGamutMappingIntent enumeration

يحدد تعداد GamutMappingIntent العلاقة بين الألوان المنطقية والفيزيائية.

```csharp
[Flags]
public enum WmfGamutMappingIntent
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| LCS_GM_ABS_COLORIMETRIC | `8` | يحدد أنه يجب الحفاظ على نقطة الأبيض. يُستخدم عادةً عندما يجب مطابقة الألوان المنطقية مع أقرب لون فيزيائي في نطاق ألوان الوجهة. Intent: Match اسم ICC: Absolute Colorimetric |
| LCS_GM_BUSINESS | `1` | يحدد أنه يجب الحفاظ على التشبع. يُستخدم عادةً للمخططات التجارية وغيرها من الحالات التي لا يتطلب فيها التدرج اللوني. Intent: Graphic اسم ICC: Saturation |
| LCS_GM_GRAPHICS | `2` | يحدد أنه يجب الحفاظ على مطابقة لونية. يُستخدم عادةً لتصاميم الجرافيك والألوان المسماة. Intent: Proof اسم ICC: Relative Colorimetric |
| LCS_GM_IMAGES | `4` | يحدد أنه يجب الحفاظ على التباين. يُستخدم عادةً للصور الفوتوغرافية والصور الطبيعية. Intent: Picture اسم ICC: Perceptual |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


