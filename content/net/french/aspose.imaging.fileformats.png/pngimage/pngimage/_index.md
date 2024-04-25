---
title: PngImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duPngImageaspose.imaging.fileformats.png/pngimage classe.
type: docs
weight: 10
url: /fr/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur. |
| height | Int32 | La hauteur. |

### Exemples

Cet exemple montre comment créer une image PNG de la taille spécifiée, la remplir avec une couleur unie et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Effectuez un traitement d'image, par exemple remplissez toute l'image en rouge.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Enregistrer dans un fichier.
    pngImage.Save(dir + "output.png");
}
```

### Voir également

* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin pour charger une image. |

### Exemples

Cet exemple montre comment charger une image PNG à partir d'un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image PNG à partir d'un fichier.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Transforme l'image en représentation en niveaux de gris
    pngImage.Grayscale();

    // Enregistrer dans un fichier.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Voir également

* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(RasterImage rasterImage)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image raster. |

### Exemples

Cet exemple montre comment charger une image PNG à partir d'une image BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image PNG TrueColor à partir d'une image BMP.
// Tout d'abord, créez une image BMP temporelle qui servira de base à la création d'une image PNG.
// Vous pouvez également charger une image BMP à partir d'un fichier ou utiliser une image de tout autre format raster.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Remplit toute l'image BMP en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin pour charger une image. |
| colorType | PngColorType | Le type de couleur. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException |  |

### Exemples

Cet exemple montre comment charger une image PNG à partir d'un fichier avec le type de couleur spécifié.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image PNG à partir d'un fichier.
// Notez que l'image colorée sera automatiquement convertie en niveaux de gris.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Enregistrer dans un fichier.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Voir également

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image raster. |
| colorType | PngColorType | Le type de couleur. |

### Exemples

Cet exemple montre comment charger une image PNG à partir d'une image BMP avec le type de couleur spécifié.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image PNG en niveaux de gris à partir d'une image BMP colorée.
// Tout d'abord, créez une image BMP temporelle qui servira de base à la création d'une image PNG.
// Vous pouvez également charger une image BMP à partir d'un fichier ou utiliser une image de tout autre format raster.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Remplit toute l'image BMP en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Les couleurs des pixels de l'image seront converties en leurs homologues en niveaux de gris.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux pour charger une image. |

### Exemples

Cet exemple montre comment charger une image PNG à partir d'un fichier ou d'un flux de fichiers.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image PNG à partir d'un flux de fichiers.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Transforme l'image en représentation en niveaux de gris
        pngImage.Grayscale();

        // Enregistrer dans un fichier.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Voir également

* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur. |
| height | Int32 | La hauteur. |
| colorType | PngColorType | Le type de couleur. |

### Exemples

Cet exemple montre comment créer une image PNG de la taille spécifiée avec le type de couleur spécifié, la remplir avec une couleur unie et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image PNG en niveaux de gris de 100x100 px.
// Toutes les couleurs seront automatiquement converties au format en niveaux de gris.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Effectuez un traitement d'image, par exemple remplissez toute l'image en rouge.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Enregistrer dans un fichier.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Voir également

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Initialise une nouvelle instance du[`PngImage`](../../pngimage) classe.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pngOptions | PngOptions | Les options png. |
| width | Int32 | La largeur. |
| height | Int32 | La hauteur. |

### Exemples

Cet exemple montre comment créer une image PNG avec les options spécifiées, la remplir avec un dégradé de couleurs linéaire et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Le nombre de bits par canal de couleur
createOptions.BitDepth = 8;

// Chaque pixel est un triplet (rouge, vert, bleu) suivi de la composante alpha.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Le niveau maximum de compression.
createOptions.CompressionLevel = 9;

// L'utilisation de filtres permet de compresser plus efficacement les images tonales continues.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Utiliser le chargement progressif
createOptions.Progressive = true;

// Crée une image PNG avec des paramètres personnalisés.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplit l'image avec un dégradé semi-transparent.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Enregistrer dans un fichier.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### Voir également

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* espace de noms [Aspose.Imaging.FileFormats.Png](../../pngimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
