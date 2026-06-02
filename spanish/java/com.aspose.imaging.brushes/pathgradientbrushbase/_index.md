---
title: "PathGradientBrushBase"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa un Brush con funcionalidad de degradado de ruta base."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Representa un `Brush` con funcionalidad de degradado de ruta base.

Tenga en cuenta que al crear la clase `PathGradientBrushBase` debe inicializarse con al menos 2 puntos. La ruta interna creada siempre será una figura cerrada, el último punto conecta con el primer punto. Esa forma se rellena con este `PathGradientBrushBase`. La implementación GDI+ lanza un `OutOfMemoryError` al pasar matrices vacías o conjuntos de puntos con las mismas coordenadas. El `PathGradientBrushBase` lanza una excepción cuando la matriz de puntos contiene menos de 2 puntos; se lanza `ArgumentException` en lugar de `OutOfMemoryError` cuando la matriz de puntos es inaceptable. El punto central se calcula como el centro de masa de los puntos pasados por defecto. Un usuario puede cambiar este punto más tarde. Las escalas de foco son un punto vacío (0.0, 0.0) por defecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Obtiene los puntos de ruta sobre los que se construyó este brush. |
| [getGraphicsPath()](#getGraphicsPath--) | Obtiene la ruta gráfica sobre la que se construyó este brush. |
| [getCenterPoint()](#getCenterPoint--) | Obtiene o establece el punto central del degradado de ruta. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Obtiene o establece el punto central del degradado de ruta. |
| [getFocusScales()](#getFocusScales--) | Obtiene el punto de foco para la caída del degradado. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Obtiene o establece el punto de foco para la caída del degradado. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Obtiene los puntos de ruta sobre los que se construyó este brush.

**Returns:**
com.aspose.imaging.PointF[] - Los puntos de ruta.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Obtiene la ruta gráfica sobre la que se construyó este brush.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Obtiene o establece el punto central del degradado de ruta.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Obtiene o establece el punto central del degradado de ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Una `Aspose.Imaging.PointF` que representa el punto central del degradado de ruta. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Obtiene el punto de foco para la caída del degradado.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Obtiene o establece el punto de foco para la caída del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Un `Aspose.Imaging.PointF` que representa el punto focal para la caída del degradado. |

