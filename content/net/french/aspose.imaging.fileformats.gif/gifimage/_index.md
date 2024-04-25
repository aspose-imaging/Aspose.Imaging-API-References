---
title: GifImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Une image gif.
type: docs
weight: 6700
url: /fr/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

Une image gif.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GifImage](gifimage#constructor)(GifFrameBlock) | Initialise une nouvelle instance du[`GifImage`](../gifimage) classe. |
| [GifImage](gifimage#constructor_1)(GifFrameBlock, IColorPalette) | Initialise une nouvelle instance du[`GifImage`](../gifimage) classe. |
| [GifImage](gifimage#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Initialise une nouvelle instance du[`GifImage`](../gifimage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | Obtient ou définit le cadre actif. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | Obtient ou définit l'index de couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | Obtient les blocs GIF. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtient le[`Image`](../../aspose.imaging/image) conteneur. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | Obtient une valeur de format de fichier |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Obtient une valeur indiquant si cette instance a alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | Obtient une valeur indiquant si l'image a une couleur d'arrière-plan. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | Obtient ou définit une valeur indiquant si le GIF a une bande-annonce. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | Obtient une valeur indiquant si le cadre actif a une couleur transparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Obtient la hauteur de l'image. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | Obtient l'opacité de cette image (cadre actif). |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | Obtient une valeur indiquant si cette instance d'image est entrelacée. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | Obtient ou définit une valeur indiquant si la palette est triée. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | Obtient le nombre de boucles (si l'image gif contient des informations sur les boucles) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | Obtient le nombre de pages. |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | Obtient ou définit l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant l'enregistrement de chaque page. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | Obtient les pages. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | Obtient ou définit les bits de résolution de couleur de la palette. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | Obtient ou définit le format des pixels. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Obtient les paramètres de données brutes actuels. Notez que lorsque vous utilisez ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur indexé |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Obtient la taille de ligne brute en octets. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtient la taille de l'image. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | Obtient la couleur transparente du cadre actif. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Obtient une valeur indiquant si la palette d'images est utilisée. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement des données brutes lorsque le chargement des données brutes est disponible. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Obtient la largeur de l'image. |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | Obtient ou définit les métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | Ajoute un nouveau bloc GIF. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | Ajoute une page à l'image. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | Ajustement d'un*brightness* pour image. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | Ajuste le contraste. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma_1)(float, float, float) | Correction gamma d'une image. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley#binarizebradley)(double) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | Binarisation d'une image avec seuil prédéfini |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | Binarisation d'une image avec seuillage Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Cache les données privées. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | Efface tous les blocs GIF. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop#crop)(Rectangle) | Recadrage de l'image. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtient une image pixel ARGB 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut à l'aide du chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut à l'aide du chargeur de pixels partiel. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../../aspose.imaging/datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../../aspose.imaging/image/save) méthode comme deuxième paramètre. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtient un pixel d'image. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtient l'angle d'inclinaison. Cette méthode est applicable aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | Transformation d'une image en sa représentation en niveaux de gris |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | Ajoute un nouveau bloc GIF. |
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
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | Ordonne les blocs GIF selon la spécification GIF. Quelques[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) peut être supprimé pour une mise en page GIF appropriée. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | Supprime le bloc GIF. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Redimensionne l'image. Le défautNearestNeighbourResample est utilisé. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | Redimensionne l'image en utilisant des images complètes pour chaque page GIF. Nécessaire pour éviter l'apparition possible d'artefacts. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | Effectue un redimensionnement proportionnel sur l'image. Le redimensionnement proportionnel redimensionne chaque image en fonction du rapport de*newWidth*/largeur et*newHeight* /hauteur. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Faire pivoter l'image autour du centre. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image autour du centre. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne le cadre actif uniquement. |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | Définit la durée de toutes les trames en millisecondes. La modification de cette valeur réinitialisera le délai pour toutes les trames. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Définit la palette d'images. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Définit un pixel d'image pour la position spécifiée. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Définit la résolution pour ce[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |

### Exemples

Exportation d'une partie de l'animation à partir d'une image GIF basée sur un intervalle de temps.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

Cet exemple montre comment créer une image GIF et l'enregistrer dans un fichier.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée un bloc Frame GIF de 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Remplit tout le bloc en rouge.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Créez une image GIF multipage à l'aide d'images raster d'une seule page.

```csharp
[C#]

static void Main(string[] args)
{
    // Charger les trames
    var frames = LoadFrames("Animation frames").ToArray();

    // Crée une image GIF en utilisant la première image
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Ajoute des cadres à l'image GIF en utilisant la méthode AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Enregistrer l'image GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Voir également

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
