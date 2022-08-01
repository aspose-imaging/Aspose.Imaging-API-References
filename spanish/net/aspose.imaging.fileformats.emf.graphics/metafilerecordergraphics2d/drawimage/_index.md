---
title: DrawImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Dibuja la Imagen especificada utilizando su tamaño físico original en la ubicación especificada.
type: docs
weight: 80
url: /es/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

Dibuja la Imagen especificada, utilizando su tamaño físico original, en la ubicación especificada.

```csharp
public void DrawImage(RasterImage image, Point location)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen para dibujar. |
| location | Point | La ubicación de la esquina superior izquierda de la imagen dibujada. |

### Ver también

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* asamblea [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Rectangle, Rectangle, GraphicsUnit) {#drawimage_1}

Dibuja la parte especificada de la imagen especificada en la ubicación especificada y con el tamaño especificado.

```csharp
public void DrawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | RasterImage | La imagen para dibujar. |
| destRect | Rectangle | Estructura de rectángulo que especifica la ubicación y el tamaño de la imagen dibujada. La imagen se escala para ajustarse al rectángulo. |
| srcRect | Rectangle | Estructura de rectángulo que especifica la parte del objeto de imagen que se va a dibujar. |
| srcUnit | GraphicsUnit | Las unidades de medida utilizadas por el parámetro srcRect. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | srcUnit;Admite solo unidades de píxeles |

### Ejemplos

Este ejemplo muestra cómo crear una imagen WMF y dibujar algunas formas geométricas usando WmfRecorderGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Esta es la resolución de pantalla predeterminada.
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Crear una imagen WMF.
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// Dibuje un rectángulo negro a lo largo de los bordes de la imagen con un bolígrafo negro de 1 píxel de ancho.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Rellena un rectángulo con el color del humo blanco.
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// Dibuja dos líneas diagonales con un bolígrafo verde oscuro de 1 píxel de ancho.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

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
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
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
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

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

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* asamblea [Aspose.Imaging](../../../)

---

## DrawImage(byte[], Rectangle, GraphicsUnit) {#drawimage_2}

Dibuja la imagen.

```csharp
public void DrawImage(byte[] imageBytes, Rectangle destRect, GraphicsUnit srcUnit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageBytes | Byte[] | Los bytes de la imagen. |
| destRect | Rectangle | El destino recto. |
| srcUnit | GraphicsUnit | La unidad fuente. |

### Ver también

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* asamblea [Aspose.Imaging](../../../)

---

## DrawImage(Stream, Rectangle, GraphicsUnit) {#drawimage_3}

Dibuja la imagen.

```csharp
public void DrawImage(Stream stream, Rectangle destRect, GraphicsUnit srcUnit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| destRect | Rectangle | El destino recto. |
| srcUnit | GraphicsUnit | La unidad fuente. |

### Ver también

* struct [Rectangle](../../../aspose.imaging/rectangle)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit)
* class [MetafileRecorderGraphics2D](../../metafilerecordergraphics2d)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
