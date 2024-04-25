---
title: PolygonShape
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa una forma de polígono.
type: docs
weight: 11000
url: /es/aspose.imaging.shapes/polygonshape/
---
## PolygonShape class

Representa una forma de polígono.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PolygonShape](polygonshape#constructor)() | Inicializa una nueva instancia del[`PolygonShape`](../polygonshape) clase. |
| [PolygonShape](polygonshape#constructor_1)(PointF[]) | Inicializa una nueva instancia del[`PolygonShape`](../polygonshape) clase. |
| [PolygonShape](polygonshape#constructor_2)(PointF[], bool) | Inicializa una nueva instancia del[`PolygonShape`](../polygonshape) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/polygonshape/bounds) { get; } | Obtiene los límites del objeto. |
| override [Center](../../aspose.imaging.shapes/polygonshape/center) { get; } | Obtiene el centro de la forma. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint) { get; } | Obtiene el punto de forma final. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments) { get; } | Obtiene un valor que indica si la forma tiene segmentos. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed) { get; set; } | Obtiene o establece un valor que indica si la forma está cerrada. |
| [Points](../../aspose.imaging.shapes/polygonshape/points) { get; set; } | Obtiene o establece los puntos de la curva. |
| override [Segments](../../aspose.imaging.shapes/polygonshape/segments) { get; } | Obtiene los segmentos de forma. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint) { get; } | Obtiene el punto de forma inicial. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse)() | Invierte el orden de los puntos de esta forma. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform)(Matrix) | Aplica la transformación especificada a la forma. |

### Ejemplos

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

* class [Shape](../../aspose.imaging/shape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* espacio de nombres [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
