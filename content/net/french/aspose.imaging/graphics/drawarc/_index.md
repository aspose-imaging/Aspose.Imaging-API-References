---
title: DrawArc
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Dessine un arc représentant une portion dellipse spécifiée par une paire de coordonnées une largeur et une hauteur.
type: docs
weight: 160
url: /fr/aspose.imaging/graphics/drawarc/
---
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Dessine un arc représentant une portion d'ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de l'arc. |
| x | Single | Coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | Single | Coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | Single | Largeur du rectangle qui définit l'ellipse. |
| height | Single | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Dessine un arc représentant une portion d'ellipse spécifiée par un[`RectangleF`](../../rectanglef) structure.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) structure qui définit les limites de l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul |

### Voir également

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Dessine un arc représentant une portion d'ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de l'arc. |
| x | Int32 | Coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | Int32 | Coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | Int32 | Largeur du rectangle qui définit l'ellipse. |
| height | Int32 | Hauteur du rectangle qui définit l'ellipse. |
| startAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Int32 | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Dessine un arc représentant une portion d'ellipse spécifiée par un[`Rectangle`](../../rectangle) structure.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | Rectangle | [`RectangleF`](../../rectanglef) structure qui définit les limites de l'ellipse. |
| startAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre entre l'axe des x et le point de départ de l'arc. |
| sweepAngle | Single | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du*startAngle* paramètre au point final de l'arc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Exemples

Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface Image. Pour illustrer l'opération, l'exemple crée une nouvelle image au format PNG et dessine des formes primitives sur la surface de l'image à l'aide des méthodes Draw exposées par la classe Graphics

```csharp
[C#]

// Crée une instance de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Créer une instance de PngOptions et définir ses différentes propriétés
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Définir la source pour PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Créer une instance de Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Créer et initialiser une instance de la classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Effacer la surface graphique
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // Dessine un arc en spécifiant l'objet Pen de couleur noire, 
        //un rectangle entourant l'arc, l'angle de départ et l'angle de balayage
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        // Dessinez un Bézier en spécifiant l'objet Pen ayant la couleur bleue et les points de coordonnées.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        // Dessinez une courbe en spécifiant l'objet Pen de couleur verte et un tableau de points
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        // Dessine une ellipse à l'aide de l'objet Pen et d'un rectangle environnant
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Tracer une ligne 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // Dessine un segment de tarte
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        // Dessinez un polygone en spécifiant l'objet Pen de couleur rouge et un tableau de points
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        // Dessine un rectangle
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Créer un objet SolidBrush et définir ses différentes propriétés
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        // Dessine une chaîne à l'aide de l'objet SolidBrush et de la police, à un point spécifique
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // Enregistrer toutes les modifications.
        image.Save();
    }
}
```

### Voir également

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
