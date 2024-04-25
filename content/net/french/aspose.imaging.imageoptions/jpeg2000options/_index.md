---
title: Jpeg2000Options
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de format de fichier Jpeg2000.
type: docs
weight: 10020
url: /fr/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Les options de format de fichier Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Initialise une nouvelle instance du[`Jpeg2000Options`](../jpeg2000options) classe. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Initialise une nouvelle instance du[`Jpeg2000Options`](../jpeg2000options) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec) { get; set; } | Obtient ou définit le codec JPEG2000 |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments) { get; set; } | Obtient ou définit les marqueurs de commentaire Jpeg. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios) { get; set; } | Obtient ou définit le tableau de taux de compression. Différents taux de compression pour les couches successives. Le taux spécifié pour chaque niveau de qualité est le facteur de compression souhaité. Diminution des taux requis. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible) { get; set; } | Obtient ou définit une valeur indiquant si vous utilisez la compression DWT 9-7 irréversible (vrai) ou utilisez la compression DWT 5-3 sans perte (par défaut). |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.imaging.imageoptions/jpeg2000options/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

L'exemple suivant montre comment convertir une image vectorielle de plusieurs pages au format JPEG 2000 de manière générale sans faire référence à un type d'image particulier.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exporte uniquement les deux premières pages. En fait, une seule page sera pixellisée car JPEG 2000 n'est pas un format multipage.
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
