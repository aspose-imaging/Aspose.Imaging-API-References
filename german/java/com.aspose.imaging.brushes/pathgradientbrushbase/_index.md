---
title: "PathGradientBrushBase"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt einen Pinsel mit Basis-Pfadverlauf-Funktionalität dar."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

Stellt einen `Brush` mit Basis-Pfad‑Gradientfunktionalität dar.

Beachten Sie, dass beim Erstellen der `PathGradientBrushBase`-Klasse diese mit mindestens 2 Punkten initialisiert werden sollte. Der interne Pfad wird immer eine geschlossene Figur sein, der letzte Punkt verbindet den ersten Punkt. Diese Form wird mit diesem `PathGradientBrushBase` gefüllt. Die GDI+-Implementierung wirft einen `OutOfMemoryError`, wenn leere Arrays oder Punktmengen mit gleichen Koordinaten übergeben werden. Die `PathGradientBrushBase` wirft eine Ausnahme, wenn das Punktarray weniger als 2 Punkte enthält; die `ArgumentException` wird anstelle von `OutOfMemoryError` ausgelöst, wenn das Punktarray unzulässig ist. Der Mittelpunkt wird standardmäßig als Schwerpunkt der übergebenen Punkte berechnet. Ein Benutzer kann diesen Punkt später ändern. Die Fokus-Skala ist standardmäßig ein leerer Punkt (0.0, 0.0).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | Ruft die Pfadpunkte ab, auf denen dieser Pinsel aufgebaut wurde. |
| [getGraphicsPath()](#getGraphicsPath--) | Ruft den Grafikpfad ab, auf dem dieser Pinsel aufgebaut wurde. |
| [getCenterPoint()](#getCenterPoint--) | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | Liest oder setzt den Mittelpunkt des Pfadverlaufs. |
| [getFocusScales()](#getFocusScales--) | Ruft den Fokuspunkt für den Farbverlaufsabfall ab. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | Liest oder setzt den Fokuspunkt für den Farbverlaufsabfall. |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Ruft die Pfadpunkte ab, auf denen dieser Pinsel aufgebaut wurde.

**Returns:**
com.aspose.imaging.PointF[] - Die Pfadpunkte.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Ruft den Grafikpfad ab, auf dem dieser Pinsel aufgebaut wurde.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Liest oder setzt den Mittelpunkt des Pfadverlaufs.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


Liest oder setzt den Mittelpunkt des Pfadverlaufs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Ein `Aspose.Imaging.PointF`, das den Mittelpunkt des Pfadverlaufs darstellt. |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Ruft den Fokuspunkt für den Farbverlaufsabfall ab.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


Liest oder setzt den Fokuspunkt für den Farbverlaufsabfall.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | Ein `Aspose.Imaging.PointF`, das den Fokuspunkt für den Verlaufabfall darstellt. |

