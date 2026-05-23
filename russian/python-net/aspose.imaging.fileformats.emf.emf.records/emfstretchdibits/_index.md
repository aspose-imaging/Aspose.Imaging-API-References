---
title: "EmfStretchDiBits Класс"
type: docs
weight: 1410
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

**Summary:** The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStretchDiBits(source)](#EmfStretchDiBits_source_1) | Инициализирует новый экземпляр класса [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Получает или задаёт 32‑битное беззнаковое целое, которое определяет код растровой операции <br/>            . Эти коды определяют, как цветовые данные исходного прямоугольника должны быть объединены с <br/>            цветовыми данными целевого прямоугольника и, при необходимости, с шаблоном кисти, чтобы получить окончательный цвет. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            ограничивающий прямоугольник назначения в единицах устройства. |
| cx_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину целевого прямоугольника. |
| cx_src | int | r/w | Получает или задаёт 32‑битное знаковое целое, которое определяет ширину в пикселях исходного прямоугольника. |
| cy_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту целевого прямоугольника. |
| cy_src | int | r/w | Получает или задаёт 32‑битное знаковое целое, которое определяет высоту в пикселях исходного прямоугольника. |
| size | int | r/w | Получает или задает размер записи |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задаёт буфер, содержащий исходный битмап, который не обязан быть <br/>            смежным с фиксированной частью записи EMR_STRETCHDIBITS. Соответственно, поля в <br/>            этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в <br/>            таблице цветов заголовка исходного битмапа. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
| x_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату x верхнего левого <br/> угла прямоугольника назначения. |
| x_src | int | r/w | Получает или задаёт 32‑битное знаковое целое, которое определяет координату x в пикселях верхнего левого <br/>            угла исходного прямоугольника. |
| y_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату y верхнего левого <br/> угла прямоугольника назначения. |
| y_src | int | r/w | Получает или задаёт 32‑битное знаковое целое, которое определяет координату y в пикселях верхнего левого <br/>            угла исходного прямоугольника. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchDiBits(source) {#EmfStretchDiBits_source_1}


```
 EmfStretchDiBits(source) 
```

Инициализирует новый экземпляр класса [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/).

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


