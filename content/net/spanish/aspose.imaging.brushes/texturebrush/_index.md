---
title: TextureBrush
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Cada propiedad delTextureBrush./texturebrush la clase es unBrush../aspose.imaging/brush objeto que usa una imagen para llenar el interior de una forma. Esta clase no se puede heredar.
type: docs
weight: 220
url: /es/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

Cada propiedad del[`TextureBrush`](../texturebrush) la clase es un[`Brush`](../../aspose.imaging/brush) objeto que usa una imagen para llenar el interior de una forma. Esta clase no se puede heredar.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que usa la imagen especificada. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que usa la imagen especificada y el rectángulo delimitador. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que usa la imagen especificada y el rectángulo delimitador. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen especificada y el modo de ajuste. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen, el rectángulo delimitador y los atributos de imagen especificados. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen, el rectángulo delimitador y los atributos de imagen especificados. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Inicializa una nueva instancia del[`TextureBrush`](../texturebrush) clase que utiliza la imagen especificada, el modo de ajuste y el rectángulo delimitador. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) objeto asociado con este[`TextureBrush`](../texturebrush) objeto. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | Obtiene el[`ImageAttributes`](./imageattributes) asociado con este[`TextureBrush`](../texturebrush) . |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | Obtiene el[`Rectangle`](../../aspose.imaging/rectangle) asociado con este[`TextureBrush`](../texturebrush) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Obtiene un valor que indica si las transformaciones se modificaron de alguna manera. Por ejemplo, establecer la matriz de transformación o llamar a cualquiera de los métodos que alteran la matriz de transformación. La propiedad se introduce por compatibilidad con versiones anteriores de GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. El valor 0 significa que el pincel es completamente visible, el valor 1 significa que el pincel es completamente opaco. |
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
