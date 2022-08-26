---
title: ToArgbIcc
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit Standardprofilen.
type: docs
weight: 80
url: /de/net/aspose.imaging/cmykcolorhelper/toargbicc/
---
## ToArgbIcc(int[]) {#toargbicc_2}

Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit Standardprofilen.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | Int32[] | Die CMYK-Pixel werden als 32-Bit-Ganzzahlwerte dargestellt. |

### Rückgabewert

Die ARGB-Farben.

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | Int32[] | Die CMYK-Farben werden als 32-Bit-Integerwerte dargestellt. |
| cmykIccStream | Stream | Der Stream, der das CMYK-Icc-Profil enthält. |
| rgbIccStream | Stream | Der Stream, der das RGB Icc-Profil enthält. |

### Rückgabewert

Die ARGB-Farben.

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToArgbIcc(int) {#toargbicc}

Die Konvertierung von CMYK-Farbe in ARGB-Farbe mithilfe der Icc-Konvertierung mit Standardprofilen.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | Int32 | Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert. |

### Rückgabewert

Die ARGB-Farbe.

### Beispiele

Das folgende Beispiel zeigt, wie CMYK-Farben mithilfe von ICC-Profilen in ihre RGB-Gegenstücke konvertiert werden.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Gelb
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Schwarz
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

// Geben Sie Ihren Pfad zu benutzerdefinierten RGB- und CMYK-ICC-Profilen an.
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

//Die Ausgabe sieht so aus:
//Konvertieren Sie CMYK in RGB mit Standard-ICC-Profilen.            
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
// Konvertieren Sie CMYK in RGB mit benutzerdefinierten ICC-Profilen.
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

Die Konvertierung von CMYK-Farbe in ARGB-Farbe mithilfe der Icc-Konvertierung mit benutzerdefiniertem Profil.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | Int32 | Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert. |
| cmykIccStream | Stream | Der Stream, der das CMYK-Icc-Profil enthält. |
| rgbIccStream | Stream | Der Stream, der das RGB Icc-Profil enthält. |

### Rückgabewert

Die ARGB-Farbe.

### Beispiele

Das folgende Beispiel zeigt, wie CMYK-Farben mithilfe von ICC-Profilen in ihre RGB-Gegenstücke konvertiert werden.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Gelb
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Schwarz
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

// Geben Sie Ihren Pfad zu benutzerdefinierten RGB- und CMYK-ICC-Profilen an.
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

//Die Ausgabe sieht so aus:
//Konvertieren Sie CMYK in RGB mit Standard-ICC-Profilen.            
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//CMYK(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
// Konvertieren Sie CMYK in RGB mit benutzerdefinierten ICC-Profilen.
//CMYK(255,0,0,0) => RGB(46.188.220)
//CMYK(0,255,0,0) => RGB(231,52,142)
//(0,0,255,0) => RGB(244,253,63)
//CMYK(0,0,0,255) => RGB(21,21,21)
```

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
