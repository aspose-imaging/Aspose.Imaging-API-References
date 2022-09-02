---
title: LinearMulticolorGradientBrush
second_title: Aspose.Imaging für .NET-API-Referenz
description: steht für aBrush../aspose.imaging/brush mit linearem Farbverlauf der durch mehrere Farben und geeignete Positionen definiert ist. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 170
url: /de/net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

steht für a[`Brush`](../../aspose.imaging/brush) mit linearem Farbverlauf, der durch mehrere Farben und geeignete Positionen definiert ist. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse mit Standardparametern. Die Startfarbe ist Schwarz, die Endfarbe Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich in (0,0) mit der Größe (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse mit den angegebenen Punkten. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse basierend auf einem Rechteck und einem Orientierungswinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse basierend auf einem Rechteck und einem Orientierungswinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse basierend auf einem Rechteck und einem Orientierungswinkel. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | Initialisiert eine neue Instanz von[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush) Klasse basierend auf einem Rechteck und einem Orientierungswinkel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Ruft den Steigungswinkel ab oder legt ihn fest. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob die Gammakorrektur dafür aktiviert ist[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | Holt oder setzt a[`ColorBlend`](../../aspose.imaging/colorblend) das einen mehrfarbigen linearen Farbverlauf definiert. |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob[`Angle`](../lineargradientbrushbase/angle) wird bei Transformationen damit verändert[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Ruft einen Wert ab, der angibt, ob Transformationen auf irgendeine Weise geändert wurden. Zum Beispiel Setzen der Transformationsmatrix oder Aufrufen einer der Methoden, die die Transformationsmatrix ändern. Die Eigenschaft wird aus Gründen der Abwärtskompatibilität mit GDI+ eingeführt. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass der Pinsel vollständig sichtbar ist, der Wert 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Ruft einen rechteckigen Bereich ab oder legt diesen fest, der die Start- und Endpunkte des Farbverlaufs definiert. |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Abmessungen. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Siehe auch

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* namensraum [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
