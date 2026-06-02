---
title: "Класс EmfBitBlt"
type: docs
weight: 70
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---

**Summary:** The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBitBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBitBlt(source)](#EmfBitBlt_source_1) | Инициализирует новый экземпляр класса [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет код растровой операции <br/>            . Этот код определяет, как данные цвета исходного прямоугольника комбинируются с <br/>            данными цвета целевого прямоугольника и, при необходимости, с шаблоном кисти, чтобы получить окончательный цвет. |
| bk_src_argb_32_color | int | r/w | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет<br/>            фоновый цвет исходного битмапа. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            ограничивающий прямоугольник назначения в единицах устройства. |
| cx_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину исходного и <br/>            целевого прямоугольников. |
| cy_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту исходного и <br/>            целевого прямоугольников. |
| size | int | r/w | Получает или задает размер записи |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает буфер, содержащий исходный битмап, который не обязан быть <br/>            смежным с фиксированной частью записи EMR_BITBLT. Соответственно, поля в этом буфере <br/>            с меткой "UndefinedSpace" являются необязательными и ДОЛЖНЫ игнорироваться. |
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


### Constructor: EmfBitBlt(source) {#EmfBitBlt_source_1}


```
 EmfBitBlt(source) 
```

Инициализирует новый экземпляр класса [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/).

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


