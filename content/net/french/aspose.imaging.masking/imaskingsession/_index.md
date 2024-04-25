---
title: IMaskingSession
second_title: Référence de l'API Aspose.Imaging pour .NET
description: La séance de masquage
type: docs
weight: 10420
url: /fr/aspose.imaging.masking/imaskingsession/
---
## IMaskingSession interface

La séance de masquage

```csharp
public interface IMaskingSession : IDisposable
```

## Méthodes

| Nom | La description |
| --- | --- |
| [Decompose](../../aspose.imaging.masking/imaskingsession/decompose)() | Effectue la première opération de décomposition grossière |
| [DecomposeAsync](../../aspose.imaging.masking/imaskingsession/decomposeasync)() | Crée la tâche asynchrone qui peut effectuer la première opération de décomposition grossière |
| [ImproveDecomposition](../../aspose.imaging.masking/imaskingsession/improvedecomposition)(IMaskingArgs) | Effectue une opération de décomposition de recyclage |
| [ImproveDecompositionAsync](../../aspose.imaging.masking/imaskingsession/improvedecompositionasync)(IMaskingArgs) | Crée la tâche asynchrone qui peut effectuer l'opération de décomposition de recyclage |
| [Save](../../aspose.imaging.masking/imaskingsession/save#save)(Stream) | Enregistrer l'état de la session dans le flux spécifié. |
| [Save](../../aspose.imaging.masking/imaskingsession/save#save_1)(string) | Enregistre l'état de la session dans le fichier spécifié. |

### Exemples

Enregistrement de la session de masquage dans un fichier pour les longues sessions, ainsi que pour la possibilité de reprendre la session dans un autre environnement.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Options d'exportation de masquage
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Utilise le clustering GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// La couleur de fond sera orange.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Démarrage d'une session pour la première fois et enregistrement dans un fichier
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Reprise d'une session de masquage depuis un fichier
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crée une instance de la classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analyse visuellement l'image et définit les points qui appartiennent à des objets séparés.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Transfert explicite des options d'exportation, car il n'est pas sérialisable
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Voir également

* espace de noms [Aspose.Imaging.Masking](../../aspose.imaging.masking)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
