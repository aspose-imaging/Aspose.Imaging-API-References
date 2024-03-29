---
title: ToCmyk
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Konvertierung von ARGB-Farben in CMYK-Farben.
type: docs
weight: 90
url: /de/net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

Die Konvertierung von ARGB-Farben in CMYK-Farben.

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | Int32[] | Die ARGB-Farben werden als 32-Bit-Ganzzahlwerte dargestellt. |

### Rückgabewert

Die CMYK-Farben werden als 32-Bit-Ganzzahlwerte dargestellt.

### Siehe auch

* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

Die Umwandlung von ARGB-Farbe in CMYK-Farbe.

```csharp
public static int ToCmyk(int argbPixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixel | Int32 | Die als 32-Bit-Integerwert dargestellte ARGB-Farbe. |

### Rückgabewert

Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert.

### Siehe auch

* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

Die Umwandlung von ARGB-Farbe in CMYK-Farbe.

```csharp
public static int ToCmyk(Color pixel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | Color | Die ARGB-Farbe. |

### Rückgabewert

Die CMYK-Farbe, dargestellt als 32-Bit-Ganzzahlwert.

### Beispiele

Im folgenden Beispiel wird der zentrale Bereich eines Rasterbilds mithilfe der Aspose.Imaging.RasterImage.SaveCmyk32Pixels-Methode mit schwarzen Pixeln gefüllt.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Holen Sie sich eine ganzzahlige Darstellung von Schwarz im CMYK-Farbraum.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Das schwarze Quadrat.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Zeichnen Sie das schwarze Quadrat in der Mitte des Bildes.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

Das folgende Beispiel zeigt, wie Sie RGB-Farben in ihre CMYK-Gegenstücke konvertieren, ohne ICC-Profile anzuwenden.

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

//Die Ausgabe sieht so aus:
//RGB in CMYK umwandeln, ohne ICC-Profile zu verwenden.
//RGB(255,0,0) => CMYK(0,255,255,0)
//RGB(0,128,0) => CMYK(255,0,255,127)
//RGB(0,0,255) => CMYK(255,255,0,0)
```

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

Die Konvertierung von ARGB-Farben in CMYK-Farben.

```csharp
public static int[] ToCmyk(Color[] pixels)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | Color[] | Die ARGB-Farben. |

### Rückgabewert

Die CMYK-Farben werden als 32-Bit-Ganzzahlwerte dargestellt.

### Siehe auch

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* namensraum [Aspose.Imaging](../../cmykcolorhelper)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
