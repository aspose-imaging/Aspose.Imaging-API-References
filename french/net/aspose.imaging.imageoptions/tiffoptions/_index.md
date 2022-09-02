---
title: TiffOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de limage par les paramètres de largeur et de hauteur il nest donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut mais cela ne signifie pas que cette option est définie explicitement en tant que valeur de balise. Pour vérifier que la balise est présente utilisez la propriété Tags ou la méthode IsTagPresent correspondante.
type: docs
weight: 10220
url: /fr/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

Les options de format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de l'image par les paramètres de largeur et de hauteur, il n'est donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut, mais cela ne signifie pas que cette option est définie explicitement en tant que valeur de balise. Pour vérifier que la balise est présente, utilisez la propriété Tags ou la méthode IsTagPresent correspondante.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Initialise une nouvelle instance du[`TiffOptions`](../tiffoptions) classe. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Initialise une nouvelle instance du[`TiffOptions`](../tiffoptions)classer. Par défaut, la convention Little Endian est utilisée. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Initialise une nouvelle instance du[`TiffOptions`](../tiffoptions) classe. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialise une nouvelle instance du[`TiffOptions`](../tiffoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Obtient ou définit l'option de stockage alpha. Options autres queUnspecified sont utilisés lorsqu'il y a plus de 3[`SamplesPerPixel`](./samplesperpixel) défini. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Obtient ou définit l'artiste. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Obtient les bits par pixel. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Obtient ou définit les bits par échantillon. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Obtient ou définit une valeur indiquant l'ordre des octets tiff. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Obtient ou définit la palette de couleurs. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Obtient ou définit la qualité de l'image compressée. Utilisé avec la compression Jpeg. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Obtient ou définit la compression. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Obtient ou définit le copyright. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Obtient ou définit la date et l'heure. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Obtient ou définit une valeur indiquant si l'exportation du profil ICC est désactivée (le profil ICC est appliqué au préalable aux pixels source). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Obtient ou définit le nom du document. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Obtient ou définit le pointeur sur EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Obtient les valeurs d'échantillons supplémentaires. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Obtient ou définit les options de télécopie t4. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Obtient ou définit la norme de fichier TIFF. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Obtient ou définit les indices de demi-teintes. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Obtient ou définit le flux de profil Icc. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Obtient ou définit la description de l'image. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Obtient ou définit la longueur de l'image. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Obtient ou définit la largeur de l'image. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Obtient ou définit les noms d'encre. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Obtient une valeur indiquant si l'image est en mosaïque. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Obtient une valeur indiquant si le[`TiffOptions`](../tiffoptions) ont été correctement configurés. Utilisez la méthode Validate as pour trouver la raison de l'échec. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Obtient ou définit la valeur maximale de l'échantillon. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Obtient ou définit la valeur minimale de l'échantillon. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Obtient ou définit l'orientation. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Obtient ou définit le nom de la page. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Obtient ou définit la balise de numéro de page. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Obtient ou définit la photométrie. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Obtient ou définit la configuration planaire. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Obtient ou définit le prédicteur pour la compression LZW. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Obtient ou définit l'unité de résolution. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Obtient ou définit les lignes par bande. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Obtient ou définit le format de l'échantillon. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Obtient les échantillons par pixel. Pour modifier cette valeur de propriété, utilisez le[`BitsPerSample`](./bitspersample) propriété setter. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Obtient ou définit le fabricant du scanner. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Obtient ou définit le modèle du scanner. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Obtient ou définit la valeur maximale de l'échantillon. La valeur a un type de champ qui correspond le mieux aux exemples de données (type Byte, Short ou Long). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Obtient ou définit la valeur minimale de l'échantillon. La valeur a un type de champ qui correspond le mieux aux exemples de données (type Byte, Short ou Long). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Obtient ou définit le type de logiciel. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Obtient ou définit le nombre d'octets de bande. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Obtient ou définit les décalages de bande. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Obtient ou définit les balises. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Obtient ou définit l'imprimante cible. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Obtient ou définit le seuil. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Obtient ou définit le nombre d'octets de mosaïque. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Obtient ou définit la longueur des tuiles. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Obtient ou définit les décalages de mosaïque. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Obtient ou définit la largeur des tuiles. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Obtient le nombre total de pages. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Obtient le nombre de balises valides. Il ne s'agit pas du nombre total de balises mais du nombre de balises pouvant être conservées. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Obtient ou définit l'auteur de l'image, qui est utilisé par l'Explorateur Windows. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Obtient ou définit un commentaire sur l'image, qui est utilisé par l'Explorateur Windows. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Obtient ou définit l'image du sujet, qui est utilisée par l'Explorateur Windows. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Obtient ou définit la position x. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Obtient ou définit des informations sur l'image, utilisées par l'Explorateur Windows. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Obtient ou définit des informations sur l'image, utilisées par l'Explorateur Windows. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Obtient ou définit la résolution x. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Obtient ou définit les YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Obtient ou définit la position y. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Obtient ou définit la résolution y. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Ajoute une nouvelle balise. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Ajoute les balises. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Obtient l'instance de la balise par type. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Détermine si le tag est présent ou non dans les options. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Supprime la balise. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Valide si les options ont une combinaison valide de balises |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Obtient le nombre de balises valides. |

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

L'exemple suivant montre comment convertir une image vectorielle multipage au format TIFF de manière générale sans faire référence à un type d'image particulier.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exporte uniquement les deux premières pages. Ces pages seront présentées sous forme de cadres dans le fichier TIFF de sortie.
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

Ces exemples utilisent GraphicsPath et la classe Graphics pour créer et manipuler des figures sur une surface Image. L'exemple crée une nouvelle image (de type Tiff), efface la surface et dessine des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour restituer les chemins sur la surface.

```csharp
[C#]

//Créer une instance de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Créer une instance de TiffOptions et définir ses différentes propriétés
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Définir la source de l'instance de ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Créer une instance de Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Créer et initialiser une instance de la classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Effacer la surface graphique
        graphics.Clear(Color.Wheat);

        //Créer une instance de la classe GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Créer une instance de la classe Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Ajouter des formes à l'objet Figure
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Ajouter un objet Figure à GraphicsPath
        graphicspath.AddFigure(figure);

        // Dessine un chemin avec un objet Pen de couleur noire
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // Enregistrer toutes les modifications.
        image.Save();
    }
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espace de noms [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
