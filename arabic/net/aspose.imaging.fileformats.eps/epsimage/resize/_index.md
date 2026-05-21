---
title: "EpsImage.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة EpsImage. تقوم هذه الطريقة بتغيير حجم الصورة وضبط أبعادها وفقًا للمعلمات المحددة. توفر طريقة بسيطة لتعديل حجم الصورة مع ضمان المرونة وسهولة الاستخدام للمطورين."
type: docs
weight: 200
url: /ar/net/aspose.imaging.fileformats.eps/epsimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

تقوم هذه الطريقة بتغيير حجم الصورة، وضبط أبعادها وفقًا للمعلمات المحددة. توفر طريقة بسيطة لتعديل حجم الصورة، مع ضمان المرونة وسهولة الاستخدام للمطورين.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

إعادة تحجيم صورة EPS وتصديرها إلى صيغة PNG.

```csharp
[C#]

// تحميل صورة EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // إعادة تحجيم الصورة باستخدام طريقة Mitchell cubic interpolation.
    image.Resize(400, 400, ResizeType.Mitchell);

    // تصدير الصورة إلى صيغة PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

تقوم هذه الطريقة بتغيير حجم الصورة باستخدام إعدادات مسبقة التعريف، مما يسمح بضبط الأبعاد بكفاءة. توفر طريقة مريحة لتعديل حجم الصورة مع الحفاظ على التحكم في المعلمات المختلفة، مما يضمن نتائج مثالية لحالات الاستخدام المتنوعة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات التحجيم. |

## أمثلة

إعادة تحجيم صورة EPS باستخدام إعدادات متقدمة.

```csharp
[C#]

// تحميل صورة EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // إعادة تحجيم الصورة باستخدام إعدادات تحجيم متقدمة
    image.Resize(400, 400, new ImageResizeSettings
    {
        // تعيين وضع الاستيفاء
        Mode = ResizeType.LanczosResample,

        // تعيين نوع الفلتر
        FilterType = ImageFilterType.SmallRectangular,

        // يضبط طريقة مقارنة اللون
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // حدد طريقة تكميم اللون
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // تصدير الصورة إلى صيغة PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

### انظر أيضًا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)


