---
title: "CmykColorHelper.ToArgbIcc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة CmykColorHelper. التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية"
type: docs
weight: 80
url: /ar/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | Int32[] | بكسلات CMYK مقدمة كقيم صحيحة 32-بت. |

### قيمة الإرجاع

ألوان ARGB.

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | Int32[] | ألوان CMYK معروضة كقيم صحيحة 32-بت. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |

### قيمة الإرجاع

ألوان ARGB.

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

التحويل من لون CMYK إلى ARGB Color باستخدام تحويل Icc مع ملفات تعريف افتراضية.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | Int32 | لون CMYK معروض كقيمة صحيحة 32-بت. |

### قيمة الإرجاع

لون ARGB.

## أمثلة

المثال التالي يوضح كيفية تحويل ألوان CMYK إلى نظيراتها RGB باستخدام ملفات تعريف ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Yellow
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Black
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

// حدد المسار إلى ملفات تعريف ICC المخصصة لـ RGB و CMYK.
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

//الإخراج يبدو هكذا:
//تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC الافتراضية.            
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC مخصصة.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

التحويل من لون CMYK إلى ARGB Color باستخدام تحويل Icc مع ملف تعريف مخصص.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | Int32 | لون CMYK معروض كقيمة صحيحة 32-بت. |
| cmykIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgbIccStream | Stream | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |

### قيمة الإرجاع

لون ARGB.

## أمثلة

المثال التالي يوضح كيفية تحويل ألوان CMYK إلى نظيراتها RGB باستخدام ملفات تعريف ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Yellow
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Black
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

// حدد المسار إلى ملفات تعريف ICC المخصصة لـ RGB و CMYK.
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

//الإخراج يبدو هكذا:
//تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC الافتراضية.            
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//تحويل CMYK إلى RGB باستخدام ملفات تعريف ICC مخصصة.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### انظر أيضًا

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


