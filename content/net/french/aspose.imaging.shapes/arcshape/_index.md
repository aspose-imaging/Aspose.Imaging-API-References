---
title: ArcShape
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente une forme darc.
type: docs
weight: 10950
url: /fr/aspose.imaging.shapes/arcshape/
---
## ArcShape class

Représente une forme d'arc.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ArcShape](arcshape#constructor)() | Initialise une nouvelle instance du[`ArcShape`](../arcshape) classe. |
| [ArcShape](arcshape#constructor_1)(RectangleF, float, float) | Initialise une nouvelle instance du[`ArcShape`](../arcshape) classe. |
| [ArcShape](arcshape#constructor_2)(RectangleF, float, float, bool) | Initialise une nouvelle instance du[`ArcShape`](../arcshape) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Obtient les limites de l'objet. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Obtient le centre de la forme. |
| [EndPoint](../../aspose.imaging.shapes/arcshape/endpoint) { get; } | Obtient le point de forme de fin. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Obtient une valeur indiquant si la forme a des segments. |
| [IsClosed](../../aspose.imaging.shapes/arcshape/isclosed) { get; set; } | Obtient ou définit une valeur indiquant si la forme ordonnée est fermée. Lors du traitement d'une forme ordonnée fermée, les points de départ et d'arrivée n'ont aucune signification. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Obtient le point du rectangle inférieur gauche. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Obtient le point du rectangle supérieur gauche. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Obtient la hauteur du rectangle. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Obtient la largeur du rectangle. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Obtient le point du rectangle inférieur droit. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Obtient le point du rectangle supérieur droit. |
| override [Segments](../../aspose.imaging.shapes/arcshape/segments) { get; } | Obtient les segments de forme. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | Obtient ou définit l'angle de départ. |
| [StartPoint](../../aspose.imaging.shapes/arcshape/startpoint) { get; } | Obtient le point de départ de la forme. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | Obtient ou définit l'angle de balayage. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [Reverse](../../aspose.imaging.shapes/arcshape/reverse)() | Inverse l'ordre des points pour cette forme. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | Applique la transformation spécifiée à la forme. |

### Exemples

Cet exemple crée une nouvelle Image et dessine une variété de formes en utilisant Figures et GraphicsPath sur la surface Image

```csharp
[C#]

// Crée une instance de BmpOptions et définit ses différentes propriétés            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de BmpOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Créer une instance de Image 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Créer et initialiser une instance de la classe Graphics
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Effacer la surface graphique
    graphics.Clear(Color.Wheat);

    //Créer une instance de la classe GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Créer une instance de la classe Figure
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    // Ajouter une forme à l'objet Figure
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Créer une instance de la classe Figure
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    // Ajouter une forme à l'objet Figure
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //Ajouter un objet Figure à GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Dessine un chemin avec un objet Pen de couleur noire
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // Enregistrer toutes les modifications.
    image.Save();
}
```

### Voir également

* class [PieShape](../pieshape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* espace de noms [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
