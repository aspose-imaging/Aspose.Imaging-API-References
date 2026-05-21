---
title: "المندوب CustomFontSource"
second_title: "Aspose.Imaging for .NET API Reference"
description: "دالة موفر مصدر الخط المخصص"
type: docs
weight: 770
url: /ar/net/aspose.imaging/customfontsource/
---
## CustomFontSource delegate

دالة موفر مصدر الخط المخصص

```csharp
public delegate CustomFontData[] CustomFontSource(params object[] args);
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| args | Object[] | الوسائط. |

### قيمة الإرجاع

قائمة الخطوط المحددة لتصيير الصورة

## أمثلة

يوضح هذا المثال مصدر الخط المخصص الذي يتيح استخدام الخط(وط) المحدد لتصيير الصورة. على عكس طريقة FontSettings.SetFontsFolders التي تعمل ضمن نطاق الصورة وتسمح بتوفير الخطوط في سيناريوهات متعددة المستخدمين.

```csharp
[C#]

public void CustomFontSourceTest(string inputPath, string outputPath, string fileName, string fontPath)
{
    var loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.AddCustomFontSource(GetFontSource, fontPath);
    using (var img = Image.Load(System.IO.Path.Combine(inputPath, fileName), loadOptions))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions =
            (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)img.GetDefaultOptions(new object[] { Color.White, img.Width, img.Height });
        vectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        vectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;

        img.Save(System.IO.Path.Combine(outputPath, fileName + ".png"), new Aspose.Imaging.ImageOptions.PngOptions
        {
            VectorRasterizationOptions = vectorRasterizationOptions
        });
    }
}

// مثال موفر الخطوط المخصصة.
private Aspose.Imaging.CustomFontHandler.CustomFontData[] GetFontSource(params object[] args)
{
    string fontsPath = string.Empty;
    if (args.Length > 0)
    {
        fontsPath = args[0].ToString();
    }

    var customFontData = new System.Collections.Generic.List<Aspose.Imaging.CustomFontHandler.CustomFontData>();
    foreach (var font in System.IO.Directory.GetFiles(fontsPath))
    {
        customFontData.Add(new Aspose.Imaging.CustomFontHandler.CustomFontData(Path.GetFileNameWithoutExtension(font), System.IO.File.ReadAllBytes(font)));
    }

    return customFontData.ToArray();
}
```

### انظر أيضًا

* class [CustomFontData](../../aspose.imaging.customfonthandler/customfontdata/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


