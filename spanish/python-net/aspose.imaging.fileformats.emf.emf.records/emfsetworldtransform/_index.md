---
title: "EmfSetWorldTransform Clase"
type: docs
weight: 1370
url: /es/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---

**Summary:** The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfSetWorldTransform()](#EmfSetWorldTransform__1) | Inicializa una nueva instancia de la clase [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/). |
| [EmfSetWorldTransform(source)](#EmfSetWorldTransform_source_2) | Inicializa una nueva instancia de la clase [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| tamaño | int | r/w | Obtiene o establece el tamaño del registro |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtiene o establece el tipo. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece un objeto XForm (sección 2.2.28), que define una transformación de espacio mundial a espacio de página. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inicializa una nueva instancia de la clase [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWorldTransform() {#EmfSetWorldTransform__1}


```
 EmfSetWorldTransform() 
```

Inicializa una nueva instancia de la clase [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/).

### Constructor: EmfSetWorldTransform(source) {#EmfSetWorldTransform_source_2}


```
 EmfSetWorldTransform(source) 
```

Inicializa una nueva instancia de la clase [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/).

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


