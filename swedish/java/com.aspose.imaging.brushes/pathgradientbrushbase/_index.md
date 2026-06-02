---
title: "PathGradientBrushBase"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en pensel med grundläggande path gradient-funktionalitet."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Representerar en `Brush` med basvägsgradientfunktion.

Observera att när `PathGradientBrushBase`-klassen skapas bör den initieras med minst 2 punkter. Den interna banan som skapas kommer alltid att vara en sluten figur, den sista punkten kopplar till den första. Den formen fylls med detta `PathGradientBrushBase`. GDI+-implementationen kastar ett `OutOfMemoryError` när tomma arrayer eller punkter med samma koordinater skickas in. `PathGradientBrushBase` kastar ett undantag när punktarrayen innehåller färre än 2 punkter, `ArgumentException` kastas istället för `OutOfMemoryError` när punktarrayen är oacceptabel. Centerpunkten beräknas som masscentrum för de inmatade punkterna som standard. En användare kan ändra denna punkt senare. Fokus-skalan är en tom punkt (0.0, 0.0) som standard.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Hämtar banpunkterna som denna pensel byggdes på. |
| [getGraphicsPath()](#getGraphicsPath--) | Hämtar grafikbanan som denna pensel byggdes på. |
| [getCenterPoint()](#getCenterPoint--) | Hämtar eller anger centerpunkten för path gradienten. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Hämtar eller anger centerpunkten för path gradienten. |
| [getFocusScales()](#getFocusScales--) | Hämtar fokuspunkten för gradientens avtagande. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Hämtar eller anger fokuspunkten för gradientens avtagande. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Hämtar banpunkterna som denna pensel byggdes på.

**Returns:**
com.aspose.imaging.PointF[] - Banpunkterna.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Hämtar grafikbanan som denna pensel byggdes på.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Hämtar eller anger centerpunkten för path gradienten.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Hämtar eller anger centerpunkten för path gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | En `Aspose.Imaging.PointF` som representerar centerpunkten för path gradienten. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Hämtar fokuspunkten för gradientens avtagande.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Hämtar eller anger fokuspunkten för gradientens avtagande.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | En `Aspose.Imaging.PointF` som representerar fokuspunkten för gradientens avtagande. |

