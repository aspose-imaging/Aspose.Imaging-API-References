---
title: Region
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Describe el interior de una forma gráfica compuesta de rectángulos y caminos. Esta clase no se puede heredar.
type: docs
weight: 10850
url: /es/net/aspose.imaging/region/
---
## Region class

Describe el interior de una forma gráfica compuesta de rectángulos y caminos. Esta clase no se puede heredar.

```csharp
public sealed class Region
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Region](region#constructor)() | Inicializa un nuevo[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Inicializa un nuevo[`Region`](../region) con lo especificado[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Inicializa un nuevo[`Region`](../region) de lo especificado[`Rectangle`](../rectangle) estructura. |
| [Region](region#constructor_3)(RectangleF) | Inicializa un nuevo[`Region`](../region) de lo especificado[`RectangleF`](../rectanglef) estructura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | Actualiza esto[`Region`](../region) para contener la porción de lo especificado[`GraphicsPath`](../graphicspath) que no se cruza con esto[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | Actualiza esto[`Region`](../region) para contener la porción de lo especificado[`Rectangle`](../rectangle) estructura que no se cruza con esta[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | Actualiza esto[`Region`](../region) para contener la porción de lo especificado[`RectangleF`](../rectanglef) estructura que no se cruza con esta[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | Actualiza esto[`Region`](../region) para contener la porción de lo especificado[`Region`](../region) que no se cruza con esto[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | Crea una copia profunda exacta de este[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | Comprueba si el especificado[`Region`](../region) es identico a este[`Region`](../region) en la superficie de dibujo especificada. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | Actualiza esto[`Region`](../region) contener sólo la parte de su interior que no intersecta con el especificado[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | Actualiza esto[`Region`](../region) contener sólo la parte de su interior que no intersecta con el especificado[`Rectangle`](../rectangle) estructura. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | Actualiza esto[`Region`](../region) contener sólo la parte de su interior que no intersecta con el especificado[`RectangleF`](../rectanglef) estructura. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | Actualiza esto[`Region`](../region) contener sólo la parte de su interior que no intersecta con el especificado[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | Actualiza esto[`Region`](../region) a la intersección de sí mismo con el especificado[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | Actualiza esto[`Region`](../region) a la intersección de sí mismo con el especificado[`Rectangle`](../rectangle) estructura. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | Actualiza esto[`Region`](../region) a la intersección de sí mismo con el especificado[`RectangleF`](../rectanglef) estructura. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | Actualiza esto[`Region`](../region) a la intersección de sí mismo con el especificado[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | Comprueba si este[`Region`](../region) tiene un interior vacío en la superficie de dibujo especificada. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | Comprueba si este[`Region`](../region) tiene un interior infinito en la superficie de dibujo especificada. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | Comprueba si el especificado[`Point`](../point) estructura está contenida dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | Comprueba si el especificado[`PointF`](../pointf) estructura está contenida dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | Comprueba si alguna parte del valor especificado[`Rectangle`](../rectangle) estructura está contenida dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | Comprueba si alguna parte del valor especificado[`RectangleF`](../rectanglef) estructura está contenida dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | Comprueba si el punto especificado está contenido dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | Comprueba si el especificado[`Point`](../point) estructura está contenida dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | Comprueba si el especificado[`PointF`](../pointf) estructura está contenida dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | Comprueba si alguna parte del valor especificado[`Rectangle`](../rectangle) estructura está contenida dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | Comprueba si alguna parte del valor especificado[`RectangleF`](../rectanglef) estructura está contenida dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | Comprueba si el punto especificado está contenido dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | Comprueba si el punto especificado está contenido dentro de este[`Region`](../region) objeto cuando se dibuja usando el especificado[`Graphics`](../graphics) objeto. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Comprueba si alguna parte del rectángulo especificado está contenida dentro de este[`Region`](../region)cuando se dibuja usando el especificado[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | Inicializa esto[`Region`](../region) a un interior vacío. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | Inicializa esto[`Region`](../region) objeto a un interior infinito. |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | Transforma esto[`Region`](../region) por el especificado[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | Desplaza las coordenadas de este[`Region`](../region) por la cantidad especificada. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | Desplaza las coordenadas de este[`Region`](../region) por la cantidad especificada. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | Actualiza esto[`Region`](../region) a la unión de sí mismo y lo especificado[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | Actualiza esto[`Region`](../region) a la unión de sí mismo y lo especificado[`Rectangle`](../rectangle) estructura. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | Actualiza esto[`Region`](../region) a la unión de sí mismo y lo especificado[`RectangleF`](../rectanglef) estructura. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | Actualiza esto[`Region`](../region) a la unión de sí mismo y lo especificado[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | Actualiza esto[`Region`](../region) a la unión menos la intersección de sí mismo con el especificado[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | Actualiza esto[`Region`](../region) a la unión menos la intersección de sí mismo con el especificado[`Rectangle`](../rectangle) estructura. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | Actualiza esto[`Region`](../region) a la unión menos la intersección de sí mismo con el especificado[`RectangleF`](../rectanglef) estructura. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | Actualiza esto[`Region`](../region) a la unión menos la intersección de sí mismo con el especificado[`Region`](../region) . |

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
