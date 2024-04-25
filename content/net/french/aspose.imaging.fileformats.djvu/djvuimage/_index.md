---
title: DjvuImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Classe DjvuDocument
type: docs
weight: 2440
url: /fr/aspose.imaging.fileformats.djvu/djvuimage/
---
## DjvuImage class

Classe DjvuDocument

```csharp
public sealed class DjvuImage : RasterCachedMultipageImage, INotifyPropertyChanged
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DjvuImage](djvuimage#constructor)(Stream) | Initialise une nouvelle instance du[`DjvuImage`](../djvuimage) classe. |
| [DjvuImage](djvuimage#constructor_1)(Stream, LoadOptions) | Initialise une nouvelle instance du[`DjvuImage`](../djvuimage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.djvu/djvuimage/activepage) { get; set; } | Obtient ou définit la page actuellement active |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtient le[`Image`](../../aspose.imaging/image) conteneur. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [DjvuPages](../../aspose.imaging.fileformats.djvu/djvuimage/djvupages) { get; } | Récupère les pages du document |
| override [FileFormat](../../aspose.imaging.fileformats.djvu/djvuimage/fileformat) { get; } | Obtient une valeur de format de fichier |
| [FirstPage](../../aspose.imaging.fileformats.djvu/djvuimage/firstpage) { get; } | Obtient la première page du document |
| override [HasAlpha](../../aspose.imaging.fileformats.djvu/djvuimage/hasalpha) { get; } | Obtient le canal alpha A. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Obtient une valeur indiquant si l'image a une couleur transparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Obtient la hauteur de l'image. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [Identifier](../../aspose.imaging.fileformats.djvu/djvuimage/identifier) { get; } | Obtient l'identifiant unique du document |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Obtient l'opacité de cette image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [LastPage](../../aspose.imaging.fileformats.djvu/djvuimage/lastpage) { get; } | Obtient la dernière page du document |
| [NextPage](../../aspose.imaging.fileformats.djvu/djvuimage/nextpage) { get; } | Obtient la page suivante du document |
| override [PageCount](../../aspose.imaging.fileformats.djvu/djvuimage/pagecount) { get; } | Obtient le nombre de pages. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | Obtient ou définit l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant l'enregistrement de chaque page. |
| override [Pages](../../aspose.imaging.fileformats.djvu/djvuimage/pages) { get; } | Obtient les pages. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [PreviousPage](../../aspose.imaging.fileformats.djvu/djvuimage/previouspage) { get; } | Obtient la page précédente du document |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Obtient les paramètres de données brutes actuels. Notez que lorsque vous utilisez ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur indexé |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Obtient la taille de ligne brute en octets. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtient la taille de l'image. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Obtient la couleur transparente de l'image. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Obtient une valeur indiquant si la palette d'images est utilisée. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement des données brutes lorsque le chargement des données brutes est disponible. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Obtient la largeur de l'image. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Obtient ou définit les données XMP du cadre. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument#loaddocument)(Stream) | Charge le document. |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument#loaddocument_1)(Stream, LoadOptions) | Charge le document. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness)(int) | Ajustement d'un*brightness* pour image. |
| override [AdjustContrast](../../aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contraste |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma#adjustgamma)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma#adjustgamma_1)(float, float, float) | Correction gamma d'une image. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeBradley](../../aspose.imaging.fileformats.djvu/djvuimage/binarizebradley#binarizebradley_1)(double, int) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeFixed](../../aspose.imaging.fileformats.djvu/djvuimage/binarizefixed)(byte) | Binarisation d'une image avec seuil prédéfini |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu)() | Binarisation d'une image avec seuillage Otsu |
| override [CacheData](../../aspose.imaging.fileformats.djvu/djvuimage/cachedata)() | Cache les données privées. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop#crop)(Rectangle) | Recadrage de l'image. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop#crop_1)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.imaging.fileformats.djvu/djvuimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| override [Filter](../../aspose.imaging.fileformats.djvu/djvuimage/filter)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtient une image pixel ARGB 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut à l'aide du chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut à l'aide du chargeur de pixels partiel. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../../aspose.imaging/datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../../aspose.imaging/image/save) méthode comme deuxième paramètre. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtient un pixel d'image. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtient l'angle d'inclinaison. Cette méthode est applicable aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.imaging.fileformats.djvu/djvuimage/grayscale)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Charge les pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Charge les pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Charge les pixels au format CMJN. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Charge les pixels ARGB 32 bits partiellement par packs. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Charge les pixels partiellement par packs. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Charge les pixels. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) et[`Rotate`](../../aspose.imaging/rasterimage/rotate) méthodes. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise!:GetSkewAngle et[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) méthodes. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Redimensionne l'image. Le défautNearestNeighbourResample est utilisé. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Faire pivoter l'image autour du centre. |
| override [Rotate](../../aspose.imaging.fileformats.djvu/djvuimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image autour du centre. |
| override [RotateFlip](../../aspose.imaging.fileformats.djvu/djvuimage/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne le cadre actif uniquement. |
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

### Exemples

Cet exemple montre comment charger une image DJVU à partir d'un flux de fichiers.

```csharp
[C#]

string dir = "c:\\temp\\";

// Charge une image DJVU à partir d'un flux de fichiers.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // Enregistre chaque page en tant qu'image PNG individuelle.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Génère un nom de fichier basé sur le numéro de page.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Voir également

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* espace de noms [Aspose.Imaging.FileFormats.Djvu](../../aspose.imaging.fileformats.djvu)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
