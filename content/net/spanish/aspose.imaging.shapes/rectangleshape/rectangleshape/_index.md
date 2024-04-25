---
title: RectangleShape
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delRectangleShapeaspose.imaging.shapes/rectangleshape clase.
type: docs
weight: 10
url: /es/aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape() {#constructor}

Inicializa una nueva instancia del[`RectangleShape`](../../rectangleshape) clase.

```csharp
public RectangleShape()
```

### Ver también

* class [RectangleShape](../../rectangleshape)
* espacio de nombres [Aspose.Imaging.Shapes](../../rectangleshape)
* asamblea [Aspose.Imaging](../../../)

---

## RectangleShape(RectangleF) {#constructor_1}

Inicializa una nueva instancia del[`RectangleShape`](../../rectangleshape) clase.

```csharp
public RectangleShape(RectangleF rectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | RectangleF | el rectángulo |

### Ejemplos

Estos ejemplos hacen uso de las clases GraphicsPath y Graphics para crear y manipular figuras en una superficie de imagen. El ejemplo crea una nueva imagen (de tipo Tiff), limpia la superficie y dibuja rutas con la ayuda de la clase GraphicsPath. Al final, se llama al método DrawPath expuesto por la clase Graphics para representar las rutas en la superficie.

```csharp
[C#]

//Crear una instancia de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Crear una instancia de TiffOptions y establecer sus diversas propiedades
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Establecer el origen de la instancia de ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Crear e inicializar una instancia de la clase Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Borrar superficie gráfica
        graphics.Clear(Color.Wheat);

        //Crear una instancia de la clase GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Crear una instancia de la clase Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Agregar formas al objeto Figura
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Agregar objeto Figura a GraphicsPath
        graphicspath.AddFigure(figure);

        //Dibujar ruta con objeto Pluma de color Negro
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // guarda todos los cambios.
        image.Save();
    }
}
```

Este ejemplo crea una nueva imagen y dibuja una variedad de formas usando Figuras y GraphicsPath en la superficie de la imagen.

```csharp
[C#]

//Crea una instancia de BmpOptions y establece sus diversas propiedades            
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Cree una instancia de FileCreateSource y asígnela como Fuente para la instancia de BmpOptions
//El segundo parámetro booleano determina si el archivo a crear es temporal o no
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//Crear una instancia de Imagen 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Crear e inicializar una instancia de la clase Graphics
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Borrar superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crear una instancia de la clase GraphicsPath
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Crear una instancia de la clase Figure
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    // Agregar forma al objeto de figura
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Crear una instancia de la clase Figure
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    // Agregar forma al objeto de figura
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //Agregar objeto Figura a GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Dibujar ruta con objeto Pluma de color Negro
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // guarda todos los cambios.
    image.Save();
}
```

### Ver también

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [RectangleShape](../../rectangleshape)
* espacio de nombres [Aspose.Imaging.Shapes](../../rectangleshape)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
