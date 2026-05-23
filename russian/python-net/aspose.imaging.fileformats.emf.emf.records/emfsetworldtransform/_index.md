---
title: "Класс EmfSetWorldTransform"
type: docs
weight: 1370
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---

**Summary:** The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetWorldTransform()](#EmfSetWorldTransform__1) | Инициализирует новый экземпляр класса [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/). |
| [EmfSetWorldTransform(source)](#EmfSetWorldTransform_source_2) | Инициализирует новый экземпляр класса [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWorldTransform() {#EmfSetWorldTransform__1}


```
 EmfSetWorldTransform() 
```

Инициализирует новый экземпляр класса [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/).

### Constructor: EmfSetWorldTransform(source) {#EmfSetWorldTransform_source_2}


```
 EmfSetWorldTransform(source) 
```

Инициализирует новый экземпляр класса [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Источник. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Тип записи. |

**Returns**

| Тип | Описание |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


