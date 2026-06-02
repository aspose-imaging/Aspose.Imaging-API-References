---
title: "EmfGlsBoundedRecord Класс"
type: docs
weight: 540
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---

**Summary:** The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsBoundedRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfGlsBoundedRecord(source)](#EmfGlsBoundedRecord_source_1) | Инициализирует новый экземпляр класса [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий<br/>прямоугольник в единицах устройства для вывода, получаемого при выполнении функции OpenGL. |
| cb_data | int | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет размер, в байтах, поля Data.<br/>            Если это значение равно нулю, к этой записи не прикрепляются данные. |
| данные | System.Byte | r/w | Получает или задает необязательный массив байтов длиной cbData, который определяет данные для функции OpenGL. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGlsBoundedRecord(source) {#EmfGlsBoundedRecord_source_1}


```
 EmfGlsBoundedRecord(source) 
```

Инициализирует новый экземпляр класса [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/).

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


