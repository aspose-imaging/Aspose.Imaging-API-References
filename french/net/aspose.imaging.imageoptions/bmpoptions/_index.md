---
title: BmpOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de création de format de fichier bmp.
type: docs
weight: 9910
url: /fr/net/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

Les options de création de format de fichier bmp.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BmpOptions](bmpoptions#constructor)() | Initialise une nouvelle instance du[`BmpOptions`](../bmpoptions) classe. |
| [BmpOptions](bmpoptions#constructor_1)(BmpOptions) | Initialise une nouvelle instance du[`BmpOptions`](../bmpoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel) { get; set; } | Obtient ou définit le nombre de bits d'image par pixel. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression) { get; set; } | Obtient ou définit la compression. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

Cet exemple crée un nouveau fichier image à un emplacement du disque spécifié par la propriété Source de l'instance BmpOptions. Plusieurs propriétés pour l'instance BmpOptions sont définies avant de créer l'image réelle. Surtout la propriété Source, qui fait référence à l'emplacement réel du disque dans ce cas.

```csharp
[C#]

//Créer une instance de BmpOptions et définir ses différentes propriétés
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Créer une instance de Image et l'initialiser avec une instance de BmpOptions en appelant la méthode Create
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // faire du traitement d'image

    // Enregistrer toutes les modifications
    image.Save();
}
```

Cet exemple illustre l'utilisation de différentes classes de l'espace de noms SaveOptions à des fins d'exportation. Une image de type Gif est chargée dans une instance de Image puis exportée vers plusieurs formats.

```csharp
[C#]

string dir = "c:\\temp\\";

//Charge une image existante (de type Gif) dans une instance de la classe Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Exporter au format de fichier BMP en utilisant les options par défaut
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    // Exporter au format de fichier JPEG en utilisant les options par défaut
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    // Exporter au format de fichier PNG en utilisant les options par défaut
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    // Exporter au format de fichier TIFF en utilisant les options par défaut
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

L'exemple suivant montre comment convertir une image vectorielle multipage au format BMP de manière générale sans faire référence à un type d'image particulier.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exporte uniquement les deux premières pages. En fait, une seule page sera pixellisée car BMP n'est pas un format multi-pages.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espace de noms [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
