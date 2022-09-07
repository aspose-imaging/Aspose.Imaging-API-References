---
title: LinearGradientBrush
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفLinearGradientBrushaspose.imaging.brushes/lineargradientbrush فئة ذات معلمات افتراضية . لون البداية أسود ولون النهاية أبيض والزاوية 45 درجة والمستطيل يقع في 00 بحجم 11 .
type: docs
weight: 10
url: /ar/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة ذات معلمات افتراضية . لون البداية أسود ولون النهاية أبيض والزاوية 45 درجة والمستطيل يقع في (0،0) بحجم (1،1) .

```csharp
public LinearGradientBrush()
```

### أنظر أيضا

* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة بالنقاط والألوان المحددة.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| point1 | Point | أ[`Point`](../../../aspose.imaging/point) الهيكل الذي يمثل نقطة البداية للتدرج الخطي. |
| point2 | Point | أ[`Point`](../../../aspose.imaging/point) الهيكل الذي يمثل نقطة نهاية التدرج الخطي. |
| color1 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون البداية للتدرج الخطي. |
| color2 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون النهاية للتدرج الخطي. |

### أمثلة

يوضح المثال التالي كيفية إنشاء نسخة بتدرج الرمادي لإطار موجود وإضافته إلى صورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم وليس مؤقتًا.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العلوية إلى الزاوية اليمنى السفلية للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الإطار النشط بفرشاة متدرجة خطية.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // خيارات تدرج الرمادي
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // إنشاء نسخة بتدرج الرمادي من الإطار النشط.
    // يتم الاحتفاظ ببيانات البكسل ولكن يتم تحويلها إلى التنسيق المطلوب.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // أضف الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### أنظر أيضا

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة بالنقاط والألوان المحددة.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| point1 | PointF | أ[`PointF`](../../../aspose.imaging/pointf) الهيكل الذي يمثل نقطة البداية للتدرج الخطي. |
| point2 | PointF | أ[`PointF`](../../../aspose.imaging/pointf) الهيكل الذي يمثل نقطة نهاية التدرج الخطي. |
| color1 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون البداية للتدرج الخطي. |
| color2 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون النهاية للتدرج الخطي. |

### أنظر أيضا

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | أ[`RectangleF`](../../../aspose.imaging/rectanglef) الهيكل الذي يحدد حدود التدرج الخطي. |
| color1 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون البداية للتدرج. |
| color2 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون النهاية للتدرج. |
| angle | Single | الزاوية المقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني لخط اتجاه التدرج. |

### أنظر أيضا

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | RectangleF | أ[`RectangleF`](../../../aspose.imaging/rectanglef) الهيكل الذي يحدد حدود التدرج الخطي. |
| color1 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون البداية للتدرج. |
| color2 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون النهاية للتدرج. |
| angle | Single | الزاوية المقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني لخط اتجاه التدرج. |

### أنظر أيضا

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | أ[`RectangleF`](../../../aspose.imaging/rectanglef) الهيكل الذي يحدد حدود التدرج الخطي. |
| color1 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون البداية للتدرج. |
| color2 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون النهاية للتدرج. |
| angle | Single | الزاوية المقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني لخط اتجاه التدرج. |
| isAngleScalable | Boolean | إذا تم التعيين على`حقيقي` يتم تغيير الزاوية أثناء التحولات بهذا[`LinearGradientBrush`](../../lineargradientbrush). |

### أنظر أيضا

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`LinearGradientBrush`](../../lineargradientbrush) فئة تعتمد على المستطيل ، ألوان البداية والنهاية ، وزاوية الاتجاه.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | RectangleF | أ[`RectangleF`](../../../aspose.imaging/rectanglef) الهيكل الذي يحدد حدود التدرج الخطي. |
| color1 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون البداية للتدرج. |
| color2 | Color | أ[`Color`](../../../aspose.imaging/color) الهيكل الذي يمثل لون النهاية للتدرج. |
| angle | Single | الزاوية المقاسة بالدرجات في اتجاه عقارب الساعة من المحور السيني لخط اتجاه التدرج. |
| isAngleScalable | Boolean | إذا تم التعيين على`حقيقي` يتم تغيير الزاوية أثناء التحولات بهذا[`LinearGradientBrush`](../../lineargradientbrush). |

### أنظر أيضا

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* مساحة الاسم [Aspose.Imaging.Brushes](../../lineargradientbrush)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
