---
title: "ImageOptionsBase.BufferSizeHint"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ImageOptionsBase. يحصل أو يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن المؤقتة الداخلية"
type: docs
weight: 10
url: /ar/net/aspose.imaging/imageoptionsbase/buffersizehint/
---
## ImageOptionsBase.BufferSizeHint property

الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية.

```csharp
public int BufferSizeHint { get; set; }
```

### Property Value

تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الموجبة تعني عدم وجود حد للذاكرة للمخازن الداخلية

## أمثلة

المثال التالي يوضح كيفية تعيين حد للذاكرة عند إنشاء صورة JPEG جديدة. حد الذاكرة هو الحد الأقصى المسموح به (بالميغابايت) لجميع المخازن المؤقتة الداخلية.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// تعيين حد للذاكرة قدره 50 ميغابايت للصورة المستهدفة المُنشأة
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.JpegOptions
{
    CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive,
    BufferSizeHint = 50,
    Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "createdFile.jpg", false),
};
    
using (var image = Aspose.Imaging.Image.Create(createOptions, 1000, 1000))
{
    image.Save(); // save to same location
}
```

المثال التالي يوضح كيفية تعيين حد للذاكرة عند إنشاء صورة PNG ورسم رسومات معقدة عليها. حد الذاكرة هو الحد الأقصى المسموح به (بالميغابايت) لجميع المخازن المؤقتة الداخلية.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30; // Memory limit is 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    // يمكنك استخدام أي عمليات رسومية هنا، جميعها سيتم تنفيذها ضمن حد الذاكرة المحدد
    // على سبيل المثال:
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

// يتم دعم عدد كبير من العمليات الرسومية أيضاً:
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30; // Memory limit is 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.BeginUpdate();
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);

    int x, y;
    int numberOfOperations = 0;
    for (int column = 0; column * OperationAreaSize < ImageSize; column++)
    {
        for (int row = 0; row * OperationAreaSize < ImageSize; row++)
        {
            x = column * OperationAreaSize;
            y = row * OperationAreaSize;

            bool reversed = (column + row) % 2 != 0;
            if (reversed)
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x + OperationAreaSize - 2,
                    y,
                    x,
                    y + OperationAreaSize);
            }
            else
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x,
                    y,
                    x + OperationAreaSize - 2,
                    y + OperationAreaSize);
            }

            numberOfOperations++;
        }
    }

    // سيتم تطبيق حوالي 40 ألف عملية هنا، بينما لا تستهلك الكثير من الذاكرة
    // لأنها تم تفريغها بالفعل إلى الملف الخارجي، وسيتم تحميلها منه واحدة تلو الأخرى
    graphics.EndUpdate();

    image.Save();
}
```

### انظر أيضًا

* class [ImageOptionsBase](../)
* namespace [Aspose.Imaging](../../imageoptionsbase/)
* assembly [Aspose.Imaging](../../../)


