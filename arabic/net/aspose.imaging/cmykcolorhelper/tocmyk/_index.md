---
title: "CmykColorHelper.ToCmyk"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CmykColorHelper. التحويل من ألوان ARGB إلى ألوان CMYK"
type: docs
weight: 90
url: /ar/net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

التحويل من ألوان ARGB إلى ألوان CMYK.

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | Int32[] | ألوان ARGB مقدمة كقيم صحيحة 32-بت. |

### قيمة الإرجاع

ألوان CMYK معروضة كقيم صحيحة 32-بت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

التحويل من لون ARGB إلى لون CMYK.

```csharp
public static int ToCmyk(int argbPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixel | Int32 | لون ARGB مقدم كقيمة صحيحة 32-بت. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

التحويل من لون ARGB إلى لون CMYK.

```csharp
public static int ToCmyk(Color pixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسل | لون | لون ARGB. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

## أمثلة

المثال التالي يملأ المنطقة المركزية من صورة نقطية بكسلات سوداء باستخدام طريقة Aspose.Imaging.RasterImage.SaveCmyk32Pixels.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على تمثيل صحيح للون الأسود في مساحة ألوان CMYK.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // المربع الأسود.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // ارسم المربع الأسود في مركز الصورة.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

المثال التالي يوضح كيفية تحويل ألوان RGB إلى نظيراتها في CMYK دون تطبيق ملفات تعريف ICC.

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK without using ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

//الإخراج يبدو هكذا:
//تحويل RGB إلى CMYK دون استخدام ملفات تعريف ICC.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

التحويل من ألوان ARGB إلى ألوان CMYK.

```csharp
public static int[] ToCmyk(Color[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البكسلات | Color[] | ألوان ARGB. |

### قيمة الإرجاع

ألوان CMYK معروضة كقيم صحيحة 32-بت.

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


