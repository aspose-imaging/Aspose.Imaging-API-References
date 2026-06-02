---
title: "EmfPlusBlendColors Class"
type: docs
weight: 80
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Initialisiert eine neue Instanz der EmfPlusBlendColors‑Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Liest oder setzt ein Array von PositionCount EmfPlusARGB‑Objekten (Abschnitt 2.2.2.1), die <br/>            Farben an den im Feld BlendPositions definierten Positionen angeben. |
| blend_positions | float[] | r/w | Liest oder schreibt die Blend‑Positionen<br/>            Ein Array von PositionCount 32‑Bit Fließkommawerten<br/>            das die Proportionen der Entfernung entlang der Verlaufs­linie angibt.<br/>            Jedes Element MUSS eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein. <br/>            Für einen linearen Verlaufs‑Pinsel steht 0,0 für den Startpunkt <br/>            und 1,0 für den Endpunkt. Für einen Pfad‑Verlaufs‑Pinsel <br/>            steht 0,0 für den Mittelpunkt und 1,0 für einen Endpunkt. |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Initialisiert eine neue Instanz der EmfPlusBlendColors‑Klasse

