---
title: "TiffImage.Rotate"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. تدوير الصورة حول نقطة مركزها بزاوية محددة، مما يتيح تعديلًا دقيقًا للاتجاه. دمج هذه الوظيفة في خط أنابيب معالجة الصور الخاص بك لتسهيل التحولات الدقيقة وضمان محاذاة وعرض مثالي للمحتوى البصري داخل تطبيقك."
type: docs
weight: 370
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/rotate/
---
## TiffImage.Rotate method

دوّر الصورة حول نقطة مركزها بزاوية محددة، مما يتيح تعديلًا دقيقًا للاتجاه. دمج هذه الوظيفة في خط أنابيب معالجة الصور لتسهيل التحولات الدقيقة، وضمان محاذاة وعرض مثالي للمحتوى البصري داخل تطبيقك.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | فردي | زاوية التدوير بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | Boolean | إذا تم الضبط على `true` سيتغير حجم الصورة وفقاً لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى يبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| backgroundColor | لون | لون الخلفية. |

## أمثلة

المثال التالي يوضح كيفية تدوير صورة TIFF حول المركز بزاوية 45 درجة باتجاه عقارب الساعة.

```csharp
[C#]

string dir = "c:\\temp\\";
Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// إنشاء مصدر ملف دائم، وليس مؤقت.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "rotated.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الإطار النشط بفرشاة التدرج الخطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // دوّر الصورة حول المركز بزاوية 45 درجة باتجاه عقارب الساعة.
    // تغيّر حجم الصورة وفقًا للمستطيل المدور (نقاط الزوايا).
    tiffImage.Rotate(45f, true, Aspose.Imaging.Color.Black);
    tiffImage.Save();

    // دوّر الصورة حول المركز بزاوية 45 درجة باتجاه عقارب الساعة.
    // اترك أبعاد الصورة دون تعديل، وتدوير المحتوى الداخلي للصورة فقط.
    tiffImage.Rotate(45f, false, Aspose.Imaging.Color.Gray);
    tiffImage.Save(dir + "rotated.preservesize.tif");
}
```

### انظر أيضًا

* struct [Color](../../../aspose.imaging/color/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


