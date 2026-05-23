---
title: "Clase EmfPolyTextOutW"
type: docs
weight: 890
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---

**Summary:** The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPolyTextOutW()](#EmfPolyTextOutW__1) | Inicializa una nueva instancia de la clase [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/). |
| [EmfPolyTextOutW(source)](#EmfPolyTextOutW_source_2) | Inicializa una nueva instancia de la clase [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19), que especifica el <br/>            rectángulo delimitador en unidades de dispositivo. |
| ex_scale | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala X de unidades de página a <br/>            unidades de .01mm si el modo gráfico es GM_COMPATIBLE. |
| ey_scale | float | r/w | Obtiene o establece un valor de punto flotante de 32 bits que especifica la escala Y de unidades de página a <br/>            unidades de .01mm si el modo gráfico es GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el modo gráfico actual, <br/>            de la enumeración GraphicsMode (sección 2.1.16). |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| w_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Obtiene o establece una matriz de objetos EmrText (sección 2.2.5) que especifican las cadenas de salida <br/>            en caracteres Unicode UTF16-LE de 16 bits, con atributos de texto y valores de espaciado. El <br/>            número de objetos EmrText se especifica mediante cStrings. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyTextOutW() {#EmfPolyTextOutW__1}


```
 EmfPolyTextOutW() 
```

Inicializa una nueva instancia de la clase [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/).

### Constructor: EmfPolyTextOutW(source) {#EmfPolyTextOutW_source_2}


```
 EmfPolyTextOutW(source) 
```

Inicializa una nueva instancia de la clase [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/).

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


