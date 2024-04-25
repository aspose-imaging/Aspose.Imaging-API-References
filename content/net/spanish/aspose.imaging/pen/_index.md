---
title: Pen
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Define un objeto utilizado para dibujar líneas curvas y figuras.
type: docs
weight: 10690
url: /es/aspose.imaging/pen/
---
## Pen class

Define un objeto utilizado para dibujar líneas, curvas y figuras.

```csharp
public class Pen : TransparencySupporter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Inicializa una nueva instancia del[`Pen`](../pen) clase con el especificado[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Inicializa una nueva instancia del[`Pen`](../pen) clase con el color especificado. |
| [Pen](pen#constructor_1)(Brush, float) | Inicializa una nueva instancia del[`Pen`](../pen) clase con el especificado[`Brush`](./brush) y[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Inicializa una nueva instancia del[`Pen`](../pen) clase con el especificado[`Color`](./color) y[`Width`](./width) propiedades. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Obtiene o establece la alineación para este[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Obtiene o establece el[`Brush`](./brush) que determina los atributos de este[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Obtiene o establece el color de este[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Obtiene o establece una matriz de valores que especifica una pluma compuesta. Un bolígrafo compuesto dibuja una línea compuesta formada por líneas paralelas y espacios. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Obtiene o establece un límite personalizado para usar al final de las líneas dibujadas con este[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Obtiene o establece un límite personalizado para usar al comienzo de las líneas dibujadas con este[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Obtiene o establece el estilo de mayúscula utilizado al final de los guiones que forman las líneas discontinuas dibujadas con este[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Obtiene o establece la distancia desde el inicio de una línea hasta el inicio de un patrón de guiones. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Obtiene o establece una matriz de guiones y espacios personalizados. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Obtiene o establece el estilo utilizado para las líneas discontinuas dibujadas con este[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Obtiene o establece el estilo de mayúscula utilizado al final de las líneas dibujadas con este[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Obtiene o establece el límite del grosor de la unión en una esquina a inglete. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Obtiene o establece la opacidad del objeto. El valor debe estar entre 0 y 1. El valor de 0 significa que el objeto es completamente visible, el valor de 1 significa que el objeto es completamente opaco. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Obtiene el estilo de las líneas dibujadas con este[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Obtiene o establece el estilo de mayúscula utilizado al comienzo de las líneas dibujadas con este[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Obtiene o establece una copia de la transformación geométrica para este[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Obtiene o establece el ancho de este[`Pen`](../pen) , en unidades del objeto Graphics utilizado para dibujar. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Multiplica la matriz de transformación para este[`Pen`](../pen) por el especificado[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multiplica la matriz de transformación para este[`Pen`](../pen) por el especificado[`Matrix`](../matrix) en el orden especificado. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Restablece la matriz de transformación geométrica para este[`Pen`](../pen) a identidad. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Gira la transformación geométrica local en el ángulo especificado. Este método antepone la rotación a la transformación. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Gira la transformación geométrica local el ángulo especificado en el orden especificado. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Escala la transformación geométrica local según los factores especificados. Este método antepone la matriz de escala a la transformación. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Escala la transformación geométrica local según los factores especificados en el orden especificado. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Establece los valores que determinan el estilo de cap usado para terminar las líneas dibujadas por este[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a la transformación. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ejemplos

Este ejemplo muestra la creación y el uso de objetos Pen. El ejemplo crea una nueva imagen y dibuja rectángulos en la superficie de la imagen.

```csharp
[C#]

//Cree una instancia de BmpOptions y configure sus diversas propiedades
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Cree una instancia de FileCreateSource y asígnela como Fuente para la instancia de BmpOptions
//El segundo parámetro booleano determina si el archivo a crear es temporal o no
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Crear una instancia de Imagen en la ruta especificada
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Crea una instancia de Graphics e inicialízala con el objeto Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // Limpiar la superficie de gráficos con color blanco
    graphics.Clear(Aspose.Imaging.Color.White);

    //Crear una instancia de Pen con color Rojo y ancho 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Crear una instancia de HatchBrush y establecer sus propiedades
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Crear una instancia de Pen
    //inicializarlo con objeto HatchBrush y ancho
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    // Dibujar rectángulos especificando el objeto Pen
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // guarda todos los cambios.
    image.Save();
}
```

### Ver también

* class [TransparencySupporter](../transparencysupporter)
* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
