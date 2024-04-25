---
title: GifImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duGifImageaspose.imaging.fileformats.gif/gifimage classe.
type: docs
weight: 10
url: /fr/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

Initialise une nouvelle instance du[`GifImage`](../../gifimage) classe.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstFrame | GifFrameBlock | La première image avec laquelle initialiser l'image gif. |
| globalPalette | IColorPalette | La palette globale à utiliser. Notez si les deux*firstFrame* et*globalPalette* sont nuls, la palette globale par défaut est utilisée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le cadre ne peut pas être nul ; firstFrame |
| ArgumentException | La première image appartient déjà à une autre image. Vérifiez la propriété Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La palette spécifiée doit contenir un nombre d'entrées égal à la puissance de 2. La taille minimale de la palette est 2, la taille maximale est 256. |

### Exemples

Cet exemple montre comment créer une image GIF avec une palette personnalisée et l'enregistrer dans un fichier.

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

    // Utilisez la palette 4 bits pour réduire la taille de l'image. La qualité peut empirer.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### Voir également

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Assemblée [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

Initialise une nouvelle instance du[`GifImage`](../../gifimage) classe.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstFrame | GifFrameBlock | La première image avec laquelle initialiser l'image gif. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le cadre ne peut pas être nul ; firstFrame |
| ArgumentException | La première image appartient déjà à une autre image. Vérifiez la propriété Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La palette spécifiée doit contenir un nombre d'entrées égal à la puissance de 2. La taille minimale de la palette est 2, la taille maximale est 256. |

### Exemples

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

L'exemple suivant montre comment composer une image GIF animée à partir de blocs GIF individuels.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crée une image GIF 100 x 100 px.
// Le premier bloc est entièrement noir par défaut.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Le premier cercle est rouge
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Le deuxième cercle est noir
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Augmente progressivement l'angle de la forme d'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Augmente progressivement l'angle de l'arc noir et efface l'arc rouge.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Voir également

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Assemblée [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

Initialise une nouvelle instance du[`GifImage`](../../gifimage) classe.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| firstFrame | GifFrameBlock | La première image avec laquelle initialiser l'image gif. |
| globalPalette | IColorPalette | La palette globale à utiliser. Notez si les deux*firstFrame* et*globalPalette* sont nuls, la palette globale par défaut est utilisée. |
| isPaletteSorted | Boolean | si réglé sur`vrai` la palette est triée. Notez que le paramètre est utilisé lorsque*globalPalette* est non nulle. |
| paletteColorResolution | Byte | La résolution des couleurs de la palette. Notez que le paramètre est utilisé lorsque*globalPalette* est non nulle. |
| paletteBackgroundColorIndex | Byte | L'index de couleur d'arrière-plan de la palette. |
| aspectRatio | Byte | Le rapport d'aspect. |
| hasTrailer | Boolean | si réglé sur`vrai` l'image gif a une bande-annonce sinon aucune bande-annonce n'est écrite à la fin du flux. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le cadre ne peut pas être nul ; firstFrame |
| ArgumentException | La première image appartient déjà à une autre image. Vérifiez la propriété Container.;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | La palette spécifiée doit contenir un nombre d'entrées égal à la puissance de 2. La taille minimale de la palette est 2, la taille maximale est 256. |

### Voir également

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* espace de noms [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
