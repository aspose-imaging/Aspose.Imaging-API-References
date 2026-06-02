---
title: "Clase EmfColorAdjustment"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | Inicializa una nueva instancia de la clase EmfColorAdjustment |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para el <br/>
            primario azul de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. <br/>
            Un valor de 10,000 indica que la corrección gamma NO DEBE realizarse. |
| brillo | int | r/w | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de brillo a aplicar al objeto de origen. <br/>
            Este valor DEBERÍA estar en el rango de –100 a 100.<br/>
            Un valor de cero indica que el ajuste de brillo NO DEBE realizarse. |
| colorfullness | int | r/w | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de colorido a aplicar al objeto de origen. <br/>
            Este valor DEBERÍA estar en el rango de –100 a 100. <br/>
            Un valor de cero indica que el ajuste de colorido NO DEBE realizarse |
| contraste | int | r/w | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de contraste a aplicar al objeto de origen. <br/>
            Este valor DEBERÍA estar en el rango de –100 a 100. Un valor de cero indica que el ajuste de contraste NO DEBE realizarse. |
| green_gamma | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para el primario verde de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000. <br/>
            Un valor de 10,000 indica que la corrección gamma NO DEBE realizarse. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el tipo de fuente de luz estándar bajo la cual se visualiza la <br/>
            imagen, a partir de la enumeración Illuminant (sección 2.1.19). |
| red_gamma | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el valor de corrección gamma de n-ésima potencia para el primario rojo de los colores de origen. Este valor DEBERÍA estar en el rango de 2,500 a 65,000.<br/>
            Un valor de 10,000 indica que la corrección gamma NO DEBE realizarse. |
| red_green_tint | int | r/w | Obtiene o establece un entero con signo de 16 bits que especifica la cantidad de ajuste de tono rojo o verde a aplicar <br/>
            al objeto de origen. Este valor DEBERÍA estar en el rango de –100 a 100. <br/>
            Los números positivos ajustan hacia el rojo y los negativos hacia el verde. <br/>
            Un valor de cero indica que el ajuste de tono NO DEBE realizarse |
| reference_black | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia negra para los colores de origen. <br/>
            Cualquier color más oscuro que este se trata como negro. <br/>
            Este valor DEBERÍA estar en el rango de cero a 4,000 |
| reference_white | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica la referencia blanca para los colores de origen. <br/>
            Cualquier color más claro que este se trata como blanco. <br/>
            Este valor DEBERÍA estar en el rango de 6,000 a 10,000. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el tamaño en bytes de este objeto. Esto DEBE ser 0x0018. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica cómo preparar la imagen de salida. Este campo puede <br/>
            establecerse en NULL o en cualquier combinación de valores de la enumeración ColorAdjustment (sección 2.1.5). |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

Inicializa una nueva instancia de la clase EmfColorAdjustment

