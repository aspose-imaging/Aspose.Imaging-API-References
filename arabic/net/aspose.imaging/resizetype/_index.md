---
title: "التعداد ResizeType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.ResizeType. يحدد نوع التحجيم"
type: docs
weight: 11450
url: /ar/net/aspose.imaging/resizetype/
---
## ResizeType enumeration

يحدد نوع تغيير الحجم.

```csharp
public enum ResizeType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لا يتم الحفاظ على البكسلات أثناء عملية التحجيم. |
| LeftTopToLeftTop | `1` | النقطة اليسرى العليا للصورة الجديدة ستتطابق مع النقطة اليسرى العليا للصورة الأصلية. سيحدث القص إذا لزم الأمر. |
| RightTopToRightTop | `2` | النقطة اليمنى العليا للصورة الجديدة ستتطابق مع النقطة اليمنى العليا للصورة الأصلية. سيحدث القص إذا لزم الأمر. |
| RightBottomToRightBottom | `3` | النقطة اليمنى السفلية للصورة الجديدة ستتطابق مع النقطة اليمنى السفلية للصورة الأصلية. سيحدث القص إذا لزم الأمر. |
| LeftBottomToLeftBottom | `4` | النقطة اليسرى السفلية للصورة الجديدة ستتطابق مع النقطة اليسرى السفلية للصورة الأصلية. سيحدث القص إذا لزم الأمر. |
| CenterToCenter | `5` | مركز الصورة الجديدة سيتطابق مع مركز الصورة الأصلية. سيحدث القص إذا لزم الأمر. |
| LanczosResample | `6` | إعادة أخذ عينات باستخدام خوارزمية lanczos مع a=3. |
| NearestNeighbourResample | `7` | إعادة أخذ عينات باستخدام خوارزمية أقرب جار. |
| AdaptiveResample | `8` | إعادة أخذ عينات باستخدام خوارزمية تكيفية تعتمد على الدالة الكسرية الموزونة والممزوجة وخوارزميات استيفاء lanczos3. |
| BilinearResample | `9` | إعادة أخذ عينات باستخدام استيفاء ثنائي الخطية. يُسمح بالترشيح المسبق للصورة لإزالة الضوضاء قبل إعادة أخذ العينات، عند الحاجة. |
| HighQualityResample | `10` | إعادة أخذ عينات عالية الجودة. |
| CatmullRom | `11` | طريقة استيفاء مكعبية Catmull-Rom. |
| CubicConvolution | `12` | طريقة استيفاء مكعبية Cubic Convolution. |
| CubicBSpline | `13` | طريقة استيفاء مكعبية CubicBSpline. |
| Mitchell | `14` | طريقة استيفاء مكعبية Mitchell. |
| SinC | `15` | طريقة استيفاء مكعبية Sinc (Lanczos3). |
| Bell | `16` | طريقة استيفاء Bell. |

## أمثلة

تغيير حجم الصورة باستخدام نوع التحجيم المحدد.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

هذا المثال يحمل صورة ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


