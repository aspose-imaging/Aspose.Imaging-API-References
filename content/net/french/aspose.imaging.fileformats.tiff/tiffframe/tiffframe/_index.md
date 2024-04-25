---
title: TiffFrame
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duTiffFrameaspose.imaging.fileformats.tiff/tiffframe classe.
type: docs
weight: 10
url: /fr/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger une image et initialiser les données de pixel et de palette du cadre avec. |

### Voir également

* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel charger une image et initialiser les données de pixel et de palette du cadre avec. |
| options | TiffOptions | Les options à utiliser pour le cadre nouvellement créé. |

### Voir également

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(string path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger une image et initialiser les données de pixels et de palette du cadre. |

### Voir également

* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| path | String | Chemin d'accès à partir duquel charger une image et initialiser les données de pixels et de palette du cadre. |
| options | TiffOptions | Les options à utiliser pour le cadre nouvellement créé. |

### Voir également

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(RasterImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette du cadre. |

### Exemples

L'exemple suivant montre comment composer un fichier TIFF multipage à partir d'images raster individuelles.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Il s'agit de la police et du pinceau pour dessiner du texte sur des cadres individuels.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // Crée 5 images
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Crée une image PNG et dessine le numéro de page dessus.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Crée un cadre basé sur l'image PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Ajoute le cadre à l'image TIFF.
        tiffImage.AddFrame(frame);
    }

    // L'image a été créée avec un seul cadre par défaut. Enlevons-le.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // N'oubliez pas de supprimer le cadre si vous ne l'ajoutez pas à un autre TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image avec laquelle initialiser les données de pixel et de palette du cadre. |
| options | TiffOptions | Les options à utiliser pour le cadre nouvellement créé. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Initialise une nouvelle instance du[`TiffFrame`](../../tiffframe) classe.

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | TiffOptions | Les options de cadre. |
| width | Int32 | La largeur. |
| height | Int32 | La hauteur. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le paramètre Options est nul. |

### Exemples

Cet exemple montre comment créer une image TIFF à partir de zéro et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Définissez 8 bits pour chaque composant de couleur.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Définir l'ordre des octets Big Endian (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Définit la compression LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Définit le modèle de couleur RVB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tous les composants de couleur seront stockés dans un seul plan.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crée un cadre TIFF de 100x100 px.
// Notez que vous n'avez pas besoin de supprimer explicitement un cadre s'il est inclus dans TiffImage.
// Lorsque le conteneur est supprimé, tous les cadres seront supprimés automatiquement.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Remplir tout le cadre avec le dégradé bleu-jaune.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Crée une image TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

Cet exemple montre comment créer une image TIFF avec 2 cadres et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Options pour la première image
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Définissez 8 bits pour chaque composant de couleur.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Définir l'ordre des octets Big Endian (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Définit la compression LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Définit le modèle de couleur RVB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Tous les composants de couleur seront stockés dans un seul plan.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crée la première image TIFF de 100x100 px.
// Notez que vous n'avez pas à supprimer explicitement les cadres s'ils sont inclus dans TiffImage.
// Lorsque le conteneur est supprimé, tous les cadres seront supprimés automatiquement.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Remplir le premier cadre avec le dégradé bleu-jaune.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Options pour la première image
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Définir 1 bit par pixel pour une image N/B.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Définit l'ordre des octets Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Définit la compression CCITT Group 3 Fax.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Définit le modèle de couleur N/B où 0 est noir, 1 est blanc.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Crée la deuxième image TIFF de 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Remplir le deuxième cadre avec le dégradé bleu-jaune.
// Il sera automatiquement converti au format N/B en raison des paramètres correspondants du cadre.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Crée une image TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Voir également

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* espace de noms [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
