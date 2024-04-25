---
title: TiffOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duTiffOptionsaspose.imaging.imageoptions/tiffoptions classe.
type: docs
weight: 10
url: /fr/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Initialise une nouvelle instance du[`TiffOptions`](../../tiffoptions) classe.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Le format de fichier tiff attendu. |
| byteOrder | TiffByteOrder | L'ordre des octets du format de fichier tiff à utiliser. |

### Voir également

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Initialise une nouvelle instance du[`TiffOptions`](../../tiffoptions)classer. Par défaut, la convention Little Endian est utilisée.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Le format de fichier tiff attendu. |

### Exemples

L'exemple suivant montre comment créer une copie en niveaux de gris d'un cadre existant et l'ajouter à une image TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Crée une source de fichier permanente et non temporaire.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Le dégradé linéaire du coin supérieur gauche au coin inférieur droit de l'image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Remplir le cadre actif avec un pinceau dégradé linéaire.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Options de niveaux de gris
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Crée une copie en niveaux de gris du cadre actif.
    // Les données de pixel sont conservées mais converties au format souhaité.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Ajoute le cadre nouvellement créé à l'image TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

Cet exemple montre comment enregistrer une image raster au format TIFF à l'aide de diverses options.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Définissez 8 bits pour chaque composant de couleur.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Définir l'ordre des octets Big Endian (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Définit la compression LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Permet de réduire la taille des images à tons continus.
// Actuellement, ce champ n'est utilisé qu'avec l'encodage LZW car LZW est probablement le seul schéma d'encodage TIFF
// qui bénéficie de manière significative d'une étape de prédiction.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Définit le modèle de couleur RVB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Pour YCbCr, vous pouvez utiliser l'un des choix suivants :
// Champ YCbCrSubSampling Facteurs d'échantillonnage JPEG
// ----------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(valeur par défaut) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tous les composants de couleur seront stockés dans un seul plan.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crée un cadre TIFF de 100x100 px.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Remplir toute l'image avec le dégradé bleu-jaune.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### Voir également

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Initialise une nouvelle instance du[`TiffOptions`](../../tiffoptions) classe.

```csharp
public TiffOptions(TiffOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | TiffOptions | Les options à partir desquelles copier. |

### Voir également

* class [TiffOptions](../../tiffoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Initialise une nouvelle instance du[`TiffOptions`](../../tiffoptions) classe.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| tags | TiffDataType[] | Les balises avec lesquelles initialiser les options. |

### Voir également

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../tiffoptions)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
