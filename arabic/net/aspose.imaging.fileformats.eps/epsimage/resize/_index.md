---
title: Resize
second_title: Aspose.Imaging لمرجع NET API
description: يغير حجم الصورة.
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.eps/epsimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

يغير حجم الصورة.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

### أمثلة

قم بتغيير حجم صورة EPS وتصديرها إلى تنسيق PNG.

```csharp
[C#]

// تحميل صورة EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // قم بتغيير حجم الصورة باستخدام طريقة Mitchell cubic interpolation
    image.Resize(400, 400, ResizeType.Mitchell);

    // تصدير الصورة إلى تنسيق PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

### أنظر أيضا

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [EpsImage](../../epsimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Eps](../../epsimage)
* المجسم [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

يغير حجم الصورة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| settings | ImageResizeSettings | إعدادات تغيير الحجم. |

### أمثلة

قم بتغيير حجم صورة EPS باستخدام الإعدادات المتقدمة.

```csharp
[C#]

// تحميل صورة EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // تغيير حجم الصورة باستخدام إعدادات تغيير الحجم المتقدمة
    image.Resize(400, 400, new ImageResizeSettings
    {
        // ضبط وضع الاستيفاء
        Mode = ResizeType.LanczosResample,

        // تعيين نوع المرشح
        FilterType = ImageFilterType.SmallRectangular,

        // يعين طريقة مقارنة الألوان
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // ضبط طريقة تكميم اللون
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // تصدير الصورة إلى تنسيق PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

### أنظر أيضا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [EpsImage](../../epsimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Eps](../../epsimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
