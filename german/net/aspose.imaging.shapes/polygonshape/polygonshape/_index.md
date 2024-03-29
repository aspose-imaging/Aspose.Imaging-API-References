---
title: PolygonShape
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonPolygonShapeaspose.imaging.shapes/polygonshape Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.shapes/polygonshape/polygonshape/
---
## PolygonShape() {#constructor}

Initialisiert eine neue Instanz von[`PolygonShape`](../../polygonshape) Klasse.

```csharp
public PolygonShape()
```

### Siehe auch

* class [PolygonShape](../../polygonshape)
* namensraum [Aspose.Imaging.Shapes](../../polygonshape)
* Montage [Aspose.Imaging](../../../)

---

## PolygonShape(PointF[]) {#constructor_1}

Initialisiert eine neue Instanz von[`PolygonShape`](../../polygonshape) Klasse.

```csharp
public PolygonShape(PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | PointF[] | Das Punkte-Array. |

### Siehe auch

* struct [PointF](../../../aspose.imaging/pointf)
* class [PolygonShape](../../polygonshape)
* namensraum [Aspose.Imaging.Shapes](../../polygonshape)
* Montage [Aspose.Imaging](../../../)

---

## PolygonShape(PointF[], bool) {#constructor_2}

Initialisiert eine neue Instanz von[`PolygonShape`](../../polygonshape) Klasse.

```csharp
public PolygonShape(PointF[] points, bool isClosed)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | PointF[] | Das Punkte-Array. |
| isClosed | Boolean | Wenn eingestellt`Stimmt` Das Polygon ist geschlossen. |

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

* struct [PointF](../../../aspose.imaging/pointf)
* class [PolygonShape](../../polygonshape)
* namensraum [Aspose.Imaging.Shapes](../../polygonshape)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
