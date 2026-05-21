---
title: "LinearGradientBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Encapsula un Aspose.Imaging.Brush con un degradado lineal."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Encapsula un `Aspose.Imaging.Brush` con un degradado lineal. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush). |
| [LinearGradientBrush()](#LinearGradientBrush--) | Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) con parámetros predeterminados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Establece un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |
| [getLinearColors()](#getLinearColors--) | Obtiene los colores inicial y final del degradado. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | Establece los colores inicial y final del degradado. |
| [getStartColor()](#getStartColor--) | Obtiene el color inicial del degradado. |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | Establece el color inicial del degradado. |
| [getEndColor()](#getEndColor--) | Obtiene el color final del degradado. |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | Establece el color final del degradado. |
| [getBlend()](#getBlend--) | Obtiene un `Aspose.Imaging.Blend` que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | Establece un `Aspose.Imaging.Blend` que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Crea una caída de degradado basada en una curva en forma de campana. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Crea una caída de degradado basada en una curva en forma de campana. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo. |
| color1 | [Color](../../com.aspose.imaging/color) | El color1. |
| color2 | [Color](../../com.aspose.imaging/color) | El color2. |
| angle | float | El ángulo. |
| isAngleScalable | boolean | si se establece en `true` [es escalable en ángulo]. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| color1 | [Color](../../com.aspose.imaging/color) | El color1. |
| color2 | [Color](../../com.aspose.imaging/color) | El color2. |
| angle | float | El ángulo. |
| isAngleScalable | boolean | si se establece en `true` [es escalable en ángulo]. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | El rectángulo. |
| color1 | [Color](../../com.aspose.imaging/color) | El color1. |
| color2 | [Color](../../com.aspose.imaging/color) | El color2. |
| angle | float | El ángulo. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| color1 | [Color](../../com.aspose.imaging/color) | El color1. |
| color2 | [Color](../../com.aspose.imaging/color) | El color2. |
| angle | float | El ángulo. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | El punto1. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | El punto2. |
| color1 | [Color](../../com.aspose.imaging/color) | El color1. |
| color2 | [Color](../../com.aspose.imaging/color) | El color2. |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | El punto1. |
| point2 | [Point](../../com.aspose.imaging/point) | El punto2. |
| color1 | [Color](../../com.aspose.imaging/color) | El color1. |
| color2 | [Color](../../com.aspose.imaging/color) | El color2. |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Inicializa una nueva instancia de la clase [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) con parámetros predeterminados. El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1).

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

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Obtiene los colores inicial y final del degradado.

**Returns:**
com.aspose.imaging.Color[] - Una matriz de dos estructuras `Color` que representa los colores inicial y final del degradado.
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


Establece los colores inicial y final del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | Una matriz de dos estructuras `Color` que representa los colores inicial y final del degradado. |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Obtiene el color inicial del degradado.

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


Establece el color inicial del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | El color inicial del degradado. |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Obtiene el color final del degradado.

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


Establece el color final del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | El color final del degradado. |

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


Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el color inicial y el color final se mezclan por igual). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Crea una caída de degradado basada en una curva en forma de campana.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |
| escala | float | Un valor de 0 a 1 que especifica qué tan rápido se atenúan los colores desde el `focus`. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enfoque | float | Un valor de 0 a 1 que especifica el centro del degradado (el punto donde el degradado está compuesto solo por el color final). |
| escala | float | Un valor de 0 a 1 que especifica qué tan rápido se atenúan los colores desde el color inicial hasta el `focus` (color final). |

