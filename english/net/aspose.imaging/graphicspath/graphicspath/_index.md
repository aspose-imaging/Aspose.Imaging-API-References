---
title: GraphicsPath.GraphicsPath
second_title: Aspose.Imaging for .NET API Reference
description: GraphicsPath constructor. Initializes a new instance of the GraphicsPath class
type: docs
weight: 10
url: /net/aspose.imaging/graphicspath/graphicspath/
---
## GraphicsPath() {#constructor}

Initializes a new instance of the [`GraphicsPath`](../) class.

```csharp
public GraphicsPath()
```

## Examples

This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface.

```csharp
[C#]

//Create an instance of FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Create an instance of TiffOptions and set its various properties
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Set the source for the instance of ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Create and initialize an instance of Graphics class
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Clear Graphics surface
        graphics.Clear(Color.Wheat);

        //Create an instance of GraphicsPath class
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Create an instance of Figure class
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Add Shapes to Figure object
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Add Figure object to GraphicsPath
        graphicspath.AddFigure(figure);

        //Draw path with Pen object of color Black
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // save all changes.
        image.Save();
    }
}
```

### See Also

* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[]) {#constructor_1}

Initializes a new instance of the [`GraphicsPath`](../) class.

```csharp
public GraphicsPath(Figure[] figures)
```

| Parameter | Type | Description |
| --- | --- | --- |
| figures | Figure[] | The figures to initialize from. |

### See Also

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[], FillMode) {#constructor_2}

Initializes a new instance of the [`GraphicsPath`](../) class.

```csharp
public GraphicsPath(Figure[] figures, FillMode fillMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| figures | Figure[] | The figures to initialize from. |
| fillMode | FillMode | The fill mode. |

### See Also

* class [Figure](../../figure/)
* enum [FillMode](../../fillmode/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## GraphicsPath(FillMode) {#constructor_3}

Initializes a new instance of the [`GraphicsPath`](../) class.

```csharp
public GraphicsPath(FillMode fillMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | FillMode | The fill mode. |

### See Also

* enum [FillMode](../../fillmode/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


