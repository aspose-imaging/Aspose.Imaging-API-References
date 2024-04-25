---
title: GraphicsPath
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.
type: docs
weight: 9370
url: /fr/aspose.imaging/graphicspath/
---
## GraphicsPath class

Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Initialise une nouvelle instance du[`GraphicsPath`](../graphicspath) classe. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Initialise une nouvelle instance du[`GraphicsPath`](../graphicspath) classe. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Initialise une nouvelle instance du[`GraphicsPath`](../graphicspath) classe. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Initialise une nouvelle instance du[`GraphicsPath`](../graphicspath) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Obtient ou définit les limites de l'objet. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Obtient les chiffres du chemin. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Obtient ou définit un[`FillMode`](../fillmode) énumération qui détermine comment les intérieurs des formes dans ce[`GraphicsPath`](../graphicspath) sont remplis. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Ajoute une nouvelle figure. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Ajoute de nouveaux chiffres. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Ajoute le spécifié[`GraphicsPath`](../graphicspath) à ce chemin. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Ajoute le spécifié[`GraphicsPath`](../graphicspath) à ce chemin. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Effectue un clone en profondeur de ce chemin graphique. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Applique la transformation spécifiée, puis convertit chaque courbe dans cette[`GraphicsPath`](../graphicspath) en une séquence de segments de ligne connectés. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Convertit chaque courbe dans ce[`GraphicsPath`](../graphicspath) en une séquence de segments de ligne connectés. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) et en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) et en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) et en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce[`GraphicsPath`](../graphicspath) lorsqu'il est dessiné avec le spécifié[`Pen`](../pen) et en utilisant le spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) dans la zone de clip visible du fichier spécifié[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Indique si le point spécifié est contenu dans ce[`GraphicsPath`](../graphicspath) , en utilisant le spécifié[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Supprime une figure. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Supprime les chiffres. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Vide le chemin graphique et définit le[`FillMode`](../fillmode) àAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Inverse l'ordre des chiffres, des formes et des points dans chaque forme de ce[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Applique la transformation spécifiée à la forme. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Ajoute un contour supplémentaire au chemin. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | Ajoute un contour supplémentaire au[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Remplace ceci[`GraphicsPath`](../graphicspath)avec des courbes qui entourent la zone qui est remplie lorsque ce chemin est dessiné par le stylo spécifié. |

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
