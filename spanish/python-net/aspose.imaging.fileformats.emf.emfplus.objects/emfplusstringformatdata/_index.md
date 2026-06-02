---
title: "Clase EmfPlusStringFormatData"
type: docs
weight: 660
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

**Summary:** The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData__1) | Inicializa una nueva instancia de la clase EmfPlusStringFormatData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| char_range | [EmfPlusCharacterRange[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange/) | r/w | Obtiene o establece una matriz opcional de RangeCount EmfPlusCharacterRange <br/>            objetos que especifican el rango de posiciones de caracteres <br/>            dentro de una cadena de texto. La región delimitadora se define<br/>            por el área de la pantalla ocupada por un grupo <br/>            de caracteres especificados por el rango de caracteres.<br/>            Este campo DEBE estar presente si el valor de RangeCount<br/>            en el objeto EmfPlusStringFormat es mayor que 0. |
| tab_stops | float[] | r/w | Obtiene o establece una matriz opcional de valores de punto flotante que especifican <br/>            las ubicaciones opcionales de tabulaciones para este objeto. Cada valor de tabulación <br/>            representa la cantidad de espacios entre tabulaciones o, para la primera tabulación, la cantidad de espacios <br/>            entre el comienzo de una línea de texto y la primera tabulación. <br/>            Este campo DEBE estar presente si el valor de TabStopCount <br/>            en el objeto EmfPlusStringFormat es mayor que 0. |


### Constructor: EmfPlusStringFormatData() {#EmfPlusStringFormatData__1}


```
 EmfPlusStringFormatData() 
```

Inicializa una nueva instancia de la clase EmfPlusStringFormatData

