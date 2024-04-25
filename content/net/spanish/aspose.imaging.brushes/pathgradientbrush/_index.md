---
title: PathGradientBrush
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Encapsula unBrush../aspose.imaging/brush objeto con un degradado. Esta clase no se puede heredar.
type: docs
weight: 180
url: /es/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Encapsula un[`Brush`](../../aspose.imaging/brush) objeto con un degradado. Esta clase no se puede heredar.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Inicializa una nueva instancia del[`PathGradientBrush`](../pathgradientbrush) clase con la ruta especificada. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Inicializa una nueva instancia del[`PathGradientBrush`](../pathgradientbrush) clase con los puntos especificados. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Inicializa una nueva instancia del[`PathGradientBrush`](../pathgradientbrush) clase con los puntos especificados. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Inicializa una nueva instancia del[`PathGradientBrush`](../pathgradientbrush) clase con los puntos especificados y modo de ajuste. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Inicializa una nueva instancia del[`PathGradientBrush`](../pathgradientbrush) clase con los puntos especificados y modo de ajuste. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Obtiene o establece un[`Blend`](../../aspose.imaging/blend) que especifica posiciones y factores que definen una caída personalizada para el degradado. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Obtiene o establece el color en el centro del degradado de la ruta. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Obtiene o establece el punto central del gradiente de la ruta. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Obtiene o establece el punto de enfoque para la disminución del gradiente. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Obtiene la ruta de gráficos sobre la que se creó este pincel. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor 0 significa que el pincel es completamente visible, el valor 1 significa que el pincel es completamente opaco. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Obtiene los puntos de ruta sobre los que se construyó este pincel. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Obtiene o establece una matriz de colores que corresponden a los puntos de la ruta que[`PathGradientBrush`](../pathgradientbrush) llena. |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Crea un degradado con un color central y una caída lineal a un color circundante. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Crea un degradado con un color central y una caída lineal para cada color circundante. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Crea un pincel de degradado que cambia de color desde el centro del camino hacia afuera hasta el límite del camino. La transición de un color a otro se basa en una curva en forma de campana. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Crea un pincel de degradado que cambia de color desde el centro del camino hacia afuera hasta el límite del camino. La transición de un color a otro se basa en una curva en forma de campana. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Traduce la transformación geométrica local por las dimensiones especificadas. Este método antepone la traducción a transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Traduce la transformación geométrica local por las dimensiones especificadas en el orden especificado. |

### Observaciones

El color central es blanco por defecto. Un usuario puede cambiar este valor en cualquier momento posterior.

La matriz de colores envolventes se inicializa con un solo elemento que contiene color blanco de forma predeterminada. Los colores envolventes se pueden cambiar más tarde, sin embargo, se requiere al menos un elemento único al configurar los colores envolventes.

Ver el[`Blend`](./blend) para más detalles sobre su inicialización.

### Ver también

* class [PathGradientBrushBase](../pathgradientbrushbase)
* espacio de nombres [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
