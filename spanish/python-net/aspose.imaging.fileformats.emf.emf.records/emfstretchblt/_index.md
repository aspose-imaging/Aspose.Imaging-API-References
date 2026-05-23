---
title: "Clase EmfStretchBlt"
type: docs
weight: 1400
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

**Summary:** The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfStretchBlt()](#EmfStretchBlt__1) | Inicializa una nueva instancia de la clase [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
| [EmfStretchBlt(source)](#EmfStretchBlt_source_2) | Inicializa una nueva instancia de la clase [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el <br/>            color de fondo del mapa de bits de origen. |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el código de operación raster <br/>            . Este código define cómo se combinan los datos de color del rectángulo de origen con los <br/>            datos de color del rectángulo de destino y, opcionalmente, un patrón de pincel, para lograr el color final. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el <br/>            rectángulo delimitador de destino en unidades del dispositivo. |
| cx_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| cx_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| cy_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino. |
| cy_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece el rectángulo de destino. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no necesita ser <br/>            contiguo con la porción fija del registro EMR_STRETCHBLT. En consecuencia, los campos en este <br/>            búfer etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece el rectángulo de origen. |
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


### Constructor: EmfStretchBlt() {#EmfStretchBlt__1}


```
 EmfStretchBlt() 
```

Inicializa una nueva instancia de la clase [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

### Constructor: EmfStretchBlt(source) {#EmfStretchBlt_source_2}


```
 EmfStretchBlt(source) 
```

Inicializa una nueva instancia de la clase [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

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


