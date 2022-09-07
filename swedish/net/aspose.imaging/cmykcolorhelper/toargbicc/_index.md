---
title: ToArgbIcc
second_title: Aspose.Imaging för .NET API-referens
description: Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering med standardprofiler.
type: docs
weight: 80
url: /sv/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering med standardprofiler.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK-pixlarna presenteras som 32-bitars heltalsvärden. |

### Returvärde

ARGB-färgerna.

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

Konverteringen från CMYK-färger till ARGB-färger med hjälp av Icc-konvertering med anpassade profiler.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK-färgerna presenteras som 32-bitars heltalsvärden. |
| cmykIccStream | Stream | Strömmen som innehåller CMYK Icc-profil. |
| rgbIccStream | Stream | Strömmen som innehåller RGB Icc-profil. |

### Returvärde

ARGB-färgerna.

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering med standardprofiler.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |

### Returvärde

ARGB-färgen.

### Exempel

Följande exempel visar hur man konverterar CMYK-färger till deras RGB-motsvarigheter med hjälp av ICC-profiler.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Gul
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Svart
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

// Ange din väg till anpassade RGB- och CMYK ICC-profiler.
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

//Utgången ser ut så här:
//Konvertera CMYK till RGB med standard ICC-profiler.            
//CMYK(255;0;0;0) => RGB(46 188 220)
//CMYK(0,255;0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21;21;21)
//Konvertera CMYK till RGB med hjälp av anpassade ICC-profiler.
//CMYK(255;0;0;0) => RGB(46 188 220)
//CMYK(0,255;0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21;21;21)
```

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering med anpassad profil.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | Int32 | CMYK-färgen presenteras som ett 32-bitars heltalsvärde. |
| cmykIccStream | Stream | Strömmen som innehåller CMYK Icc-profil. |
| rgbIccStream | Stream | Strömmen som innehåller RGB Icc-profil. |

### Returvärde

ARGB-färgen.

### Exempel

Följande exempel visar hur man konverterar CMYK-färger till deras RGB-motsvarigheter med hjälp av ICC-profiler.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Gul
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Svart
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

// Ange din väg till anpassade RGB- och CMYK ICC-profiler.
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

//Utgången ser ut så här:
//Konvertera CMYK till RGB med standard ICC-profiler.            
//CMYK(255;0;0;0) => RGB(46 188 220)
//CMYK(0,255;0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21;21;21)
//Konvertera CMYK till RGB med hjälp av anpassade ICC-profiler.
//CMYK(255;0;0;0) => RGB(46 188 220)
//CMYK(0,255;0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21;21;21)
```

### Se även

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namnutrymme [Aspose.Imaging](../../cmykcolorhelper)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
