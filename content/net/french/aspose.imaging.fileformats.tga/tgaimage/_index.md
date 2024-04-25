---
title: TgaImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Limage TGA.
type: docs
weight: 7580
url: /fr/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

L'image TGA.

```csharp
public class TgaImage : RasterCachedImage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TgaImage](tgaimage#constructor)(RasterImage) | Initialise une nouvelle instance du[`TgaImage`](../tgaimage) classe. |
| [TgaImage](tgaimage#constructor_1)(Stream) | Initialise une nouvelle instance du[`TgaImage`](../tgaimage) classe. |
| [TgaImage](tgaimage#constructor_2)(string) | Initialise une nouvelle instance du[`TgaImage`](../tgaimage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments) { get; set; } | Obtient ou définit les commentaires de l'auteur. Il s'agit d'un champ ASCII composé de 324 octets organisés en quatre lignes de 80 caractères, chacune suivie d'un terminateur nul. |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname) { get; set; } | Obtient ou définit le nom de l'auteur. Ce champ contient un total de 40 caractères ASCII pour le nom. Si le champ est utilisé, il doit contenir le nom de la personne qui a créé l'image (auteur). |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel) { get; } | Obtient des bits par pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel) { get; } | Récupère les octets par pixel. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtient le[`Image`](../../aspose.imaging/image) conteneur. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp) { get; set; } | Obtient ou définit l'horodatage. Ce champ définit la valeur de la date et de l'heure d'enregistrement de l'image. Même si les systèmes d'exploitation horodatent généralement les fichiers, cette fonctionnalité est fournie car le système d'exploitation peut modifier l'horodatage si le fichier est copié. En utilisant cette zone, vous avez la garantie d'une région non modifiée pour l'enregistrement de la date et de l'heure . |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat) { get; } | Obtient le format de fichier. |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator) { get; } | Gets Gamma Value Denominator part. Une image non corrigée (une image sans gamma) doit avoir la valeur 1.0 comme résultat. |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator) { get; } | Gets Gamma Value Numerator part. Une image non corrigée (une image sans gamma) doit avoir la valeur 1.0 comme résultat. |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha) { get; } | Obtient une valeur indiquant si cela[`TgaImage`](../tgaimage) a un canal alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap) { get; } | Obtient une valeur indiquant si cette image a une carte de couleurs. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur transparente. |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height) { get; } | Obtient cette hauteur d'image. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid) { get; set; } | Obtient ou définit l'ID de l'image. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Obtient l'opacité de cette image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale) { get; } | Obtient une valeur indiquant si cela[`TgaImage`](../tgaimage) est en niveaux de gris. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid) { get; set; } | Obtient ou définit le nom/ID de la tâche. |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime) { get; set; } | Obtient ou définit l'heure du travail. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator) { get; } | Obtient la partie du dénominateur du rapport d'aspect des pixels. |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator) { get; } | Obtient la partie numérateur du rapport d'aspect des pixels. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Obtient les paramètres de données brutes actuels. Notez que lorsque vous utilisez ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur indexé |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Obtient la taille de ligne brute en octets. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtient la taille de l'image. |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid) { get; set; } | Obtient ou définit l'ID du logiciel. Un total de 40 caractères ASCII pour l'ID du logiciel. |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion) { get; set; } | Obtient ou définit la version du logiciel. La longueur de chaîne de version acceptée est de 3 à 4 caractères. |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter) { get; set; } | Obtient ou définit la partie lettre de la version du logiciel. |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber) { get; set; } | Obtient ou définit le numéro de version du logiciel part. |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor) { get; set; } | Obtient ou définit la couleur de la clé. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Obtient une valeur indiquant si la palette d'images est utilisée. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement des données brutes lorsque le chargement des données brutes est disponible. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width) { get; } | Obtient cette largeur d'image. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Obtient ou définit les métadonnées XMP. |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin) { get; set; } | Obtient ou définit la coordonnée horizontale absolue pour le coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par exemple, la série TARGA). |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin) { get; set; } | Obtient ou définit la coordonnée verticale absolue pour le coin inférieur gauche de l'image telle qu'elle est positionnée sur un dispositif d'affichage ayant une origine en bas à gauche de l'écran (par exemple, la série TARGA). |

## Méthodes

| Nom | La description |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Réglage d'une luminosité pour l'image. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Image contrastée |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Correction gamma d'une image. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarisation d'une image avec seuil prédéfini |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarisation d'une image avec seuillage Otsu |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone)() | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone_1)(TgaImage) | Cloner autre[`TgaImage`](../tgaimage) propriétés de l'objet. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop)(Rectangle) | Recadrage de l'image. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop_1)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals_1)(object) | Comparaison d'égalité. |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals)(TgaImage) | Comparaison d'égalité. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtient une image pixel ARGB 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut à l'aide du chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut à l'aide du chargeur de pixels partiel. |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode)() | Obtenez le code de hachage de cette instance. Ne convient pas pour être utilisé comme clé car[`TgaImage`](../tgaimage) n'est pas immuable. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../../aspose.imaging/datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../../aspose.imaging/image/save) méthode comme deuxième paramètre. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtient un pixel d'image. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtient l'angle d'inclinaison. Cette méthode est applicable aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Charge les pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Charge les pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Charge les pixels au format CMJN. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Charge les pixels ARGB 32 bits partiellement par packs. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Charge les pixels partiellement par packs. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Charge les pixels. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) et[`Rotate`](../../aspose.imaging/rasterimage/rotate) méthodes. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) et[`Rotate`](../../aspose.imaging/rasterimage/rotate) méthodes. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Redimensionne l'image. Le défautNearestNeighbourResample est utilisé. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Faire pivoter l'image autour du centre. |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image autour du centre. |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip)(RotateFlipType) | Le retournement de rotation. |
| [Save](../../aspose.imaging/image/save)() | Enregistre les données d'image dans le flux sous-jacent. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| override [Save](../../aspose.imaging/image/save)(string) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Enregistre les pixels ARGB 32 bits. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Enregistre les pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Enregistre les pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Enregistre les données brutes. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Définit un pixel ARGB 32 bits d'image pour la position spécifiée. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Définit la palette d'images. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Définit un pixel d'image pour la position spécifiée. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Définit la résolution pour ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality) | Comparaison d'égalité. |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality) | Comparaison de non-égalité. |

### Exemples

Enregistrement de l'image JPG en tant qu'image TGA.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Chargement de l'image PNG, conversion de celle-ci en TgaImage et enregistrement en tant qu'image TGA.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

Mise à jour des propriétés publiques de l'image TGA chargée.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Obtention des valeurs des propriétés publiques de l'image TGA chargée.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### Voir également

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* espace de noms [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
