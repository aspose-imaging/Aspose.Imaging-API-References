---
title: LinearGradientBrushBase
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa unBrush../aspose.imaging/brush con capacidades de degradado y propiedades apropiadas.
type: docs
weight: 160
url: /es/aspose.imaging.brushes/lineargradientbrushbase/
---
## LinearGradientBrushBase class

Representa un[`Brush`](../../aspose.imaging/brush) con capacidades de degradado y propiedades apropiadas.

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Obtiene o establece el ángulo de gradiente. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Obtiene o establece un valor que indica si la corrección gamma está habilitada para este[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Obtiene o establece un valor que indica si[`Angle`](./angle) se cambia durante las transformaciones con este[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor 0 significa que el pincel es completamente visible, el valor 1 significa que el pincel es completamente opaco. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Obtiene o establece una región rectangular que define los puntos inicial y final del degradado. |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Ver también

* class [TransformBrush](../transformbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
