---
title: "RasterImage.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تعيد تحجيم الصورة باستخدام خيارات موسعة."
type: docs
weight: 550
url: /ar/net/aspose.imaging/rasterimage/resize/
---
## RasterImage.Resize method

يعيد تحجيم الصورة باستخدام خيارات موسعة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات التحجيم. |

## أمثلة

هذا المثال يحمل صورة نقطية ويعيد تحجيمها باستخدام إعدادات تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة النسبية الموزونة والمختلطة وتداخل lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// المرشح المستطيل الصغير
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// عدد الألوان في لوحة الألوان.
resizeSettings.EntriesCount = 256;

// لم يتم استخدام تقليل الألوان
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// الطريقة الإقليدية
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### انظر أيضًا

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


