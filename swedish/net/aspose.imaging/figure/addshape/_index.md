---
title: AddShape
second_title: Aspose.Imaging för .NET API-referens
description: Lägger till en form till figuren.
type: docs
weight: 60
url: /sv/net/aspose.imaging/figure/addshape/
---
## Figure.AddShape method

Lägger till en form till figuren.

```csharp
public void AddShape(Shape shape)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | Shape | Formen att lägga till. |

### Exempel

I det här exemplet används GraphicsPath och Graphics-klassen för att skapa och manipulera figurer på en bildyta. Exempel skapar en ny bild (av typen Tiff), rensar ytan och ritar banor med hjälp av klassen GraphicsPath. I slutet anropas DrawPath-metoden som exponeras av Graphics-klassen för att rendera banorna på ytan.

```csharp
[C#]

//Skapa en instans av FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Skapa en instans av TiffOptions och ställ in dess olika egenskaper
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Ställ in källan för instansen av ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Skapa en instans av bild 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Skapa och initiera en instans av klassen Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Rensa grafikytan
        graphics.Clear(Color.Wheat);

        //Skapa en instans av klassen GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Skapa en instans av figurklassen
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Lägg till former till figurobjekt
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Lägg till figurobjekt till GraphicsPath
        graphicspath.AddFigure(figure);

        //Rita bana med pennobjekt av färg svart
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // spara alla ändringar.
        image.Save();
    }
}
```

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

* class [Shape](../../shape)
* class [Figure](../../figure)
* namnutrymme [Aspose.Imaging](../../figure)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
