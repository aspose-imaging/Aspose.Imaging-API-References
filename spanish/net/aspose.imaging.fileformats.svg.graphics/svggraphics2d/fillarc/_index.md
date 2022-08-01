---
title: FillArc
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Rellena un arco que representa una parte de una elipse especificada por una estructura Rectangle.
type: docs
weight: 100
url: /es/net/aspose.imaging.fileformats.svg.graphics/svggraphics2d/fillarc/
---
## SvgGraphics2D.FillArc method

Rellena un arco que representa una parte de una elipse especificada por una estructura Rectangle.

```csharp
public void FillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | El bolígrafo para dibujar el contorno de la figura. |
| brush | Brush | El pincel para rellenar el interior de la figura. |
| rect | Rectangle | Los límites de la elipse. |
| startAngle | Single | El ángulo en grados medido en el sentido de las agujas del reloj desde el eje x hasta el punto inicial del arco. |
| arcAngle | Single | El ángulo en grados medido en el sentido de las agujas del reloj desde el parámetro startAngle hasta el punto final del arco. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen SVG del tamaño especificado y dibujar diferentes formas en ella usando SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Dibuje un rectángulo negro a lo largo de los bordes de la imagen con un bolígrafo negro de 1 píxel de ancho.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Rellena un rectángulo con el color del humo blanco.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Dibuja dos líneas diagonales con un bolígrafo verde oscuro de 1 píxel de ancho.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Dibuja un arco dentro del rectángulo {0, 0, 200, 200} usando un bolígrafo azul de 2 píxeles de ancho.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Rellenar un arco
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dibuja un bezier cúbico con un bolígrafo rojo de 2 píxeles de ancho.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Dibujar una imagen rasterizada del tamaño especificado en la ubicación especificada.
// La imagen se escala para ajustarse al rectángulo deseado.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Dibujar una cadena de texto
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Crea un camino para llenar
Aspose.Imaging.Figure figureToFill = new Aspose.Imaging.Figure();
figureToFill.IsClosed = true;

Aspose.Imaging.GraphicsPath pathToFill = new Aspose.Imaging.GraphicsPath();
pathToFill.AddFigure(figureToFill);

figureToFill.AddShapes(new Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.Rectangle(400, 0, 200, 100), 45, 300),
        new Aspose.Imaging.Shapes.BezierShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 200),
                new Aspose.Imaging.PointF(400, 200),
                new Aspose.Imaging.PointF(500, 100),
                new Aspose.Imaging.PointF(600, 200),
            }),
        new Aspose.Imaging.Shapes.PolygonShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 100),
            }),
        new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(0, 100, 200, 200)),
    });

// Rellena el trazado con un pincel amarillo y un bolígrafo verde para dibujar el contorno
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Crear un camino para dibujar
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Dibuja la ruta con un bolígrafo naranja de 5 píxeles de ancho.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Obtener la imagen SVG final que incluye todos los comandos de dibujo
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Ver también

* class [Pen](../../../aspose.imaging/pen)
* class [Brush](../../../aspose.imaging/brush)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [SvgGraphics2D](../../svggraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
