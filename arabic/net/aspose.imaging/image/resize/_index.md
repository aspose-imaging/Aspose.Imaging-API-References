---
title: "Image.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تُعيد تحجيم الصورة"
type: docs
weight: 260
url: /ar/net/aspose.imaging/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

تغيير حجم الصورة.

```csharp
public virtual void Resize(int newWidth, int newHeight, ResizeType resizeType)
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

هذا المثال يحمل صورة WMF ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
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

هذا المثال يحمل صورة نقطية ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
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
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

هذا المثال يحمل صورة ODG متعددة الصفحات ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

استخدام قناع الجزء لتسريع عملية التجزئة

```csharp
[C#]

// خيارات تصدير القناع
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// لون الخلفية سيكون شفافًا.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // تقليل حجم الصورة لتسريع عملية التجزئة
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // إنشاء نسخة من الفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على قناع المقدمة
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // زيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على جزء من المقدمة
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### انظر أيضًا

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

تغيير حجم الصورة.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات التحجيم. |

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

هذا المثال يحمل صورة ويعيد تحجيمها باستخدام إعدادات تحجيم مختلفة.

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
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int) {#resize}

يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي.

```csharp
public void Resize(int newWidth, int newHeight)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |

## أمثلة

المثال التالي يوضح كيفية إعادة تحجيم ملف ميتا (WMF و EMF).

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string[] fileNames = new[] { "image3.emf", "image4.wmf" };
foreach (string fileName in fileNames)
{
    string inputFilePath = dir + fileName;
    string outputFilePath = dir + "Downscale_" + fileName;

    using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
    {
        image.Resize(image.Width / 4, image.Height / 4);
        image.Save(outputFilePath);
    }
}
```

المثال التالي يوضح كيفية إعادة تحجيم صورة SVG وحفظها كـ PNG.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3549";
string[] fileNames = new string[]
{
    "Logotype.svg",
    "sample_car.svg",
    "rg1024_green_grapes.svg",
    "MidMarkerFigure.svg",
    "embeddedFonts.svg"
};

Aspose.Imaging.PointF[] scales = new Aspose.Imaging.PointF[]
{
    new Aspose.Imaging.PointF(0.5f, 0.5f),
    new Aspose.Imaging.PointF(1f, 1f),
    new Aspose.Imaging.PointF(2f, 2f),
    new Aspose.Imaging.PointF(3.5f, 9.2f),
};

foreach (string inputFile in fileNames)
{
    foreach (Aspose.Imaging.PointF scale in scales)
    {
        string outputFile = string.Format("{0}_{1}_{2}.png", inputFile, scale.X.ToString(System.Globalization.CultureInfo.InvariantCulture), scale.Y.ToString(System.Globalization.CultureInfo.InvariantCulture));
        using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, inputFile)))
        {
            image.Resize((int)(image.Width * scale.X), (int)(image.Height * scale.Y));
            image.Save(System.IO.Path.Combine(dir, outputFile), new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


