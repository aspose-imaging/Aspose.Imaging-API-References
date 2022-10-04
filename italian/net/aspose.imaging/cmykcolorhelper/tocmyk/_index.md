---
title: ToCmyk
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La conversione dai colori ARGB ai colori CMYK.
type: docs
weight: 90
url: /it/net/aspose.imaging/cmykcolorhelper/tocmyk/
---
## ToCmyk(int[]) {#tocmyk_3}

La conversione dai colori ARGB ai colori CMYK.

```csharp
public static int[] ToCmyk(int[] argbPixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | Int32[] | I colori ARGB presentati come valori interi a 32 bit. |

### Valore di ritorno

I colori CMYK presentati come valori interi a 32 bit.

### Guarda anche

* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToCmyk(int) {#tocmyk_1}

La conversione dal colore ARGB al colore CMYK.

```csharp
public static int ToCmyk(int argbPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixel | Int32 | Il colore ARGB presentato come un valore intero a 32 bit. |

### Valore di ritorno

Il colore CMYK presentato come un valore intero a 32 bit.

### Guarda anche

* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToCmyk(Color) {#tocmyk}

La conversione dal colore ARGB al colore CMYK.

```csharp
public static int ToCmyk(Color pixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | Color | Il colore ARGB. |

### Valore di ritorno

Il colore CMYK presentato come un valore intero a 32 bit.

### Esempi

L'esempio seguente riempie l'area centrale di un'immagine raster con pixel neri usando il metodo Aspose.Imaging.RasterImage.SaveCmyk32Pixels.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Ottieni una rappresentazione intera del nero nello spazio colore CMYK.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Il quadrato nero.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Disegna il quadrato nero al centro dell'immagine.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

L'esempio seguente mostra come convertire i colori RGB nelle loro controparti CMYK senza applicare i profili ICC.

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

//L'output è simile a questo:
//Converti RGB in CMYK senza utilizzare i profili ICC.
//RGB(255,0,0) => CMYK(0,255,255,0)
//RGB(0,128,0) => CMYK(255,0,255,127)
//RGB(0,0,255) => CMYK(255,255,0,0)
```

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToCmyk(Color[]) {#tocmyk_2}

La conversione dai colori ARGB ai colori CMYK.

```csharp
public static int[] ToCmyk(Color[] pixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | Color[] | I colori ARGB. |

### Valore di ritorno

I colori CMYK presentati come valori interi a 32 bit.

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->