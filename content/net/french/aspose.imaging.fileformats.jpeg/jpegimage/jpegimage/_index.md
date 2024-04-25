---
title: JpegImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duJpegImageaspose.imaging.fileformats.jpeg/jpegimage classe.
type: docs
weight: 10
url: /fr/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

Initialise une nouvelle instance du[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |

### Exemples

L'exemple montre comment charger un JpegImage à partir d'un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image JPEG à partir d'un fichier.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Effectue un traitement d'image.
    // Enregistrer dans un autre fichier JPEG.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### Voir également

* class [JpegImage](../../jpegimage)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Assemblée [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

Initialise une nouvelle instance du[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |

### Exemples

L'exemple montre comment charger un JpegImage à partir d'un flux de fichiers.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image JPEG à partir d'un flux de fichiers.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Effectue un traitement d'image.
        // Enregistrer dans un autre fichier JPEG.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### Voir également

* class [JpegImage](../../jpegimage)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Assemblée [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

Initialise une nouvelle instance du[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette. |

### Exemples

L'exemple montre comment charger un JpegImage à partir d'un autre RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image JPEG à partir d'une autre image raster.
// Tout d'abord, créez une image PNG temporelle qui servira de base à la création d'une image JPEG.
// Vous pouvez également charger une image PNG à partir d'un fichier ou utiliser une image de tout autre format raster.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Remplir toute l'image PNG en rouge.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // Crée une image JPEG basée sur l'image PNG.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // Enregistrer dans un fichier JPEG
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Assemblée [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

Initialise une nouvelle instance du[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image. |
| height | Int32 | La hauteur de l'image. |

### Exemples

L'exemple suivant montre comment créer une image JPEG de la taille spécifiée.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image JPEG de 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Effectue un traitement d'image.
    // Enregistrer dans un fichier.
    jpegImage.Save(dir + "output.jpg");
}
```

L'exemple suivant charge une image BMP et l'enregistre au format JPEG à l'aide de diverses options d'enregistrement.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un fichier.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Effectue un traitement d'image.

    // Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Le nombre de bits par canal est de 8.
    // Lorsqu'une palette est utilisée, l'index de couleur est stocké dans les données de l'image au lieu de la couleur elle-même.
    saveOptions.BitsPerChannel = 8;

    // Définit le type de compression progressive.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Définit la qualité de l'image. C'est une valeur comprise entre 1 et 100.
    saveOptions.Quality = 100;

    // Définissez la résolution horizontale/verticale sur 96 points par pouce.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Si l'image source est colorée, elle sera convertie en niveaux de gris.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Utilisez une palette pour réduire la taille de sortie.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

### Voir également

* class [JpegImage](../../jpegimage)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Assemblée [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

Initialise une nouvelle instance du[`JpegImage`](../../jpegimage) classe.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| jpegOptions | JpegOptions | Les options jpeg. |
| width | Int32 | Largeur de l'image. |
| height | Int32 | Hauteur de l'image. |

### Exemples

L'exemple suivant charge une image BMP et l'enregistre au format JPEG à l'aide de diverses options d'enregistrement.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image BMP à partir d'un fichier.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Effectue un traitement d'image.

    // Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Le nombre de bits par canal est de 8.
    // Lorsqu'une palette est utilisée, l'index de couleur est stocké dans les données de l'image au lieu de la couleur elle-même.
    saveOptions.BitsPerChannel = 8;

    // Définit le type de compression progressive.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Définit la qualité de l'image. C'est une valeur comprise entre 1 et 100.
    saveOptions.Quality = 100;

    // Définissez la résolution horizontale/verticale sur 96 points par pouce.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Si l'image source est colorée, elle sera convertie en niveaux de gris.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Utilisez une palette pour réduire la taille de sortie.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

L'exemple suivant montre comment créer une image JPEG de la taille spécifiée avec les paramètres spécifiés.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image JPEG de 100x100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb en conséquence.
createOptions.BitsPerChannel = 8;

// Définit le type de compression progressive.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Définit la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.Quality = 100;

// Définissez la résolution horizontale/verticale sur 96 points par pouce.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Il s'agit d'une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous-échantillonnés, compressés.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Remplit l'image avec un dégradé de gris
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Enregistrer dans un fichier.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Voir également

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
