---
title: PolygonShape
second_title: Aspose.Imaging för .NET API-referens
description: Representerar en polygonform.
type: docs
weight: 11000
url: /sv/net/aspose.imaging.shapes/polygonshape/
---
## PolygonShape class

Representerar en polygonform.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PolygonShape](polygonshape#constructor)() | Initierar en ny instans av[`PolygonShape`](../polygonshape) class. |
| [PolygonShape](polygonshape#constructor_1)(PointF[]) | Initierar en ny instans av[`PolygonShape`](../polygonshape) class. |
| [PolygonShape](polygonshape#constructor_2)(PointF[], bool) | Initierar en ny instans av[`PolygonShape`](../polygonshape) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/polygonshape/bounds) { get; } | Hämtar objektets gränser. |
| override [Center](../../aspose.imaging.shapes/polygonshape/center) { get; } | Hämtar formens centrum. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint) { get; } | Får slutformpunkten. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments) { get; } | Får ett värde som indikerar om formen har segment. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed) { get; set; } | Hämtar eller ställer in ett värde som anger om formen är stängd. |
| [Points](../../aspose.imaging.shapes/polygonshape/points) { get; set; } | Hämtar eller ställer in kurvpunkterna. |
| override [Segments](../../aspose.imaging.shapes/polygonshape/segments) { get; } | Hämtar formsegmenten. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint) { get; } | Får startpunkten för formen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse)() | Vänder om ordningen på punkterna för denna form. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform)(Matrix) | Tillämpar den angivna transformationen på formen. |

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

* class [Shape](../../aspose.imaging/shape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* namnutrymme [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
