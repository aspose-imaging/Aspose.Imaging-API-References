---
title: "CmykColorHelper.FromComponents"
second_title: "Aspose.Imaging for .NET API Reference"
description: "CmykColorHelper method. تنشئ CMYK من قيم سيان، ماجنتا، أصفر وأسود بعمق 32 بت."
type: docs
weight: 10
url: /ar/net/aspose.imaging/cmykcolorhelper/fromcomponents/
---
## CmykColorHelper.FromComponents method

ينشئ CMYK من قيم سيان، ماجنتا، أصفر وأسود 32-بت.

```csharp
public static int FromComponents(int cyan, int magenta, int yellow, int black)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| سيان | Int32 | المكوّن السماوي. القيم الصالحة هي من 0 إلى 255. |
| ماجنتا | Int32 | المكوّن الماجنتا. القيم الصالحة هي من 0 إلى 255. |
| أصفر | Int32 | المكوّن الأصفر. القيم الصالحة هي من 0 إلى 255. |
| أسود | Int32 | المكوّن الأسود. القيم الصالحة هي من 0 إلى 255. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

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

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


