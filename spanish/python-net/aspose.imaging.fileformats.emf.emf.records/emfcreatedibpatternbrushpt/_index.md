---
title: "Clase EmfCreateDibPatternBrushPt"
type: docs
weight: 290
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---

**Summary:** The EMR_CREATEDIBPATTERNBRUSHPT record defines a pattern brush for graphics operations. The<br/>            pattern is specified by a DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateDibPatternBrushPt

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt__1) | Inicializa una nueva instancia de la clase [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/). |
| [EmfCreateDibPatternBrushPt(source)](#EmfCreateDibPatternBrushPt_source_2) | Inicializa una nueva instancia de la clase [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtiene o establece un búfer que contiene un DIB empaquetado en forma de un objeto WMF<br/>            DeviceIndependentBitmap ([MS-WMF] sección 2.2.2.9). No es necesario que sea<br/>            contiguo con la porción fija del registro EMR_CREATEDIBPATTERNBRUSHPT. |
| ih_brush | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el índice del pincel de patrón<br/>            en la tabla de objetos EMF (sección 3.1.1.1). Este índice DEBE guardarse para que este objeto<br/>            pueda reutilizarse o modificarse. |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica cómo interpretar los valores en la tabla de colores<br/>            del encabezado DIB. Este valor DEBE estar en la enumeración DIBColors (sección 2.1.9). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt__1}


```
 EmfCreateDibPatternBrushPt() 
```

Inicializa una nueva instancia de la clase [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/).

### Constructor: EmfCreateDibPatternBrushPt(source) {#EmfCreateDibPatternBrushPt_source_2}


```
 EmfCreateDibPatternBrushPt(source) 
```

Inicializa una nueva instancia de la clase [EmfCreateDibPatternBrushPt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/).

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


