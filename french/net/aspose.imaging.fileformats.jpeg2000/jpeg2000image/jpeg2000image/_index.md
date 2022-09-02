---
title: Jpeg2000Image
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image classe.
type: docs
weight: 10
url: /fr/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |

### Exemples

Cet exemple montre comment charger une image JPEG2000 à partir d'un fichier et l'enregistrer au format PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image JPEG2000.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Enregistrer en PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Le chemin pour charger l'image à partir de et initialiser les données de pixel et de palette avec |
| bitsPerPixel | Int32 | Les bits par pixel. |

### Voir également

* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |

### Exemples

Cet exemple montre comment charger une image JPEG2000 à partir d'un flux de fichiers et l'enregistrer au format PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image JPEG2000 à partir du flux.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // Enregistrer en PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Voir également

* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger l'image et initialiser les données de pixel et de palette avec. |
| bitsPerPixel | Int32 | Les bits par pixel. |

### Voir également

* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image |
| height | Int32 | La hauteur des images |

### Exemples

Cet exemple montre comment créer une image JPEG2000 et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image JPEG2000 de 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Remplit toute l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Enregistrer dans un fichier
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Voir également

* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image |
| height | Int32 | La hauteur des images |
| options | Jpeg2000Options | Les options. |

### Exemples

Cet exemple montre comment créer une image PNG et l'enregistrer au format JPEG2000 avec les options souhaitées.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplit toute l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Utiliser la transformée en ondelettes discrète irréversible 9-7
    saveOptions.Irreversible = true;

    // JP2 est le format "conteneur" pour les flux codés JPEG 2000.
    // J2K correspond à des données compressées brutes, sans wrapper.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // Enregistrer dans un fichier
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

Cet exemple montre comment créer une image JPEG2000 avec les options souhaitées et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Utiliser la transformée en ondelettes discrète irréversible 9-7
createOptions.Irreversible = true;

// JP2 est le format "conteneur" pour les flux codés JPEG 2000.
// J2K correspond à des données compressées brutes, sans wrapper.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// Crée une image JPEG2000 de 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Remplit toute l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Enregistrer dans un fichier
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Voir également

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image |
| height | Int32 | La hauteur des images |
| bitsCount | Int32 | Les bits comptent. |

### Voir également

* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image. |

### Exemples

Cet exemple montre comment créer une image JPEG2000 à partir d'une autre image raster.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image PNG de 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Remplit toute l'image en rouge.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Crée une image JPEG2000 basée sur l'image PNG.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // Enregistrer dans un fichier
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Initialise une nouvelle instance du[`Jpeg2000Image`](../../jpeg2000image) classe.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rasterImage | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette. |
| bitsPerPixel | Int32 | Les bits par pixel. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* espace de noms [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
