---
title: "EmfPlusLevelsEffect Clase"
type: docs
weight: 420
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Inicializa una nueva instancia de la clase EmfPlusLevelsEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| resaltar | int | r/w | Obtiene o establece el especifica cuánto aclarar los reflejos de una imagen. Los valores del canal de color en el extremo alto del rango de intensidad se alteran más que los valores cercanos al medio o a los extremos bajos, lo que significa que una imagen puede aclararse sin perder el contraste entre las partes más oscuras de la imagen.<br/>            0 ≤ value &lt; Especifica que los reflejos con un porcentaje de intensidad por encima de este umbral DEBERÁN aumentarse.<br/>            100 Especifica que los reflejos NO DEBEN cambiar. |
| mid_tone | int | r/w | Obtiene o establece el especifica cuánto aclarar o oscurecer los tonos medios de una imagen. Los valores del canal de color en el medio del rango de intensidad se alteran más que los valores cercanos a los extremos alto o bajo, lo que significa que una imagen puede aclararse u oscurecerse sin perder el contraste entre las partes más oscuras y más claras de la imagen.<br/>            -100 ≤ value &lt; 0 Especifica que los tonos medios se vuelven más oscuros.<br/>            0 Especifica que los tonos medios NO DEBEN cambiar.<br/>            0 &lt; value ≤ 100 Especifica que los tonos medios se vuelven más claros. |
| shadow | int | r/w | Obtiene o establece el especifica cuánto oscurecer las sombras de una imagen. Los valores del canal de color en el extremo bajo del rango de intensidad se alteran más que los valores cercanos al medio o a los extremos altos, lo que significa que una imagen puede oscurecerse sin perder el contraste entre las partes más claras de la imagen.<br/>            0 Especifica que las sombras NO DEBEN cambiar.<br/>            0 &lt; value ≤ 100<br/>            Especifica que las sombras con un porcentaje de intensidad por debajo de este umbral se vuelven más oscuras. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Inicializa una nueva instancia de la clase EmfPlusLevelsEffect

