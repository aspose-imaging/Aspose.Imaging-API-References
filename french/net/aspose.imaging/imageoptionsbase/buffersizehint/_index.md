---
title: BufferSizeHint
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Obtient ou définit lindice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes.
type: docs
weight: 10
url: /fr/net/aspose.imaging/imageoptionsbase/buffersizehint/
---
## ImageOptionsBase.BufferSizeHint property

Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes.

```csharp
public int BufferSizeHint { get; set; }
```

### Valeur de la propriété

L'indice de taille de tampon, en mégaoctets. Une valeur non positive signifie qu'il n'y a pas de limitation de mémoire pour les tampons internes

### Exemples

L'exemple suivant montre comment définir une limite de mémoire lors de la création d'une nouvelle image JPEG. La limite de mémoire est la taille maximale autorisée (en mégaoctets) pour tous les tampons internes.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// Définition d'une limite de mémoire de 50 mégaoctets pour l'image créée cible
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.JpegOptions
{
    CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive,
    BufferSizeHint = 50,
    Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "createdFile.jpg", false),
};
    
using (var image = Aspose.Imaging.Image.Create(createOptions, 1000, 1000))
{
    image.Save(); // enregistrer au même endroit
}
```

L'exemple suivant montre comment définir une limite de mémoire lors de la création d'une image PNG et du dessin de graphiques complexes dessus. La limite de mémoire est la taille maximale autorisée (en mégaoctets) pour tous les tampons internes.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30; // La limite de mémoire est de 30 Mo

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    // Vous pouvez utiliser n'importe quelle opération graphique ici, toutes seront effectuées dans la limite de mémoire établie
    // Par exemple:
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

// Un grand nombre d'opérations graphiques sont également supportées :
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30; // La limite de mémoire est de 30 Mo

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.BeginUpdate();
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);

    int x, y;
    int numberOfOperations = 0;
    for (int column = 0; column * OperationAreaSize < ImageSize; column++)
    {
        for (int row = 0; row * OperationAreaSize < ImageSize; row++)
        {
            x = column * OperationAreaSize;
            y = row * OperationAreaSize;

            bool reversed = (column + row) % 2 != 0;
            if (reversed)
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x + OperationAreaSize - 2,
                    y,
                    x,
                    y + OperationAreaSize);
            }
            else
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x,
                    y,
                    x + OperationAreaSize - 2,
                    y + OperationAreaSize);
            }

            numberOfOperations++;
        }
    }

    // Environ 40k opérations seront appliquées ici, alors qu'elles ne prennent pas trop de mémoire 
    // car ils sont déjà déchargés dans le fichier externe, et seront chargés à partir de là un par un
    graphics.EndUpdate();

    image.Save();
}
```

### Voir également

* class [ImageOptionsBase](../../imageoptionsbase)
* espace de noms [Aspose.Imaging](../../imageoptionsbase)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
