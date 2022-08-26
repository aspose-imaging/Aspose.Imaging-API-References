---
title: GraphicsPath
second_title: Aspose.Imaging für .NET-API-Referenz
description: Repräsentiert eine Reihe verbundener Linien und Kurven. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 9370
url: /de/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

Repräsentiert eine Reihe verbundener Linien und Kurven. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Initialisiert eine neue Instanz von[`GraphicsPath`](../graphicspath) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Ruft die Grenzen des Objekts ab oder legt sie fest. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Ruft die Wegzahlen ab. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Holt oder setzt a[`FillMode`](../fillmode) Aufzählung, die bestimmt, wie die Innenräume der Formen in diesem[`GraphicsPath`](../graphicspath) sind gefüllt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Fügt eine neue Figur hinzu. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Fügt neue Zahlen hinzu. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Fügt die angegebene an[`GraphicsPath`](../graphicspath) zu diesem Pfad. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Fügt die angegebene an[`GraphicsPath`](../graphicspath) zu diesem Pfad. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Führt einen tiefen Klon dieses Grafikpfads durch. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Konvertiert jede Kurve in diesem Pfad in eine Folge verbundener Liniensegmente. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Wendet die angegebene Transformation an und wandelt dann jede Kurve in diese um[`GraphicsPath`](../graphicspath) in eine Folge verbundener Liniensegmente. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Wandelt jede Kurve in diese um[`GraphicsPath`](../graphicspath) in eine Folge verbundener Liniensegmente. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Ruft die Grenzen des Objekts ab. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Ruft die Grenzen des Objekts ab. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Umrisslinie davon enthalten ist[`GraphicsPath`](../graphicspath) wenn mit den angegebenen gezeichnet[`Pen`](../pen) und unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) im sichtbaren Clip-Bereich des angegebenen[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Gibt an, ob der angegebene Punkt darin enthalten ist[`GraphicsPath`](../graphicspath) , unter Verwendung der angegebenen[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Entfernt eine Figur. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Entfernt Zahlen. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Leert den Grafikpfad und setzt die[`FillMode`](../fillmode) zuAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Kehrt die Reihenfolge der Figuren, Formen und Punkte in jeder Form davon um[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Wendet die angegebene Transformation auf die Form an. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | Fügt einen zusätzlichen Umriss hinzu[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Ersetzt dies[`GraphicsPath`](../graphicspath)mit Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |

### Beispiele

Dieses Beispiel verwendet GraphicsPath und die Graphics-Klasse, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Beispiel erstellt ein neues Bild (vom Typ Tiff), löscht die Oberfläche und zeichnet Pfade mit Hilfe der GraphicsPath-Klasse. Am Ende wird die DrawPath-Methode aufgerufen, die von der Graphics-Klasse bereitgestellt wird, um die Pfade auf der Oberfläche zu rendern.

```csharp
[C#]

//Eine Instanz von FileStream erstellen
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Eine Instanz von TiffOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Setzen Sie die Quelle für die Instanz von ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Eine Instanz der Graphics-Klasse erstellen und initialisieren
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafikoberfläche löschen
        graphics.Clear(Color.Wheat);

        //Eine Instanz der GraphicsPath-Klasse erstellen
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Eine Instanz der Figure-Klasse erstellen
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Formen zum Figurobjekt hinzufügen
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Figure-Objekt zu GraphicsPath hinzufügen
        graphicspath.AddFigure(figure);

        // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // Alle Änderungen speichern.
        image.Save();
    }
}
```

### Siehe auch

* class [ObjectWithBounds](../objectwithbounds)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
