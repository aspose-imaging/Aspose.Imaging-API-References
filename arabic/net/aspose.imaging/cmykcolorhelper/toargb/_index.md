---
title: "CmykColorHelper.ToArgb"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CmykColorHelper. التحويل من ألوان CMYK إلى ألوان ARGB."
type: docs
weight: 60
url: /ar/net/aspose.imaging/cmykcolorhelper/toargb/
---
## ToArgb(int[]) {#toargb_1}

التحويل من ألوان CMYK إلى ألوان ARGB.

```csharp
public static Color[] ToArgb(int[] cmykPixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | Int32[] | ألوان CMYK معروضة كقيم صحيحة 32-بت. |

### قيمة الإرجاع

ألوان ARGB.

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgb(int) {#toargb}

التحويل من لون CMYK إلى لون ARGB.

```csharp
public static Color ToArgb(int cmykPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | Int32 | لون CMYK معروض كقيمة صحيحة 32-بت. |

### قيمة الإرجاع

لون ARGB.

## أمثلة

المثال التالي يوضح كيفية تحويل ألوان CMYK إلى نظيراتها RGB بطريقة سريعة باستخدام صيغ بسيطة دون استخدام ملفات تعريف ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Yellow
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Black
};

System.Console.WriteLine("Convert CMYK to RGB without using ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgb(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);

    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

//الإخراج يبدو هكذا:
//تحويل CMYK إلى RGB دون استخدام ملفات تعريف ICC.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


