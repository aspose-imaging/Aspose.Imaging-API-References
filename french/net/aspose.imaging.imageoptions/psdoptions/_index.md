---
title: PsdOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Le format de fichier psd créer des options.
type: docs
weight: 10140
url: /fr/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Le format de fichier psd créer des options.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Initialise une nouvelle instance du[`PsdOptions`](../psdoptions) classe. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Initialise une nouvelle instance du[`PsdOptions`](../psdoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Obtient ou définit le nombre de bits par canal de couleur. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Obtient ou définit le nombre de canaux de couleur. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | Obtient ou définit le mode de couleur psd. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | Obtient ou définit la méthode de compression psd. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Obtient ou définit la version du format de fichier. Il peut s'agir de PSD ou de PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Obtient ou définit une valeur indiquant si [actualiser les données d'aperçu de l'image] - option utilisée pour maximiser la compatibilité avec d'autres visualiseurs d'images PSD. Veuillez noter que le dessin des calques de texte jusqu'à la mise en page finale n'est pas pris en charge pour la plate-forme Compact Framework |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Obtient ou définit une valeur indiquant si - Supprimer la ressource globale du moteur de texte - Utilisé pour certains fichiers psd à calques de texte, dans le seul cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement pour les calques de texte de polices absents liés). Après avoir utilisé cette option, l'utilisateur doit créer le prochain fichier ouvert dans Photoshop : Menu "Texte" -&gt; "Traiter les polices absentes". Après cette opération, tout le texte apparaîtra à nouveau. Veuillez noter que cette opération peut entraîner des modifications finales de la mise en page. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | Obtient ou définit les options de vectorisation PSD. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | Obtient ou définit la version du fichier psd. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | Obtenir ou définir le conteneur de données XMP |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

Cet exemple illustre l'utilisation de l'API Aspsoe.Imaging pour .Net pour convertir des images au format PSD. Pour atteindre cet objectif, cet exemple charge une image existante, puis l'enregistre au format PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une instance de la classe d'image et l'initialise avec un fichier existant via le chemin du fichier
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Créer une instance de la classe PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // Définissez CompressionMethod sur RLE
    //Remarque : l'autre méthode de compression prise en charge est CompressionMethod.RAW [Pas de compression]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    // Définissez le ColorMode sur GrayScale
    //Remarque : les autres ColorModes pris en charge sont ColorModes.Bitmap et ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    // Enregistrez l'image sur le disque avec les paramètres PsdOptions fournis
    image.Save(dir + "output.psd", psdOptions);
}
```

L'exemple suivant montre comment convertir une image vectorielle de plusieurs pages au format PSD de manière générale sans faire référence à un type d'image particulier.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exporte uniquement les deux premières pages. Ces pages seront présentées sous forme de calques dans le PSD de sortie.
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
