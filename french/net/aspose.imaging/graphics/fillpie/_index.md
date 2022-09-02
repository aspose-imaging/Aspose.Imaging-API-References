---
title: FillPie
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Remplit lintérieur dune section circulaire définie par une ellipse spécifiée par unRectangleFaspose.imaging/rectanglef structure et deux lignes radiales.
type: docs
weight: 370
url: /fr/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par un[`RectangleF`](../../rectanglef) structure et deux lignes radiales.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) qui détermine les caractéristiques du remblai. |
| rect | Rectangle | [`Rectangle`](../../rectangle)structure qui représente le rectangle englobant qui définit l'ellipse d'où provient la section circulaire. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le premier côté de la section du secteur. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au deuxième côté de la section du camembert. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Exemples

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

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par un[`RectangleF`](../../rectanglef) structure et deux lignes radiales.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) qui détermine les caractéristiques du remblai. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)structure qui représente le rectangle englobant qui définit l'ellipse d'où provient la section circulaire. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le premier côté de la section du secteur. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au deuxième côté de la section du camembert. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir également

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) qui détermine les caractéristiques du remblai. |
| x | Single | Coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| y | Single | Coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| width | Single | Largeur du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| height | Single | Hauteur du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le premier côté de la section du secteur. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au deuxième côté de la section du camembert. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir également

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Remplit l'intérieur d'une section circulaire définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) qui détermine les caractéristiques du remblai. |
| x | Int32 | Coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| y | Int32 | Coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| width | Int32 | Largeur du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| height | Int32 | Hauteur du rectangle englobant qui définit l'ellipse d'où provient la section du secteur. |
| startAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le premier côté de la section du secteur. |
| sweepAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au deuxième côté de la section du camembert. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. |

### Voir également

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
