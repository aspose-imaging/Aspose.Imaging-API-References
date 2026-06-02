---
title: "LinearGradientBrush.LinearGradientBrush"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ LinearGradientBrush. يهيئ نسخة جديدة من فئة LinearGradientBrush."
type: docs
weight: 10
url: /ar/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

يهيئ نسخة جديدة من فئة [`LinearGradientBrush`](../).

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | RectangleF | المستطيل. |
| color1 | لون | اللون1. |
| color2 | لون | اللون2. |
| زاوية | فردي | الزاوية. |
| isAngleScalable | Boolean | إذا تم تعيينه إلى `true` [قابل لتوسيع الزاوية]. |

### انظر أيضًا

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

يهيئ نسخة جديدة من فئة [`LinearGradientBrush`](../).

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل. |
| color1 | لون | اللون1. |
| color2 | لون | اللون2. |
| زاوية | فردي | الزاوية. |
| isAngleScalable | Boolean | إذا تم تعيينه إلى `true` [قابل لتوسيع الزاوية]. |

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

يهيئ نسخة جديدة من فئة [`LinearGradientBrush`](../).

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | RectangleF | المستطيل. |
| color1 | لون | اللون1. |
| color2 | لون | اللون2. |
| زاوية | فردي | الزاوية. |

### انظر أيضًا

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

يهيئ نسخة جديدة من فئة [`LinearGradientBrush`](../).

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل. |
| color1 | لون | اللون1. |
| color2 | لون | اللون2. |
| زاوية | فردي | الزاوية. |

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

يهيئ نسخة جديدة من فئة [`LinearGradientBrush`](../).

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | PointF | النقطة1. |
| point2 | PointF | النقطة2. |
| color1 | لون | اللون1. |
| color2 | لون | اللون2. |

### انظر أيضًا

* struct [PointF](../../../aspose.imaging/pointf/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

يهيئ نسخة جديدة من فئة [`LinearGradientBrush`](../).

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | Point | النقطة1. |
| point2 | Point | النقطة2. |
| color1 | لون | اللون1. |
| color2 | لون | اللون2. |

## أمثلة

المثال التالي يوضح كيفية إنشاء نسخة بالأبيض والأسود من إطار موجود وإضافتها إلى صورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم، وليس مؤقت.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
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

    // ملء الإطار النشط بفرشاة تدرج خطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // خيارات التدرج الرمادي
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // إنشاء نسخة تدرج رمادي من الإطار النشط.
    // يتم الحفاظ على بيانات البكسل ولكن يتم تحويلها إلى الصيغة المطلوبة.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // إضافة الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### انظر أيضًا

* struct [Point](../../../aspose.imaging/point/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush() {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`LinearGradientBrush`](../) باستخدام المعلمات الافتراضية. اللون الابتدائي هو الأسود، واللون النهائي هو الأبيض، والزاوية 45 درجة والمستطيل يقع في (0,0) بحجم (1,1).

```csharp
public LinearGradientBrush()
```

### انظر أيضًا

* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)


