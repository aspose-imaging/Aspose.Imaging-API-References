---
title: "Clase EmfPlusDrawCurve"
type: docs
weight: 100
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) está comprimido.<br/>            Este bit indica si el campo PointData especifica datos comprimidos.<br/>            Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. <br/>            Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits<br/>            Nota: Si la bandera Relative (abajo) está establecida, esta bandera es indefinida y DEBE ser ignorada |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| num_segments | int | r/w | Obtiene o establece el recuento de segmentos <br/>            Un entero sin signo de 32 bits que especifica el número de segmentos de línea que componen la spline. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de un objeto EmfPlusPen (sección 2.2.1.7) en el EMF+<br/>            tabla de objetos para dibujar la curva. El valor DEBE ser de 0 a 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece una matriz de enteros con signo de 32 bits o números de punto flotante de 32 bits de <br/>            longitud Count que define los valores de coordenadas de los puntos finales de las líneas a trazar. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| tensión | float | r/w | Obtiene o establece la tensión<br/>            Un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline <br/>            al pasar por los puntos. Un valor de 0 indica que <br/>            la spline es una secuencia de líneas rectas. A medida que el valor aumenta, <br/>            la curva se vuelve más redondeada. Para más información, consulte [SPLINE77] y [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

