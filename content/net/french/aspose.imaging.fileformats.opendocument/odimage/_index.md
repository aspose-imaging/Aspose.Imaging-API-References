---
title: OdImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Le document ouvert
type: docs
weight: 7370
url: /fr/aspose.imaging.fileformats.opendocument/odimage/
---
## OdImage class

Le document ouvert

```csharp
public abstract class OdImage : VectorMultipageImage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [OdImage](odimage#constructor)(StreamContainer) | Initialise une nouvelle instance du[`OdImage`](../odimage) classe. |
| [OdImage](odimage#constructor_1)(StreamContainer, LoadOptions) | Initialise une nouvelle instance du[`OdImage`](../odimage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtient le[`Image`](../../aspose.imaging/image) conteneur. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Obtient une valeur de format de fichier |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| override [Height](../../aspose.imaging.fileformats.opendocument/odimage/height) { get; } | Obtient la hauteur de l'image. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Obtient la hauteur de l'objet, en pouces. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement mises en cache et qu'aucune lecture de données n'est requise. |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata) { get; } | Obtient les métadonnées. |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount) { get; } | Obtient le nombre de pages. |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction) { get; set; } | Obtient ou définit l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant l'enregistrement de chaque page. |
| abstract [Pages](../../aspose.imaging/vectormultipageimage/pages) { get; } | Obtient les pages. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records) { get; } | Obtient les enregistrements. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtient la taille de l'image. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Obtient la taille de l'objet, en pouces. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtient une valeur indiquant si la palette d'images est utilisée. |
| override [Width](../../aspose.imaging.fileformats.opendocument/odimage/width) { get; } | Obtient la largeur de l'image. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Obtient la largeur de l'objet, en pouces. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Obtient les images intégrées. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../../aspose.imaging/datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../../aspose.imaging/image/save) méthode comme deuxième paramètre. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Redimensionne l'image. Le défautNearestNeighbourResample est utilisé. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| override [RotateFlip](../../aspose.imaging.fileformats.opendocument/odimage/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.imaging/image/save)() | Enregistre les données d'image dans le flux sous-jacent. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| override [Save](../../aspose.imaging/image/save)(string) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette)(IColorPalette, bool) | Définit la palette d'images. |

### Voir également

* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage)
* espace de noms [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
