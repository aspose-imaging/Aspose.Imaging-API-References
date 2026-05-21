---
title: "PathGradientBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Encapsula un objeto Aspose.Imaging.Brush con un degradado."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Encapsula un objeto `Aspose.Imaging.Brush` con un degradado. Esta clase no puede heredarse.

El color central es blanco por defecto. Un usuario puede cambiar este valor en cualquier momento más tarde.

La matriz de colores circundantes se inicializa con un solo elemento que contiene el color blanco por defecto. Los colores circundantes pueden cambiarse más tarde, sin embargo se requiere al menos un solo elemento al configurar los colores circundantes.

Consulte `Blend` para obtener más detalles sobre su inicialización.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados y el modo de ajuste. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados y el modo de ajuste. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | Inicializa una nueva instancia de la clase `PathGradientBrush` con la ruta especificada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Establece un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |
| [getCenterColor()](#getCenterColor--) | Obtiene el color en el centro del gradiente de ruta. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | Establece el color en el centro del gradiente de ruta. |
| [getSurroundColors()](#getSurroundColors--) | Obtiene una matriz de colores que corresponde a los puntos en la ruta que este `PathGradientBrush` rellena. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | Establece una matriz de colores que corresponde a los puntos en la ruta que este `PathGradientBrush` rellena. |
| [getBlend()](#getBlend--) | Obtiene un `Aspose.Imaging.Blend` que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Establece un `Aspose.Imaging.Blend` que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un degradado con un color central y una caída lineal hacia un color circundante. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un degradado con un color central y una caída lineal hacia cada color circundante. |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de estructuras `Aspose.Imaging.PointF` que representa los puntos que forman los vértices de la ruta. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Una matriz de estructuras `Aspose.Imaging.PointF` que representa los puntos que forman los vértices de la ruta. |
| wrapMode | int | Un `Aspose.Imaging.WrapMode` que especifica cómo se repiten los rellenos dibujados con este `PathGradientBrush`. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Una matriz de estructuras `Aspose.Imaging.Point` que representa los puntos que forman los vértices de la ruta. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Inicializa una nueva instancia de la clase `PathGradientBrush` con los puntos especificados y el modo de ajuste.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | Una matriz de estructuras `Aspose.Imaging.Point` que representa los puntos que forman los vértices de la ruta. |
| wrapMode | int | Un `Aspose.Imaging.WrapMode` que especifica cómo se repiten los rellenos dibujados con este `PathGradientBrush`. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Inicializa una nueva instancia de la clase `PathGradientBrush` con la ruta especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | El `GraphicsPath` que define el área rellenada por este `PathGradientBrush`. |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Obtiene un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor.

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Establece un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | Un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Obtiene el color en el centro del gradiente de ruta.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


Establece el color en el centro del gradiente de ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Un `com.aspose.imaging.Color` que representa el color en el centro del gradiente de ruta. |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Obtiene una matriz de colores que corresponde a los puntos en la ruta que este `PathGradientBrush` rellena.

**Returns:**
com.aspose.imaging.Color[] - Una matriz de estructuras `com.aspose.imaging.Color` que representa los colores asociados a cada punto en la ruta que este `PathGradientBrush` rellena.
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


Establece una matriz de colores que corresponde a los puntos en la ruta que este `PathGradientBrush` rellena.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Una matriz de estructuras `com.aspose.imaging.Color` que representa los colores asociados a cada punto en la ruta que este `PathGradientBrush` rellena. |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Obtiene un `Aspose.Imaging.Blend` que especifica posiciones y factores que definen una caída personalizada para el degradado.

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


Establece un `Aspose.Imaging.Blend` que especifica posiciones y factores que definen una caída personalizada para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | Un `Aspose.Imaging.Blend` que representa una caída personalizada para el degradado. |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (por defecto) coloca la máxima intensidad en el centro de la ruta. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea un pincel de degradado que cambia de color comenzando desde el centro de la ruta hacia el límite de la ruta. La transición de un color a otro se basa en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (por defecto) coloca la máxima intensidad en el centro de la ruta. |
| escala | float | Un valor de 0 a 1 que especifica la intensidad máxima del color central que se mezcla con el color del límite. Un valor de 1 produce la mayor intensidad posible del color central, y es el valor por defecto. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un degradado con un color central y una caída lineal hacia un color circundante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (por defecto) coloca la máxima intensidad en el centro de la ruta. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un degradado con un color central y una caída lineal hacia cada color circundante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica dónde, a lo largo de cualquier radial desde el centro de la ruta hasta el límite de la ruta, el color central alcanzará su máxima intensidad. Un valor de 1 (por defecto) coloca la máxima intensidad en el centro de la ruta. |
| escala | float | Un valor de 0 a 1 que especifica la intensidad máxima del color central que se mezcla con el color del límite. Un valor de 1 produce la mayor intensidad posible del color central, y es el valor por defecto. |

