---
title: DrawImage
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Dessine limage spécifiée en utilisant sa taille physique dorigine à lemplacement spécifié.
type: docs
weight: 80
url: /fr/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

Dessine l'image spécifiée, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

```csharp
public void DrawImage(RasterImage image, Point location)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image à dessiner. |
| location | Point | L'emplacement du coin supérieur gauche de l'image dessinée. |

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Rectangle, Rectangle, GraphicsUnit) {#drawimage_1}

Dessine la partie spécifiée de l'image spécifiée à l'emplacement spécifié et avec la taille spécifiée.

```csharp
public void DrawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image à dessiner. |
| destRect | Rectangle | Structure rectangulaire qui spécifie l'emplacement et la taille de l'image dessinée. L'image est mise à l'échelle pour s'adapter au rectangle. |
| srcRect | Rectangle | Structure rectangle qui spécifie la partie de l'objet image à dessiner. |
| srcUnit | GraphicsUnit | Les unités de mesure utilisées par le paramètre srcRect. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | srcUnit ; ne prend en charge que l'unité Pixel |

### Exemples

Cet exemple montre comment créer une image WMF et dessiner des formes géométriques à l'aide de WmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// C'est la résolution d'écran par défaut.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Crée une image WMF.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// Dessinez un rectangle noir le long des bordures de l'image à l'aide d'un stylo noir de 1 pixel de large.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Remplir un rectangle avec la couleur de la fumée blanche.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Dessine deux lignes diagonales à l'aide d'un stylo vert foncé de 1 pixel de large.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Dessine un arc dans le rectangle {0, 0, 200, 200} à l'aide d'un stylo bleu de 2 pixels de large.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Remplit un arc
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dessine un Bézier cubique à l'aide d'un stylo rouge de 2 pixels de large.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Dessine une image raster de la taille spécifiée à l'emplacement spécifié.
// L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Dessine une chaîne de texte
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Afin de pixelliser SVG, nous devons spécifier les options de pixellisation.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Récupère l'image WMF finale qui inclut toutes les commandes de dessin
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

Cet exemple montre comment créer une image EMF et y dessiner des formes géométriques à l'aide d'EmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

// La taille de l'image en pixels
int deviceWidth = 600;
int deviceHeight = 400;

// La taille de l'image en millimètres
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crée une image EMF.
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// Dessinez un rectangle noir le long des bordures de l'image à l'aide d'un stylo noir de 1 pixel de large.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// Remplir un rectangle avec la couleur de la fumée blanche.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Dessine deux lignes diagonales à l'aide d'un stylo vert foncé de 1 pixel de large.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// Dessine un arc dans le rectangle {0, 0, 200, 200} à l'aide d'un stylo bleu de 2 pixels de large.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Remplit un arc
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dessine un Bézier cubique à l'aide d'un stylo rouge de 2 pixels de large.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Dessine une image raster de la taille spécifiée à l'emplacement spécifié.
// L'image est mise à l'échelle pour s'adapter au rectangle souhaité.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Dessine une chaîne de texte
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Afin de pixelliser SVG, nous devons spécifier les options de pixellisation.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Récupère l'image WMF finale qui inclut toutes les commandes de dessin
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### Voir également

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawImage(byte[], Rectangle, GraphicsUnit) {#drawimage_2}

Dessine l'image.

```csharp
public void DrawImage(byte[] imageBytes, Rectangle destRect, GraphicsUnit srcUnit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageBytes | Byte[] | Les octets de l'image. |
| destRect | Rectangle | Le plus rect. |
| srcUnit | GraphicsUnit | L'unité source. |

### Voir également

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* Assemblée [Aspose.Imaging](../../../)

---

## DrawImage(Stream, Rectangle, GraphicsUnit) {#drawimage_3}

Dessine l'image.

```csharp
public void DrawImage(Stream stream, Rectangle destRect, GraphicsUnit srcUnit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux. |
| destRect | Rectangle | Le plus rect. |
| srcUnit | GraphicsUnit | L'unité source. |

### Voir également

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
