---
title: "EmfPlusLevelsEffect Klasse"
type: docs
weight: 420
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Initialisiert eine neue Instanz der EmfPlusLevelsEffect Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Hervorheben | int | r/w | Liest oder setzt die Gibt an, wie stark die Highlights eines Bildes aufgehellt werden sollen. Die Farb<br/>            Kanalwerte am oberen Ende des Intensitätsbereichs werden stärker verändert als Werte nahe dem<br/>            mittleren oder unteren Ende, was bedeutet, dass ein Bild aufgehellt werden kann, ohne den Kontrast<br/>            zwischen den dunkleren Bildbereichen zu verlieren.<br/>            0 ≤ value &lt; Gibt an, dass Highlights mit einem Intensitätsprozentsatz über diesem Schwellenwert ERHÖHT WERDEN SOLLTEN<br/>            100 erhöht werden.<br/>            100 Gibt an, dass Highlights NICHT geändert werden dürfen. |
| mid_tone | int | r/w | Liest oder setzt die Gibt an, wie stark die Mitteltöne eines Bildes aufgehellt oder abgedunkelt werden sollen. Farb<br/>            Kanalwerte in der Mitte des Intensitätsbereichs werden stärker verändert als Werte nahe dem hohen<br/>            oder niedrigen Ende, was bedeutet, dass ein Bild aufgehellt oder abgedunkelt werden kann, ohne den Kontrast<br/>            zwischen den dunkelsten und hellsten Bildbereichen zu verlieren.<br/>            -100 ≤ value &lt; 0 Gibt an, dass Mitteltöne dunkler gemacht werden.<br/>            0 Gibt an, dass Mitteltöne NICHT geändert werden dürfen.<br/>            0 &lt; value ≤ 100 Gibt an, dass Mitteltöne heller gemacht werden. |
| shadow | int | r/w | Liest oder setzt die Gibt an, wie stark die Schatten eines Bildes abgedunkelt werden sollen. Farb<br/>            Kanalwerte am unteren Ende des Intensitätsbereichs werden stärker verändert als Werte nahe der Mitte oder<br/>            dem oberen Ende, was bedeutet, dass ein Bild abgedunkelt werden kann, ohne den Kontrast zwischen den<br/>            helleren Bildbereichen zu verlieren.<br/>            0 Gibt an, dass Schatten NICHT geändert werden dürfen.<br/>            0 &lt; value ≤ 100<br/>            Gibt an, dass Schatten mit einem Intensitätsprozentsatz unter diesem Schwellenwert dunkler gemacht werden. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Initialisiert eine neue Instanz der EmfPlusLevelsEffect Klasse

