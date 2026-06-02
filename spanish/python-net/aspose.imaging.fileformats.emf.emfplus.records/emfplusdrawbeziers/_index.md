---
title: "Clase EmfPlusDrawBeziers"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| comprimido | bool | r/w | Obtiene o establece un valor que indica si los datos de PointData están comprimidos. <br/>
            Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con <br/>
            coordenadas enteras de 16 bits. Si está despejado, PointData especifica ubicaciones absolutas <br/>
            en el espacio de coordenadas con coordenadas de punto flotante de 32 bits.<br/>
            Nota: Si el indicador Relative (abajo) está establecido, este indicador es indefinido y DEBE ser ignorado. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>
            El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+<br/>
            para dibujar las curvas Bézier. El valor DEBE estar entre 0 y 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece los datos de los puntos<br/>
            Una matriz de puntos Count que especifican los puntos de inicio, fin y control de las curvas Bézier. La coordenada final de una curva Bézier es la coordenada inicial de la siguiente. Los puntos de control se utilizan para producir el efecto Bézier.<br/>
            El tipo de datos en esta matriz se especifica mediante el campo Flags, como sigue: Significado del Tipo de Datos<br/>
            objeto EmfPlusPointR (sección 2.2.2.37)<br/>
            Si el indicador P está establecido en Flags, los puntos especifican ubicaciones relativas.<br/>
            objeto EmfPlusPointF (sección 2.2.2.36)<br/>
            Si los bits P y C están despejados en el campo Flags, los puntos especifican ubicaciones absolutas.<br/>
            objeto EmfPlusPoint (sección 2.2.2.35)<br/>
            Si el bit P está despejado y el bit C está establecido en Flags, los puntos especifican ubicaciones relativas.<br/>
            Una curva Bézier no pasa por sus puntos de control. Los puntos de control actúan como |
| relative | bool | r/w | Obtiene o establece un valor que indica si el PointData es relativo.<br/> Si se establece, cada elemento en PointData especifica una ubicación en el espacio de coordenadas <br/> que es relativa a la ubicación especificada por el elemento anterior en la matriz. <br/> En el caso del primer elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si se borra, PointData especifica ubicaciones absolutas según la bandera C.<br/> Nota: Si esta bandera está establecida, la bandera C (arriba) es indefinida y DEBE ser ignorada. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

