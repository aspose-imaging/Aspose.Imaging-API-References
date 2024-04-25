---
title: PathGradientBrushBase
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa unBrush../aspose.imaging/brush con funcionalidad de gradiente de ruta base.
type: docs
weight: 190
url: /es/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Representa un[`Brush`](../../aspose.imaging/brush) con funcionalidad de gradiente de ruta base.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Obtiene o establece el punto central del gradiente de la ruta. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Obtiene o establece el punto de enfoque para la disminución del gradiente. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Obtiene la ruta de gráficos sobre la que se creó este pincel. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor 0 significa que el pincel es completamente visible, el valor 1 significa que el pincel es completamente opaco. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Obtiene los puntos de ruta sobre los que se construyó este pincel. |
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

### Observaciones

Tenga en cuenta que al crear el[`PathGradientBrushBase`](../pathgradientbrushbase) class debe inicializarse con 2 puntos como mínimo. La ruta interna created siempre será una figura cerrada, el último punto conecta el primer punto. Esa forma está llena de esto.[`PathGradientBrushBase`](../pathgradientbrushbase) . La implementación de GDI+ genera unOutOfMemoryException al pasar matrices vacías o conjuntos de puntos que tienen las mismas coordenadas. El[`PathGradientBrushBase`](../pathgradientbrushbase) lanza una excepción cuando la matriz de puntos contiene menos de 2 puntos, elArgumentException is lanzado en lugar deOutOfMemoryExceptioncuando la matriz de puntos es inaceptable. El punto central se calcula como un centro de masa para los puntos pasados de forma predeterminada. Un usuario puede cambiar este punto más tarde. La escala de enfoque es un punto vacío (0.0, 0.0) por defecto.

### Ver también

* class [TransformBrush](../transformbrush)
* espacio de nombres [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
