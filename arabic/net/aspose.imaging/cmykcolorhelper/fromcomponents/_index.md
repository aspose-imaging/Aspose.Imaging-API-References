---
title: FromComponents
second_title: Aspose.Imaging لمرجع NET API
description: إنشاء CMYK من قيم 32 بت سماوي وأرجواني وأصفر وأسود.
type: docs
weight: 10
url: /ar/net/aspose.imaging/cmykcolorhelper/fromcomponents/
---
## CmykColorHelper.FromComponents method

إنشاء CMYK من قيم 32 بت سماوي وأرجواني وأصفر وأسود.

```csharp
public static int FromComponents(int cyan, int magenta, int yellow, int black)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cyan | Int32 | مكون السماوي. القيم الصالحة من 0 إلى 255. |
| magenta | Int32 | المكون الأرجواني. القيم الصالحة من 0 إلى 255. |
| yellow | Int32 | المكون الأصفر. القيم الصالحة من 0 إلى 255. |
| black | Int32 | المكون الأسود. القيم الصالحة من 0 إلى 255. |

### قيمة الإرجاع

يتم تقديم لون CMYK كقيمة عدد صحيح 32 بت.

### أمثلة

يوضح المثال التالي كيفية تحويل ألوان CMYK إلى نظيراتها من RGB بطريقة سريعة باتباع الصيغ المباشرة دون استخدام ملفات تعريف ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // ازرق سماوي
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // أرجواني
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // الأصفر
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // أسود
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

// يبدو الإخراج كالتالي:
// تحويل CMYK إلى RGB بدون استخدام ملفات تعريف ICC.
// CMYK (255،0،0،0) = > ; RGB (0،255،255)
// CMYK (0،255،0،0) = > ; RGB (255،0،255)
// CMYK (0،0،255،0) = > ; RGB (255،255،0)
// CMYK (0،0،0،255) = > ; RGB (0،0،0)
```

### أنظر أيضا

* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->