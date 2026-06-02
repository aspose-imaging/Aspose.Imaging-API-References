---
title: "EmfPlusBlurEffect Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Initialisiert eine neue Instanz der EmfPlusBlurEffect Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Liest oder setzt eine 32‑Bit-Gleitkommazahl, die den Unschärferadius in Pixeln angibt,<br/>            welcher die Anzahl der Pixel bestimmt, die bei der Berechnung des neuen Werts eines bestimmten Pixels einbezogen werden.<br/>            Dieser Wert MUSS im Bereich von 0,0 bis 255,0 liegen. |
| expand_edge | bool | r/w | Liest oder setzt einen 32‑Bit‑Booleschen Wert, der angibt, ob das Bitmap um<br/>            einen Betrag, der dem Wert von BlurRadius entspricht, erweitert wird, um weiche Kanten zu erzeugen. Dieser Wert MUSS einer der folgenden sein:<br/>            FALSE<br/>            0x00000000<br/>            Die Größe des Bitmaps DARF NICHT geändert werden, und seine weichen Kanten SOLLTEN auf die Größe von BlurRadius beschnitten werden.<br/>            TRUE<br/>            0x00000001<br/>            Die Größe des Bitmaps SOLLTE um einen Betrag, der dem BlurRadius entspricht, erweitert werden, um weiche Kanten zu erzeugen. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Initialisiert eine neue Instanz der EmfPlusBlurEffect Klasse

