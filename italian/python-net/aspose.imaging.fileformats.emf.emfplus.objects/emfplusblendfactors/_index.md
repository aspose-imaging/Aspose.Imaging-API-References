---
title: "EmfPlusBlendFactors Classe"
type: docs
weight: 90
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Inizializza una nuova istanza della classe EmfPlusBlendFactors |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Ottiene o imposta un array di valori a virgola mobile a 32 bit PositionCount che <br/>            specificano le proporzioni dei colori nelle posizioni definite nel campo BlendPositions. <br/>            Ogni valore DEVE essere un numero compreso tra 0.0 e 1.0, inclusi. |
| blend_positions | float[] | r/w | Ottiene o imposta le posizioni di fusione<br/>            Un array di valori a virgola mobile a 32 bit PositionCount<br/>             che specificano le proporzioni della distanza lungo la linea del gradiente.<br/>            Ogni elemento DEVE essere un numero compreso tra 0.0 e 1.0, inclusi. <br/>            Per un pennello a gradiente lineare, 0.0 rappresenta il punto iniziale <br/>            e 1.0 rappresenta il punto finale. Per un pennello a gradiente di percorso, <br/>            0.0 rappresenta il punto medio e 1.0 rappresenta un punto finale |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Inizializza una nuova istanza della classe EmfPlusBlendFactors

