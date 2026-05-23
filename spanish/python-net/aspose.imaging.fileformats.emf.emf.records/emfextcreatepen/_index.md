---
title: "Clase EmfExtCreatePen"
type: docs
weight: 430
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---

**Summary:** The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An<br/>            optional DIB can be specified to use as the line style.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfExtCreatePen()](#EmfExtCreatePen__1) | Inicializa una nueva instancia de la clase [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/). |
| [EmfExtCreatePen(record)](#EmfExtCreatePen_record_2) | Inicializa una nueva instancia de la clase [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer opcional que contiene un DIB empaquetado en forma de un objeto WMF DeviceIndependentBitmap<br/>            ([MS-WMF] sección 2.2.2.9). No es necesario que sea contiguo con la porción fija del registro EMR_EXTCREATEPEN. |
| elp | [EmfLogPenEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/) | r/w | Obtiene o establece un objeto LogPenEx (sección 2.2.20) que especifica un lápiz lógico extendido <br/>            con atributos que incluyen una matriz opcional de estilo de línea. |
| ih_pen | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del objeto de lápiz lógico extendido <br/>            en la Tabla de Objetos EMF (sección 3.1.1.1). <br/>            Este índice DEBE guardarse para que este objeto pueda reutilizarse o modificarse. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtCreatePen() {#EmfExtCreatePen__1}


```
 EmfExtCreatePen() 
```

Inicializa una nueva instancia de la clase [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/).

### Constructor: EmfExtCreatePen(record) {#EmfExtCreatePen_record_2}


```
 EmfExtCreatePen(record) 
```

Inicializa una nueva instancia de la clase [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | El registro. |

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


