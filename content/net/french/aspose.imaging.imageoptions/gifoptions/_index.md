---
title: GifOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de création de format de fichier gif.
type: docs
weight: 10000
url: /fr/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Les options de création de format de fichier gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Initialise une nouvelle instance du[`GifOptions`](../gifoptions) classe. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Initialise une nouvelle instance du[`GifOptions`](../gifoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Obtient ou définit l'index de couleur d'arrière-plan GIF. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Obtient ou définit la résolution de couleur GIF. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Obtient ou définit une valeur indiquant si le GIF a une bande-annonce. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image GIF a une couleur transparente. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Vrai si l'image doit être entrelacée. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Obtient ou définit une valeur indiquant si les entrées de la palette sont triées. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Obtient ou définit le nombre de boucles (par défaut 1 boucle) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Obtient ou définit la différence de pixels maximale autorisée. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression optimale avec perte est de 80. 30 est une compression très légère, 200 est lourde. Cela fonctionne mieux lorsque seule une faible perte est introduite, et en raison de la limitation de l'algorithme de compression des niveaux de perte très élevés ne donneront pas autant de gain. La plage de valeurs autorisées est [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Obtient ou définit le format des pixels GIF. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

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

L'exemple suivant montre comment convertir une image vectorielle multipage au format GIF de manière générale sans faire référence à un type d'image particulier.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exporte uniquement les deux premières pages. Ces pages seront présentées sous forme de cadres animés dans le GIF de sortie.
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

Cet exemple montre comment charger les informations de pixel dans un tableau de type couleur, manipuler le tableau et le redéfinir sur l'image. Pour effectuer ces opérations, cet exemple crée un nouveau fichier Image (au format GIF) utilisant l'objet MemoryStream.

```csharp
[C#]

//Créer une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créer une instance de GifOptions et définir ses différentes propriétés, y compris la propriété Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Créer une instance de Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        // Récupère les pixels de l'image en spécifiant la zone comme limite de l'image
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Boucle sur le tableau et définit la couleur du pixel indexé alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Définit la couleur du pixel indexé sur jaune
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                // Définit la couleur du pixel indexé sur bleu
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Appliquer les changements de pixel à l'image
        image.SavePixels(image.Bounds, pixels);

        // Enregistrer toutes les modifications.
        image.Save();
    }

    // Écrire MemoryStream dans le fichier
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espace de noms [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
