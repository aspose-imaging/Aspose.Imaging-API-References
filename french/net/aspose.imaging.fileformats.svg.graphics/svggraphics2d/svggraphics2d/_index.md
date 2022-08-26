---
title: SvgGraphics2D
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duSvgGraphics2Daspose.imaging.fileformats.svg.graphics/svggraphics2d classe.
type: docs
weight: 10
url: /fr/net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/svggraphics2d/
---
## SvgGraphics2D(int, int, int) {#constructor_1}

Initialise une nouvelle instance du[`SvgGraphics2D`](../../svggraphics2d) classe.

```csharp
public SvgGraphics2D(int width, int height, int dpi)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| width | Int32 | La largeur de l'image Svg de sortie. |
| height | Int32 | La largeur de l'image Svg de sortie. |
| dpi | Int32 | La résolution de l'appareil, par exemple 96 points par pouce. |

### Exemples

Cet exemple montre comment créer une image SVG de la taille spécifiée et la pixelliser en PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 100;
int imageHeight = 100;
int dpi = 96;

// Crée une image SVG de 100x100 px.
Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 10);
Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

// Remplit toute l'image en rouge.
// Dessine un rectangle jaune de 10 pixels de large le long des limites de l'image.
graphics.FillRectangle(pen, brush, 0, 0, imageWidth, imageHeight);

// Récupère l'image Svg finale qui inclut toutes les commandes de dessin
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

Cet exemple montre comment créer une image SVG de la taille spécifiée et y dessiner différentes formes à l'aide de SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Dessinez un rectangle noir le long des bordures de l'image à l'aide d'un stylo noir de 1 pixel de large.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Remplir un rectangle avec la couleur de la fumée blanche.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Dessine deux lignes diagonales à l'aide d'un stylo vert foncé de 1 pixel de large.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Dessine un arc dans le rectangle {0, 0, 200, 200} à l'aide d'un stylo bleu de 2 pixels de large.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Remplit un arc
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dessine un Bézier cubique à l'aide d'un stylo rouge de 2 pixels de large.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Dessine une image raster de la taille spécifiée à l'emplacement spécifié.
// L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Dessine une chaîne de texte
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Crée un chemin à remplir
Aspose.Imaging.Figure figureToFill = new Aspose.Imaging.Figure();
figureToFill.IsClosed = true;

Aspose.Imaging.GraphicsPath pathToFill = new Aspose.Imaging.GraphicsPath();
pathToFill.AddFigure(figureToFill);

figureToFill.AddShapes(new Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.Rectangle(400, 0, 200, 100), 45, 300),
        new Aspose.Imaging.Shapes.BezierShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 200),
                new Aspose.Imaging.PointF(400, 200),
                new Aspose.Imaging.PointF(500, 100),
                new Aspose.Imaging.PointF(600, 200),
            }),
        new Aspose.Imaging.Shapes.PolygonShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 100),
            }),
        new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(0, 100, 200, 200)),
    });

// Remplissez le chemin à l'aide d'un pinceau jaune et d'un stylo vert pour dessiner le contour
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Crée un chemin à dessiner
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Dessine le chemin à l'aide d'un stylo orange de 5 pixels de large.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Obtient l'image SVG finale qui inclut toutes les commandes de dessin
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Voir également

* class [SvgGraphics2D](../../svggraphics2d)
* espace de noms [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* Assemblée [Aspose.Imaging](../../../)

---

## SvgGraphics2D(SvgImage) {#constructor}

Initialise une nouvelle instance du[`SvgGraphics2D`](../../svggraphics2d) classe.

```csharp
public SvgGraphics2D(SvgImage image)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | SvgImage | L'image sur laquelle effectuer les opérations de dessin. |

### Voir également

* class [SvgImage](../../../aspose.imaging.fileformats.svg/svgimage)
* class [SvgGraphics2D](../../svggraphics2d)
* espace de noms [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
