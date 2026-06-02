---
title: "ColorPaletteHelper.GetCloseTransparentImagePalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ColorPaletteHelper. يحصل على لوحة ألوان من صورة نقطية تقوم بإنشاء لوحة ألوان للصورة إذا لم تكن لها واحدة. في حال وجود لوحة ألوان، سيتم استخدامها بدلاً من إجراء الحسابات"
type: docs
weight: 80
url: /ar/net/aspose.imaging/colorpalettehelper/getclosetransparentimagepalette/
---
## ColorPaletteHelper.GetCloseTransparentImagePalette method

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. إذا وجدت لوحة، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseTransparentImagePalette(RasterImage image, int entriesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


