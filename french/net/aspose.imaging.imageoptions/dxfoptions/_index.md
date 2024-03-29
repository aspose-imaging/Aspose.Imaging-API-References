---
title: DxfOptions
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Les options de création de format de fichier Dxf.
type: docs
weight: 9960
url: /fr/net/aspose.imaging.imageoptions/dxfoptions/
---
## DxfOptions class

Les options de création de format de fichier Dxf.

```csharp
public class DxfOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DxfOptions](dxfoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BezierPointCount](../../aspose.imaging.imageoptions/dxfoptions/bezierpointcount) { get; set; } | Combien de points générer lors de la conversion des courbes de Bézier en polylignes, minimum 4. Utilisé lorsque et sont tous les deux /// définis sur`vrai` |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ConvertTextBeziers](../../aspose.imaging.imageoptions/dxfoptions/converttextbeziers) { get; set; } | Fonctionne quand est réglé sur`vrai` . S'il faut convertir les courbes de Bézier dans les contours de texte en polylignes multipoints. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [TextAsLines](../../aspose.imaging.imageoptions/dxfoptions/textaslines) { get; set; } | Indique si le texte doit être exporté sous forme de contours constitués de polylignes (par défaut) ou sous forme d'entités TEXTE Autocad modifiables. Si cette option est définie |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

Cet exemple illustre l'exportation au format Dxf

```csharp
[C#]

//Créer une instance d'image et l'initialiser avec un fichier image existant à partir de l'emplacement du disque
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"input.svg"))
{
    Aspose.Imaging.ImageOptions.DxfOptions options = new Aspose.Imaging.ImageOptions.DxfOptions();
    options.TextAsLines = true;
    options.ConvertTextBeziers = true;
    options.BezierPointCount = 20;
    image.Save("output.dxf", options);
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espace de noms [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
