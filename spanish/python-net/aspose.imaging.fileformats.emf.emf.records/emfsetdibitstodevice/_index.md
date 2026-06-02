---
title: "EmfSetDiBitsToDevice Clase"
type: docs
weight: 1150
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---

**Summary:** The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of <br/>            a source bitmap to a destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetDiBitsToDevice

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetDiBitsToDevice(source)](#EmfSetDiBitsToDevice_source_1) | Inicializa una nueva instancia de la clase [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el <br/>            rectángulo delimitador de destino en unidades del dispositivo. |
| c_scans | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de líneas de escaneo. |
| cx_src | int | r/w | Obtiene o establece un 32-bit signed integer que especifica el ancho en píxeles del rectángulo de origen. |
| cy_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura en píxeles del rectángulo de origen. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no es necesario que sea <br/>            contiguo con la porción fija del registro EMR_SETDIBITSTODEVICE. En consecuencia, los campos <br/>            en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. |
| start_scan | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica la primera línea de escaneo en la matriz. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la <br/>            tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
| x_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda <br/>            del rectángulo de destino. |
| x_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x en píxeles de la esquina inferior izquierda <br/>            del rectángulo de origen. |
| y_dest | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda <br/>            del rectángulo de destino. |
| y_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y en píxeles de la esquina inferior izquierda <br/>            del rectángulo de origen. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetDiBitsToDevice(source) {#EmfSetDiBitsToDevice_source_1}


```
 EmfSetDiBitsToDevice(source) 
```

Inicializa una nueva instancia de la clase [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/).

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


