---
title: GraphicsPath
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonGraphicsPathaspose.imaging/graphicspath Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging/graphicspath/graphicspath/
---
## GraphicsPath() {#constructor}

Initialisiert eine neue Instanz von[`GraphicsPath`](../../graphicspath) Klasse.

```csharp
public GraphicsPath()
```

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

* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[]) {#constructor_1}

Initialisiert eine neue Instanz von[`GraphicsPath`](../../graphicspath) Klasse.

```csharp
public GraphicsPath(Figure[] figures)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | Figure[] | Die zu initialisierenden Zahlen. |

### Siehe auch

* class [Figure](../../figure)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[], FillMode) {#constructor_2}

Initialisiert eine neue Instanz von[`GraphicsPath`](../../graphicspath) Klasse.

```csharp
public GraphicsPath(Figure[] figures, FillMode fillMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | Figure[] | Die zu initialisierenden Zahlen. |
| fillMode | FillMode | Der Füllmodus. |

### Siehe auch

* class [Figure](../../figure)
* enum [FillMode](../../fillmode)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

---

## GraphicsPath(FillMode) {#constructor_3}

Initialisiert eine neue Instanz von[`GraphicsPath`](../../graphicspath) Klasse.

```csharp
public GraphicsPath(FillMode fillMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillMode | FillMode | Der Füllmodus. |

### Siehe auch

* enum [FillMode](../../fillmode)
* class [GraphicsPath](../../graphicspath)
* namensraum [Aspose.Imaging](../../graphicspath)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
