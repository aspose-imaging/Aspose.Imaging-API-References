---
title: "EmfPlusBlendColors Classe"
type: docs
weight: 80
url: /it/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Inizializza una nuova istanza della classe EmfPlusBlendColors |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Ottiene o imposta un array di oggetti PositionCount EmfPlusARGB (sezione 2.2.2.1) che <br/>            specificano i colori nelle posizioni definite nel campo BlendPositions. |
| blend_positions | float[] | r/w | Ottiene o imposta le posizioni di fusione<br/>            Un array di valori a virgola mobile a 32 bit PositionCount<br/>             che specificano le proporzioni della distanza lungo la linea del gradiente.<br/>            Ogni elemento DEVE essere un numero compreso tra 0.0 e 1.0, inclusi. <br/>            Per un pennello a gradiente lineare, 0.0 rappresenta il punto iniziale <br/>            e 1.0 rappresenta il punto finale. Per un pennello a gradiente di percorso, <br/>            0.0 rappresenta il punto medio e 1.0 rappresenta un punto finale |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Inizializza una nuova istanza della classe EmfPlusBlendColors

