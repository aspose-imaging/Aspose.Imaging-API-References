---
title: EllipseShape
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt eine Ellipsenform dar.
type: docs
weight: 10980
url: /de/net/aspose.imaging.shapes/ellipseshape/
---
## EllipseShape class

Stellt eine Ellipsenform dar.

```csharp
public class EllipseShape : RectangleShape
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EllipseShape](ellipseshape#constructor)() | Initialisiert eine neue Instanz von[`EllipseShape`](../ellipseshape) Klasse. |
| [EllipseShape](ellipseshape#constructor_1)(RectangleF) | Initialisiert eine neue Instanz von[`EllipseShape`](../ellipseshape) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Ruft die Grenzen des Objekts ab. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Ruft den Mittelpunkt der Form ab. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Ruft einen Wert ab, der angibt, ob die Form Segmente hat. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Ruft den linken unteren Rechteckpunkt ab. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Ruft den linken oberen Rechteckpunkt ab. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Ruft die Rechteckhöhe ab. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Ruft die Breite des Rechtecks ab. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Ruft den rechten unteren Rechteckpunkt ab. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Ruft den rechten oberen Rechteckpunkt ab. |
| override [Segments](../../aspose.imaging.shapes/ellipseshape/segments) { get; } | Ruft die Formsegmente ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds)(Matrix) | Ruft die Grenzen des Objekts ab. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds)(Matrix, Pen) | Ruft die Grenzen des Objekts ab. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

### Beispiele

Dieses Beispiel erstellt ein neues Image und zeichnet eine Vielzahl von Formen mithilfe von Figures und GraphicsPath auf der Image-Oberfläche

```csharp
[C#]

//Erzeugt eine Instanz von BmpOptions und setzt ihre verschiedenen Eigenschaften            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von BmpOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Eine Instanz von Image erstellen 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Eine Instanz der Graphics-Klasse erstellen und initialisieren
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Grafikoberfläche löschen
    graphics.Clear(Color.Wheat);

    //Eine Instanz der GraphicsPath-Klasse erstellen
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Eine Instanz der Figure-Klasse erstellen
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //Shape zum Figure-Objekt hinzufügen
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Eine Instanz der Figure-Klasse erstellen
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //Shape zum Figure-Objekt hinzufügen
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //Figure-Objekt zu GraphicsPath hinzufügen
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // Alle Änderungen speichern.
    image.Save();
}
```

### Siehe auch

* class [RectangleShape](../rectangleshape)
* namensraum [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
