---
title: "EmfPlusBlurEffect Clase"
type: docs
weight: 100
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Inicializa una nueva instancia de la clase EmfPlusBlurEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Obtiene o establece un número de punto flotante de 32 bits que especifica el radio de desenfoque en píxeles,<br/>            lo que determina la cantidad de píxeles involucrados en calcular el nuevo valor de un píxel dado.<br/>            Este valor DEBE estar en el rango de 0.0 a 255.0. |
| expand_edge | bool | r/w | Obtiene o establece un valor booleano de 32 bits que especifica si el mapa de bits se expande en<br/>            una cantidad igual al valor de BlurRadius para producir bordes suaves. Este valor DEBE ser<br/>            uno de los siguientes:<br/>            FALSE<br/>            0x00000000<br/>            El tamaño del mapa de bits NO DEBE cambiar, y sus bordes suaves DEBERÍAN recortarse al<br/>            tamaño de BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            El tamaño del mapa de bits DEBERÍA expandirse en una cantidad igual a BlurRadius para<br/>            producir bordes suaves. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Inicializa una nueva instancia de la clase EmfPlusBlurEffect

