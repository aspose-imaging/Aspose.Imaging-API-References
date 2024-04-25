---
title: DrawLine
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Dessine une ligne reliant deuxPointaspose.imaging/point structures.
type: docs
weight: 250
url: /fr/aspose.imaging/graphics/drawline/
---
## DrawLine(Pen, Point, Point) {#drawline}

Dessine une ligne reliant deux[`Point`](../../point) structures.

```csharp
public void DrawLine(Pen pen, Point point1, Point point2)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | Point | [`Point`](../../point) structure qui représente le premier point à connecter. |
| point2 | Point | [`Point`](../../point) structure qui représente le deuxième point à connecter. |

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
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawLine(Pen, PointF, PointF) {#drawline_1}

Dessine une ligne reliant deux[`PointF`](../../pointf) structures.

```csharp
public void DrawLine(Pen pen, PointF point1, PointF point2)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | PointF | [`PointF`](../../pointf) structure qui représente le premier point à connecter. |
| point2 | PointF | [`PointF`](../../pointf) structure qui représente le deuxième point à connecter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawLine(Pen, int, int, int, int) {#drawline_2}

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

```csharp
public void DrawLine(Pen pen, int x1, int y1, int x2, int y2)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | Int32 | Coordonnée x du premier point. |
| y1 | Int32 | Coordonnée y du premier point. |
| x2 | Int32 | Coordonnée x du deuxième point. |
| y2 | Int32 | Coordonnée y du deuxième point. |

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

## DrawLine(Pen, float, float, float, float) {#drawline_3}

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

```csharp
public void DrawLine(Pen pen, float x1, float y1, float x2, float y2)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | Single | Coordonnée x du premier point. |
| y1 | Single | Coordonnée y du premier point. |
| x2 | Single | Coordonnée x du deuxième point. |
| y2 | Single | Coordonnée y du deuxième point. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. |

### Voir également

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* espace de noms [Aspose.Imaging](../../graphics)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
