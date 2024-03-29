---
title: GetM
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient la valeur du composant magenta.
type: docs
weight: 40
url: /fr/net/aspose.imaging/cmykcolorhelper/getm/
---
## CmykColorHelper.GetM method

Obtient la valeur du composant magenta.

```csharp
public static int GetM(int cmyk)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| cmyk | Int32 | La couleur CMJN présentée sous la forme d'une valeur entière 32 bits. |

### Return_Value

La valeur du composant magenta.

### Exemples

L'exemple suivant montre comment convertir les couleurs RVB en leurs homologues CMJN sans appliquer les profils ICC.

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

//La sortie ressemble à ceci :
//Convertit RVB en CMJN sans utiliser de profils ICC.
//RVB(255,0,0) => CMJN(0,255,255,0)
//RVB(0,128,0) => CMJN(255,0,255,127)
//RVB(0,0,255) => CMJN(255,255,0,0)
```

L'exemple suivant montre comment convertir rapidement les couleurs CMJN en leurs homologues RVB en suivant des formules simples sans utiliser de profils ICC.

```csharp
[C#]

int[] cmykColors = new int[]
{
    Aspose.Imaging.CmykColorHelper.FromComponents(255, 0, 0, 0),   // Cyan
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 255, 0, 0),   // Magenta
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 255, 0),   // Jaune
    Aspose.Imaging.CmykColorHelper.FromComponents(0, 0, 0, 255),   // Le noir
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

//La sortie ressemble à ceci :
//Convertir CMJN en RVB sans utiliser les profils ICC.
//CMJN(255,0,0,0) => RVB(0,255,255)
//CMJN(0,255,0,0) => RVB (255,0,255)
//CMJN(0,0,255,0) => RVB(255,255,0)
//CMJN(0,0,0,255) => RVB(0,0,0)
```

### Voir également

* class [CmykColorHelper](../../cmykcolorhelper)
* espace de noms [Aspose.Imaging](../../cmykcolorhelper)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
