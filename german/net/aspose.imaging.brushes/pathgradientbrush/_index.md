---
title: PathGradientBrush
second_title: Aspose.Imaging für .NET-API-Referenz
description: Kapselt aBrush../aspose.imaging/brush Objekt mit Farbverlauf. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 180
url: /de/net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Kapselt a[`Brush`](../../aspose.imaging/brush) Objekt mit Farbverlauf. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Initialisiert eine neue Instanz von[`PathGradientBrush`](../pathgradientbrush) Klasse mit dem angegebenen Pfad. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Initialisiert eine neue Instanz von[`PathGradientBrush`](../pathgradientbrush) Klasse mit den angegebenen Punkten. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Initialisiert eine neue Instanz von[`PathGradientBrush`](../pathgradientbrush) Klasse mit den angegebenen Punkten. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Initialisiert eine neue Instanz von[`PathGradientBrush`](../pathgradientbrush) Klasse mit den angegebenen Punkten und Wrap-Modus. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Initialisiert eine neue Instanz von[`PathGradientBrush`](../pathgradientbrush) Klasse mit den angegebenen Punkten und Wrap-Modus. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Holt oder setzt a[`Blend`](../../aspose.imaging/blend) die Positionen und Faktoren angibt, die einen benutzerdefinierten Abfall für den Farbverlauf definieren. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Ruft die Farbe in der Mitte des Pfadverlaufs ab oder legt sie fest. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Ruft den Mittelpunkt des Pfadgradienten ab oder legt ihn fest. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Ruft den Fokuspunkt für den Verlaufsabfall ab oder legt ihn fest. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Ruft den Grafikpfad ab, auf dem dieser Pinsel erstellt wurde. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel Setzen der Transformationsmatrix oder Aufrufen einer der Methoden, die die Transformationsmatrix ändern. Die Eigenschaft wird aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass der Pinsel vollständig sichtbar ist, der Wert 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Ruft die Pfadpunkte ab, auf denen dieser Pinsel erstellt wurde. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Holt oder setzt ein Array von Farben, die den Punkten im Pfad this entsprechen[`PathGradientBrush`](../pathgradientbrush) füllt. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Ruft eine Kopie ab oder legt sie fest[`Matrix`](../../aspose.imaging/matrix) die dafür eine lokale geometrische Transformation definiert[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Holt oder setzt a[`WrapMode`](../../aspose.imaging/wrapmode) Enumeration, die den Umbruchmodus dafür angibt[`TransformBrush`](../transformbrush) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Erstellt einen neuen tiefen Klon des aktuellen[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Multipliziert die[`Matrix`](../../aspose.imaging/matrix) das die lokale geometrische Transformation davon darstellt[`LinearGradientBrush`](../lineargradientbrush) durch die angegebenen[`Matrix`](../../aspose.imaging/matrix) durch Voranstellen der angegebenen[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Multipliziert die[`Matrix`](../../aspose.imaging/matrix) das die lokale geometrische Transformation davon darstellt[`LinearGradientBrush`](../lineargradientbrush) durch die angegebenen[`Matrix`](../../aspose.imaging/matrix) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Setzt die zurück[`Transform`](../transformbrush/transform) Eigentum an Identität. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode stellt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge. Diese Methode stellt der Transformation die Skalierungsmatrix voran. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Beträge in der angegebenen Reihenfolge. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Erstellt einen Farbverlauf mit einer Mittelfarbe und einem linearen Abfall zu einer umgebenden Farbe. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Erstellt einen Verlauf mit einer Mittelfarbe und einem linearen Abfall zu jeder umgebenden Farbe. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Erstellt einen Verlaufspinsel, der die Farbe ändert, beginnend von der Mitte des Pfads nach außen bis zur Begrenzung des Pfads. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Erstellt einen Verlaufspinsel, der die Farbe ändert, beginnend von der Mitte des Pfads nach außen bis zur Begrenzung des Pfads. Der Übergang von einer Farbe zur anderen basiert auf einer glockenförmigen Kurve. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Bemerkungen

Die mittlere Farbe ist standardmäßig weiß. Ein Benutzer kann diesen Wert später jederzeit ändern.

Das Surround-Farbarray wird standardmäßig durch ein einzelnes Element initialisiert, das weiße Farbe enthält. Die Umgebungsfarben können später geändert werden, es ist jedoch mindestens ein Element erforderlich, wenn die Umgebungsfarben eingerichtet werden.

Siehe die[`Blend`](./blend) für weitere Details über seine Initialisierung.

### Siehe auch

* class [PathGradientBrushBase](../pathgradientbrushbase)
* namensraum [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
