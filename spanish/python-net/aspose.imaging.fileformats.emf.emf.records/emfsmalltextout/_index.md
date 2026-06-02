---
title: "EmfSmallTextOut Clase"
type: docs
weight: 1380
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | Inicializa una nueva instancia de la [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL opcional de 128 bits ([MS-WMF] sección 2.2.2.19) que<br/>            especifica el rectángulo delimitador en unidades del dispositivo. |
| c_chars | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres de 16 bits en la<br/>            cadena. La cadena NO está terminada en nulo. |
| ex_scale | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección x. |
| ey_scale | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica cuánto escalar el texto en la dirección y. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica las opciones de salida de texto a usar. Estas<br/>            opciones se especifican mediante uno o una combinación de valores de la enumeración ExtTextOutOptions<br/>            (sección 2.1.11). |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico, de la enumeración<br/>            GraphicsMode (sección 2.1.16). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| text_string | string | r/w | Obtiene o establece una cadena de longitud variable que contiene la cadena de texto a dibujar, ya sea en códigos de caracteres de 8 bits o de 16 bits, según el valor del campo fuOptions. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| x | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada x donde colocar la cadena. |
| y | int | r/w | Obtiene o establece un entero con signo de 32 bits que especifica la coordenada y donde colocar la cadena. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

Inicializa una nueva instancia de la [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) clase.

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


