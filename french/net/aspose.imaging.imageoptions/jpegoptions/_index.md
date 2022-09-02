---
title: JpegOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de création du format de fichier jpeg.
type: docs
weight: 10030
url: /fr/net/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

Les options de création du format de fichier jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | Initialise une nouvelle instance du[`JpegOptions`](../jpegoptions) classe. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | Initialise une nouvelle instance du[`JpegOptions`](../jpegoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel) { get; set; } | Obtient ou définit des bits par canal pour une image jpeg sans perte. Nous prenons désormais en charge de 2 à 8 bits par canal. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | Le profil de couleur CMJN de destination pour les images jpeg CMJN. À utiliser pour enregistrer des images. Doit être en paire avec RGBColorProfile pour une conversion de couleur correcte. |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype) { get; set; } | Obtient ou définit le type de couleur pour l'image jpeg. |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment) { get; set; } | Obtient ou définit le commentaire du fichier jpeg. |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype) { get; set; } | Obtient ou définit le type de compression. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata) { get; set; } | Obtenir ou définir le conteneur de données exif |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling) { get; set; } | Obtient ou définit les sous-échantillonnages horizontaux pour chaque composant. |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif) { get; set; } | Obtient ou définit le jfif. |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | Obtient ou définit la différence JPEG-LS liée au codage presque sans perte (paramètre NEAR de la spécification JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | Obtient ou définit le mode d'entrelacement JPEG-LS. |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset) { get; set; } | Obtient ou définit les paramètres prédéfinis JPEG-LS. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | Obtient ou définit une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière-plan, si le canal alpha est présent. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality) { get; set; } | Obtient ou définit la qualité de l'image. |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings) { get; set; } | Obtient ou définit les paramètres de l'optimiseur RD. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit) { get; set; } | Obtient ou définit l'unité de résolution. |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | Le profil de couleur RVB de destination pour les images JPEG CMJN. À utiliser pour enregistrer des images. Doit être en paire avec CMYKColorProfile pour une conversion correcte des couleurs. |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | Obtient ou définit le mode d'arrondi de l'échantillon pour ajuster une valeur 8 bits à une valeur n bits.BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality) { get; } | La qualité mise à l'échelle. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling) { get; set; } | Obtient ou définit les sous-échantillonnages verticaux pour chaque composant. |
| override [XmpData](../../aspose.imaging.imageoptions/jpegoptions/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

Cet exemple montre l'utilisation de System.IO.Stream pour créer un nouveau fichier image (un type JPEG)

```csharp
[C#]

// Crée une instance de JpegOptions et définit ses différentes propriétés
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Créer une instance de System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Définir la propriété source pour l'instance de JpegOptions
// Le deuxième paramètre booléen détermine si le flux est éliminé une fois sorti de la portée
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

// Crée une instance de Image et appelle la méthode Create avec JpegOptions comme paramètre pour initialiser l'objet Image   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    // faire du traitement d'image
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

L'exemple suivant montre comment convertir une image vectorielle multipage au format JPEG de manière générale sans faire référence à un type d'image particulier.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exporte uniquement les deux premières pages. En fait, une seule page sera pixellisée car JPEG n'est pas un format multi-pages.
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
