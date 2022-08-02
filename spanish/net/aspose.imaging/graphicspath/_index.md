---
title: GraphicsPath
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa una serie de líneas y curvas conectadas. Esta clase no se puede heredar.
type: docs
weight: 9370
url: /es/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

Representa una serie de líneas y curvas conectadas. Esta clase no se puede heredar.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Inicializa una nueva instancia del[`GraphicsPath`](../graphicspath) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Obtiene o establece los límites del objeto. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Obtiene las cifras de la ruta. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Obtiene o establece un[`FillMode`](../fillmode) enumeración que determina cómo los interiores de las formas en este[`GraphicsPath`](../graphicspath) están llenos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Agrega una nueva figura. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Agrega nuevas figuras. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Agrega el especificado[`GraphicsPath`](../graphicspath) a este camino. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Agrega el especificado[`GraphicsPath`](../graphicspath) a este camino. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Realiza una clonación profunda de esta ruta de gráficos. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Convierte cada curva de esta ruta en una secuencia de segmentos de línea conectados. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Aplica la transformación especificada y luego convierte cada curva en este[`GraphicsPath`](../graphicspath) en una secuencia de segmentos de línea conectados. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Convierte cada curva en este[`GraphicsPath`](../graphicspath) en una secuencia de segmentos de línea conectados. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Obtiene los límites del objeto. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Obtiene los límites del objeto. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Indica si el punto especificado está contenido dentro (debajo) del contorno de este[`GraphicsPath`](../graphicspath) cuando se dibuja con el especificado[`Pen`](../pen) y utilizando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) en la región de recorte visible del especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Indica si el punto especificado está contenido dentro de este[`GraphicsPath`](../graphicspath) , usando el especificado[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Elimina una figura. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Elimina figuras. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Vacía la ruta de gráficos y establece el[`FillMode`](../fillmode) aAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Invierte el orden de figuras, formas y puntos en cada forma de este[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Aplica la transformación especificada a la forma. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Aplica una transformación warp, definida por un rectángulo y un paralelogramo, a este[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Agrega un contorno adicional a la ruta. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | Agrega un esquema adicional al[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Reemplaza esto[`GraphicsPath`](../graphicspath)con curvas que encierran el área que se rellena cuando la pluma especificada dibuja esta ruta. |

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

### Ver también

* class [ObjectWithBounds](../objectwithbounds)
* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
