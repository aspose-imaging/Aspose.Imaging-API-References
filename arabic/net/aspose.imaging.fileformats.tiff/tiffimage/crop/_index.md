---
title: "TiffImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. قص الصورة باستخدام منطقة مستطيلة محددة تسمح باختيار دقيق للمحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لإزالة المناطق غير المرغوب فيها بفعالية والتركيز على التفاصيل الأساسية، مما يعزز وضوح الصورة وتركيبها العام."
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/crop/
---
## Crop(Rectangle) {#crop}

قم بقص الصورة باستخدام منطقة مستطيلة محددة، مما يتيح اختيارًا دقيقًا للمحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لإزالة المناطق غير المرغوبة بفعالية والتركيز على التفاصيل الأساسية، معززًا الوضوح والتركيب العام للصورة.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

## أمثلة

المثال التالي يقتص صورة TIFF. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(tiffImage.Width / 4, tiffImage.Height / 4, tiffImage.Width / 2, tiffImage.Height / 2);
    tiffImage.Crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

قم بقص الصورة عن طريق تحديد إزاحات في الاتجاهات اليسرى، اليمنى، العليا والسفلى. تمكّن هذه الطريقة من اختيار دقيق للجزء المطلوب من الصورة، مسهلةً إزالة المناطق غير المرغوبة بفعالية والتركيز على المحتوى الأساسي. دمج هذه الوظيفة في خط أنابيب معالجة الصور لتعزيز الوضوح والتركيب حسب الحاجة داخل تطبيقك.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | Int32 | الإزاحة اليسرى. |
| rightShift | Int32 | الإزاحة اليمنى. |
| topShift | Int32 | الإزاحة العلوية. |
| bottomShift | Int32 | الإزاحة السفلية. |

## أمثلة

المثال التالي يقتص صورة TIFF. يتم تحديد منطقة القص عبر هوامش اليسار، الأعلى، اليمين، الأسفل.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // اقطع مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
    int horizontalMargin = tiffImage.Width / 10;
    int verticalMargin = tiffImage.Height / 10;
    tiffImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // احفظ الصورة المقتطعة بصيغة PNG.
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


