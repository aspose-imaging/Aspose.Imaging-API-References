---
title: Resize
second_title: Aspose.Imaging لمرجع NET API
description: يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم .
type: docs
weight: 200
url: /ar/net/aspose.imaging/image/resize/
---
## Resize(int, int) {#resize}

يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم .

```csharp
public void Resize(int newWidth, int newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد . |
| newHeight | Int32 | الارتفاع الجديد . |

### أمثلة

يوضح المثال التالي كيفية تغيير حجم ملف تعريف (WMF و EMF).

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

يوضح المثال التالي كيفية تغيير حجم صورة SVG وحفظها في PNG.

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

### أنظر أيضا

* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

يغير حجم الصورة.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد . |
| newHeight | Int32 | الارتفاع الجديد . |
| resizeType | ResizeType | نوع تغيير الحجم . |

### أمثلة

تغيير حجم الصورة باستخدام نوع معين من تغيير الحجم.

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

يقوم هذا المثال بتحميل الصورة وتغيير حجمها باستخدام طرق مختلفة لتغيير الحجم.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قم بالزيادة بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قم بالارتقاء بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

استخدام قناع مقطعي لتسريع عملية التجزئة

```csharp
[C#]

// إخفاء خيارات التصدير
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// سيكون لون backgroung شفافًا.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // تصغير حجم الصورة لتسريع عملية التجزئة
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // إنشاء مثيل لفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (شرائح).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على القناع الأمامي
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // قم بزيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على مقطع أمامي
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### أنظر أيضا

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

يغير حجم الصورة.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| settings | ImageResizeSettings | إعدادات تغيير الحجم. |

### أمثلة

تغيير حجم الصورة باستخدام نوع معين من تغيير الحجم.

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

يقوم هذا المثال بتحميل الصورة وتغيير حجمها باستخدام إعدادات تغيير الحجم المختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// الخوارزمية التكيفية القائمة على الوظيفة المنطقية الموزونة والمختلطة واستيفاء lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// مرشح صغير مستطيل
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// عدد الألوان في اللوحة.
resizeSettings.EntriesCount = 256;

// لا يتم استخدام تكميم اللون
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// الطريقة الإقليدية
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة التشكيل التكيفية.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### أنظر أيضا

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
