---
title: "DjvuImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تقوم وظيفة Crop بقص صورتك للتركيز على تفاصيل محددة أو إزالة العناصر غير المرغوبة مما يعزز تكوينها وتأثيرها البصري. سواءً كنت تعدل الصور لوسائل التواصل الاجتماعي أو تنشئ لافتات مواقع ويب أو تصمم مواد مطبوعة، فإن هذه الأداة تساعدك على تحسين صورك بدقة ووضوح."
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/crop/
---
## Crop(Rectangle) {#crop}

\"Crop\" يقتطع صورتك للتركيز على تفاصيل محددة أو إزالة العناصر غير المرغوبة، مما يعزز تركيبتها وتأثيرها البصري. سواءً كنت تعدل الصور لوسائل التواصل الاجتماعي، أو تنشئ لافتات مواقع ويب، أو تصمم مواد مطبوعة، فإن هذه الأداة تساعدك على صقل صورك بدقة ووضوح.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

## أمثلة

المثال التالي يقتطع صورة DJVU. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(djvuImage.Width / 4, djvuImage.Height / 4, djvuImage.Width / 2, djvuImage.Height / 2);
    djvuImage.Crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    djvuImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

يتيح لك Crop with shifts ضبط موضع وأبعاد المنطقة المقتطعة داخل الصورة بدقة. هذه الميزة لا تقدر بثمن لتصحيح التركيبات، ومحاذاة العناصر، وتأكيد نقاط التركيز في مرئياتك. من خلال دمج الإزاحات في عملية القص، يمكنك تحقيق دقة بكسلية مثالية وضبط إطار صورك بسهولة.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | Int32 | الإزاحة اليسرى. |
| rightShift | Int32 | الإزاحة اليمنى. |
| topShift | Int32 | الإزاحة العلوية. |
| bottomShift | Int32 | الإزاحة السفلية. |

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


