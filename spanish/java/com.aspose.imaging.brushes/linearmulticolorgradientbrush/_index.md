---
title: "LinearMulticolorGradientBrush"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un Brush con un degradado lineal definido por múltiples colores y posiciones apropiadas."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Representa un `Brush` con un degradado lineal definido por múltiples colores y posiciones apropiadas. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con parámetros predeterminados. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con los puntos especificados. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con los puntos especificados. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | Obtiene un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | Establece un `com.aspose.imaging.ColorBlend` que define un degradado lineal multicolor. |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con parámetros predeterminados. El color inicial es negro, el color final es blanco, el ángulo es 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Una estructura `Aspose.Imaging.Point` que representa el punto inicial del degradado lineal. |
| point2 | [Point](../../com.aspose.imaging/point) | Una estructura `Aspose.Imaging.Point` que representa el punto final del degradado lineal. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` con los puntos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Una estructura `Aspose.Imaging.PointF` que representa el punto inicial del degradado lineal. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Una estructura `Aspose.Imaging.PointF` que representa el punto final del degradado lineal. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura `Aspose.Imaging.RectangleF` que especifica los límites del degradado lineal. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura `Aspose.Imaging.RectangleF` que especifica los límites del degradado lineal. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Una estructura `Aspose.Imaging.RectangleF` que especifica los límites del degradado lineal. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| isAngleScalable | boolean | si se establece en `true`, el ángulo se cambia durante las transformaciones con este `LinearMulticolorGradientBrush`. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Inicializa una nueva instancia de la clase `LinearMulticolorGradientBrush` basada en un rectángulo y un ángulo de orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Una estructura `Aspose.Imaging.RectangleF` que especifica los límites del degradado lineal. |
| angle | float | El ángulo, medido en grados en sentido horario desde el eje x, de la línea de orientación del degradado. |
| isAngleScalable | boolean | si se establece en `true`, el ángulo se cambia durante las transformaciones con este `LinearMulticolorGradientBrush`. |

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

