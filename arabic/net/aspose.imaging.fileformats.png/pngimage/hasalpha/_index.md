---
title: "PngImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngImage. تُعيد قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على قناة ألفا التي تحدد شفافيتها. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى معالجة الشفافية، مما يتيح للمطورين تحديد ما إذا كان هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة."
type: docs
weight: 50
url: /ar/net/aspose.imaging.fileformats.png/pngimage/hasalpha/
---
## PngImage.HasAlpha property

يرجع قيمة منطقية تُظهر ما إذا كانت الصورة تحتوي على قناة ألفا، التي تحدد شفافيتها. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى التعامل مع الشفافية، مما يسمح للمطورين بتحديد ما إذا كانت هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة.

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` إذا كان هذا الكائن يحتوي على قناة ألفا؛ وإلا `false`.

## أمثلة

يوضح المثال التالي كيفية التحقق مما إذا كانت صورة PNG تدعم قناة ألفا.

```csharp
[C#]

// احصل على جميع أنواع ألوان PNG المدعومة.
System.Array colorTypes = System.Enum.GetValues(typeof(Aspose.Imaging.FileFormats.Png.PngColorType));

foreach (Aspose.Imaging.FileFormats.Png.PngColorType colorType in colorTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    createOptions.Source = new Sources.StreamSource(new System.IO.MemoryStream());
    createOptions.ColorType = colorType;

    using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
    {
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

        if (pngImage.HasAlpha)
        {
            System.Console.WriteLine("A {0} PNG image supports alpha channel", createOptions.ColorType);
        }
        else
        {
            System.Console.WriteLine("A {0} PNG image doesn't support alpha channel", createOptions.ColorType);
        }
    }
}

// الإخراج يبدو هكذا:
// صورة PNG ذات تدرج رمادي لا تدعم قناة ألفا.
// صورة PNG ذات ألوان حقيقية لا تدعم قناة ألفا.
// صورة PNG ذات ألوان مفهرسة لا تدعم قناة ألفا.
// صورة PNG ذات تدرج رمادي مع ألفا تدعم قناة ألفا.
// صورة PNG ذات ألوان حقيقية مع ألفا تدعم قناة ألفا.
```

### انظر أيضًا

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


