---
title: EmfRecorderGraphics2D
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Inicializa una nueva instancia delEmfRecorderGraphics2Daspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d clase.
type: docs
weight: 10
url: /es/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/emfrecordergraphics2d/
---
## EmfRecorderGraphics2D constructor

Inicializa una nueva instancia del[`EmfRecorderGraphics2D`](../../emfrecordergraphics2d) clase.

```csharp
public EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| frame | Rectangle | El marco. |
| deviceSize | Size | Tamaño del dispositivo. |
| deviceSizeMm | Size | El tamaño del dispositivo mm. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen EMF y dibujar algunas formas geométricas en ella usando EmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

// El tamaño de la imagen en píxeles
int deviceWidth = 600;
int deviceHeight = 400;

// El tamaño de la imagen en milímetros
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Crea una imagen EMF.
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// Dibuje un rectángulo negro a lo largo de los bordes de la imagen con un bolígrafo negro de 1 píxel de ancho.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// Rellena un rectángulo con el color del humo blanco.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Dibuja dos líneas diagonales con un bolígrafo verde oscuro de 1 píxel de ancho.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// Dibuja un arco dentro del rectángulo {0, 0, 200, 200} usando un bolígrafo azul de 2 píxeles de ancho.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Rellenar un arco
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Dibuja un bezier cúbico con un bolígrafo rojo de 2 píxeles de ancho.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// Dibujar una imagen rasterizada del tamaño especificado en la ubicación especificada.
// La imagen se escala para ajustarse al rectángulo deseado.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// Dibujar una cadena de texto
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

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

// Para rasterizar SVG necesitamos especificar las opciones de rasterización.
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// Obtener la imagen WMF final que incluye todos los comandos de dibujo
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### Ver también

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Size](../../../aspose.imaging/size)
* class [EmfRecorderGraphics2D](../../emfrecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Graphics](../../emfrecordergraphics2d)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
