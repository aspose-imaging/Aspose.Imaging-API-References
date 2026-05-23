---
title: "Clase EmfMaskBlt"
type: docs
weight: 600
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | Inicializa una nueva instancia de la clase [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el <br/>            color de fondo del mapa de bits de origen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el <br/>            rectángulo delimitador de destino en unidades del dispositivo. |
| cx_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de destino. |
| cy_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de destino. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene los mapas de bits de máscara, que no <br/>            requieren ser contiguos con la porción fija del registro EMR_MASKBLT o con cada <br/>            otro. En consecuencia, los campos en este búfer etiquetados como "UndefinedSpace" son opcionales y <br/>            DEBEN ser ignorados. |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | Obtiene o establece una operación raster cuaternaria, que especifica operaciones raster ternarias para <br/>            los colores de primer plano y de fondo de un mapa de bits. Estos valores definen cómo los datos de color del <br/>            rectángulo de origen deben combinarse con los datos de color del rectángulo de destino. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene los mapas de bits de origen, que no <br/>            requieren ser contiguos con la porción fija del registro EMR_MASKBLT o con cada <br/>            otro. En consecuencia, los campos en este búfer etiquetados como "UndefinedSpace" son opcionales y <br/>            DEBEN ser ignorados. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la <br/>            tabla de colores en el encabezado del mapa de bits de máscara. Este valor DEBE estar en la enumeración DIBColors. |
| usage_src | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la <br/>            tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
| x_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda <br/>            del rectángulo de destino. |
| x_mask | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| x_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda <br/>            del rectángulo de origen. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| y_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda <br/>            del rectángulo de destino. |
| y_mask | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| y_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda <br/>            del rectángulo de origen. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

Inicializa una nueva instancia de la clase [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/).

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


