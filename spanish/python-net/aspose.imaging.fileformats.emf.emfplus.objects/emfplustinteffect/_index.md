---
title: "Clase EmfPlusTintEffect"
type: docs
weight: 700
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustinteffect/
---

**Summary:** The TintEffect object specifies an addition of black or white to a specified hue in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTintEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusTintEffect()](#EmfPlusTintEffect__1) | Inicializa una nueva instancia de la clase EmfPlusTintEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| amount | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica cuánto se refuerza o debilita el tono.<br/>            -100 ≤ valor &lt; 0<br/>            Los valores negativos indican cuánto se debilita el tono, lo que equivale a la<br/>            adición de negro.<br/>            0 Un valor de 0 indica que el tinte NO DEBE cambiar.<br/>            0 &lt; valor ≤ 100<br/>            Los valores positivos indican cuánto se refuerza el tono, lo que equivale a la<br/>            adición de blanco. |
| tono | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el tono al que se aplica el efecto de tinte.<br/>            -180 ≤ valor &lt; 0 <br/>            El color en una rotación antihoraria especificada de la rueda de colores, comenzando<br/>            desde el azul.<br/>            0 Un valor de 0 indica el color azul en la rueda de colores.<br/>            0 &lt; valor ≤ 180<br/>            El color en una rotación horaria especificada de la rueda de colores, comenzando desde el azul. |


### Constructor: EmfPlusTintEffect() {#EmfPlusTintEffect__1}


```
 EmfPlusTintEffect() 
```

Inicializa una nueva instancia de la clase EmfPlusTintEffect

