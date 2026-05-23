---
title: "Clase EmfPlusDrawClosedCurve"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType - Un entero sin signo de 16 bits que identifica este tipo de registro como EmfPlusDrawClosedCurve<br/>            de la enumeración RecordType (sección 2.1.1.1). El valor DEBE ser 0x4017. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) está comprimido.<br/>            Este bit indica si el campo PointData especifica datos comprimidos.<br/>            Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. <br/>            Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits<br/>            Nota: Si la bandera Relative (abajo) está establecida, esta bandera es indefinida y DEBE ser ignorada |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+<br/>            para dibujar la curva cerrada. El valor DEBE ser de 0 a 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece los datos de los puntos<br/>            Una matriz de Count puntos que especifican los extremos de las líneas que definen la spline. En una spline cardinal cerrada, <br/>            la curva continúa a través del último punto en la matriz PointData y se conecta con el primer punto de la matriz.<br/>            El tipo de datos en esta matriz se especifica mediante el campo Flags, como sigue: Tipo de dato Significado<br/>            objeto EmfPlusPointR (sección 2.2.2.37)<br/>            Si la bandera P está activada en Flags, los puntos especifican ubicaciones relativas.<br/>            objeto EmfPlusPointF (sección 2.2.2.36)<br/>            Si los bits P y C están activados en el campo Flags, los puntos especifican ubicaciones absolutas.<br/>            objeto EmfPlusPoint (sección 2.2.2.35)<br/>            Si el bit P está desactivado y el bit C está activado en el campo Flags, los puntos especifican ubicaciones relativas. |
| relative | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) es relativo.<br/>            Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas.<br/>            Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa <br/>            a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer <br/>            elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está despejado, <br/>            PointData especifica ubicaciones absolutas según la bandera C.<br/>            Nota: Si esta bandera está establecida, la bandera Compressed (arriba) es indefinida y DEBE ser ignorada |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| tensión | float | r/w | Obtiene o establece la tensión<br/>            Un número de punto flotante de 32 bits que especifica cuán estrechamente se curva la spline <br/>            al pasar por los puntos. Un valor de 0 indica que <br/>            la spline es una secuencia de líneas rectas. A medida que el valor aumenta, <br/>            la curva se vuelve más redondeada. Para más información, consulte [SPLINE77] y [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType - Un entero sin signo de 16 bits que identifica este tipo de registro como EmfPlusDrawClosedCurve<br/>            de la enumeración RecordType (sección 2.1.1.1). El valor DEBE ser 0x4017.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

