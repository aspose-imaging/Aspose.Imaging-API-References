---
title: Image
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Limage est la classe de base pour tous les types dimages.
type: docs
weight: 9660
url: /fr/aspose.imaging/image/
---
## Image class

L'image est la classe de base pour tous les types d'images.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
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
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Obtient la hauteur de l'image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement mises en cache et qu'aucune lecture de données n'est requise. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtient la taille de l'image. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtient une valeur indiquant si la palette d'images est utilisée. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Obtient la largeur de l'image. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | Crée une nouvelle image les images spécifiées en tant que pages. |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | Charge une nouvelle image à partir du flux spécifié. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | Charge une nouvelle image à partir du fichier spécifié. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | Charge une nouvelle image à partir du flux spécifié. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | Charge une nouvelle image à partir du fichier spécifié. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](./save) méthode comme deuxième paramètre. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | Redimensionne l'image. Le défautNearestNeighbourResample est utilisé. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. Le défautNearestNeighbourResample est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.imaging/image/save#save)() | Enregistre les données d'image dans le flux sous-jacent. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Définit la palette d'images. |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | Détermine si l'image peut être chargée à partir du flux spécifié. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | Détermine si l'image peut être chargée à partir du chemin de fichier spécifié. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | Détermine si l'image peut être chargée à partir du flux spécifié et éventuellement en utilisant le*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | Détermine si l'image peut être chargée à partir du chemin de fichier spécifié et éventuellement à l'aide des options d'ouverture spécifiées. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | Obtient le format de fichier. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | Obtient le format de fichier. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Obtient un rectangle qui correspond à l'image actuelle. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Obtient un rectangle qui correspond à l'image actuelle. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Obtient une hauteur proportionnelle. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Obtient une largeur proportionnelle. |

### Exemples

Déterminez si la palette est utilisée par l'image.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Redimensionnez l'image en utilisant un type de redimensionnement spécifique.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Cet exemple crée un nouveau fichier image à un emplacement du disque spécifié par la propriété Source de l'instance BmpOptions. Plusieurs propriétés pour l'instance BmpOptions sont définies avant de créer l'image réelle. Surtout la propriété Source, qui fait référence à l'emplacement réel du disque dans ce cas.

```csharp
[C#]

//Créer une instance de BmpOptions et définir ses différentes propriétés
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Créer une instance de Image et l'initialiser avec une instance de BmpOptions en appelant la méthode Create
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // faire du traitement d'image

    // Enregistrer toutes les modifications
    image.Save();
}
```

### Voir également

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
