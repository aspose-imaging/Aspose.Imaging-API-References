---
title: "Класс EmfStretchBlt"
type: docs
weight: 1400
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

**Summary:** The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStretchBlt()](#EmfStretchBlt__1) | Инициализирует новый экземпляр класса [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
| [EmfStretchBlt(source)](#EmfStretchBlt_source_2) | Инициализирует новый экземпляр класса [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет <br/>            цвет фона исходного битмапа. |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет код растровой операции <br/>            . Этот код определяет, как цветовые данные исходного прямоугольника должны быть объединены с <br/>            цветовыми данными целевого прямоугольника и, при необходимости, с шаблоном кисти, чтобы получить окончательный цвет. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            ограничивающий прямоугольник назначения в единицах устройства. |
| cx_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину целевого прямоугольника. |
| cx_src | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину исходного прямоугольника. |
| cy_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту целевого прямоугольника. |
| cy_src | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту исходного прямоугольника. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает целевой прямоугольник. |
| size | int | r/w | Получает или задает размер записи |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает буфер, содержащий исходный битмап, который не обязан быть <br/>            смежным с фиксированной частью записи EMR_STRETCHBLT. Соответственно, поля в этом <br/>            буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает исходный прямоугольник. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в <br/>            таблице цветов заголовка исходного битмапа. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
| x_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату x верхнего левого <br/> угла прямоугольника назначения. |
| x_src | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату x верхнего левого <br/> угла исходного прямоугольника. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| y_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату y верхнего левого <br/> угла прямоугольника назначения. |
| y_src | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату y верхнего левого <br/> угла исходного прямоугольника. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchBlt() {#EmfStretchBlt__1}


```
 EmfStretchBlt() 
```

Инициализирует новый экземпляр класса [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

### Constructor: EmfStretchBlt(source) {#EmfStretchBlt_source_2}


```
 EmfStretchBlt(source) 
```

Инициализирует новый экземпляр класса [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

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


