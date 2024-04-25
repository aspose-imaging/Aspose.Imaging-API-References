---
title: ArcShape
second_title: Aspose.Imaging för .NET API-referens
description: Representerar en bågform.
type: docs
weight: 10950
url: /sv/aspose.imaging.shapes/arcshape/
---
## ArcShape class

Representerar en bågform.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ArcShape](arcshape#constructor)() | Initierar en ny instans av[`ArcShape`](../arcshape) class. |
| [ArcShape](arcshape#constructor_1)(RectangleF, float, float) | Initierar en ny instans av[`ArcShape`](../arcshape) class. |
| [ArcShape](arcshape#constructor_2)(RectangleF, float, float, bool) | Initierar en ny instans av[`ArcShape`](../arcshape) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Hämtar formens centrum. |
| [EndPoint](../../aspose.imaging.shapes/arcshape/endpoint) { get; } | Får slutformpunkten. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Får ett värde som indikerar om formen har segment. |
| [IsClosed](../../aspose.imaging.shapes/arcshape/isclosed) { get; set; } | Hämtar eller ställer in ett värde som anger om ordnad form är stängd. Vid bearbetning av sluten ordnad form har start- och slutpunkterna ingen betydelse. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Får den nedre vänstra rektangelpunkten. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Får den vänstra övre rektangelpunkten. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Hämtar rektangelhöjden. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Hämtar rektangelbredden. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Får den högra nedre rektangelpunkten. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Får den högra övre rektangelpunkten. |
| override [Segments](../../aspose.imaging.shapes/arcshape/segments) { get; } | Hämtar formsegmenten. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | Hämtar eller ställer in startvinkeln. |
| [StartPoint](../../aspose.imaging.shapes/arcshape/startpoint) { get; } | Får startpunkten för formen. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | Hämtar eller ställer in svepvinkeln. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [Reverse](../../aspose.imaging.shapes/arcshape/reverse)() | Vänder om ordningen på punkterna för denna form. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | Tillämpar den angivna transformationen på formen. |

### Exempel

Det här exemplet skapar en ny bild och ritar en mängd olika former med hjälp av Figurer och GraphicsPath på bildytan

```csharp
[C#]

//Skapar en instans av BmpOptions och ställer in dess olika egenskaper            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Skapa en instans av bild 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Skapa och initiera en instans av klassen Graphics
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Rensa grafikytan
    graphics.Clear(Color.Wheat);

    //Skapa en instans av klassen GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Skapa en instans av figurklassen
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //Lägg till form till figurobjekt
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Skapa en instans av figurklassen
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //Lägg till form till figurobjekt
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //Lägg till figurobjekt till GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Rita bana med pennobjekt av färg svart
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // spara alla ändringar.
    image.Save();
}
```

### Se även

* class [PieShape](../pieshape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* namnutrymme [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
