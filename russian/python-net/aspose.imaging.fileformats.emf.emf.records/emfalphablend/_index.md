---
title: "Класс EmfAlphaBlend"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | Инициализирует новый экземпляр класса [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет<br/>            фоновый цвет исходного битмапа. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | Получает или задает структуру, определяющую операции смешивания для исходного и <br/>            целевого битмапов. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            ограничивающий прямоугольник назначения в единицах устройства. |
| cx_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину прямоугольника назначения <br/>            . Это значение ДОЛЖНО быть больше нуля. |
| cx_src | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую ширину исходного прямоугольника. <br/>            Это значение ДОЛЖНО быть больше нуля. |
| cy_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту прямоугольника назначения <br/>            . Это значение ДОЛЖНО быть больше нуля. |
| cy_src | int | r/w | Получает или задает 32-битное знаковое целое, которое определяет логическую высоту исходного <br/>            прямоугольника. Это значение ДОЛЖНО быть больше нуля. |
| size | int | r/w | Получает или задает размер записи |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает буфер, содержащий исходный битмап, который не обязателен быть <br/>            смежным с фиксированной частью записи EMR_ALPHABLEND. Соответственно, поля в этом <br/>            буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Получает или задает тип. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет способ интерпретации значений в <br/>            таблице цветов заголовка исходного битмапа. Это значение ДОЛЖНО находиться в перечислении DIBColors (раздел 2.1.9). |
| x_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату x верхнего левого <br/> угла прямоугольника назначения. |
| x_src | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату x верхнего левого <br/> угла исходного прямоугольника. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает объект XForm (раздел 2.2.28), который определяет преобразование из мирового пространства в пространство страницы, применяемое к исходному битмапу. |
| y_dest | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату y верхнего левого <br/> угла прямоугольника назначения. |
| y_src | int | r/w | Получает или задает 32-битное знаковое целое, которое указывает логическую координату y верхнего левого <br/> угла исходного прямоугольника. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Инициализирует новый экземпляр класса [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

Инициализирует новый экземпляр класса [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/).

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


