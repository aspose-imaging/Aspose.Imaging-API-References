---
title: ToArgbIcc
second_title: Aspose.Imaging لمرجع NET API
description: التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.
type: docs
weight: 80
url: /ar/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cmykPixels | Int32[] | يتم تقديم وحدات البكسل CMYK كقيم عدد صحيح 32 بت. |

### قيمة الإرجاع

ألوان ARGB .

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات التعريف المخصصة.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cmykPixels | Int32[] | يتم تقديم ألوان CMYK كقيم عدد صحيح 32 بت. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف CMYK Icc. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |

### قيمة الإرجاع

ألوان ARGB .

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cmykPixel | Int32 | يتم تقديم لون CMYK كقيمة عدد صحيح 32 بت. |

### قيمة الإرجاع

لون ARGB .

### أمثلة

يوضح المثال التالي كيفية تحويل ألوان CMYK إلى نظائرها من RGB باستخدام ملفات تعريف ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // ازرق سماوي
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // أرجواني
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // الأصفر
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // أسود
};

System.Console.WriteLine("Convert CMYK to RGB using default ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
        
    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// حدد مسارك إلى ملفات تعريف RGB و CMYK ICC المخصصة.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert CMYK to RGB using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (int cmykColor in cmykColors)
    {
        Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
            
        System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
    }
}

// يبدو الإخراج كالتالي:
// تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC الافتراضية.            
// CMYK (255،0،0،0) = > ; RGB (46188220)
// CMYK (0،255،0،0) = > ; RGB (231،52،142)
// CMYK (0،0،255،0) = > ; RGB (244،253،63)
// CMYK (0،0،0،255) = > ; RGB (21،21،21)
// تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC المخصصة.
// CMYK (255،0،0،0) = > ; RGB (46188220)
// CMYK (0،255،0،0) = > ; RGB (231،52،142)
// (0،0،255،0) = > ; RGB (244،253،63)
// CMYK (0،0،0،255) = > ; RGB (21،21،21)
```

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cmykPixel | Int32 | يتم تقديم لون CMYK كقيمة عدد صحيح 32 بت. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف CMYK Icc. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |

### قيمة الإرجاع

لون ARGB .

### أمثلة

يوضح المثال التالي كيفية تحويل ألوان CMYK إلى نظائرها من RGB باستخدام ملفات تعريف ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // ازرق سماوي
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // أرجواني
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // الأصفر
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // أسود
};

System.Console.WriteLine("Convert CMYK to RGB using default ICC profiles.");
foreach (int cmykColor in cmykColors)
{
    Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
        
    System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
}

// حدد مسارك إلى ملفات تعريف RGB و CMYK ICC المخصصة.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert CMYK to RGB using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (int cmykColor in cmykColors)
    {
        Aspose.Imaging.Color rgbColor = Aspose.Imaging.CmykColorHelper.ToArgbIcc(cmykColor);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmykColor);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmykColor);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmykColor);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmykColor);
            
        System.Console.WriteLine("CMYK({0},{1},{2},{3})\t\t=> RGB({4},{5},{6})", c, m, y, k, rgbColor.R, rgbColor.G, rgbColor.B);
    }
}

// يبدو الإخراج كالتالي:
// تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC الافتراضية.            
// CMYK (255،0،0،0) = > ; RGB (46188220)
// CMYK (0،255،0،0) = > ; RGB (231،52،142)
// CMYK (0،0،255،0) = > ; RGB (244،253،63)
// CMYK (0،0،0،255) = > ; RGB (21،21،21)
// تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC المخصصة.
// CMYK (255،0،0،0) = > ; RGB (46188220)
// CMYK (0،255،0،0) = > ; RGB (231،52،142)
// (0،0،255،0) = > ; RGB (244،253،63)
// CMYK (0،0،0،255) = > ; RGB (21،21،21)
```

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
