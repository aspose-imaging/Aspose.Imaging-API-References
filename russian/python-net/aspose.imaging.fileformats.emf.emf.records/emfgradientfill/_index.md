---
title: "Класс EmfGradientFill"
type: docs
weight: 560
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---

**Summary:** The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGradientFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfGradientFill(source)](#EmfGradientFill_source_1) | Инициализирует новый экземпляр класса [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            ограничивающий прямоугольник в включительно‑включительных единицах устройства. |
| n_tri | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет количество прямоугольников или треугольников для заполнения. |
| n_ver | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет количество вершин. |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| ul_mode | [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgradientfill/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет режим градиентного заполнения. Значение <br/>            ДОЛЖНО находиться в перечислении GradientFill (раздел 2.1.15). |
| vertex_data | [EmfVertexData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/) | r/w | Получает или задает объекты, которые определяют вершины прямоугольников или треугольников и <br/>            соответствующие им цвета. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGradientFill(source) {#EmfGradientFill_source_1}


```
 EmfGradientFill(source) 
```

Инициализирует новый экземпляр класса [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/).

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


