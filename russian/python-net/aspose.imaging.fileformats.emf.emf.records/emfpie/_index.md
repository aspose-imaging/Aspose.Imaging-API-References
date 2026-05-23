---
title: "Класс EmfPie"
type: docs
weight: 730
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Инициализирует новый экземпляр класса [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
| [EmfPie(source)](#EmfPie_source_2) | Инициализирует новый экземпляр класса [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL, указанный в [MS-WMF] разделе 2.2.2.19, который <br/>            определяет включительно‑включительный ограничивающий прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64-битный объект PointL, который определяет координаты, в логических единицах, конечной точки второго радиала. |
| size | int | r/w | Получает или задает размер записи |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Получает или задает 64-битные объекты WMF PointL, указанные в [MS-WMF] разделе 2.2.2.15, которые <br/>            определяют координаты, в логических единицах, конечной точки первого радиала. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Инициализирует новый экземпляр класса [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Инициализирует новый экземпляр класса [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

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


