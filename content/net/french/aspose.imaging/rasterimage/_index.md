---
title: RasterImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente une image raster prenant en charge les opérations graphiques raster.
type: docs
weight: 10810
url: /fr/aspose.imaging/rasterimage/
---
## RasterImage class

Représente une image raster prenant en charge les opérations graphiques raster.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtient le[`Image`](../image) conteneur. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Obtient une valeur de format de fichier |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha) { get; } | Obtient une valeur indiquant si cette instance a alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor) { get; set; } | Obtient une valeur indiquant si l'image a une couleur transparente. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Obtient la hauteur de l'image. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce[`RasterImage`](../rasterimage) . |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Obtient l'opacité de cette image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement mises en cache et qu'aucune lecture de données n'est requise. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`RasterImage`](../rasterimage) . |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Obtient la largeur de l'image. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Obtient ou définit les métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.imaging/rasterimage/adjustbrightness)(int) | Réglage d'une luminosité pour l'image. |
| virtual [AdjustContrast](../../aspose.imaging/rasterimage/adjustcontrast)(float) | Image contrastée |
| virtual [AdjustGamma](../../aspose.imaging/rasterimage/adjustgamma#adjustgamma)(float) | Correction gamma d'une image. |
| virtual [AdjustGamma](../../aspose.imaging/rasterimage/adjustgamma#adjustgamma_1)(float, float, float) | Correction gamma d'une image. |
| virtual [BinarizeBradley](../../aspose.imaging/rasterimage/binarizebradley#binarizebradley)(double) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| virtual [BinarizeBradley](../../aspose.imaging/rasterimage/binarizebradley#binarizebradley_1)(double, int) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| virtual [BinarizeFixed](../../aspose.imaging/rasterimage/binarizefixed)(byte) | Binarisation d'une image avec seuil prédéfini |
| virtual [BinarizeOtsu](../../aspose.imaging/rasterimage/binarizeotsu)() | Binarisation d'une image avec seuillage Otsu |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop#crop)(Rectangle) | Rogne le rectangle spécifié. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop#crop_1)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [Dither](../../aspose.imaging/rasterimage/dither#dither)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| abstract [Dither](../../aspose.imaging/rasterimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtient une image pixel ARGB 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut à l'aide du chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata#getdefaultrawdata)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut à l'aide du chargeur de pixels partiel. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../image/save) méthode comme deuxième paramètre. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtient un pixel d'image. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtient l'angle d'inclinaison. Cette méthode est applicable aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation. |
| virtual [Grayscale](../../aspose.imaging/rasterimage/grayscale)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Charge les pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Charge les pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Charge les pixels au format CMJN. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Charge les pixels ARGB 32 bits partiellement par packs. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Charge les pixels partiellement par packs. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Charge les pixels. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle#normalizeangle)() | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](./getskewangle) et[`Rotate`](./rotate) méthodes. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle#normalizeangle_1)(bool, Color) | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](./getskewangle) et[`Rotate`](./rotate) méthodes. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor#replacecolor)(Color, byte, Color) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor#replacecolor_1)(int, byte, int) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors#replacenontransparentcolors)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour enregistrer des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Redimensionne l'image. Le défautNearestNeighbourResample est utilisé. |
| override [Resize](../../aspose.imaging/rasterimage/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image avec des options étendues. |
| override [Resize](../../aspose.imaging/rasterimage/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate#rotate)(float) | Faire pivoter l'image autour du centre. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate#rotate_1)(float, bool, Color) | Faire pivoter l'image autour du centre. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.imaging/image/save)() | Enregistre les données d'image dans le flux sous-jacent. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| override [Save](../../aspose.imaging/image/save)(string) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [Save](../../aspose.imaging/rasterimage/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Enregistre les pixels ARGB 32 bits. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Enregistre les pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Enregistre les pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Enregistre les données brutes. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Définit un pixel ARGB 32 bits d'image pour la position spécifiée. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Définit la palette d'images. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Définit un pixel d'image pour la position spécifiée. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Définit la résolution pour ce[`RasterImage`](../rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |

### Exemples

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

* class [Image](../image)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
