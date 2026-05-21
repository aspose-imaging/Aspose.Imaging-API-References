---
title: "CmykColorHelper.ToCmykIcc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "CmykColorHelper method. التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة"
type: docs
weight: 130
url: /ar/net/aspose.imaging/cmykcolorhelper/tocmykicc/
---
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_5}

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البكسلات | Color[] | ألوان ARGB. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

### قيمة الإرجاع

ألوان CMYK معروضة كقيم صحيحة 32-بت.

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int[], Stream, Stream) {#tocmykicc_7}

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

```csharp
public static int[] ToCmykIcc(int[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البكسلات | Int32[] | ألوان ARGB. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

### قيمة الإرجاع

ألوان CMYK معروضة كقيم صحيحة 32-بت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_4}

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
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

---

## ToCmykIcc(int[]) {#tocmykicc_6}

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

```csharp
public static int[] ToCmykIcc(int[] pixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البكسلات | Int32[] | ألوان ARGB. |

### قيمة الإرجاع

ألوان CMYK معروضة كقيم صحيحة 32-بت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

```csharp
public static int ToCmykIcc(Color pixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسل | لون | لون ARGB. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

## أمثلة

المثال التالي يوضح كيفية تحويل ألوان RGB إلى نظيراتها في CMYK باستخدام ملفات تعريف ICC.

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

// حدد المسار إلى ملفات تعريف ICC لـ RGB و CMYK.
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

//الإخراج يبدو هكذا:
//حوّل RGB إلى CMYK باستخدام ملفات تعريف ICC الافتراضية.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//حوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int) {#tocmykicc_2}

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

```csharp
public static int ToCmykIcc(int argb)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | Int32 | لون ARGB. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسل | لون | لون ARGB. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

## أمثلة

المثال التالي يوضح كيفية تحويل ألوان RGB إلى نظيراتها في CMYK باستخدام ملفات تعريف ICC.

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

// حدد المسار إلى ملفات تعريف ICC لـ RGB و CMYK.
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

//الإخراج يبدو هكذا:
//حوّل RGB إلى CMYK باستخدام ملفات تعريف ICC الافتراضية.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//حوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToCmykIcc(int, Stream, Stream) {#tocmykicc_3}

التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

```csharp
public static int ToCmykIcc(int argb, Stream rgbIccStream, Stream cmykIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | Int32 | لون ARGB. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

### قيمة الإرجاع

لون CMYK معروض كقيمة صحيحة 32-بت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


