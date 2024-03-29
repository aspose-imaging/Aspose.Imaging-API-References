---
title: AddFigure
second_title: Aspose.Imaging för .NET API-referens
description: Lägger till en ny figur.
type: docs
weight: 50
url: /sv/net/aspose.imaging/graphicspath/addfigure/
---
## GraphicsPath.AddFigure method

Lägger till en ny figur.

```csharp
public void AddFigure(Figure figure)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figure | Figure | Siffran att lägga till. |

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

### Se även

* class [Figure](../../figure)
* class [GraphicsPath](../../graphicspath)
* namnutrymme [Aspose.Imaging](../../graphicspath)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
