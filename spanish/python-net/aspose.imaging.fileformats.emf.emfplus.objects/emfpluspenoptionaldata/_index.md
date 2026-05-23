---
title: "Clase EmfPlusPenOptionalData"
type: docs
weight: 560
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Inicializa una nueva instancia de la clase EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Obtiene o establece el objeto opcional EmfPlusCompoundLineData (sección 2.2.2.9) <br/>            que especifica una matriz de valores de punto flotante que definen <br/>            la línea compuesta de un lápiz, que está formada por líneas paralelas <br/>            y espacios. Este campo DEBE estar presente si la <br/>            bandera PenDataCompoundLine está establecida en el campo PenDataFlags <br/>            del objeto EmfPlusPenData |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Obtiene o establece el objeto opcional EmfPlusCustomEndCapData (sección 2.2.2.11) <br/>            que define la forma de capucha final personalizada, que es la forma a <br/>            usar al final de una línea dibujada con este lápiz. Puede ser cualquiera de <br/>            varias formas, como un cuadrado, círculo o diamante. Este <br/>            campo DEBE estar presente si la bandera PenDataCustomEndCap está <br/>            establecida en el campo PenDataFlags del objeto EmfPlusPenData |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Obtiene o establece el objeto opcional EmfPlusCustomStartCapData (sección 2.2.2.15) <br/>            que define la forma de capucha inicial personalizada, que es la forma a <br/>            usar al inicio de una línea dibujada con este lápiz. Puede ser cualquiera <br/>            de varias formas, como un cuadrado, círculo o diamante. <br/>            Este campo DEBE estar presente si la bandera PenDataCustomStartCap está <br/>            establecida en el campo PenDataFlags del objeto EmfPlusPenData |
| dash_offset | float | r/w | Obtiene o establece un valor opcional de punto flotante de 32 bits que especifica la <br/>            distancia desde el inicio de una línea hasta el inicio del <br/>            primer espacio en un patrón de línea punteada. Este campo DEBE estar <br/>            presente si la bandera PenDataDashedLineOffset está establecida en el <br/>            campo PenDataFlags del objeto EmfPlusPenData. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma para <br/>            ambos extremos de cada guión en una línea punteada. Este campo DEBE estar <br/>            presente si la bandera PenDataDashedLineCap está establecida en el <br/>            campo PenDataFlags del objeto EmfPlusPenData, y el <br/>            valor DEBE estar definido en la enumeración DashedLineCapType <br/>            (sección 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Obtiene o establece el objeto opcional EmfPlusDashedLineData (sección 2.2.2.16) <br/>            que especifica las longitudes de los guiones y espacios en una línea punteada personalizada. Este campo DEBE estar presente si la bandera PenDataDashedLine <br/>            está establecida en el campo PenDataFlags del EmfPlusPenData<br/>            objeto. |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Obtiene o establece un entero opcional con signo de 32 bits que especifica la forma<br/>            para el extremo de una línea en el campo CustomEndCapData. Este <br/>            campo DEBE estar presente si la bandera PenDataEndCap está establecida en el <br/>            campo PenDataFlags del objeto EmfPlusPenData, y el valor <br/>            DEBE estar definido en la enumeración LineCapType |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Obtiene o establece un entero opcional con signo de 32 bits que especifica cómo unir<br/>            dos líneas dibujadas por el mismo lápiz y cuyos extremos se encuentran. <br/>            Este campo DEBE estar presente si la bandera PenDataJoin está establecida en <br/>            el campo PenDataFlags del objeto EmfPlusPenData, y el <br/>            valor DEBE estar definido en la enumeración LineJoinType <br/>            (sección 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Obtiene o establece un entero opcional con signo de 32 bits que especifica el estilo <br/>            usado para las líneas dibujadas con este objeto lápiz. Este campo DEBE <br/>            estar presente si la bandera PenDataLineStyle está establecida en el <br/>            campo PenDataFlags del objeto EmfPlusPenData, y el <br/>            valor DEBE estar definido en la enumeración LineStyle <br/>            (sección 2.1.1.20). |
| miter_limit | float | r/w | Obtiene o establece un valor opcional de punto flotante de 32 bits que especifica el bisel <br/>            límite, que es la relación máxima permitida entre la longitud del bisel y<br/>            el ancho de línea. La longitud del bisel es la distancia desde la<br/>            intersección de las paredes de la línea en el interior de la unión hasta <br/>            la intersección de las paredes de la línea fuera de la unión. <br/>            La longitud del bisel puede ser grande cuando el ángulo entre dos <br/>            líneas es pequeño. Este campo DEBE estar presente si la <br/>            bandera PenDataMiterLimit está establecida en el campo PenDataFlags <br/>            del objeto EmfPlusPenData. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Obtiene o establece un entero con signo opcional de 32 bits que especifica la <br/>            distribución del ancho del lápiz con respecto a las <br/>            coordenadas de la línea que se está dibujando. Este campo DEBE <br/>            estar presente si la bandera PenDataNonCenter está establecida en el <br/>            campo PenDataFlags del objeto EmfPlusPenData, y <br/>            el valor DEBE estar definido en la enumeración PenAlignment <br/>            (sección 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Obtiene o establece un entero con signo opcional de 32 bits que especifica la forma para<br/>             el inicio de una línea en el campo CustomStartCapData. <br/>            Este campo DEBE estar presente si la bandera PenDataStartCap está establecida <br/>            en el campo PenDataFlags del objeto EmfPlusPenData, y el<br/>             valor DEBE estar definido en la enumeración LineCapType <br/>            (sección 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto EmfPlusTransformMatrix opcional (sección 2.2.2.47) <br/>            que especifica una transformación de espacio mundial a espacio del dispositivo para <br/>            el lápiz. Este campo DEBE estar presente si la bandera PenDataTransform <br/>            está establecida en el campo PenDataFlags del objeto EmfPlusPenData <br/>            . |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Inicializa una nueva instancia de la clase EmfPlusPenOptionalData

