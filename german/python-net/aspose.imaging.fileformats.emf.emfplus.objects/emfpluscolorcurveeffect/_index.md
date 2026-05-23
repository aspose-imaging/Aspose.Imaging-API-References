---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | Initialisiert eine neue Instanz der Klasse EmfPlusColorCurveEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Liest oder setzt die Gibt an, welche Intensität die Kurvenanpassung für den durch CurveChannel angegebenen Farbkanal hat. Die sinnvollen Wertebereiche für dieses Feld variieren je nach CurveAdjustment-Wert, wie folgt:<br/>            Belichtungs-Anpassungsbereich:<br/>            -255 ≤ value &lt; 0 Wenn der Wert sinkt, sollte die Belichtung des Bildes abnehmen.<br/>            0 Ein Wert von 0 gibt an, dass die Belichtung NICHT geändert werden darf.<br/>            0 &lt; value ≤ 255 Wenn der Wert steigt, sollte die Belichtung des Bildes zunehmen.<br/>            Dichte-Anpassungsbereich:<br/>            -255 ≤ value &lt; 0<br/>            Wenn der Wert sinkt, sollte die Dichte des Bildes abnehmen, was zu einem dunkleren Bild führt.<br/>            0 Ein Wert von 0 gibt an, dass die Dichte NICHT geändert werden darf.<br/>            0 &lt; value ≤ 255<br/>            Wenn der Wert steigt, sollte die Dichte des Bildes zunehmen.<br/>            Kontrast-Anpassungsbereich:<br/>            -100 ≤ value &lt; 0 Wenn der Wert sinkt, sollte der Kontrast des Bildes abnehmen.<br/>            0 Ein Wert von 0 gibt an, dass der Kontrast NICHT geändert werden darf.<br/>            0 &lt; value ≤ 100 Wenn der Wert steigt, sollte der Kontrast des Bildes zunehmen.<br/>            Highlight-Anpassungsbereich:<br/>            -100 ≤ value &lt; 0 Wenn der Wert sinkt, sollten die hellen Bereiche des Bildes dunkler erscheinen.<br/>            0 Ein Wert von 0 gibt an, dass das Highlight NICHT geändert werden darf.<br/>            0 &lt; value ≤ 100 Wenn der Wert steigt, sollten die hellen Bereiche des Bildes heller erscheinen.<br/>            Schatten-Anpassungsbereich:<br/>            -100 ≤ value &lt; 0 Wenn der Wert sinkt, sollten die dunklen Bereiche des Bildes dunkler erscheinen.<br/>            0 Ein Wert von 0 gibt an, dass der Schatten NICHT geändert werden darf.<br/>            0 &lt; value ≤ 100 Wenn der Wert steigt, sollten die dunklen Bereiche des Bildes heller erscheinen.<br/>            Weiß-Sättigungs-Anpassungsbereich:<br/>            0 — 255 Wenn der Wert steigt, erhöht sich die obere Grenze des Bereichs der Farbkanalintensitäten.<br/>            Schwarz-Sättigungs-Anpassungsbereich:<br/>            0 — 255 Wenn der Wert steigt, erhöht sich die untere Grenze des Bereichs der Farbkanalintensitäten. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Liest oder setzt die Gibt an, welche Kurvenanpassung auf die Farben im Bitmap angewendet wird. Dieser Wert MUSS im CurveAdjustments-Enumeration (Abschnitt 2.1.1.7) definiert sein. |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Liest oder setzt die Gibt an, welcher Farbkanal von der Kurvenanpassung betroffen ist. Dieser Wert MUSS in der CurveChannel-Enumeration (Abschnitt 2.1.1.8) definiert sein. |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

Initialisiert eine neue Instanz der Klasse EmfPlusColorCurveEffect

