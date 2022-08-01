---
title: Rectangle
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.
type: docs
weight: 10830
url: /es/net/aspose.imaging/rectangle/
---
## Rectangle structure

Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.

```csharp
public struct Rectangle
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Inicializa una nueva instancia del[`Rectangle`](../rectangle) estructura con la ubicación y tamaño especificados. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Inicializa una nueva instancia del[`Rectangle`](../rectangle) estructura con la ubicación y tamaño especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Obtiene una nueva instancia del[`Rectangle`](../rectangle) estructura que tiene[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) y[`Height`](./height) valores establecidos en cero. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Obtiene o establece la coordenada y que es la suma de los[`Y`](./y) y[`Height`](./height) valores de propiedad de este[`Rectangle`](../rectangle) estructura. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Obtiene o establece la altura de este[`Rectangle`](../rectangle) estructura. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Obtiene un valor que indica si todas las propiedades numéricas de este[`Rectangle`](../rectangle) tener valores de cero. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Obtiene o establece la coordenada x del borde izquierdo de este[`Rectangle`](../rectangle) estructura. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Obtiene o establece las coordenadas de la esquina superior izquierda de este[`Rectangle`](../rectangle) estructura. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Obtiene o establece la coordenada x que es la suma de[`X`](./x) y[`Width`](./width) valores de propiedad de este[`Rectangle`](../rectangle) estructura. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Obtiene o establece el tamaño de este[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Obtiene o establece la coordenada y del borde superior de este[`Rectangle`](../rectangle) estructura. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Obtiene o establece el ancho de este[`Rectangle`](../rectangle) estructura. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Obtiene o establece la coordenada x de la esquina superior izquierda de este[`Rectangle`](../rectangle) estructura. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Obtiene o establece la coordenada y de la esquina superior izquierda de este[`Rectangle`](../rectangle) estructura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Convierte el especificado[`RectangleF`](../rectanglef) estructura a un[`Rectangle`](../rectangle) estructura redondeando el[`RectangleF`](../rectanglef) valores a los siguientes valores enteros más altos. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Crea un[`Rectangle`](../rectangle) estructura con las ubicaciones de borde especificadas. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Crea un nuevo[`Rectangle`](../rectangle) de dos puntos especificados. Dos verticales de lo creado[`Rectangle`](../rectangle) será igual a lo pasado*point1* y*point2* . Estos serían típicamente los vértices opuestos. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Crea y devuelve una copia inflada del especificado[`Rectangle`](../rectangle) estructura. La copia se infla en la cantidad especificada. El original[`Rectangle`](../rectangle) la estructura permanece sin modificar. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Devuelve un tercio[`Rectangle`](../rectangle) estructura que representa la intersección de otros dos[`Rectangle`](../rectangle) estructuras Si no hay intersección, un vacío[`Rectangle`](../rectangle) se devuelve. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Convierte el especificado[`RectangleF`](../rectanglef) a un[`Rectangle`](../rectangle) redondeando el[`RectangleF`](../rectanglef)valores a los valores enteros más cercanos. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Convierte el especificado[`RectangleF`](../rectanglef) a un[`Rectangle`](../rectangle) al truncar el[`RectangleF`](../rectanglef) valores. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | Obtiene un[`Rectangle`](../rectangle) estructura que contiene la unión de dos[`Rectangle`](../rectangle) estructuras. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Determina si el punto especificado está contenido dentro de este[`Rectangle`](../rectangle) estructura. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Determina si la región rectangular representada por*rect* está completamente contenido dentro de este[`Rectangle`](../rectangle) estructura. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Determina si el punto especificado está contenido dentro de este[`Rectangle`](../rectangle) estructura. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Comprueba si*obj* es un[`Rectangle`](../rectangle)estructura con la misma ubicación y tamaño de esta[`Rectangle`](../rectangle) estructura. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Devuelve el código hash para este[`Rectangle`](../rectangle) estructura. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | infla esto[`Rectangle`](../rectangle) por la cantidad especificada. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | infla esto[`Rectangle`](../rectangle) por la cantidad especificada. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Reemplaza esto[`Rectangle`](../rectangle) con la intersección de sí mismo y el especificado[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Determina si este rectángulo se cruza con*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Normaliza el rectángulo haciendo que el ancho y la altura sean positivos, la izquierda menos que la derecha y la parte superior menos que la inferior. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Ajusta la ubicación de este rectángulo en la cantidad especificada. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Convierte los atributos de este[`Rectangle`](../rectangle) a una cadena legible por humanos. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Comprueba si dos[`Rectangle`](../rectangle)las estructuras tienen la misma ubicación y tamaño. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Comprueba si dos[`Rectangle`](../rectangle) las estructuras difieren en ubicación o tamaño. |

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
