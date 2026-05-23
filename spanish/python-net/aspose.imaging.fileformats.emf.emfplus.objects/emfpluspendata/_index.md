---
title: "Clase EmfPlusPenData"
type: docs
weight: 550
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Inicializa una nueva instancia de la clase EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Obtiene o establece un objeto opcional EmfPlusPenOptionalData (sección 2.2.2.34) <br/>            que especifica datos adicionales para el objeto de la pluma. El contenido específico <br/>            de este campo está determinado por el valor del campo <br/>            PenDataFlags. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo <br/>            OptionalData. Este valor DEBE estar compuesto por los indicadores PenData <br/>            (sección 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica las unidades de medida <br/>            para la pluma. El valor DEBE provenir de la enumeración UnitType <br/>            (sección 2.1.1.33). |
| pen_width | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica el ancho de la <br/>            línea dibujada por la pluma en las unidades especificadas por el campo PenUnit <br/>            . Si se especifica un ancho cero, se utiliza un valor mínimo, <br/>            que está determinado por las unidades. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Inicializa una nueva instancia de la clase EmfPlusPenData

