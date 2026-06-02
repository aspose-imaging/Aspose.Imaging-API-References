---
title: "EmfPlgBlt Clase"
type: docs
weight: 750
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Inicializa una nueva instancia de la [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtiene o establece una matriz de tres objetos WMF PointL ([MS-WMF] sección 2.2.2.15) que <br/>            especifica tres esquinas de un área de destino en forma de paralelogramo para la transferencia de bloque.<br/>            La esquina superior izquierda del rectángulo de origen se asigna al primer punto de esta matriz, la <br/>            esquina superior derecha al segundo punto, y la esquina inferior izquierda al tercer punto. La esquina inferior derecha del rectángulo de origen se asigna al cuarto punto implícito del <br/>            paralelogramo, que se calcula a partir de los tres primeros puntos (A, B y C) tratándolos como <br/>            vectores. <br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | Obtiene o establece un objeto WMF ColorRef ([MS-WMF] sección 2.2.2.8) que especifica el <br/>            color de fondo del mapa de bits de origen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que define el <br/>            rectángulo delimitador, en unidades del dispositivo, para la salida al destino. |
| cx_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica el ancho lógico del rectángulo de origen. |
| cy_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la altura lógica del rectángulo de origen. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene el mapa de bits de máscara, que no <br/>            es necesario que sea contiguo con la parte fija del registro EMR_PLGBLT o entre sí. <br/>            En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene el mapa de bits de origen, que no <br/>            es necesario que sea contiguo con la parte fija del registro EMR_PLGBLT o entre sí. <br/>            En consecuencia, los campos en este búfer que están etiquetados como "UndefinedSpace" son opcionales y DEBEN ser ignorados. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la <br/>            tabla de colores en el encabezado del mapa de bits de máscara. Este valor DEBE estar en la enumeración DIBColors. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la <br/>            tabla de colores del encabezado del mapa de bits de origen. Este valor DEBE estar en la enumeración DIBColors |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto XForm (sección 2.2.28) que especifica una transformación de espacio mundial a espacio de página para aplicar al mapa de bits de origen. |
| x_mask | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| x_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x lógica de la esquina superior izquierda <br/>            del rectángulo de origen. |
| y_mask | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda del mapa de bits de la máscara. |
| y_src | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y lógica de la esquina superior izquierda <br/>            del rectángulo de origen. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Inicializa una nueva instancia de la [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/) clase.

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


