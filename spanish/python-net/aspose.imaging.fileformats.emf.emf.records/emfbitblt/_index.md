---
title: "EmfBitBlt Clase"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---

**Summary:** The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBitBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfBitBlt(source)](#EmfBitBlt_source_1) | Inicializa una nueva instancia de la clase [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación raster <br/>            . Este código define cómo se combinan los datos de color del rectángulo de origen con los<br/>            datos de color del rectángulo de destino y, opcionalmente, un patrón de pincel, para lograr el color final. |
| bk_src_argb_32_color | int | r/w | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el<br/>            color de fondo del mapa de bits de origen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el <br/>            rectángulo delimitador de destino en unidades del dispositivo. |
| cx_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico de los rectángulos de origen y <br/>            destino. |
| cy_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica de los rectángulos de origen y <br/>            destino. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no necesita ser <br/>            contiguo con la porción fija del registro EMR_BITBLT. En consecuencia, los campos en este búfer <br/>            que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la <br/>            tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
| x_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda <br/>            del rectángulo de destino. |
| x_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda <br/>            del rectángulo de origen. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| y_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda <br/>            del rectángulo de destino. |
| y_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda <br/>            del rectángulo de origen. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfBitBlt(source) {#EmfBitBlt_source_1}


```
 EmfBitBlt(source) 
```

Inicializa una nueva instancia de la clase [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La fuente. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | El tipo de registro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


