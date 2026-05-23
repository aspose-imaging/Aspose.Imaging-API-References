---
title: "Clase EmfPlusBlendColors"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Inicializa una nueva instancia de la clase EmfPlusBlendColors |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Obtiene o establece una matriz de objetos EmfPlusARGB de PositionCount (sección 2.2.2.1) que <br/>            especifican colores en las posiciones definidas en el campo BlendPositions. |
| blend_positions | float[] | r/w | Obtiene o establece las posiciones de mezcla<br/> Una matriz de valores de punto flotante de 32 bits PositionCount<br/> que especifican proporciones de distancia a lo largo de la línea de degradado.<br/> Cada elemento DEBE ser un número entre 0.0 y 1.0 inclusive. <br/> Para un pincel de degradado lineal, 0.0 representa el punto inicial <br/> y 1.0 representa el punto final. Para un pincel de degradado de ruta, <br/> 0.0 representa el punto medio y 1.0 representa un punto final |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Inicializa una nueva instancia de la clase EmfPlusBlendColors

