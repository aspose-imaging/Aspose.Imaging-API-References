---
title: "Image.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تقص المستطيل المحدد"
type: docs
weight: 210
url: /ar/net/aspose.imaging/image/crop/
---
## Crop(Rectangle) {#crop}

يقص المستطيل المحدد.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

## أمثلة

يوضح المثال التالي قص صورة نقطية. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    image.Crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    image.Save(dir + "sample.Crop.png");
}
```

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

قص الصورة مع إزاحات.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | Int32 | الإزاحة اليسرى. |
| rightShift | Int32 | الإزاحة اليمنى. |
| topShift | Int32 | الإزاحة العلوية. |
| bottomShift | Int32 | الإزاحة السفلية. |

## أمثلة

يوضح المثال التالي قص صورة نقطية. يتم تحديد منطقة القص عبر هوامش اليسار، الأعلى، اليمين، الأسفل.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // اقطع مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
    int horizontalMargin = rasterImage.Width / 10;
    int verticalMargin = rasterImage.Height / 10;
    image.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // احفظ الصورة المقتطعة بصيغة PNG.
    image.Save(dir + "sample.Crop.png");
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


