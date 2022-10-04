---
title: ToArgb
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La conversione dai colori CMYK ai colori ARGB.
type: docs
weight: 60
url: /it/net/aspose.imaging/cmykcolorhelper/toargb/
---
## ToArgb(int[]) {#toargb_1}

La conversione dai colori CMYK ai colori ARGB.

```csharp
public static Color[] ToArgb(int[] cmykPixels)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | Int32[] | I colori CMYK presentati come valori interi a 32 bit. |

### Valore di ritorno

I colori ARGB.

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

---

## ToArgb(int) {#toargb}

La conversione dal colore CMYK al colore ARGB.

```csharp
public static Color ToArgb(int cmykPixel)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | Int32 | Il colore CMYK presentato come un valore intero a 32 bit. |

### Valore di ritorno

Il colore ARGB.

### Esempi

L'esempio seguente mostra come convertire rapidamente i colori CMYK nelle loro controparti RGB seguendo semplici formule senza utilizzare i profili ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Ciano
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Giallo
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Nero
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

//L'output è simile a questo:
//Converti CMYK in RGB senza utilizzare i profili ICC.
//CMYK(255,0,0,0) => RGB(0,255,255)
//CMYK(0,255,0,0) => RGB(255,0,255)
//CMYK(0,0,255,0) => RGB(255,255,0)
//CMYK(0,0,0,255) => RGB(0,0,0)
```

### Guarda anche

* struct [Color](../../color)
* class [CmykColorHelper](../../cmykcolorhelper)
* spazio dei nomi [Aspose.Imaging](../../cmykcolorhelper)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->