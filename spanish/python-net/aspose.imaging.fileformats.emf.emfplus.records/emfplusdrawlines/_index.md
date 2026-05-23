---
title: "Clase EmfPlusDrawLines"
type: docs
weight: 150
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Obtiene o establece un valor que indica si [closed shape]. |
| compressed | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) está comprimido.<br/>            Este bit indica si el campo PointData especifica datos comprimidos.<br/>            Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. <br/>            Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits<br/>            Nota: Si la bandera Relative (abajo) está establecida, esta bandera es indefinida y DEBE ser ignorada |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice de un objeto EmfPlusPen (sección 2.2.1.7) en la tabla de objetos EMF+<br/>            para dibujar las líneas. El valor DEBE ser de 0 a 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece los datos de puntos<br/>            Una matriz de puntos Count que especifican los puntos de inicio y fin de las líneas a dibujar. |
| relative | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) es relativo.<br/>            Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas.<br/>            Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa <br/>            a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer <br/>            elemento en PointData, se asume una ubicación previa en las coordenadas (0,0). Si está despejado, <br/>            PointData especifica ubicaciones absolutas según la bandera C.<br/>            Nota: Si esta bandera está establecida, la bandera Compressed (arriba) es indefinida y DEBE ser ignorada |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

