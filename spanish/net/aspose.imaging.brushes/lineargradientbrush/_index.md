---
title: LinearGradientBrush
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Encapsula unBrush../aspose.imaging/brush con un gradiente lineal. Esta clase no se puede heredar.
type: docs
weight: 150
url: /es/net/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Encapsula un[`Brush`](../../aspose.imaging/brush) con un gradiente lineal. Esta clase no se puede heredar.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase con parámetros por defecto. El color inicial es negro, el color final es blanco, el ángulo es de 45 grados y el rectángulo está ubicado en (0,0) con tamaño (1,1). |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase con los puntos y colores especificados. |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase con los puntos y colores especificados. |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación. |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación. |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación. |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | Inicializa una nueva instancia del[`LinearGradientBrush`](../lineargradientbrush) clase basada en un rectángulo, colores iniciales y finales y un ángulo de orientación. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Obtiene o establece el ángulo de gradiente. |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend) { get; set; } | Obtiene o establece un[`Blend`](../../aspose.imaging/blend) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor) { get; set; } | Obtiene o establece el color del degradado final. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Obtiene o establece un valor que indica si[`Angle`](../lineargradientbrushbase/angle) se cambia durante las transformaciones con este[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor 0 significa que el pincel es completamente visible, el valor 1 significa que el pincel es completamente opaco. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Obtiene o establece una región rectangular que define los puntos inicial y final del degradado. |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor) { get; set; } | Obtiene o establece el color de degradado inicial. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Obtiene o establece una copia[`Matrix`](../../aspose.imaging/matrix) que define una transformación geométrica local para este[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Obtiene o establece un[`WrapMode`](../../aspose.imaging/wrapmode) enumeración que indica el modo de ajuste para este[`TransformBrush`](../transformbrush) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Crea un nuevo clon profundo del actual[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Multiplica el[`Matrix`](../../aspose.imaging/matrix) que representa la transformada geométrica local de este[`LinearGradientBrush`](../lineargradientbrush) por el especificado[`Matrix`](../../aspose.imaging/matrix) anteponiendo el especificado[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multiplica el[`Matrix`](../../aspose.imaging/matrix) que representa la transformada geométrica local de este[`LinearGradientBrush`](../lineargradientbrush) por el especificado[`Matrix`](../../aspose.imaging/matrix) en el orden especificado. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Restablece el[`Transform`](../transformbrush/transform) propiedad a identidad. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Gira la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a transform. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Gira la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala al transform. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Escala la transformación geométrica local en las cantidades especificadas en el orden especificado. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Crea un degradado lineal con un color central y una caída lineal a un solo color en ambos extremos. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | Crea una caída de degradado basada en una curva en forma de campana. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Crea una caída de degradado basada en una curva en forma de campana. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ver también

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* espacio de nombres [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
