---
title: ToCmykIcc
second_title: Aspose.Imaging لمرجع NET API
description: التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف المخصصة.
type: docs
weight: 110
url: /ar/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف المخصصة.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pixels | Color[] | ألوان ARGB. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف CMYK Icc. |

### قيمة الإرجاع

يتم تقديم ألوان CMYK كقيم عدد صحيح 32 بت.

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pixels | Color[] | ألوان ARGB. |

### قيمة الإرجاع

يتم تقديم ألوان CMYK كقيم عدد صحيح 32 بت.

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف الافتراضية.

```csharp
public static int ToCmykIcc(Color pixel)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pixel | Color | لون ARGB. |

### قيمة الإرجاع

يتم تقديم لون CMYK كقيمة عدد صحيح 32 بت.

### أمثلة

يوضح المثال التالي كيفية تحويل ألوان RGB إلى نظيراتها في CMYK باستخدام ملفات تعريف ICC.

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK using default ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

// حدد مسارك إلى ملفات تعريف RGB و CMYK ICC.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert RGB to CMYK using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (Aspose.Imaging.Color rgbColor in rgbColors)
    {
        int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

        System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
    }
}

// يبدو الإخراج كالتالي:
// تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC الافتراضية.
// RGB (255،0،0) = > ; CMYK (0،254،249،15)
// RGB (0،128،0) = > ; CMYK (247،21،254،85)
// RGB (0،0،255) = > ; CMYK (254،195،0،134)
// تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC المخصصة.
// RGB (255،0،0) = > ; CMYK (0،207،219،0)
// RGB (0،128،0) = > ; CMYK (238،16،254،80)
// RGB (0،0،255) = > ; CMYK (242،182،0،0)
```

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات التعريف المخصصة.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pixel | Color | لون ARGB. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف CMYK Icc. |

### قيمة الإرجاع

يتم تقديم لون CMYK كقيمة عدد صحيح 32 بت.

### أمثلة

يوضح المثال التالي كيفية تحويل ألوان RGB إلى نظيراتها في CMYK باستخدام ملفات تعريف ICC.

```csharp
[C#]

Aspose.Imaging.Color[] rgbColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
    Aspose.Imaging.Color.Blue,
};

System.Console.WriteLine("Convert RGB to CMYK using default ICC profiles.");
foreach (Aspose.Imaging.Color rgbColor in rgbColors)
{
    int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor);
    int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
    int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
    int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
    int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

    System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
}

// حدد مسارك إلى ملفات تعريف RGB و CMYK ICC.
string dir = "c:\\temp\\iccprofiles\\";

System.Console.WriteLine("Convert RGB to CMYK using custom ICC profiles.");
using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
{
    foreach (Aspose.Imaging.Color rgbColor in rgbColors)
    {
        int cmyk = Aspose.Imaging.CmykColorHelper.ToCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = Aspose.Imaging.CmykColorHelper.GetC(cmyk);
        int m = Aspose.Imaging.CmykColorHelper.GetM(cmyk);
        int y = Aspose.Imaging.CmykColorHelper.GetY(cmyk);
        int k = Aspose.Imaging.CmykColorHelper.GetK(cmyk);

        System.Console.WriteLine("RGB({0},{1},{2})\t\t=> CMYK({3},{4},{5},{6})", rgbColor.R, rgbColor.G, rgbColor.B, c, m, y, k);
    }
}

// يبدو الإخراج كالتالي:
// تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC الافتراضية.
// RGB (255،0،0) = > ; CMYK (0،254،249،15)
// RGB (0،128،0) = > ; CMYK (247،21،254،85)
// RGB (0،0،255) = > ; CMYK (254،195،0،134)
// تحويل RGB إلى CMYK باستخدام ملفات تعريف ICC المخصصة.
// RGB (255،0،0) = > ; CMYK (0،207،219،0)
// RGB (0،128،0) = > ; CMYK (238،16،254،80)
// RGB (0،0،255) = > ; CMYK (242،182،0،0)
```

### أنظر أيضا

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* مساحة الاسم [Aspose.Imaging](../../cmykcolorhelper)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
