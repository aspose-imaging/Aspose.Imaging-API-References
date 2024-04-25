---
title: GetCloseImagePalette
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient la palette de couleurs de limage raster palettise limage au cas où limage nen aurait pas. Si la palette existe elle sera utilisée à la place pour effectuer des calculs.
type: docs
weight: 60
url: /fr/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Exemples

L'exemple suivant charge une image BMP et l'enregistre dans BMP à l'aide de diverses options d'enregistrement.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Créer des BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
    saveOptions.BitsPerPixel = 8;

    // Définit la palette de couleurs 8 bits la plus proche qui couvre le nombre maximal de pixels de l'image, de sorte qu'une image palettisée
    // est presque impossible à distinguer visuellement d'un non palettisé.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Enregistrer sans compression.
    // Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Définissez la résolution horizontale et verticale sur 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

L'exemple suivant montre comment palettiser une image BMP pour réduire sa taille de sortie.

```csharp
[C#]

// Crée une image BMP 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Remplir toute l'image avec le pinceau dégradé linéaire.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Obtient la palette de couleurs 8 bits la plus proche qui couvre autant de pixels que possible, de sorte qu'une image palettisée
    // est presque impossible à distinguer visuellement d'un non palettisé.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // La palette 8 bits contient au plus 256 couleurs.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// La sortie ressemble à ceci :
// La taille de l'image palettisée est de 11078 octets.
// La taille de l'image non palettisée est de 40054 octets.
```

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espace de noms [Aspose.Imaging](../../colorpalettehelper)
* Assemblée [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. La palette est sur le point d'être optimisée pour une meilleure qualité d'image indexée ou prise "TEL QUEL" lorsque PaletteMiningMethod.UseCurrentPalette est utilisé.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |
| paletteMiningMethod | PaletteMiningMethod | La méthode d'extraction de palette. |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Exemples

L'exemple suivant montre comment compresser une image PNG, en utilisant la couleur indexée avec la palette la mieux adaptée

```csharp
[C#]

// Charge l'image png        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Utiliser le type de couleur indexé
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Utiliser la compression maximale
         CompressionLevel = 9,
      // Obtient la palette de couleurs 8 bits la plus proche qui couvre autant de pixels que possible, de sorte qu'une image palettisée
         // est presque impossible à distinguer visuellement d'un non palettisé.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // La taille du fichier de sortie doit être considérablement réduite
```

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espace de noms [Aspose.Imaging](../../colorpalettehelper)
* Assemblée [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| destBounds | Rectangle | L'image de destination délimite. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espace de noms [Aspose.Imaging](../../colorpalettehelper)
* Assemblée [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| destBounds | Rectangle | L'image de destination délimite. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |
| useImagePalette | Boolean | S'il est défini, il utilisera sa propre palette d'images si disponible |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espace de noms [Aspose.Imaging](../../colorpalettehelper)
* Assemblée [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| destBounds | Rectangle | L'image de destination délimite. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |
| useImagePalette | Boolean | S'il est défini, il utilisera sa propre palette d'images si disponible |
| alphaBlendInColor | Color | La couleur qui doit être utilisée comme couleur d'arrière-plan pour le remplacement alpha semi-transparent. |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Voir également

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* espace de noms [Aspose.Imaging](../../colorpalettehelper)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
