---
title: Compress
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذاICompressedOptions مضغوط .
type: docs
weight: 40
url: /ar/net/aspose.imaging.imageoptions/svgoptions/compress/
---
## SvgOptions.Compress property

الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذاICompressedOptions مضغوط .

```csharp
public bool Compress { get; set; }
```

### Property_Value

`حقيقي` إذا تم ضغطه خلاف ذلك،`خاطئة` .

### أمثلة

يوضح المثال التالي كيفية تحويل صور svg إلى svgz fromat

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### أنظر أيضا

* class [SvgOptions](../../svgoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../svgoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
