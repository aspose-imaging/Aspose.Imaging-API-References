---
title: "Класс EmfPolyTextOutA"
type: docs
weight: 880
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---

**Summary:** The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutA

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyTextOutA()](#EmfPolyTextOutA__1) | Инициализирует новый экземпляр класса [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/). |
| [EmfPolyTextOutA(source)](#EmfPolyTextOutA_source_2) | Инициализирует новый экземпляр класса [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Получает или задает массив объектов EmrText (раздел 2.2.5), которые определяют выводимые <br/>            строки в 8‑битных ASCII‑символах, с атрибутами текста и значениями интервалов. Количество <br/>            объектов EmrText задаётся параметром cStrings. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            ограничивающий прямоугольник в единицах устройства. |
| ex_scale | float | r/w | Получает или задает 32‑битное значение с плавающей точкой, которое указывает масштаб X от единиц страницы к <br/>            единицам .01 мм, если режим графики GM_COMPATIBLE. |
| ey_scale | float | r/w | Получает или задает 32‑битное значение с плавающей точкой, которое указывает масштаб Y от единиц страницы к <br/>            единицам .01 мм, если режим графики GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает текущий режим графики, <br/>            из перечисления GraphicsMode (раздел 2.1.16). |
| size | int | r/w | Получает или задает размер записи |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyTextOutA() {#EmfPolyTextOutA__1}


```
 EmfPolyTextOutA() 
```

Инициализирует новый экземпляр класса [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/).

### Constructor: EmfPolyTextOutA(source) {#EmfPolyTextOutA_source_2}


```
 EmfPolyTextOutA(source) 
```

Инициализирует новый экземпляр класса [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/).

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


