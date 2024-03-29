---
title: Figure
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Le chiffre. Un conteneur pour les formes.
type: docs
weight: 1290
url: /fr/net/aspose.imaging/figure/
---
## Figure class

Le chiffre. Un conteneur pour les formes.

```csharp
public class Figure : ObjectWithBounds
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Figure](figure)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Bounds](../../aspose.imaging/figure/bounds) { get; } | Obtient ou définit les limites de l'objet. |
| [IsClosed](../../aspose.imaging/figure/isclosed) { get; set; } | Obtient ou définit une valeur indiquant si ce chiffre est fermé. Une figure fermée fera une différence uniquement dans le cas où les formes de la première et de la dernière figure sont des formes continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite à partir du dernier point de la dernière forme. |
| [Segments](../../aspose.imaging/figure/segments) { get; } | Obtient les segments entiers de la figure. |
| [Shapes](../../aspose.imaging/figure/shapes) { get; } | Obtient les formes de la figure. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddShape](../../aspose.imaging/figure/addshape)(Shape) | Ajoute une forme à la figure. |
| [AddShapes](../../aspose.imaging/figure/addshapes)(Shape[]) | Ajoute une gamme de formes à la figure. |
| override [GetBounds](../../aspose.imaging/figure/getbounds#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.imaging/figure/getbounds#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [RemoveShape](../../aspose.imaging/figure/removeshape)(Shape) | Supprime une forme de la figure. |
| [RemoveShapes](../../aspose.imaging/figure/removeshapes)(Shape[]) | Supprime une plage de formes de la figure. |
| [Reverse](../../aspose.imaging/figure/reverse)() | Inverse l'ordre des formes de cette figure et l'ordre des points de formes. |
| override [Transform](../../aspose.imaging/figure/transform)(Matrix) | Applique la transformation spécifiée à la forme. |

### Exemples

Ces exemples utilisent GraphicsPath et la classe Graphics pour créer et manipuler des figures sur une surface Image. L'exemple crée une nouvelle image (de type Tiff), efface la surface et dessine des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour restituer les chemins sur la surface.

```csharp
[C#]

//Créer une instance de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Créer une instance de TiffOptions et définir ses différentes propriétés
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Définir la source de l'instance de ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Créer une instance de Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Créer et initialiser une instance de la classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Effacer la surface graphique
        graphics.Clear(Color.Wheat);

        //Créer une instance de la classe GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Créer une instance de la classe Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Ajouter des formes à l'objet Figure
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Ajouter un objet Figure à GraphicsPath
        graphicspath.AddFigure(figure);

        // Dessine un chemin avec un objet Pen de couleur noire
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // Enregistrer toutes les modifications.
        image.Save();
    }
}
```

### Voir également

* class [ObjectWithBounds](../objectwithbounds)
* espace de noms [Aspose.Imaging](../../aspose.imaging)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
