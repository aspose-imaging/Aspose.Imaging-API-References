---
title: BmpImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duBmpImageaspose.imaging.fileformats.bmp/bmpimage classe.
type: docs
weight: 10
url: /fr/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | l'image raster est nulle;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment charger un BmpImage à partir d'un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un fichier.
// Les pixels source seront convertis au format 32-bpp si nécessaire.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Effectue un traitement d'image.
    // Enregistrer dans un autre fichier BMP.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Voir également

* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |
| bitsPerPixel | UInt16 | Les bits par pixel. |
| compression | BitmapCompression | La compression à utiliser. |
| horizontalResolution | Double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |
| verticalResolution | Double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'image raster ne peut pas être nulle ; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment charger un BmpImage à partir d'un fichier avec la profondeur de bits et la résolution spécifiées.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un fichier.
// Les pixels source seront convertis au format 24-bpp si nécessaire.
// La résolution sera définie sur 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Effectue un traitement d'image.
    // Enregistrer dans un autre fichier BMP.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Voir également

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'image raster ne peut pas être nulle ; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment charger un BmpImage à partir d'un flux de fichiers.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un flux de fichier.
// Les pixels source seront convertis au format 32-bpp si nécessaire.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Effectue un traitement d'image.
        // Enregistrer dans un autre fichier BMP.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Voir également

* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |
| bitsPerPixel | UInt16 | Les bits par pixel. |
| compression | BitmapCompression | La compression à utiliser. |
| horizontalResolution | Double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |
| verticalResolution | Double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'image raster ne peut pas être nulle ; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment charger un BmpImage à partir d'un flux de fichiers avec la profondeur de bits et la résolution spécifiées.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un flux de fichier.
// Les pixels source seront convertis au format 24-bpp si nécessaire.
// La résolution sera définie sur 96 dpi.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Effectue un traitement d'image.
        // Enregistrer dans un autre fichier BMP.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Voir également

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'image raster ne peut pas être nulle ; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment charger un BmpImage à partir d'une autre instance de RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une nouvelle image PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Remplir toute l'image PNG en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Crée une image BMP basée sur l'image PNG.
    // Les pixels source seront convertis au format 32-bpp si nécessaire.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // Enregistrer dans un fichier BMP
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette. |
| bitsPerPixel | UInt16 | Les bits par pixel. |
| compression | BitmapCompression | La compression à utiliser. |
| horizontalResolution | Double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |
| verticalResolution | Double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | L'image raster ne peut pas être nulle ; rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment charger un BmpImage à partir d'une autre instance de RasterImage avec la profondeur de bits et la compression spécifiées.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une nouvelle image PNG.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Remplir toute l'image PNG en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Crée une image BMP basée sur l'image PNG.
    // Les pixels source seront convertis au format 24-bpp si nécessaire.
    // La résolution sera définie sur 96 dpi.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Enregistrer dans un fichier BMP
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image. |
| height | Int32 | La hauteur de l'image. |

### Exceptions

| exception | condition |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment créer un BmpImage de la taille spécifiée.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image BMP 32-bpp de 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Remplit toute l'image en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Enregistrer dans un fichier BMP
    bmpImage.Save(dir + "output.bmp");
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

* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image. |
| height | Int32 | La hauteur de l'image. |
| bitsPerPixel | UInt16 | Les bits par pixel. |
| palette | IColorPalette | La palette de couleurs. |

### Exceptions

| exception | condition |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment créer un BmpImage de la taille spécifiée avec la palette spécifiée.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Crée une palette monochrome qui ne contient que des couleurs rouges et vertes.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Crée une image monochrome BMP 1-bpp de 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Remplit la moitié supérieure de l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Remplir la moitié inférieure de l'image en vert.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Enregistrer en BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Voir également

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Initialise une nouvelle instance du[`BmpImage`](../../bmpimage) classe.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image. |
| height | Int32 | La hauteur de l'image. |
| bitsPerPixel | UInt16 | Les bits par pixel. |
| palette | IColorPalette | La palette de couleurs. |
| compression | BitmapCompression | La compression à utiliser. |
| horizontalResolution | Double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |
| verticalResolution | Double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut légèrement différer de la résolution passée. |

### Exceptions

| exception | condition |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | La hauteur doit être positive. |
| ArgumentException | La palette doit être spécifiée pour les images avec 8 bits par pixel ou moins.;palette |

### Exemples

L'exemple montre comment créer un BmpImage à l'aide de diverses options.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Crée une palette monochrome qui ne contient que des couleurs rouges et vertes.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Crée une image monochrome BMP 1-bpp de 100 x 100 px.
// La résolution horizontale et verticale sera définie sur 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Remplit la moitié supérieure de l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Remplir la moitié inférieure de l'image en vert.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Enregistrer dans un fichier BMP
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Voir également

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
