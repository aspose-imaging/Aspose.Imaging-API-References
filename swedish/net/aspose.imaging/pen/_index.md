---
title: Pen
second_title: Aspose.Imaging för .NET API-referens
description: Definierar ett objekt som används för att rita linjer kurvor och figurer.
type: docs
weight: 10690
url: /sv/net/aspose.imaging/pen/
---
## Pen class

Definierar ett objekt som används för att rita linjer, kurvor och figurer.

```csharp
public class Pen : TransparencySupporter
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Initierar en ny instans av[`Pen`](../pen) klass med den angivna[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Initierar en ny instans av[`Pen`](../pen) klass med den angivna färgen. |
| [Pen](pen#constructor_1)(Brush, float) | Initierar en ny instans av[`Pen`](../pen) klass med den angivna[`Brush`](./brush) och[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Initierar en ny instans av[`Pen`](../pen) klass med den angivna[`Color`](./color) och[`Width`](./width) egenskaper. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Hämtar eller ställer in justeringen för detta[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Hämtar eller ställer in[`Brush`](./brush) som bestämmer attributen för detta[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Hämtar eller ställer in färgen på detta[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Hämtar eller ställer in en matris med värden som anger en sammansatt penna. En sammansatt penna ritar en sammansatt linje som består av parallella linjer och mellanslag. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Får eller ställer in ett anpassat tak som ska användas i slutet av linjer som ritas med detta[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Får eller ställer in ett anpassat tak som ska användas i början av linjer som ritas med detta[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Hämtar eller ställer in kapsylstilen som används i slutet av strecken som utgör streckade linjer ritade med detta[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Hämtar eller ställer in avståndet från början av en linje till början av ett streckmönster. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Hämtar eller ställer in en rad anpassade bindestreck och blanksteg. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Hämtar eller ställer in stilen som används för streckade linjer som ritas med detta[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Hämtar eller ställer in cap-stilen som används i slutet av linjer som ritas med detta[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Hämtar eller ställer in kopplingsstilen för ändarna av två på varandra följande linjer ritade med detta[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Hämtar eller ställer in gränsen för fogtjockleken på ett geringshörn. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Hämtar eller ställer in objektets opacitet. Värdet ska vara mellan 0 och 1. Värdet 0 betyder att objektet är helt synligt, värdet 1 betyder att objektet är helt ogenomskinligt. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Får stilen på linjer ritade med detta[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Hämtar eller ställer in cap-stilen som används i början av linjer som ritas med detta[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Hämtar eller ställer in en kopia av den geometriska transformationen för detta[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Hämtar eller ställer in bredden på detta[`Pen`](../pen) , i enheter av grafikobjektet som används för att rita. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Multiplicerar transformationsmatrisen för detta[`Pen`](../pen) av den angivna[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplicerar transformationsmatrisen för detta[`Pen`](../pen) av den angivna[`Matrix`](../matrix) i angiven ordning. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Återställer den geometriska transformationsmatrisen för detta[`Pen`](../pen) till identitet. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod förutsätter rotationen till transformationen. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Roterar den lokala geometriska transformationen med den angivna vinkeln i angiven ordning. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod förbereder skalningsmatrisen till transformationen. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Skalar den lokala geometriska transformationen med de angivna faktorerna i angiven ordning. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Ställer in värdena som bestämmer stilen på taket som används för att avsluta linjer som ritas av denna[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Översätter den lokala geometriska transformationen med de angivna måtten. Denna metod lägger till översättningen till transformationen. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Översätter den lokala geometriska transformationen med de angivna måtten i angiven ordning. |

### Exempel

Det här exemplet visar skapande och användning av Pen-objekt. Exemplet skapar en ny bild och ritar rektanglar på bildytan.

```csharp
[C#]

//Skapa en instans av BmpOptions och ställ in dess olika egenskaper
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Skapa en instans av bild på angiven sökväg
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Skapa en instans av Graphics och initiera den med Image object
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Rensa grafikytan med vit färg
    graphics.Clear(Aspose.Imaging.Color.White);

    //Skapa en instans av Pen med färgen Röd och bredd 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Skapa en instans av HatchBrush och ställ in dess egenskaper
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Skapa en instans av Pen
    //initiera det med HatchBrush-objekt och bredd
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //Rita rektanglar genom att ange Pen-objekt
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // spara alla ändringar.
    image.Save();
}
```

### Se även

* class [TransparencySupporter](../transparencysupporter)
* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
