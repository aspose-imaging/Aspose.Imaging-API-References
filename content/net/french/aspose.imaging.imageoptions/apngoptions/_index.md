---
title: ApngOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de format de fichier PNG animé
type: docs
weight: 9900
url: /fr/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Les options de format de fichier PNG animé

```csharp
public class ApngOptions : PngOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ApngOptions](apngoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | La profondeur de bits. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Obtient ou définit le type de la couleur. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | Le niveau de compression de l'image png dans la plage 0-9, où 9 est la compression maximale et 0 est le mode de stockage. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Obtient ou définit la durée de trame par défaut. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Obtient ou définit le type de filtre utilisé lors du processus d'enregistrement du fichier png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Obtient ou définit le nombre de fois pour boucler l'animation. 0 indique une boucle infinie. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Obtient ou définit une valeur indiquant si cette[`PngOptions`](../pngoptions) est progressif. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

L'exemple suivant montre comment exporter le format de fichier apng APNG à partir d'un autre format multipage non animé.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Configuration de la durée de trame par défaut
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

L'exemple suivant montre comment exporter au format de fichier APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Exporter vers l'animation APNG avec des cycles d'animation illimités par défaut
    image.Save("Animation1.webp.png", new ApngOptions());
    // Paramétrage des cycles d'animation
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

L'exemple suivant montre comment créer une image APNG à partir d'une autre image raster d'une seule page.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // Il est possible de définir ici le temps de trame par défaut de l'image : apngImage.DefaultFrameTime = (uint)FrameDuration ;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Nettoyage car l'image contient un frame par défaut
        apngImage.RemoveAllFrames();

        // ajoute la première image
        apngImage.AddFrame(sourceImage);

        // ajoute des cadres intermédiaires
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // ajoute la dernière image
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Voir également

* class [PngOptions](../pngoptions)
* espace de noms [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
