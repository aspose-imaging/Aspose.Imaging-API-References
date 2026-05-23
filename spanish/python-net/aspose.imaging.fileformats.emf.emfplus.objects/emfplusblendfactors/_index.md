---
title: "Clase EmfPlusBlendFactors"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Inicializa una nueva instancia de la clase EmfPlusBlendFactors |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Obtiene o establece una matriz de valores de punto flotante de 32 bits PositionCount que <br/> especifican proporciones de colores en las posiciones definidas en el campo BlendPositions. <br/> Cada valor DEBE ser un número entre 0.0 y 1.0 inclusive. |
| blend_positions | float[] | r/w | Obtiene o establece las posiciones de mezcla<br/> Una matriz de valores de punto flotante de 32 bits PositionCount<br/> que especifican proporciones de distancia a lo largo de la línea de degradado.<br/> Cada elemento DEBE ser un número entre 0.0 y 1.0 inclusive. <br/> Para un pincel de degradado lineal, 0.0 representa el punto inicial <br/> y 1.0 representa el punto final. Para un pincel de degradado de ruta, <br/> 0.0 representa el punto medio y 1.0 representa un punto final |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Inicializa una nueva instancia de la clase EmfPlusBlendFactors

