---
title: "Clase EmfSetTextAlign"
type: docs
weight: 1300
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---

**Summary:** The EMR_SETTEXTALIGN record specifies text alignment.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextAlign

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetTextAlign()](#EmfSetTextAlign__1) | Inicializa una nueva instancia de la clase [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/). |
| [EmfSetTextAlign(source)](#EmfSetTextAlign_source_2) | Inicializa una nueva instancia de la clase [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| text_alignment_mode | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica la alineación del texto mediante<br/>            una máscara de indicadores de alineación de texto. Estos son o bien [WmfTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/)<br/>            ([MS-WMF] sección 2.1.2.3) para texto con una línea base horizontal, o [WmfVerticalTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/)<br/>            ([MS-WMF] sección 2.1.2.4) para texto con una vertical<br/>            línea base. Sólo se puede elegir un valor entre los que afectan la alineación horizontal y vertical<br/>            . |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetTextAlign() {#EmfSetTextAlign__1}


```
 EmfSetTextAlign() 
```

Inicializa una nueva instancia de la clase [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/).

### Constructor: EmfSetTextAlign(source) {#EmfSetTextAlign_source_2}


```
 EmfSetTextAlign(source) 
```

Inicializa una nueva instancia de la clase [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/).

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


