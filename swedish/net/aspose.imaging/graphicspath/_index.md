---
title: GraphicsPath
second_title: Aspose.Imaging för .NET API-referens
description: Representerar en serie sammankopplade linjer och kurvor. Denna klass kan inte ärvas.
type: docs
weight: 9370
url: /sv/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

Representerar en serie sammankopplade linjer och kurvor. Denna klass kan inte ärvas.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Initierar en ny instans av[`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Initierar en ny instans av[`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Initierar en ny instans av[`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Initierar en ny instans av[`GraphicsPath`](../graphicspath) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Hämtar eller ställer in objektets gränser. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Hämtar sökvägssiffrorna. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Hämtar eller sätter en[`FillMode`](../fillmode) uppräkning som avgör hur interiören av former i detta[`GraphicsPath`](../graphicspath) är fyllda. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Lägger till en ny figur. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Lägger till nya figurer. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Lägger till det angivna[`GraphicsPath`](../graphicspath) till denna väg. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Lägger till det angivna[`GraphicsPath`](../graphicspath) till denna väg. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Utför en djup klon av denna grafikbana. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Konverterar varje kurva i denna väg till en sekvens av anslutna linjesegment. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Tillämpar den angivna transformationen och konverterar sedan varje kurva i denna[`GraphicsPath`](../graphicspath) i en sekvens av anslutna linjesegment. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Konverterar varje kurva i denna[`GraphicsPath`](../graphicspath) i en sekvens av anslutna linjesegment. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Hämtar objektets gränser. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Hämtar objektets gränser. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) och använda den angivna[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) och använda den angivna[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) och använda den angivna[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Indikerar om den angivna punkten finns inom (under) konturen av denna[`GraphicsPath`](../graphicspath) när det dras med det angivna[`Pen`](../pen) och använda den angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) i det synliga klippområdet för den angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Indikerar om den angivna punkten finns i denna[`GraphicsPath`](../graphicspath) , med den angivna[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Tar bort en figur. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Tar bort figurer. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Tömmer grafikbanan och ställer in[`FillMode`](../fillmode) tillAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Vänder om ordningen på figurer, former och punkter i varje form av detta[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Tillämpar den angivna transformationen på formen. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Lägger till en ytterligare kontur till sökvägen. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | Lägger till en ytterligare disposition till[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Ersätter detta[`GraphicsPath`](../graphicspath)med kurvor som omsluter området som fylls när denna väg ritas av den angivna pennan. |

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

* class [ObjectWithBounds](../objectwithbounds)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
