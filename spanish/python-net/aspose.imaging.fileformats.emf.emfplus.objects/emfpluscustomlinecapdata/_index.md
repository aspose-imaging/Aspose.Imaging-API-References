---
title: "EmfPlusCustomLineCapData Clase"
type: docs
weight: 270
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Inicializa una nueva instancia de la clase EmfPlusCustomLineCapData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el valor de la enumeración LineCap (sección 2.1.1.18) <br/>            en la que se basa la tapa de línea personalizada. |
| base_inset | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la distancia entre el comienzo <br/>            de la tapa de línea y el final de la línea. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica los datos en el campo OptionalData. |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece un objeto EmfPlusPointF que no se usa actualmente. DEBE establecerse en {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Obtiene o establece un objeto opcional EmfPlusCustomLineCapOptionalData (sección 2.2.2.14)<br/>             que especifica datos adicionales para la tapa de línea gráfica personalizada. L<br/>            os contenidos específicos de este campo se determinan <br/>            por el valor del campo CustomLineCapDataFlags. |
| stroke_end_cap | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica qué <br/>            tapa de línea se debe usar al final de la línea a dibujar. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece un objeto EmfPlusPointF que no se usa actualmente. DEBE establecerse en {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineJoin <br/>            (sección 2.1.1.19), que indica cómo unir dos líneas que son dibujadas por<br/>             la misma pluma y cuyos extremos se encuentran. En la intersección de los dos extremos de línea, <br/>            una unión de línea hace que la conexión parezca más continua. |
| stroke_miter_limit | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que contiene el límite del grosor<br/>             de la unión en una esquina en ángulo recto al establecer la relación máxima permitida<br/>             entre la longitud del ángulo y el ancho de la línea. |
| stroke_start_cap | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el valor en la enumeración LineCap que indica la <br/>            tapa de línea usada al inicio de la línea a dibujar |
| width_scale | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la cantidad por la cual <br/>             escalar la tapa de línea personalizada con respecto al ancho del objeto EmfPlusPen <br/>            (sección 2.2.1.7) que se usa para dibujar las líneas. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Inicializa una nueva instancia de la clase EmfPlusCustomLineCapData

