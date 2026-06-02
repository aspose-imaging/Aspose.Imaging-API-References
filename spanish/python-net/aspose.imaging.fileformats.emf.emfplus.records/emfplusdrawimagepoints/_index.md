---
title: "Clase EmfPlusDrawImagePoints"
type: docs
weight: 140
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Inicializa una nueva instancia de la clase [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Obtiene o establece un valor que indica si [applying an effect].<br/>
            Este bit indica que la representación de la imagen incluye la aplicación de un efecto.<br/>
            Si está establecido, debe haberse especificado un objeto de la clase Effect en un registro EmfPlusSerializableObject anterior (sección 2.3.5.2). |
| comprimido | bool | r/w | Obtiene o establece un valor que indica si los datos de PointData están comprimidos.<br/>
            Este bit indica si el campo PointData especifica datos comprimidos.<br/>
            Si está establecido, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits.<br/>
            Si está despejado, PointData especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits.<br/>
            Nota: Si el indicador P (abajo) está establecido, este indicador es indefinido y DEBE ser ignorado. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| image_attributes_id | int | r/w | Obtiene o establece un entero sin signo de 32 bits que contiene el índice del<br/>
            objeto opcional EmfPlusImageAttributes (sección 2.2.1.5) en la tabla de objetos EMF+. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>
            El índice de un objeto EmfPlusImage (sección 2.2.1.4) en la tabla de objetos EMF+, que especifica la imagen a renderizar. El valor DEBE estar entre 0 y 63, inclusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece una matriz de puntos Count que especifican tres puntos de un paralelogramo.<br/>
            Los tres puntos representan las esquinas superior izquierda, superior derecha e inferior izquierda del<br/>
            paralelogramo. El cuarto punto del paralelogramo se extrapola a partir de los tres primeros. La<br/>
            porción de la imagen especificada por el campo SrcRect DEBERÍA tener transformaciones de escalado y cizallado aplicadas si es necesario para encajar dentro del paralelogramo. |
| relative | bool | r/w | Obtiene o establece un valor que indica si este [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) es relativo.<br/>
            Este bit indica si el campo PointData especifica ubicaciones relativas o absolutas.<br/>
            Si está establecido, cada elemento en PointData especifica una ubicación en el espacio de coordenadas que es<br/>
            relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del<br/>
            primer elemento en PointData, se asume una ubicación previa en coordenadas (0,0). Si está despejado,<br/>
            PointData especifica ubicaciones absolutas de acuerdo con el indicador C.<br/>
            Nota: Si este indicador está establecido, el indicador C (arriba) es indefinido y DEBE ser ignorado. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Obtiene o establece un objeto EmfPlusRectF (sección 2.2.2.39) que define una porción de la imagen a renderizar. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Obtiene o establece un entero con signo de 32 bits que define las unidades del campo SrcRect. DEBE<br/>
            ser el valor UnitPixel de la enumeración UnitType (sección 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

