---
title: Compress
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذاICompressedOptions مضغوط .
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/metafileoptions/compress/
---
## MetafileOptions.Compress property

الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذاICompressedOptions مضغوط .

```csharp
public bool Compress { get; set; }
```

### Property_Value

`حقيقي` إذا تم ضغطه خلاف ذلك،`خاطئة` .

### أمثلة

يوضح المثال التالي كيفية تحويل صور emf إلى emz fromat

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

يوضح المثال التالي كيفية تحويل صور wmf إلى wmz fromat

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

### أنظر أيضا

* class [MetafileOptions](../../metafileoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../metafileoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->