---
title: "EmfPlusSharpenEffect Klasse"
type: docs
weight: 630
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---

**Summary:** The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusSharpenEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect__1) | Initialisiert eine neue Instanz der EmfPlusSharpenEffect Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| amount | float | r/w | Liest oder setzt eine 32‑Bit‑Gleitkommazahl, die die Intensitätsdifferenz<br/>            zwischen einem gegebenen Pixel und den umgebenden Pixeln angibt.<br/>            0 Gibt an, dass Schärfen MUSS NICHT durchgeführt werden.<br/>            0 &lt; Wert ≤ 100<br/>            Wenn dieser Wert steigt, sollte die Intensitätsdifferenz zwischen den Pixeln<br/>            zunehmen. |
| Radius | float | r/w | Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Schärferadius in Pixeln angibt,<br/>            die bestimmt, wie viele Pixel bei der Berechnung des neuen Werts eines bestimmten Pixels einbezogen werden.<br/>            Wenn dieser Wert steigt, erhöht sich die Anzahl der in die Berechnung einbezogenen Pixel, und das<br/>            resultierende Bitmap SOLLTE schärfer werden. |


### Constructor: EmfPlusSharpenEffect() {#EmfPlusSharpenEffect__1}


```
 EmfPlusSharpenEffect() 
```

Initialisiert eine neue Instanz der EmfPlusSharpenEffect Klasse

