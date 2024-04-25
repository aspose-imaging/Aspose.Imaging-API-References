---
title: RectangleShape
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duRectangleShapeaspose.imaging.shapes/rectangleshape classe.
type: docs
weight: 10
url: /fr/aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape() {#constructor}

Initialise une nouvelle instance du[`RectangleShape`](../../rectangleshape) classe.

```csharp
public RectangleShape()
```

### Voir également

* class [RectangleShape](../../rectangleshape)
* espace de noms [Aspose.Imaging.Shapes](../../rectangleshape)
* Assemblée [Aspose.Imaging](../../../)

---

## RectangleShape(RectangleF) {#constructor_1}

Initialise une nouvelle instance du[`RectangleShape`](../../rectangleshape) classe.

```csharp
public RectangleShape(RectangleF rectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rectangle | RectangleF | Le rectangle. |

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

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [RectangleShape](../../rectangleshape)
* espace de noms [Aspose.Imaging.Shapes](../../rectangleshape)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
