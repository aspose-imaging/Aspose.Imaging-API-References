---
title: "Clase EmfPlusFillPolygon"
type: docs
weight: 270
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Inicializa una nueva instancia de la clase [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Obtiene o establece el identificador del pincel<br/>            Un entero sin signo de 32 bits que define el pincel, cuyo contenido está determinado por el bit S en el campo Flags. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_color | bool | r/w | Obtiene o establece un valor que indica si esta instancia es de color.<br/>            Si está establecido, BrushId especifica un color como un objeto EmfPlusARGB (sección 2.2.2.1). <br/>            Si no está establecido, BrushId contiene el índice de un objeto EmfPlusBrush (sección 2.2.1.1) en la tabla de objetos EMF+. |
| is_compressed | bool | r/w | Obtiene o establece un valor que indica si esta instancia está comprimida.<br/>            Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con 16 bits <br/>            coordenadas enteras. Si no está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas <br/>            con coordenadas de punto flotante de 32 bits |
| is_relative | bool | r/w | Obtiene o establece un valor que indica si esta instancia es relativa.<br/>            Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior <br/>            en el arreglo. En el caso del primer elemento en PointData, se asume una ubicación previa <br/>            en coordenadas (0,0). Si no está establecido, PointData especifica <br/>            ubicaciones absolutas según la bandera C. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece los datos del punto<br/>            Una matriz de Count puntos que definen los vértices del polígono. <br/>            Los dos primeros puntos de la matriz especifican el primer lado del polígono. <br/>            Cada punto adicional especifica un nuevo lado, cuyos vértices <br/>            incluyen el punto y el punto anterior. Si el último punto y el <br/>            primer punto no coinciden, especifican el último lado del polígono. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

