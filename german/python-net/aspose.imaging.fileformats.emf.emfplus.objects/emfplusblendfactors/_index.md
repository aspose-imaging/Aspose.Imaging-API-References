---
title: "EmfPlusBlendFactors Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Initialisiert eine neue Instanz der EmfPlusBlendFactors Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Liest oder schreibt ein Array von PositionCount 32‑Bit Fließkommawerten, die <br/>            die Farbanteile an den im Feld BlendPositions definierten Positionen angeben. <br/>            Jeder Wert MUSS eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein. |
| blend_positions | float[] | r/w | Liest oder schreibt die Blend‑Positionen<br/>            Ein Array von PositionCount 32‑Bit Fließkommawerten<br/>            das die Proportionen der Entfernung entlang der Verlaufs­linie angibt.<br/>            Jedes Element MUSS eine Zahl zwischen 0,0 und 1,0 (einschließlich) sein. <br/>            Für einen linearen Verlaufs‑Pinsel steht 0,0 für den Startpunkt <br/>            und 1,0 für den Endpunkt. Für einen Pfad‑Verlaufs‑Pinsel <br/>            steht 0,0 für den Mittelpunkt und 1,0 für einen Endpunkt. |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Initialisiert eine neue Instanz der EmfPlusBlendFactors Klasse

